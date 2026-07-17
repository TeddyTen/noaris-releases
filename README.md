# noaris-releases

Noaris(製品A)の公開配布リポジトリ。

- `noaris/latest.json` — tauri-plugin-updater が参照する更新マニフェスト(GitHub Pagesで配信)
  - 本番URL: https://updates.slovia.jp/noaris/latest.json(CNAME設定後)
  - Pages既定URL: https://teddyten.github.io/noaris-releases/noaris/latest.json
- バイナリ実体(DMG / .app.tar.gz / .sig)は本リポジトリの **GitHub Releases** に置く。
  `latest.json` 内の `url` はそのリリースアセットURLを指す。

リリース手順は本体リポジトリの docs/release-ops.md を参照。
