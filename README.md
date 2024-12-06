# ①課題番号-プロダクト名

リアルポケモンGO（もどき）アプリ

## ②課題内容（どんな作品か）

- 地図の任意の場所周辺半径1km以内で過去に観察された生き物を検索出来るアプリです。
- ※最初はポケモンGO風にするもりが色々と難しかったので「もどき」です。
- 生物の観察記録は「iNaturalist API」を用いて取得しています。

## ③DEMO
https://saetag.github.io/APIapp_TS28/
https://github.com/user-attachments/assets/5b582a7e-5bde-4019-98c4-7396d96620a6

## ④作ったアプリケーション用のIDまたはPasswordがある場合

- ID: 今回なし
- PW: 今回なし

## ⑤工夫した点・こだわった点

- 今回はGitHubで先にレポジトリ作成してコミット＆プッシュしてデプロイしました。
- .gitignoreでAPI keyを書いたファイルをアップロードしないようにしました。
- APIは一応4つ使っています（GeocodingAPI, Maps Javascript API, Firebase, iNaturalist）

## ⑥難しかった点・次回トライしたいこと(又は機能)

- 本当は「現在地を取得」ボタンを作って、それを押すと現在地を取得する機能もつけたかったのですが時間切れで叶いませんでした。
- Google Map API を用いて地図を表示するのにほとんどの時間が溶けました。
- 次回からはtilewind CSSを使ってみたいです、もうちょっとデザインをおしゃれにしたいです。
- jQueryをまだあんまり使えていないので、次回は積極的に使ってみたいです。

## ⑦質問・疑問・感想、シェアしたいこと等なんでも

- [感想]javasctiptをprogateやUdemyの教材で復習したら、段々となんとなくですがわかってきました。
- [参考記事]
  - 1. jsのモジュールを使う方法[https://ics.media/entry/16511/]
  - 2. gitignoreの書き方徹底解説[https://terapotan.hatenablog.jp/entry/WhatIsGitignore]
  - 3. Google Maps APIキーの取得・導入[https://x.gd/u8bJk]
