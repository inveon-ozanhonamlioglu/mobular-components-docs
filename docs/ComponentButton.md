---
id: ComponentButton
title: Generic Components
sidebar_label: ComponentButton
---

## ComponentButton

ComponentButton is standardized mobular specific components buttons. 
Like as ProductGrid Buttons, ProductListSwiper Buttons...

![alt text](/img/ProductGridHeaderButton.png "ProductListSwiper")

```json
{
  "text": {
    "en": "Shop All",
    "tr": "Keşfet"
  },
  "rightIcon": "arrow-right",
  "rightIconFamily": "Ionicons",
  "letfIcon": "arrow-left",
  "leftIconFamily": "FontAwesome",
  "onPress": {
    "type": "navigate",
    "route": "productlist",
    "routeParams": {
      "id": 15
    }
  }
}
```

- [type](#type)
  - navigate: navigate to screen
    - `route`: [Required] screen route name. e.g. "productlist"
    - `routeParams`: [Optional] route with params. e.g. { id: 15 }
  - settings: go to device native settings screen 
  - finish: close application
  - openDrawer: open left drawer menu


## Styles

```json
{
  "container": {
    //button container style
  },
  "textStyle": {
    //text style
  },
  "leftIconStyle": {
    //left icon style
  },
  "rightIconStyle": {
    //right icon style
  },
}
```