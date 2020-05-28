---
id: ImageCarousel
title: Image Components
sidebar_label: ImageCarousel
---

## ImageCarousel

ImageCarousel is a images carousel component.

<img src="/img/ImageCarousel.png" width="100%">

## Props

```json
{
  //out props
  "images": [
    {
      "url": "https://example.com/image1.jpg",
      "onPress": {
        "type": "navigate",
        "route": "productlist",
        "routeParams": { 
          "campaignId": 10 
        }
      }
    },
    {
      "url": "https://example.com/image2.jpg",
      "onPress": {
        "type": "url",
        "url": "https://inveon.com"
      }
    }
  ],
  "dotsActiveColor": "#fff",
  "dotsPassiveColor": "blue",
  "dotsVisible": true,
  "navigateButtonsVisible": true, // prev-next buttons visibility
  "heightEqualToDeviceWidth": false, //component height will set to device width
  "height": 200,
  "width": "100%",
  "navigateButtonsIconColor": "blue",
  
  "styles": {}
}
```

## Styles

```json
{
  "container": {
    //component container style
  },
  "imageStyle": {
    //item image style
  },
  "dotsActiveStyle": {
    //bottom dots active style
  },
  "dotsPassiveStyle": {
    //bottom dots passive style
  },

}
```