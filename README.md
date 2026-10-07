# 霓虹贪吃蛇

一个无需安装依赖、可直接部署到 GitHub Pages 的网页版贪吃蛇。

## 在线运行

发布后访问：`https://KIMI888UI.github.io/-/`

## 本地运行

```bash
python3 -m http.server 8000
```

然后打开 <http://127.0.0.1:8000/>。

## 操作

- 方向键或 WASD：移动
- P：暂停 / 继续
- 移动设备：在棋盘上滑动

## 发布到 GitHub Pages

1. 将代码推送到 GitHub 的 `main` 分支。
2. 打开仓库的 **Settings → Pages**。
3. 选择 **Deploy from a branch**、`main` 和 `/ (root)`。
4. 保存后等待构建完成，再打开仓库生成的 Pages 地址。
