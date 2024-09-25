# Lawnchair 14

[![Build debug APK](https://github.com/LawnchairLauncher/lawnchair/actions/workflows/ci.yml/badge.svg)](https://github.com/LawnchairLauncher/lawnchair/actions/workflows/ci.yml)
[![Build release APK](https://github.com/LawnchairLauncher/lawnchair/actions/workflows/release_update.yml/badge.svg)](https://github.com/LawnchairLauncher/lawnchair/actions/workflows/release_update.yml)
[![Crowdin](https://badges.crowdin.net/e/188ba69d884418987f0b7f1dd55e3a4e/localized.svg)](https://lawnchair.crowdin.com/lawnchair)
[![OpenCollective](https://img.shields.io/opencollective/all/lawnchair?label=financial%20contributors&logo=open-collective)](https://opencollective.com/lawnchair)
[![Telegram](https://img.shields.io/endpoint?url=https%3A%2F%2Ftg.sumanjay.workers.dev%2Flccommunity)](https://t.me/lccommunity)
[![Discord](https://img.shields.io/discord/803299970169700402?label=server&logo=discord)](https://discord.gg/3x8qNWxgGZ)

<picture>
    <!-- Avoid image being clickable with slight workaround -->
    <!-- ❤️ Credit to Raine for the original mockup on the Lawnchair Discord -->
    <!-- ❤️ Credit to Lawrence Kayku for the current mockup on Unsplash 
            https://unsplash.com/photos/photography-of-green-leaves-ZVKr8wADhpc 
    -->
    <source media="(prefers-color-scheme: dark)" srcset="docs/assets/device-frame.png" width="250px">
    <img alt="Google Pixel running Lawnchair Launcher with green wallpaper" src="docs/assets/device-frame.png" width="250px">
</picture>

Lawnchair is a free, open-source home app for Android. Taking Launcher3 — Android’s default home app — as a starting point, it ports Pixel Launcher features and introduces rich options for customization.

This branch houses the codebase of Lawnchair 14, which is currently in beta and is based on Launcher3 from Android 14. For Lawnchair 9 to 13, see the branches with the `9-` to `13-` prefixes, respectively.

## Features

-   Pixel Launcher-like UI with Material You design
-   At a Glance widget with Smartspacer support
-   QuickSwitch support
-   Global Search support
-   Icons, fonts, and colors customization
-   And more!

## Download

See the [releases](https://github.com/LawnchairLauncher/lawnchair/releases) section for the latest
beta build. For development builds with upcoming features & bug fixes, use the nightly builds.

## Contributing

Please visit the [Lawnchair Contributing Guidelines](CONTRIBUTING.md) for information and tips on contributing to Lawnchair.

## Quick links

-   [News](https://t.me/lawnchairci)
-   [Lawnchair on X (formerly Twitter)](https://x.com/lawnchairapp)
-   [Website](https://lawnchair.app)
-   [_XDA_ thread](https://forum.xda-developers.com/t/lawnchair-customizable-pixel-launcher.3627137/)

You can view all our links in the [Lawnchair Wiki](https://github.com/LawnchairLauncher/lawnchair/wiki).

## Modifications

-   Added ability to copy Calculator search result to clipboard
-   Added Google Go, Lawnfeed and Neo Feed to Feed providers whitelist
-   Added iOS, Light squircle, One UI, Strong squircle and Ultra squircle to Custom Icon corner shapes
-   Added Lemon, Light squircle, Strong squircle and Ultra squircle icon shapes
-   Arranged Custom Icon corner shapes in alphabetical order
-   Arranged Feed providers in alphabetical order
-   Arranged Quick Search Bar providers in alphabetical order
-   Corrected case of user interface label
-   Ensured Custom Icon shape sliders are of equal length
-   Ensured variant is displayed after family for default font settings
-   Ensured System Icon shape is as accurate as possible
-   Ensured user interface label can be translated
-   Fixed One UI icon corner shape
-   Fixed typo in text string
-   Increased adjustment granularity of all percentage sliders from 10% to 5%
-   Prevented duplicate fonts in font list
-   Reduced minimum Home screen and App drawer Icons Label size from 50% to 30%
-   Signed APK with personal key
-   Upgraded Inter font from v3 to v4
