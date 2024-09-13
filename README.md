# Markdown 转换微信公众帐号内容

## install
```
pnpm i
pnpm run watch
pnpm run build
```

---

一个在线将`Markdown`内容转换成微信公众帐号内容的工具。

- 线上地址: <http://md.qikqiak.com/>
- 意见反馈: <https://github.com/cnych/markdown-weixin/issues/new>

### 效果图
![dashboard](http://sdn.haimaxy.com/screenshots/markdown-weixin.jpg)

### TODO

- 自动保存功能
- 增加多种主题样式
- 增加本地图片自动上传图床功能

### Changelog

#### 版本号：V1.2.2
更新日志：2020-03-19

- FIX 代码块出现数字编号的 BUG

##### 版本号：V1.2.1
更新日期：2018-07-12

- FIX 复制内容错误的BUG
- 优化页面主题代码

##### 版本号：V1.2.0
更新日期：2018-07-01

- 增加编辑区域和预览区域同步滚动
- 更改页面样式为左右结构，实时预览
- 直接复制内容到粘贴板，不要手动复制
- 替换`google-code-prettify`源为国内`CDN`源
- 支持更换代码样式主题
- 代码长度溢出时横向滚动


### LICENSE

MIT. Thanks for @barretlee.
