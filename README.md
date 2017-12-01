# Bainu WebView

## 自定义分享

### Bainu里分享
在网页的head里添加以下标签来自定义链接属性（分享时）。
```
// 必填，不能超过512字节
<meta name="bainu-share-title" content="我的标题" />
// 选填
<meta name="bainu-share-url" content="http://www.example.com" />
// 选填
<meta name="bainu-share-image" content="http://www.example.com/icon.jpg" />
// 选填，不能超过1kb
<meta name="bainu-share-desc" content="我的描述内容" />
```

### 分享到微信
如果网页head里添加下面的标签的话，点击右上角按钮就会出现分享到微信和微信朋友圈的选项。
```
// 必填，不能超过512字节
<meta name="wechat-share-title" content="我的标题" />
// 选填
<meta name="wechat-share-url" content="http://www.example.com" />
// 选填，图片大小不能超过32kb
<meta name="wechat-share-image" content="http://www.example.com/icon.jpg" />
// 选填，不能超过1kb
<meta name="wechat-share-desc" content="我的描述内容" />
```