小程序安装npm比平时多了一个步骤，微信开发者工具——“构建npm”，会新创建一个miniprogram_npm，我们的node_modules实际上会被视为一个隐藏的文件。

```
<block>即是Vue开发中的<template>
```


text使用flex居中问题
微信小程序的坑：https://blog.csdn.net/wu56yue/article/details/78728331?utm_source=blogxgwz1

会自动地添加空格
```
<text class="main-text">
  {{item.content}}
</text>
```
和 `<text>{{test}}</text>`
https://developers.weixin.qq.com/community/develop/doc/00004ca33a0650c2598a9553d50800

小程序的 template 只实现了模板作用（只支持HTML、CSS——wxml 、wxss），并没有实现模块化的作用

template的文件、样式还要分开引用。。。。。。。