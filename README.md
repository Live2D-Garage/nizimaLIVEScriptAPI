# nizima LIVE Script API (β)

## 概要
[nizima LIVE](https://nizimalive.com/)で利用できるスクリプトについてのリポジトリです。

仕様はnizima LIVE1.7時点でβ版のため、変更される可能性があります。

### スクリプトの種類
アプリケーション全体で管理されるアプリケーションスクリプトと、モデルごとに管理されるモデルスクリプトがあります。

配置する場所が異なり、できる操作も多少の違いがあります。

JavaScriptで記載します。

### イベントの種類
以下のようなタイミングでスクリプトを制御できます。
* スクリプトの有効/無効を切り替えた時
* 初期化完了時
* 更新時
* 描画時
* マウス、キーの入力時
* モデルの削除時

### オブジェクトの種類
以下のようなオブジェクトにアクセスして、情報を取得したり操作したりできます。
* Live : グローバルなオブジェクト
* Application : アプリケーション全体の情報
* Scene : 一つのウィンドウ内のすべてのオブジェクトを管理
* Model : 一つのモデルの情報
  * Parameter : 各パラメータ情報
  * Part : 各パーツ情報
  * Drawable : 各描画オブジェクトの情報
  * Motion : 各モーションの情報
  * Expression : 各表情の情報

## サンプル

https://github.com/Live2D-Garage/nizimaLIVESampleScript

## 仕様

https://live2d.github.io/nizimaLIVEScriptAPI
