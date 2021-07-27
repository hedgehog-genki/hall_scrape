# 詳細
パチンコ店のスロット出玉情報をスクレイピングしてCSVで出力するためのツールです。<br>
<br>
https://papimo.jp/<br>
上記に掲載されているパチンコ店であれば出玉情報を取得することが可能です。<br>
<br>

## 使用動画
![scrape](https://user-images.githubusercontent.com/84561429/127130952-69131b46-3a8e-4c2c-a90f-c924bd26fa2f.gif)

## 制作背景
過去に同様のツールを購入し、使用したことがあり、自身でも再現をしたいと考え、制作を行いました。

## 開発環境
Python<br>
Google Colabratory<br>
<br>

## 使用上の注意点
使用する上で、変更が必要な箇所があるので、下記に記述しています。
状況に合わせて変更することで、お店ごとに情報を取得することができます。

### 店ごとに変更しなければならないところ

1.71行目の台番号のリスト作成（デフォルトは4と9を抜いている）<br>
2.78行目のURLリストの日付を指定<br>
3.170行目の画像の保存先のパス<br>
4.181行目の画像の読み取り先のパス<br>
<br>

#### データサイトごとに変更しなければならないところ
1.193行目のスタートの座標<br>
2.206行目のy座標1に付き、何PXか<br>
<br>
## 注意点
<br>
過度なスクレイピングは禁止されていますので、1台のデータを取得した後に1秒待機するように設定してます。<br>
これ以上短くすることは規約違反になる可能性があるため、推奨致しません。<br>
