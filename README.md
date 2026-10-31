# 月の満ち欠け

月を動かし、宇宙からの位置・地球から見える形・夕方／真夜中／明け方／昼の空を比べる学習アプリです。タブレット横画面を基準にしています。

- GitHub Pages: https://learning-apps-jp.github.io/moon-phases/
- GAS版（全員・ログイン不要）: https://script.google.com/macros/s/AKfycbyl0RFMmG38JGvboq-lDHnQgBQPmMFn2y81K4Cp2gNgSk4W1f94ImPHZrS3nHdP_VAI/exec
- GitHub版の棚: https://learning-apps-jp.github.io/app-portal/
- GAS版の棚（従来の本人専用設定を維持）: https://script.google.com/macros/s/AKfycbz5IJTh3HM7E_Zb2R5UMPkVMHPVO7GFjp4KPgcCpRuskKDWaD1g67MqPT3rG335QlrLig/exec

## 使い方

月をドラッグ、軌道をタップ、スライダーや月の選択ボタンで位置を変更。再生で満ち欠けを連続表示。４つの時刻を選ぶと観察者と空の位置関係が連動します。人の表示はオン／オフできます。クイズは月の位置から形を予想します。

## モデルの範囲

満ち欠けは平均約29.5日周期。月齢は等速運動で求めた目安です。空の月は向きをそろえた記号で、実際の高度・方位・傾き・出没時刻の予測には使えません。地軸・軌道の傾き、楕円軌道、地球の公転の描画を省略しています。地球・月面は生成したイラストで、実際の地形ではありません。サイズ・距離は模式的です。

## ローカルで使う

配布ZIPでは「起動.cmd」または「dist/index.html」を開きます。このリポジトリではindex.htmlをブラウザーで開くだけで動きます。外部ライブラリ・カメラ・ユーザー登録は不要です。

## 確認

JavaScript構文、主要位相と中間の名称、４時刻の南中・地平線・地平線下を検査。1024×768の横画面で主要操作の収まりを確認。GitHub PagesのHTTP 200と棚のリンク、GAS版のログイン不要HTTP 200・満月と真夜中への切替・棚のリンクを確認しました。実機iPad Safariは未確認です。

参考：国立天文台「月はいつどんなふうに見える？昼間も見えるの？」 https://www.nao.ac.jp/faq/a0201.html
