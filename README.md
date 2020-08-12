# 会員制掲示板アプリの作成

本リポジトリは、Webアプリケーションの基礎として会員制の掲示板サービスをPythonのフレームワークであるFlaskを利用し作製したものである。

『仕様』
- 会員の者のみ（ユーザ、pw）ログインして掲示板にコメントを投稿できる（bbs_login.pyで管理）
![掲示板 001](https://user-images.githubusercontent.com/62229682/90041222-f8fa1200-dd03-11ea-90ee-7b1adcc5496f.jpeg)
- 各ユーザの投稿をメイン画面で時系列で表示して閲覧可能
![掲示板 002](https://user-images.githubusercontent.com/62229682/90041230-fac3d580-dd03-11ea-86fe-48f6f41ac8fa.jpeg)
- 投稿のデータは、{ユーザ名、投稿内容、時刻}のJSON形式で保存される
- 未登録ユーザはメイン画面を見れず、書き込みもできない
