# C級/自己紹介ページDB編（評価ボタン）

## 1.概要
Goodボタン/Badボタンを設置する。加えて、ボタンを押下した合計回数を表示出来るようにする。
<br><br>

## 2.レビューポイント
### 機能要件
* レベル1：Goodボタンを設置する。押下した際にはその情報をDBに記録する。
* レベル2：Badボタンを設置する。押下した際にはその情報をDBに記録する。
* レベル3：ボタンの押下回数の合計をボタンの中 or ボタンの近くに配置する。

※評価機能の実現方式やテーブル設計は開発者の判断に委ねる。

### 成果物の前提条件
* PHPとMySQLが使える状態であること。
* テーブルデータをエクスポートして提出する or CREATE TABLE 文をテキストファイルとして提出する。

### 使う技術の一例
* formタグ（HTML）
* POST（PHP）
* SELECT、COUNT、WHERE（SQL）

<br><br>

## 3.画面設計
<img width="700" alt="image" src="https://github.com/ppf-academy/class-c-01-06/blob/main/image/SelfIntroduction6_layoutmap.png">

※デザインは上の画像と一致する必要はない。
