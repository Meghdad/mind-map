<h1 align="center">Simple mind map</h1>

[![npm-version](https://img.shields.io/npm/v/simple-mind-map)](https://www.npmjs.com/package/simple-mind-map)
![npm download](https://img.shields.io/npm/dm/simple-mind-map)
[![GitHub stars](https://img.shields.io/github/stars/wanglin2/mind-map)](https://github.com/wanglin2/mind-map/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/wanglin2/mind-map)](https://github.com/wanglin2/mind-map/issues)
[![GitHub forks](https://img.shields.io/github/forks/wanglin2/mind-map)](https://github.com/wanglin2/mind-map/network/members)
![license](https://img.shields.io/npm/l/express.svg)

> A Simple & Powerful Web Mind Map

This project consists of two parts:

1.A js mind map library that does not depend on any framework, you can use it to quickly complete the development of Web mind map products.

Development documentation: [https://wanglin2.github.io/mind-map/#/doc/zh/](https://wanglin2.github.io/mind-map/#/doc/zh/)

2.A web mind map, developed based on the mind map library, Vue2. can be deployed to your server.

Online address: [https://wanglin2.github.io/mind-map/](https://wanglin2.github.io/mind-map/)

In addition, a client is also available for download, supporting `Windows`, `Mac` and `Linux`, download address:

Github：[releases](https://github.com/wanglin2/mind-map/releases)。

Baidu cloud disk: [地址](https://pan.baidu.com/s/1huasEbKsGNH2Af68dvWiOg?pwd=3bp3)。

# Characteristic

- [x] Plug-in architecture, in addition to the core functions, other functions are provided as plug-ins, which can be used on demand and reduce the packaging volume
- [x] Support logical structure chart, mind map, organization chart, directory organization chart, time axis, and fishbone diagram
- [x] A variety of built-in themes allow highly customized styles and support for registering new themes
- [x] Support shortcut keys
- [x] Node content supports pictures, icons, hyperlinks, notes, labels, and summaries
- [x] Support forward and backward
- [x] Support dragging and zooming
- [x] Support two multi-selection methods of right button and Ctrl+left button
- [x] Support node free dragging and dragging adjustment
- [x] Supports multiple node shapes
- [x] Support exporting to `json`, `png`, `svg`, `pdf`, `markdown`, support importing from `json`, `xmind`, `markdown`
- [x] Support small map, support watermark
- [x] Support link

# Install

```bash
npm i simple-mind-map
```

# Use

Provide a container element with a width and height other than 0:

```html
<div id="mindMapContainer"></div>
```

In addition, set the `css` style:

```css
#mindMapContainer * {
  margin: 0;
  padding: 0;
}
```

Then create an instance:

```js
import MindMap from "simple-mind-map";

const mindMap = new MindMap({
  el: document.getElementById('mindMapContainer'),
  data: {
    "data": {
        "text": "根节点"
    },
    "children": []
  }
});
```

You can get a mind map.

Want to achieve more functions? can view [development documentation](https://wanglin2.github.io/mind-map/#/doc/zh/)。

# License

MIT

# WeChat exchange group

<img src="./qrcode.jpg" style="width: 300px" />

# buy the author a cup of coffee

> A box of thick coconut milk + half a box of pure milk + ice cubes + coffee liquid = raw coconut latte yyds

<p>
  <img src="./web/src/assets/img/alipay.jpg" style="width: 300px" />
  <img src="./web/src/assets/img/wechat.jpg" style="width: 300px" />
</p>