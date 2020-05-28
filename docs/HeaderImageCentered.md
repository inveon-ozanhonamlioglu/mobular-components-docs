---
id: HeaderImageCentered
title: Header Components
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
  "rightButtons": [
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
  "leftButtons": [
    //can be same to rightButtons
  ],
  "styles": {}
}
```

## Buttons

rightButtons and leftButtons uses array of [ComponentButton](ComponentButton)

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