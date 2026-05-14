# Midjourney illustration assets

Midjourneyで生成したイラストは、このフォルダに配置します。

## Naming rules

形式:

```text
mj-{section}-{purpose}-{ratio}.{ext}
```

ルール:

- 小文字英数字とハイフンのみ
- 拡張子は原則 `.webp`、編集前の原本を残す場合のみ `.png`
- LPで使う最終画像は横幅1600px前後に圧縮
- 文字入り画像は作らない。テキストはHTML/CSS側で載せる
- Midjourneyの出力をそのまま使わず、必要なら余白・色味・破綻を調整してから配置する

## Required files

| File | Use | Ratio |
| --- | --- | --- |
| `mj-hero-homevisit-4x3.webp` | ファーストビュー。医師・看護師・診療車・住宅街 | 4:3 |
| `mj-work-visit-bag-4x3.webp` | 仕事紹介。訪問バッグ、物品、準備 | 4:3 |
| `mj-training-meeting-4x3.webp` | 教育。医師と看護師の相談・予定確認 | 4:3 |
| `mj-area-clinic-car-16x9.webp` | 地域感。成田周辺の住宅街と診療車 | 16:9 |
| `mj-contact-chat-1x1.webp` | 最終CTA。スマホ相談、吹き出し、訪問バッグ | 1:1 |
| `mj-ad-nurse-4x5.webp` | 広告用。看護師、訪問バッグ、診療車 | 4:5 |

## Optional working files

編集前や候補画像を残す場合は、`assets/illustrations/source/` に入れます。

例:

```text
source/mj-hero-homevisit-4x3-v01.png
source/mj-hero-homevisit-4x3-v02.png
source/mj-hero-homevisit-4x3-upscaled.png
```

LPで読み込むのは、このREADMEの `Required files` にある最終 `.webp` のみです。
