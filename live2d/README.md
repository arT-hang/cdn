# live2d-cdn
自用。仅包含cdnPath的live2d-widget。内置模型。

## 来源

代码魔改(~~复制粘贴~~)自 [https://github.com/stevenjoezhang/live2d-widget](https://github.com/stevenjoezhang/live2d-widget)

> 删除了apiPath这种调用live2d模型的代码
>
> 修改了waifu.css使模型出现在右侧
>
> 修改了看板娘的z-index使得她出现在页面最上层

模型来自 [https://github.com/imuncle/live2d](https://github.com/imuncle/live2d)

> 目前该仓库内置模型列表：Umaru

## 使用方法

在html文件中引入一个css文件和一个js文件。

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/font-awesome/css/font-awesome.min.css">
<script src="https://cdn.jsdelivr.net/gh/wuuconix/live2d-cdn@main/autoload.js"></script>
```

## 在线预览

[https://wuuconix.tk/live2d-cdn/](https://wuuconix.tk/live2d-cdn/)