# tou_controller

# 機能
## 次へ進む / 前へ戻る
前後の講義の動画に進むことができるボタンです。
## 連続自動再生
有効にすると、動画が終わったときに自動で次の動画に進み、再生されます。  
また、動画を開いたときに再生ボタンをおさなくても再生が始まります。

# 開発
1. npm run dev
    - `./dist`が生成される
1. Chromeの「拡張機能を管理」 > 「パッケージ化されていない拡張機能を読み込む」から、`./dist`を読み込む
