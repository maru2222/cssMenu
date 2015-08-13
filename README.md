# cssMenu
cssだけで表示できる階層型メニュー

[Demo](http://style-type.net/githubDemo/cssmenu/index.html)

## 設定方法
* subMenu

subMenuは第一階層と第二階層とメニュー部分に広告的な枠を設ける場合は、その横幅を合わせた数値を設定。その為、外枠のsideMenuより幅が広くなることもある。

* 広告枠が必要無い時

subMenuと同じセレクタにnokoukoku追記

`<div class="subMenu nokoukoku">`

* 第三階層のメニュー

第三階層のメニューが含まれるclassにthirdMenuを追記

`<li class="thirdMenu"><a href="#">thirdMenu</a>`
