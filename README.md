# Monaca 情報研究テンプレート

Monaca Education 用の最小構成テンプレートです。Cordova 11 を使い、HTML・CSS・JavaScript でアプリを作ります。

## 授業の始め方（Codespaces）

1. 「Use this template」→「Create a new repository」を選び、自分のリポジトリを作ります。
2. 「Code」→「Codespaces」→「Create codespace on main」を選び、Codespaces で開きます。
3. 画面が英語の場合は Ctrl+Shift+P を押し、「Configure Display Language」→「日本語」を選びます。
4. `www/index.html` を開き、右上のプレビューボタン（Live Preview）で表示を確認します。

## Monaca Education に取り込む方法

1. ZIP の URL は `https://github.com/OWNER/REPO/archive/refs/heads/main.zip` です。`OWNER` と `REPO` は自分のリポジトリの所有者名と名前に置き換えてください。
2. Monaca Education（https://monaca.education）にログインし、プロジェクトのインポート機能で上記 URL またはダウンロードした ZIP ファイルを指定して、プロジェクトを作成します。
3. 画面の細かいボタン名や操作が違う場合は、先生に聞いてください。

## フォルダ構成

| ファイル・フォルダ | 説明 |
| --- | --- |
| `www/index.html` | 画面。ここを編集します。 |
| `www/css/style.css` | 画面の見た目を設定します。 |
| `www/components/` | Monaca が自動生成します。編集しないでください。 |
| `config.xml`, `package.json`, `res/` | アプリの設定とアイコンです。授業で指示があるまで触らないでください。 |
| `.devcontainer/` | Codespaces の設定です。編集しないでください。 |

## 最初の課題

1. `www/index.html` の `body` の文字を自分の名前に書き換えます。
2. 保存して、プレビューに反映されたことを確認します。

## 困ったとき

- プレビューが真っ白なときは、ファイルを保存したか、HTML タグを閉じ忘れていないか確認します。
- 変更がプレビューに反映されないときは、もう一度保存してプレビューを再読み込みします。
- Codespaces や Monaca Education の操作で迷ったときは、先生に聞いてください。
