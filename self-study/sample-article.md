---
title: サンプル記事（公開テスト）
date: 2025-09-21
---

# サンプル記事（公開テスト）

これは private モノレポから公開用 GitHub Pages リポジトリへ同期するためのテスト記事です。

- 目的: 手動公開フローの確認
- 公開先: `<USER>.github.io/self-study/` 配下（スクリプト既定値）

## 手順（メモ）

1. このファイルを作成
2. `bash scripts/publish-pages.sh "publish: sample article"`
3. ブラウザで `https://<USER>.github.io/self-study/sample-article` を確認

公開確認後はこのファイルを削除して再実行するとリモートからも消えます。
