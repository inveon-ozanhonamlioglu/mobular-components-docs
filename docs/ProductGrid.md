---
id: ProductGrid
title: Product Components
sidebar_label: ProductGrid
---

## ProductGrid

ProductGrid grid layout for products.

<img src="/img/ProductGrid.png" height="500">

## Props

```json
{
  //in-app props
  "products": [
    {
      "id": 1,
      "title": "Lorem Ipsum",
      "subtitle": "Lorem ipsum dolor sit amet, consectetur adipiscing elit.",
      "oldPrice": 99.99,
      "price": 59.99,
      "currency": "TL",
      "isLiked": false
    }
  ],
  //out props
  "title": {
    "en": "RECOMMENDED FOR YOU",
    "tr": "SİZE ÖZEL"
  },
  "productListType": "insider",
  "likeButtonsEnabled": false,
  "addToCardButtonsEnabled": false,
  "itemPerRow": 3,
  "headerButtonRight": {
    "text": {
      "en": "Shop All",
      "tr": "Keşfet"
    },
    "rightIcon": "arrow-right",
    "rightIconFamily": "Ionicons",
    "onPress": {
      "type": "navigate",
      "route": "productlist",
      "routeParams": {
        "id": 15
      }
    }    
  },
  "headerButtonLeft": {
    //can be same to headerButtonRight
  },
  "styles": {}
}
```

- [productListType](#productListType)
  - popular: load component with popular products
  - newest: load component with new products
  - insider: load component with fetched products from insider sdk

## Buttons

headerButtonRight and headerButtonLeft uses [ComponentButton](ComponentButton)

## Styles

```json
{
  "container": {
    //component container style
  },
  "itemStyle": {
    //item container style
  },
  "itemImageStyle": {
    //item image component style
  },
  "itemTitleStyle": {
    //item title text style
  },
  "itemSubtitleStyle": {
    //item subtitle text style
  },
  "itemPriceViewStyle": {
    //item oldPrice and price in view style
  },
  "itemOldPriceStyle": {
    //item oldprice text style
  },
  "itemPriceStyle": {
    //item price text style
  },
}
```