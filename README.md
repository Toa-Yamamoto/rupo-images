# rupo-images

ルポ（@rupo.ai）Threads運用システム用の画像ライブラリ。

実画像は `library/` ディレクトリ、メタデータは `library.json` で管理。

## 公開URL形式

```
https://raw.githubusercontent.com/Toa-Yamamoto/rupo-images/main/library/<filename>
```

このURLを Threads API の `image_url` パラメータに渡すことで画像付き投稿が可能。

## ファイル構成

- `library.json` — 画像のメタデータ（説明・タグ・URL）
- `library/` — 実画像ファイル
