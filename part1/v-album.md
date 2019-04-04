# v-album

## Description

照片展示器组件

* album组件
* 传入图片list，布局由第一张图片的宽高比决定；
* 点击可预览，需配置viewer嵌套路由；


## Attributes

| Attribute | Description | Type  | Accepted values | Default |        Demo        |
| :-------: | :---------: | :---: | :-------------: | :-----: | :----------------: |
|   value   | images 数据 | Array |        —        |   []    | [{url: 'img.png'}] |

## Events

| Event Name | Description  |             Parameters              |
| :--------: | :----------: | :---------------------------------: |
|   click    | 点击图片回调 | ($event \| Object, index \| number) |

