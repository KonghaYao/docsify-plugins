# docsify-cc-license

在 docsify 中插入 [cc 协议标识](https://creativecommons.org/choose/) 的插件

## 载入 script

```html
<script
    type="module"
    src="https://cdn.jsdelivr.net/npm/docsify-cc-license/docsify-cc-license.js"
></script>
```

## 添加配置

```js
window.$docsify = {
    // 这个是必须要填的，如果你没有填，插件会以 console.warn 的方式提醒你
    "cc-license": {
        lang: "zh", //zh en ja
        commercial: "y", // y or n 允许对您的作品进行商业性使用吗？
        derivatives: "y", // y or n or sa 允许您的作品的演绎作品被共享吗？ sa 表示 是的，只要他人以相同方式共享
    },
};
```

## 修改样式

license 的公用样式 class 为 docsify-cc-license, 想要怎样改就怎样改吧
