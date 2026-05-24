# Hermes Dashboard 主题清单

## 1. 🌟 蝶彩 / Butterfly Color (buc)

| 项目 | 说明 |
|------|------|
| **文件名** | `buc.yaml` |
| **标签** | 蝶彩 |
| **风格** | 全浅色渐变，彩虹蝴蝶动画效果 |
| **背景** | `#f0f4ff` 浅蓝白 |
| **字体** | 17px 系统字体 |
| **圆角** | 0.75rem |
| **特点** | 根背景30秒渐变流动、侧栏相同动画、10个按钮依次轮换颜色（40秒循环）、右侧主内容区按页面匹配浅色调、标题用 Georgia 衬线字体、"Hermes Agent" mix-blend-mode 反色效果、禁用深色 Backdrop、移动遮罩白色模糊 |

### 按钮颜色轮换顺序

| 按钮 | 初始色 | 颜色名称 |
|------|--------|---------|
| 1 Sessions | `#fde8e8` | 浅玫红 |
| 2 Analytics | `#fef3cd` | 浅琥珀 |
| 3 Models | `#d1fae5` | 浅翠绿 |
| 4 Logs | `#dbeafe` | 浅天蓝 |
| 5 Skills | `#ede9fe` | 浅紫 |
| 6 Plugins | `#fce7f3` | 浅粉 |
| 7 Profiles | `#ffedd5` | 浅橙 |
| 8 Config | `#ccfbf1` | 浅青绿 |
| 9 Keys | `#fef9c3` | 浅黄 |
| 10 Docs | `#fae8ff` | 浅紫粉 |

右侧主内容区使用更浅版本（约 `#fef2f2` 级别），切换页面时1秒平滑过渡。

---

## 2. ❄️ White（极简白）

| 项目 | 说明 |
|------|------|
| **文件名** | `white.yaml` |
| **标签** | White |
| **风格** | 纯白背景，极简 |
| **背景** | `#f8f9fa` |
| **字体** | 15px 系统字体 |
| **圆角** | 0.5rem |
| **特点** | 最简配置，无 customCSS，靛蓝主色按钮 |

---

## 3. 🎨 White Colorful（白底彩色）

| 项目 | 说明 |
|------|------|
| **文件名** | `white-colorful.yaml` |
| **标签** | White Colorful |
| **风格** | 白底 + 紫粉色调，加载 Google Fonts |
| **背景** | `#f5f7fa` |
| **字体** | 15px **Inter** / JetBrains Mono（Google Fonts） |
| **圆角** | 0.75rem |
| **特点** | 需要联网加载字体，紫主色 `#8b5cf6`，粉次要 `#be185d` |

---

## 4. 💖 Vibrant Light（荧光粉红）

| 项目 | 说明 |
|------|------|
| **文件名** | `vibrant-light.yaml` |
| **标签** | Vibrant Light |
| **风格** | 浅蓝底 + 荧光粉主色 |
| **背景** | `#f0f4ff` |
| **字体** | 17px 系统字体 |
| **圆角** | 0.625rem |
| **特点** | 荧光粉主色 `#ec4899`，紫色次要 `#7c3aed`，17px大字体 |

---

## 5. 🌈 Pastel Rainbow（彩虹浅色）

| 项目 | 说明 |
|------|------|
| **文件名** | `pastel-rainbow.yaml` |
| **标签** | Pastel Rainbow |
| **风格** | 每个部件不同浅色 |
| **背景** | `#ffffff` |
| **字体** | 17px 系统字体 |
| **圆角** | 0.75rem |
| **特点** | 卡片淡粉 `#fff0f3`，弹窗淡杏 `#fff7ed`，次要淡绿 `#f0fdf4`，强调淡紫 `#f5f3ff`，按钮紫 `#a78bfa` |

---

## 6. 🌊 Rainbow Dynamic（全浅渐变· 旧版）

| 项目 | 说明 |
|------|------|
| **文件名** | `rainbow-dynamic.yaml` |
| **标签** | Rainbow Dynamic |
| **风格** | 白底 + 侧栏渐变动画，每个按钮不同色（固定） |
| **背景** | `#ffffff` |
| **字体** | 17px 系统字体 |
| **圆角** | 0.75rem |
| **特点** | 侧栏18秒渐变动画、10个按钮各不同固定色、右侧无页面匹配颜色、Hermes Agent 反色 |

---

## 对比总览

| 主题 | 动画 | 按钮颜色 | 右侧匹配 | 字体大小 | 特殊字体 | 复杂度 |
|------|------|---------|---------|---------|---------|-------|
| **蝶彩 (buc)** | ✅ 三处动画 | 轮换渐变 | ✅ 页面匹配 | 17px | Georgia 标题 | ⭐⭐⭐ |
| White | ❌ | 默认 | ❌ | 15px | 无 | ⭐ |
| White Colorful | ❌ | 默认 | ❌ | 15px | Inter/Clash | ⭐ |
| Vibrant Light | ❌ | 默认 | ❌ | 17px | 无 | ⭐ |
| Pastel Rainbow | ❌ | 各不同 | ❌ | 17px | 无 | ⭐⭐ |
| Rainbow Dynamic | ✅ 侧栏 | 各不同固定 | ❌ | 17px | Georgia 标题 | ⭐⭐ |
