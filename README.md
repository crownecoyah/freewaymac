# freewaymac

FreeWayMacの公開紹介ページとバイナリ配布専用リポジトリです。アプリのソースコードは含みません。

- Web: https://crownecoyah.github.io/freewaymac/
- Pages: main /docs
- ZIP: https://github.com/crownecoyah/freewaymac/releases/download/v1.0.0/FreeWayMac-v1.0.0.zip
- 利用条件: docs/LICENSE.txt

ダウンロード数の確認（Releaseアセットの取得数。利用者数ではありません）:

```sh
gh api repos/crownecoyah/freewaymac/releases/tags/v1.0.0 --jq '.assets[] | select(.name=="FreeWayMac-v1.0.0.zip") | .download_count'
```

GitHubが自動生成するSource codeアーカイブには、この公開ページのファイルのみが含まれます。
