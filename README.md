# [Only css Slider](https://lebryere.github.io/Magic-Grid-Gallery//)

## Browser Support

![Chrome](https://raw.githubusercontent.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png) | ![Edge](https://raw.githubusercontent.com/alrra/browser-logos/master/src/edge/edge_48x48.png) | ![Firefox](https://raw.githubusercontent.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png) | ![Safari](https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari/safari_48x48.png) | ![Opera](https://raw.githubusercontent.com/alrra/browser-logos/master/src/opera/opera_48x48.png) | ![Samsung Internet](https://raw.githubusercontent.com/alrra/browser-logos/master/src/samsung-internet/samsung-internet_48x48.png)
--- | --- | --- | --- | --- | --- |
94+ ✔ | 92+ ✔ | 89+ ✔ | 82+ ✔ | 87+ ✔ | 55+ ✔ |

## Preview

[![Resume Preview](preview.png)](https://lebryere.github.io/Magic-Grid-Gallery//)

**[View Live Preview](https://lebryere.github.io/Magic-Grid-Gallery//)**

## Status

[![GitHub license](https://img.shields.io/badge/license-MIT-green?&style=plastic)](https://github.com/LeBryere/Magic-Grid-Gallery/.github.io/blob/master/LICENSE)

## Usage

### Basic Usage


The page presents a photo gallery, which is arranged as follows:

The photos are placed within a main content element ```html(<main class="content">)```.
The photos are arranged according to their sources within img elements.
When the mouse is hovered over a photo, the other photos blur and darken, while the current photo stands out.
Styles are applied using JavaScript by listening for mouseenter and mouseleave events.
The layout of the photos is determined by the CSS grid layout module, where the img elements occupy two columns, and a special layout is applied in the img:hover state.
The CSS code contains additional styles that influence the layout and appearance of the photos based on changes in the page size.

### Variables
```css
:root{
   --image-size: 120px;
   --set-time: .25s;
}
```

## Copyright and License

Copyright 2022 Lebryere. Code released under the[![GitHub license](https://img.shields.io/badge/license-MIT-green?&style=plastic)](https://github.com/LeBryere/Magic-Grid-Gallery/.github.io/blob/master/LICENSE) license.
