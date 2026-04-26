# 轨迹 PWA 1.0

这是可以直接部署到 GitHub Pages 的发布目录。

## 包含文件

- `index.html`：应用入口
- `life-tracker-whale-1.0.webmanifest`：PWA 安装配置
- `life-tracker-whale-1.0-sw.js`：离线缓存脚本
- `life-tracker-whale-1.0-icon-192.png`：PWA 图标
- `life-tracker-whale-1.0-icon-512.png`：PWA 图标

## GitHub Pages 上传方式

1. 在 GitHub 新建一个公开仓库，例如 `life-tracker-whale`。
2. 进入仓库，点击 `Add file` -> `Upload files`。
3. 上传本目录里的所有文件，不要只上传 HTML。
4. 点击 `Commit changes`。
5. 进入 `Settings` -> `Pages`。
6. Source 选择 `Deploy from a branch`。
7. Branch 选择 `main`，Folder 选择 `/root`。
8. 保存后等待 GitHub 生成访问地址。

手机访问生成的 HTTPS 地址后，再从 Chrome 菜单选择“安装应用”或“添加到主屏幕”。
