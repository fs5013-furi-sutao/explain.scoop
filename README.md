# Scoop とは
Windows 向けのパッケージ（アプリ）管理システムのこと。
公式サイトでは `A command-line installer for Windows` （Windows 向けコマンドラインインストーラー）と説明している。

公式サイト: 
[https://scoop.sh/](https://scoop.sh/)

## Scoop を使うメリット
Scoop の特長やメリットは、以下の別ファイルを参照。

[Scoop のメリット](./01.benefits_of_scoop.md)

## Scoop はどんな人に向いているのか
開発者に向いている。

環境を作ったり、壊したり、変更したりすることが多い開発者。各アプリのインストールが楽で、ホームディレクトリで一括管理できる Scoop は、開発者に馴染みやすいツールといえる。

開発/本番環境のセットアップをスクリプトで自動化することも、可能になる。

## Scoop のインストール方法
Scoop のインストールは、以下の別ファイルを参照。

[Scoop のインストール方法](./02.how_to_install_scoop.md)

## ほしいアプリをインストールするには
最も基本的な Scoop のコマンドは以下の通り。

### インストール: アプリのインストールする
```console 
scoop install ＜アプリ名＞
```
Chrome をインストールしたい場合は次のコマンドになる。
```
scoop install chrome
```

### アンインストール: アプリを削除する
```console
scoop uninstall ＜アプリ名＞
```

Chrome を削除したい場合は次のコマンドになる。
```
scoop uninstall ＜アプリ名＞
```

### アップデート: アプリを更新する
```console
scoop update ＜アプリ名＞
```
Chrome を更新したい場合は次のコマンドになる。
```
scoop update chrome
```
Scoop 自身を更新させたい場合は、次のコマンドを実行する。
```console 
scoop update
```

### リスト: アプリ一覧を表示する
```console
scoop list
```

### サーチ: アプリを検索する
```console
scoop search ＜アプリ名＞
```
Chrome を検索したい場合は次のコマンドになる。
```
scoop search chrome
```
ただし、検索結果の読み解き方は、Scoop システムの概念を知る必要がある。

### バケット・アド: バケットを追加する
```console
scoop bucket add ＜バケット名＞
```

バケットについても、Scoop システムの概念を知る必要がある。

概念については、公式サイトのドキュメントか、このページでレクチャーしているチュートリアルで手を動かして理解してほしい。

### ヘルプ: ヘルプドキュメントを表示する
コマンドとコマンド説明の一覧を表示するには、次のコマンドを実行する。
```console
scoop help
```
各コマンドの詳細ドキュメントを見るには、次のコマンドを実行する。
```console
scoop help ＜コマンド＞
```
例えば、`bucket` コマンドの詳細を汁には、次のコマンドを実行する。
```
scoop help bucket
```

## 手を動かして Scoop の概念を知ろう！
次のチュートリアルは、Scoop でできること、入門的なことをハンズオンを通して理解していく。

[Scoop 入門チュートリアル](./03.scoop_beginners_tutotial.md)
