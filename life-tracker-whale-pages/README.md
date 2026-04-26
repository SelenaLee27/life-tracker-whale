# 轨迹 PWA

这是 `轨迹` 的 GitHub Pages 发布目录。上传本目录内的全部内容到仓库根目录即可。

## 目录结构

```text
/
├─ index.html
├─ manifest.webmanifest
├─ sw.js
├─ icons/
│  ├─ icon-192.png
│  └─ icon-512.png
├─ README.md
└─ .gitignore
```

## 部署方式

1. 进入 GitHub 仓库。
2. 删除旧的版本化文件，例如 `life-tracker-whale-1.0-*`、`life-tracker-whale-1.1-*`。
3. 上传本目录里的所有文件和 `icons` 文件夹。
4. 在 `Settings` -> `Pages` 中选择 `Deploy from a branch`，分支选择 `main`，目录选择 `/root`。
5. 手机访问 GitHub Pages 的 HTTPS 地址后，从 Chrome 菜单安装应用。

## 当前版本

应用版本：`1.1.0`

更新内容：

- 转盘动画分层处理，点击中心文字后转盘会旋转。
- 日程卡片固定渲染所有启用方向，默认折叠，可同时展开多个方向。
- 统一日程分类删除按钮字号。
- 记账说明展开时隐藏录入、筛选、明细和实时汇总。
- PWA 缓存文件改用稳定命名，后续升级只需覆盖同名文件。
