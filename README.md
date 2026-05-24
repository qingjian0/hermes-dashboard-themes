# Hermes Agent Dashboard Themes

Hermes Agent Web Dashboard 自定义浅色主题包。将 `.yaml` 文件放入 `~/.hermes/dashboard-themes/`，重启 dashboard 后在右上角主题下拉菜单中切换。

主题列表在 `theme_list.md` 中查看。

## 目录结构

```
dashboard-themes/
├── README.md               ← 本文档
├── theme_list.md           ← 主题清单（含截图说明）
├── buc.yaml                ← 🌟 [当前使用] 蝶彩 — 全浅色渐变彩虹主题
├── white.yaml              ← 极简白
├── white-colorful.yaml     ← 白底+紫粉彩色
├── vibrant-light.yaml      ← 荧光粉主色
├── pastel-rainbow.yaml     ← 每部件不同浅色
└── rainbow-dynamic.yaml    ← 全浅色渐变（上一版）
```

## 快速使用

```bash
# 1. 将主题文件复制到 ~/.hermes/dashboard-themes/
cp *.yaml ~/.hermes/dashboard-themes/

# 2. 切换主题（修改 config.yaml 中的 dashboard.theme）
#    或者直接在 dashboard 右上角 Palette 按钮中选择

# 3. 重启 dashboard
hermes dashboard --stop
hermes dashboard
```

## 安装说明

1. 确保 Hermes Agent Dashboard 已运行（`hermes dashboard`）
2. 将主题 YAML 文件放入 `~/.hermes/dashboard-themes/` 目录
3. 刷新页面，右上角 Palette 图标点击选择主题
4. 主题立即生效，本地存储记住选择

## 制作自定义主题

参考 Hermes 官方文档：在 `~/.hermes/dashboard-themes/` 放一个 `.yaml` 文件即可。

**简化写法：** 只需指定 `name`, `label`, `palette.background`, `palette.midground`, `colorOverrides` 即可，支持 `customCSS` 注入任意 CSS。

## License

MIT — 随便用，随便改。
