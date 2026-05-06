# 建筑结构检测技术实验报告工具

## 手机端使用方式

iPhone 可以运行这个工具，但不要把 `index.html` 当作普通文件在微信、QQ 或“文件”预览里打开。应把本目录作为静态网页发布，然后用 Safari 访问。

推荐方式：

1. 将 `index.html`、`manifest.webmanifest`、`icon.svg` 三个文件上传到 GitHub Pages、Netlify、学校服务器或任意静态网站空间。
2. 用 iPhone Safari 打开发布后的 HTTPS 链接。
3. 点击 Safari 分享按钮，选择“添加到主屏幕”。
4. 之后从主屏幕打开，效果接近一个手机 App。

临时方式：

在电脑上进入本目录运行：

```bash
python3 -m http.server 8000 --bind 0.0.0.0
```

手机和电脑连接同一个 Wi-Fi 后，用 Safari 打开：

```text
http://电脑局域网IP:8000/index.html
```

注意：实验数据保存在当前浏览器本地。换手机、换浏览器或清理 Safari 网站数据后，本地保存的数据不会自动同步。
