# 张秋之 · 写作作品集

纯静态网站，无需安装依赖或构建。首页为 `index.html`。

## GitHub Pages

在仓库 Settings → Pages → Build and deployment 中选择 GitHub Actions。
推送至 main 后，Deploy portfolio to GitHub Pages 工作流会发布网站。

## 本地查看

```sh
python3 -m http.server 8765
```

页面与资源使用相对路径，支持仓库子路径部署。
