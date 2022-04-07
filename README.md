# word_crowd
 
Google Colab上で日本語のテキストファイルからワードクラウドを作成する。


# Demo

夏目漱石「こころ」より

[青空文庫](https://www.aozora.gr.jp/cards/000148/card773.html)

![from_kokoro](./wordcloud.png) 

# Requirement

必要なものは下記の2点のみ
- Googleアカウント
- ワードクラウドを作成したいテキストファイル

# Usage

- Google DriveのMy Drive上にレポジトリのfontディレクトリを保存してください。

- word_cloud.ipynbをgoolge colab上で開いてください。

- `#データの取り込み。ファイルのパスや文字コードは処理ファイルに合わせてください。デモとしてkokoro.txtを使っています。
f = open('/content/drive/MyDrive/kokoro.txt', encoding ='shift_jis')`部分でファイルパスを処理したいファイルに変更してください。

- `#保存
wordcloud.to_file("/content/drive/MyDrive/wordcloud.png")`部分で出力するワードクラウドの画像の名前、保存先を指定して、すべてのセルを実行してください。
