# clean/ 目录

本目录用于存放 **无歌词空白播放器底图**（不含任何歌词文字）。

## 当前状态

- `placeholder.png` 是 1100×709 的浅灰占位图，仅用于在没有真实 clean 资源时让页面不报错。
- **CCD 系列（5 张）已就位**：`ccd-pink-diamond.png`、`ccd-silver-classic.png`、`ccd-rose-gold.png`、`ccd-black-retro.png`、`ccd-warm-gold.png`。
- **铁盒系列（5 张）已就位**：`tinbox-red-dot.png`、`tinbox-pink-grid.png`、`tinbox-cream-stripe.png`、`tinbox-blue-grid.png`、`tinbox-yellow-flower.png`。
- **电子宠物机系列（6 张）已就位**：`pet-kuromi.png`、`pet-melody.png`、`pet-pompompurin.png`、`pet-kitty.png`、`pet-cinnamoroll.png`、`pet-pochacco.png`。
- AI 音乐世界（ai-magic-world）目前仅一个 variant（music-default），继续沿用 `placeholder.png` 占位。

## 命名约定

- `ccd-{variantId}.png` — 复古 CCD 系列
- `tinbox-{variantId}.png` — 铁盒系列
- `pet-{variantId}.png` — 电子宠物机系列
- `ai-music-world-{variantId}.png` — AI 音乐世界
- `*-master.png` — 大模板共用底图

## 待补充

后续用户会按 `src/data/templates.ts` 中各 variant 的 `cleanPlayerImage` 字段补充真实无歌词图。
