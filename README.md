# 学習ログ

勉強したこととその日の調子を記録し、過去の学習ログを見返せるシンプルなアプリです。

- 画面はシンプルなHTML/CSS/JavaScriptで構成
- 学習メモとその日の調子をブラウザの `localStorage` に保存
- 記録を検索・編集・削除し、学習コンディションの推移を表示
- 1日1件の保存・上書き・編集・削除が可能

## 実行方法

ブラウザで `index.html` を開くだけで利用できます。

```bash
python3 -m http.server 8000
```

その後、ブラウザで `http://localhost:8000` を開くと動作確認できます。

## 主なファイル

- `index.html` : アプリのHTML
- `styles.css` : レイアウトとデザイン
- `app.js` : 学習ログの保存・表示・検索・編集ロジック
- `image.png` : 画面イメージ

## 参考元

- https://github.com/gigaschool/tiny-diary

## ライセンス

元リポジトリと同じく MIT License です。
