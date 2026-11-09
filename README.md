# 鸣濑白羽 · 濑户内船票 PCB

《Summer Pockets》鸣濑白羽主题的双面纪念板。正面以黑色阻焊、白色丝印和局部沉金表现人物。背面取高松至直岛宫浦港的船票为题，船名「あさひ」，日期 06.08。

![七个工程正面](images/editions.png)

## 工程与打样文件

五张人物图对应七个可编辑工程，其中林间插画有近景、中景和全景三个取景。每个目录包含嘉立创 EDA 专业版工程、Gerber 压缩包和可放大的正反面矢量预览。

| 款式 | 可编辑文件 | 制造文件 | 预览 |
| --- | --- | --- | --- |
| 蓝天 | [EDA 工程](boards/blue-sky/blue-sky.epro2) | [Gerber](boards/blue-sky/gerber.zip) | [正反面 SVG](boards/blue-sky/preview.svg) |
| 金扇 | [EDA 工程](boards/golden-fan/golden-fan.epro2) | [Gerber](boards/golden-fan/gerber.zip) | [正反面 SVG](boards/golden-fan/preview.svg) |
| 林间 · 近景 | [EDA 工程](boards/riverside-close/riverside-close.epro2) | [Gerber](boards/riverside-close/gerber.zip) | [正反面 SVG](boards/riverside-close/preview.svg) |
| 林间 · 中景 | [EDA 工程](boards/riverside-medium/riverside-medium.epro2) | [Gerber](boards/riverside-medium/gerber.zip) | [正反面 SVG](boards/riverside-medium/preview.svg) |
| 林间 · 全景 | [EDA 工程](boards/riverside-wide/riverside-wide.epro2) | [Gerber](boards/riverside-wide/gerber.zip) | [正反面 SVG](boards/riverside-wide/preview.svg) |
| 游戏立绘 | [EDA 工程](boards/game/game.epro2) | [Gerber](boards/game/gerber.zip) | [正反面 SVG](boards/game/preview.svg) |
| 动画立绘 | [EDA 工程](boards/anime/anime.epro2) | [Gerber](boards/anime/gerber.zip) | [正反面 SVG](boards/anime/preview.svg) |

[下载全部七款](https://github.com/shiroha777/shiroha-ferry-pcb/releases/tag/v1.0.0)

## 看细节

动画立绘的举手保留了蜷指间的空隙，指根和掌心的暗部用沉金表现。金扇礼装沿原图描出不同层次的刘海、鬓发与长发，腰带和袖口以密排线表现叠压暗部。

![金扇头发、衣褶和动画版举手的 Gerber 回渲](images/detail.png)

## 使用

1. 在嘉立创 EDA 专业版导入对应的 `.epro2`，打开 PCB 查看或编辑图层。
2. 查看同目录的 `preview.svg` 核对正反面。板外形约 49.87 × 99.87 mm，两个圆孔和顶部挂绳槽已写入制造文件。
3. 选择对应款式的 `gerber.zip` 打样。预览采用黑色阻焊、白色丝印、沉金配色。预览来自 Gerber 回渲，仍待实物验证。

## 来源与许可

本项目原创的船票版式、分层制图和 PCB 修改采用 **CERN-OHL-P-2.0**。许可范围、修改说明及第三方来源见 [NOTICE.md](NOTICE.md)。[许可证全文](LICENSE)
