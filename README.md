# Ads by ![Flagrow logo](https://avatars0.githubusercontent.com/u/16413865?v=3&s=20) [Flagrow](https://discuss.flarum.org/d/1832-flagrow-extension-developer-group), a project of [Gravure](https://gravure.io/)

[![MIT license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/flagrow/ads/blob/master/LICENSE.md) [![Latest Stable Version](https://img.shields.io/packagist/v/flagrow/ads.svg)](https://packagist.org/packages/flagrow/ads) [![Total Downloads](https://img.shields.io/packagist/dt/flagrow/ads.svg)](https://packagist.org/packages/flagrow/ads) [![Donate](https://img.shields.io/badge/patreon-support-yellow.svg)](https://www.patreon.com/flagrow) [![Join our Discord server](https://discordapp.com/api/guilds/240489109041315840/embed.png)](https://flagrow.io/join-discord)

Allows you to configure ads in several locations.

> Warning this is a beta version, make sure you test your ads out on a non-production website before publishing!

![Preview](https://discuss.hyn.me/assets/files/2017-02-04/18:30:230-screen-shot-2017-02-04-at-193240png.png)

> Please note that I might decide to make this extension available only with a license in the future.
> Any version published under MIT license will however remain available.
> And if a license will be required, you will be informed in advance.

## Goals

- Allow configuration of ads on your forum at different locations.

## Installation

    composer require arthurydalgo/ads

## Updating

    composer update arthurydalgo/ads
    php flarum cache:clear

## Configuration

Enable the extension under the extensions tab in the admin area.

Make sure you configure extension on the separate tab;

- Your ads on different locations, leave empty for none.
- If you use ads between posts, set the spacing.
