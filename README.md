# README



##　アプリケーション名
- buy-quickly


## 開発環境
- Ruby 2.6.5
- Ruby on Rails 6.0.0
- database postgreSQL


##　アプリケーション概要
- LINEのBotを用いたショッピング検索システムです。トーク画面に入力したワードに応じて楽天市場から人気ランキング上位3品をトーク画面に表示します。


## URL
- <a href="https://lin.ee/Ww3qVe1"><img src="https://scdn.line-apps.com/n/line_add_friends/btn/ja.png" alt="友だち追加" height="36" border="0"></a>


## 利用方法
- 上記URLからLINEのお友達追加をお願いします。
- Botのトーク画面にて、欲しい商品のワードを送信ください。
- 楽天市場の商品の中から、ワードにヒットした商品について人気ランキング上位3品をご返信します。


## 目指した課題解決

### 課題
ペルソナ
- 頻繁に使うアプリからショッピング情報にアクセスしたい人
- ネットショッピングにかける時間を短縮したい人
- 気になるアイテムについて、人気や売れ筋のものだけ簡単に確認したい人

### 解決したい課題
- ショッピングサイトは便利だが、商品を探すまでに使用中のアプリからショッピングサイトへ移動し、検索し、何百件という商品を閲覧するのに時間を費やしてしまいます。

### なぜ解決が必要か
- ショッピングに費やす時間、またはショピングサイトから得たい情報までのアクセスの時間を短縮できれば 、時間の有効活用ができます。


## 実装手順
- 楽天API取得
- LINEAPI取得
- コントローラーにボットに入力されたワードに応じて、楽天市場検索、結果の上位3品についての画像、説明文、価格を取得しトーク画面に表示