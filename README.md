# BUSTA-ROW Official Website

DJ / Producer **BUSTA-ROW** の公式サイト（GitHub Pages）。

## 構成

```
index.html        サイト本体（HTML / CSS / JS を1ファイルに収録）
img/              写真・ジャケット画像
audio/            MIX音源（現在は仮のデモ音源）
.nojekyll         GitHub Pages でそのまま配信するための設定
```

## 差し替え方法

| 内容 | ファイル / 場所 |
|---|---|
| トップの写真 | `img/top-portrait.jpg`（縦長 2:3 推奨） |
| SEE BUSTA-ROW LIVE の写真 | `img/live-stage.jpg`（横長 16:9 推奨） |
| ジャケット | `img/wakaraseru.jpg` / `img/wakaraseru-remix.jpg`（正方形） |
| LIVE MIX 2026 | `audio/demo-mix.mp3` を差し替え（同じファイル名にするか、`index.html` の `src` を変更） |
| HOUSE MIX 2026 | `audio/demo-house-mix.mp3` |

- GitHub は 1 ファイル 100MB まで。長尺の MIX は 128kbps 程度の MP3 にすると 1 時間で約 58MB に収まります。
- 文章は `index.html` 内で、日本語は `class="ja"`、英語は `class="en"` の要素に入っています。

## 公開

GitHub の **Settings → Pages** で、Branch を `main` / `/ (root)` にして保存すると公開されます。
