---
id: ProductListSwiper
title: Product Components
sidebar_label: ProductListSwiper
---

## ProductListSwiper

ProductListSwiper horizontal swiper for products.

![alt text](/img/ProductListSwiper.png "ProductListSwiper")


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
    "en": "Popular Products",
    "tr": "Popüler Ürünler"
  },
  "productListType": "popular",
  "likeButtonsEnabled": true,
  "addToCardButtonsEnabled": false,
  "headerButtonRigh": {},
  "headerButtonLeft": {},  
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