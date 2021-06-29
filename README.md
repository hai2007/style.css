# 👁️ style.css - 浏览器兼容样式和一些基础样式

<p>
  <a href="https://hai2007.gitee.io/npm-downloads?interval=7&packages=@hai2007/style"><img src="https://img.shields.io/npm/dm/@hai2007/style.svg" alt="downloads"></a>
  <a href="https://packagephobia.now.sh/result?p=@hai2007/style"><img src="https://packagephobia.now.sh/badge?p=@hai2007/style" alt="install size"></a>
  <a href="https://www.jsdelivr.com/package/npm/@hai2007/style"><img src="https://data.jsdelivr.com/v1/package/npm/@hai2007/style/badge" alt="CDN"></a>
  <a href="https://www.npmjs.com/package/@hai2007/style"><img src="https://img.shields.io/npm/v/@hai2007/style.svg" alt="Version"></a>
  <a href="https://github.com/hai2007/style.css/blob/master/LICENSE"><img src="https://img.shields.io/npm/l/@hai2007/style.svg" alt="License"></a>
    <a href="https://github.com/hai2007/style.css">
        <img alt="GitHub repo stars" src="https://img.shields.io/github/stars/hai2007/style.css?style=social">
    </a>
</p>

## Issues
使用的时候遇到任何问题或有好的建议，请点击进入[issue](https://github.com/hai2007/style.css/issues)，欢迎参与维护！

## How to use?
首先你需要通过命令行安装：

```bash
npm install --save @hai2007/style
```

安装好了以后，然后引入你需要的样式文件：

- 统一不同浏览器的基础样式

```js
import '@hai2007/style/normalize.css';
```

或

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@hai2007/style@0/normalize.css">
```

- 十二栅格化

```js
import '@hai2007/style/rasterize.css';
```

或

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@hai2007/style@0/rasterize.css">
```

[<< 查看文档](./apis/rasterize.md)

- 文档样式

```js
import '@hai2007/style/doc-view.css';
```

或

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@hai2007/style@0/doc-view.css">
```

[<< 查看文档](./apis/doc-view.md)

开源协议
---------------------------------------
[MIT](https://github.com/hai2007/style.css/blob/master/LICENSE)

Copyright (c) 2020-present [hai2007](https://hai2007.gitee.io/sweethome/) 走一步，再走一步。
