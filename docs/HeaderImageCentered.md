---
id: HeaderImageCentered
title: Product Components
sidebar_label: HeaderImageCentered
---

## HeaderImageCentered

HeaderImageCentered is a multifunctional header component.

<img src="/img/HeaderImageCentered.png" width="100%">

## Props

```json
{
  //out props
  "imageUrl": "https://example.com/logo.png",
  "headerButtonsRight": [
    {
      "text": {
        "en": "",
        "tr": ""
      },
      "rightIcon": "barcode",
      "rightIconFamily": "Ionicons",
      "onPress": {
        "type": "navigate",
        "route": "barcodescanner",
      }
    }
  ],
  "headerButtonsLeft": [
    //can be same to headerButtonsRight
  ],
  "styles": {}
}
```

## Buttons

headerButtonsRight and headerButtonsLeft uses array of [ComponentButton](ComponentButton)

## Styles

```json
{
  "container": {
    //component container style
  },
  "imageStyle": {
    //image component style
  }
}
```