# OnStepX-Japanese-Website
Japanese Localization for OnStepX Website Plugin

OnStepXのWebsiteプラグインを日本語化したものです。

## 特徴
- UIの日本語化

## ライセンス
- **OnStepX**: GPLv3 (Original by Howard Dutton)
- Japanese translation by Kenichi Aihara
- このリポジトリの改変部分も **GPLv3** の下で公開します。

## 使い方
1. このリポジトリのファイルをダウンロードします。
2. website ディレクトリを OnStepX/src/plugins ディレクトリにコピーし、以下の例のように Plugins.config.h にエントリーを追加する必要があります。実際は、コメントアウト（//）を削除して有効化します。

- #define PLUGIN1 website
- #include "website/Website.h"

3. このプラグインを使用するには、OnStepX の Config.h ファイルで Wi-Fi を有効にする必要があります。例えば次のように設定します。

- #define SERIAL_RADIO WIFI_ACCESS_POINT

4. これにより、OnStepX の Wi-Fi および Web サーバー機能が有効になります。その後、OnStepX がこのプラグインを初期化して使用可能となります。
