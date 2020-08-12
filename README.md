# 会員制掲示板アプリの作成

本リポジトリは、Webアプリケーションの基礎として会員制の掲示板サービスをPythonのフレームワークであるFlaskを利用し作製したものである。

『仕様』
- 会員の者のみ（ユーザ、pw）ログインして掲示板にコメントを投稿できる（bbs_login.pyで管理）
- 各ユーザの投稿をメイン画面で時系列で表示して閲覧可能
- 投稿のデータは、{ユーザ名、投稿内容、時刻}のJSON形式で保存される
- 未登録ユーザはメイン画面を見れず、書き込みもできない
