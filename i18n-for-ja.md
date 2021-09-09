
日本語のみを表示し、
多言語切替機能を非表示とすることを提案されたため、
英語のファイルを日本語に翻訳して使用することとする。

# 作業ログ

## 言語選択ボタンを削除

`src/templates/partials/i18n.hbs` の `ul#i18n-buttons[aria-labelledby="i18n-settings"]` をコメントアウト

## ビルドする言語を絞る

`package.json` の `languages` を、 `"en"` 以外の要素を削除する

## 翻訳

- src/data/en.ymlを編集する
- src/data/reference/en.jsonを編集する
- src/data/examples/en以下のファイルを編集する

ドキュメントが追加された場合は、
随時上記のファイルの差分を確認し、
英語用のファイルを編集する。
