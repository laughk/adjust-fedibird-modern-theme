# adjust-fedibird-modern-theme

[![](https://img.shields.io/badge/Install%20directly%20with-Stylus-116b59.svg)](https://userstyles.world/api/style/8654.user.css)

fedibird.com のモダンテーマ（ダーク・ライト共通）のデザインを調整する stylus

![screenshot1](images/screenshot1.png)

## ℹ 2023-02-25 追記

バージョン [20230222.1 ](https://github.com/laughk/adjust-fedibird-modern-theme/releases/tag/20230222.1) までに相当する内容は [mastodon/fedibird](https://github.com/fedibird/mastodon) に取り込まれています。

そのため、このユーザースタイルを導入する必要は特にないでしょう。

### 参考情報

- fedibird の 2023-02-25 の更新内容に関するアナウンス
  - https://fedibird.com/@noellabo/109924152226393671
- 対象コミット
  - https://github.com/fedibird/mastodon/commit/c663686b8550162923a1fb9ca27baccfa3336e6a
  - https://github.com/fedibird/mastodon/commit/dc7439aeda07a03f727451013aed369654223b2e

## ⚠ 注意

基本的に作者が fedibird.com を使いやすくすることを目的としているため、このスタイルを適用して発生する一切の事象に作者は責任を持てません。自己責任のもとでご利用ください。

## この userstyle でやること

このスタイルでは fedibird.com のモダンテーマそのままでは見づらい、使いづらいと作者が感じている部分を以下のとおりに修正するものです

- アクションボタンのテキストを常時非表示にします
- 引用に含まれる投稿の表示を調整します
    - 引用されたユーザー情報の表示位置（アイコン、インスタンス名）を調整
    - 画像をはみ出ないようにサイズ調整
    - テキストと境界の余白を調整
- misskey.io などで使われる横に長い絵文字が圧縮されないように調整


## 使い方

1. ブラウザ拡張 stylus を導入してください
    - 公式: [openstyles/stylus: Stylus - Userstyles Manager](https://github.com/openstyles/stylus/)
    - Chrome: [Stylus - Chrome ウェブストア](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne)
    - Firefox: [Stylus – 🦊 Firefox (ja) 向け拡張機能を入手](https://addons.mozilla.org/ja/firefox/addon/styl-us/)
2. UserStyles.world の以下のページの「Install」から導入してください
    - [Adjust-fedibird-modern-theme — UserStyles.world](https://userstyles.world/style/8654/adjust-fedibird-modern-theme)

⚠前提として、fedibird.com にて「ユーザー設定」→「外観」にある「サイトテーマ」から「モダン（ダーク）」または「モダン（ライト）」を選択している必要があります。

## 調整内容の詳細

### アクションボタンのテキスト非表示

#### 調整前

![action button before](images/screenshot-action-button-before.png)

#### 調整後

![action button ajusted](images/screenshot-action-button-adjusted.png)

- 常時テキストを非表示にします


### 引用に含まれる投稿の表示調整

#### 調整前

![quote before](images/screenshot-quote-before.png)

パブリックページ内の引用

![quoted at public before](images/screenshot-quoted-at-public-page-before.png)

#### 調整後

![quote ajusted](images/screenshot-quote-ajusted.png)

パブリックページ内の引用

![quoted at public ajusted](images/screenshot-quoted-at-public-page-ajusted.png)

- 引用元アカウント情報のアイコンと名前, id の被りを解消します
- 引用テキストと境界の隙間を調整します
- 引用している画像が枠に収まるように調整をします

ℹ️ この調整は意図したものではありませんが「マテリアル（v1-dark）」「マテリアル（v1-light）」「マテリアル（v2-dark）」「マテリアル（v2-light）」などの他のテーマの場合でも調整されることを確認しています。

### misskey.io などで使われる横に長い絵文字が圧縮されないようにする調整

#### 調整前

![wide emoji before](images/screenshot-wide-emoji-before.png)

#### 調整後

![wide emoji ajusted](images/screenshot-wide-emoji-ajusted.png)


## License

MIT License

----

## What's this userstyle do?

This style fixes the following areas of the fedibird.com modern theme that the author feels are difficult to see and use

- Hide the text of the action buttons at all times
- Adjust the display of posts included in quotes
    - Adjust display position (icon, instance name) of quoted user information
    - Adjust the size of images so they do not overflow
    - Adjust text and border margins
- Adjust to avoid compression of long horizontal emojis used in misskey.io, etc.

(Translated with www.DeepL.com/Translator)
