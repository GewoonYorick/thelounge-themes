## Modern The Lounge themes for Modern IRC

#### Used by the popular Finnish channel [#pulina @ QuakeNet](https://www.pulina.fi)

[![GitHub release](https://img.shields.io/github/tag/pulinairc/thelounge-themes.svg?style=flat-square)](https://github.com/pulinairc/thelounge-themes/releases) [![The Lounge](https://img.shields.io/badge/tested%20with%20thelounge-4.2.0-ff9e18.svg?style=flat-square)](https://github.com/thelounge/thelounge)

Aiming to be the **perfect** The Lounge theme out there.

## Requirements

- The Lounge 4.2.0

## Features

- Minimal UI
- Easy on the eyes
- Conversation layout, see [#2591](https://github.com/thelounge/thelounge/pull/2591#issuecomment-785429158)
- Automatic day and night themes
- Fixed preview images with correct dimensions
- The most readable modern fonts on Retina and 60hz mobile screens

![Screenshot](https://i.imgur.com/fOVc5Gt.png "Screenshot")

## Installation

1. Download
2. Move files under dist/ folder to your thelounge/public/themes/ directory

### Development

#### I want to change something!

Please fork this repository and make your changes.
If they are good we might even accept PRs.

#### I just want a bigger font to mobile

Add this to Settings > Advanced Settings > Custom Stylesheet:

``` css
@media (max-width: 700px) {
  .messages .msg {
    font-size: 18px !important;
  }
  
  .from {
    font-size: 18px !important;
  }
  
  .time {
    font-size: 15px !important;
    align-self: flex-start;
    line-height: 1.9;
  }
}
```

## Development

1. `cd /path/to/thelounge-themes`
2. `npm install`
3. Based on which theme you are editing, run: `scss --watch src/midnight.scss:dist/midnight.css --style compressed`
4. Start coding by running in separate Terminal: `code .` or just use any editor you wish
