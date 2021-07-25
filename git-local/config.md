# config

Git の設定・設定の確認を行うコマンド。

```
git config [name] ([value])
```

value 無しでコマンドを実行した場合、現在の設定を確認できる。

## 実行例

```
git config --global user.name kyohei
```

## 設定の適用範囲

実行時にオプションをつけることで設定の適用範囲を指定できる。

|オプション|適用範囲|
|:-:|:--|
|system|システム全体|
|global|ユーザの全リポジトリ|
|local|設定したリポジトリのみ|

## 主な設定と値の例

|name|value の例|
|:-:|:-:|
|user.name|kyohei|
|user.email|kyohei37t@gmail.com|
|core.editor|"code --wait"|

`user.name` と `user.email` は設定しないと Git を利用することができないため必須。
