# Potover Batch

公開RSSから記事メタデータを毎日収集し、Potover本体の`data/articles.json`を更新します。本文は保存しません。

GitHub Actionsの`POTOVER_REPO_TOKEN` secretに、Potoverへpushできるfine-grained PATを登録してください。毎日UTC 03:00（日本時間12:00）に実行します。
