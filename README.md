# 保育園シフト作成

保育園の月ごとのシフト表を自動で作るツールです。

- 使う: https://suzu-tatando.github.io/hoiku-shift/
- `index.html` 1つで動きます。ダウンロードしてダブルクリックで開いても使えます（インターネット接続は不要）。
- 入力した内容（職員名・休みなど）は、使っている人のブラウザの中にだけ保存され、どこにも送信されません。

シフトの計算には [HiGHS](https://highs.dev)（MIT License）と [highs-js](https://github.com/lovasoa/highs-js)（MIT License、`LICENSE-highs-js.txt`）を使っています。
