# al-goods-line
-------------
商品线性列表。

## Installation
```
npm i al-goods-line
```

## Usage
```js
/*js文件*/
import Line from 'al-goods-line';
children={
  line: new Line({
    //...
  });
};
```
```xml
<!--xml组件-->
<component key="line" name="al-goods-line" />
```
```css
/*less文件*/
@import 'al-goods-line';
```
## Props
|Property | PropType |Description|
|:---------|:----|:------|
|items|array|商品列表数据，针对`alaska-goods`service数据结构|
|onChange|func|item点击事件，返回`商品id`|