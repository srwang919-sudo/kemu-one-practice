# 自定义卡面 / 卡包贴图

把同名文件放到这个文件夹后，刷新或重新 `npm run build` 即可覆盖内置贴图（优先于 `public/textures/`）。

支持的文件名（`.png` / `.webp` / `.jpg`）：

- `pack-front` `pack-back` `pack-side`
- `card-back`
- `card-cat` `card-dog` `card-fish` `card-bird` `card-rabbit` `card-butterfly` `card-whale` `card-dragon`

建议比例：卡面约 2.5:3.5（例如 800×1120），卡包约 2:3。圆角可以画在图里，也可以交给三维模型裁切。
