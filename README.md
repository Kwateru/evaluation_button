![image](https://github.com/Kwateru/evaluation_button/assets/33171676/9cec7615-e6e3-4c84-b754-ffecc0453500)

## 1.概要
Goodボタン/Badボタンを設置する。加えて、ボタンを押下した合計回数を表示出来るようにする。
<br><br>

## 2.機能要件
* レベル1：Goodボタンを設置する。押下した際にはその情報をDBに記録する。
* レベル2：Badボタンを設置する。押下した際にはその情報をDBに記録する。
* レベル3：ボタンの押下回数の合計をボタンの中 or ボタンの近くに配置する。

## 3.仕様動作のイメージ
![Image_20240619_011923_873 (1)](https://github.com/Kwateru/evaluation_button/assets/33171676/0d6d848b-e76c-4e01-bc5d-c171bfb829fc)

## 4.使用技術
| Category          | Technology Stack    | 
| ----------------- | ------------------- | 
| Frontend          | HTML, CSS           | 
| Backend           | PHP                 | 
| Database          | phpMyAdmin          | 
| Environment setup | Docker              | 
| etc.              | Git, GitHub, vscode | 

## 5.今後の展望
* Ajaxを使って投票時の画面上部への遷移を防ぎたい。
* 1ユーザー1投票のように制限を設けてみたい。
