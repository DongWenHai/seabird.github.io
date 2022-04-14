---
    title: 原型链
    date: 2022-04-14 00:00:00
    tags:
        - javascript
    categories:
        - javascript
    keywords: javascript
    description: '原型链的理解'
    cover: /images/js-prototype-cover.png
    top_img: /images/js-prototype-cover.png
---

# 一、概念
  每个对象都可以有一个原型_proto_，这个原型还可以有它自己的原型，以此类推，形成一个原型链。查找特定属性的时候，我们先去这个对象里去找，如果没有的话就去它的原型对象里面去，如果还是没有的话再去向原型对象的原型对象里去寻找...... 这个操作被委托在整个原型链上，这个就是我们说的原型链了。

# 原型链图解
  <img src="/images/js-prototype-01.png" alt="logo" style="width:80%;" />