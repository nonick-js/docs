---
icon: diff-ignored
order: 20
---

# /info
!!!
[v4.2.2](/historty.md/#v-4-2-2)から、従来の`/info`コマンドは`/help`コマンドに名称変更されました。
!!!

## 概要
特定のユーザーやサーバーのさまざまな情報を閲覧することができるコマンドです。
このコマンドには、ユーザーの情報を表示する`/info user`と、サーバーの情報を表示する`/info server`の2つのコマンドが搭載されています。

## /info user
指定したユーザーの情報を表示します。この機能は、ユーザーを右クリックして`アプリ`→`ユーザーの情報`を選択しても使用することができます。

![](/static/features/info/1.png)

### 引数

引数   | 説明
:---   | :---:
`user` | 情報を閲覧したいユーザー<br>(サーバーにいない場合はユーザーIDを直接入力できます。)

### 表示される項目
!!!
<span style="color: red">赤文字</span>で書かれた項目はそれらが存在する場合のみ表示されます。
!!!

* ユーザー名#〇〇〇〇
* アバター画像
* ユーザーID
* アカウント作成日
* サーバー参加日
* フラッグ (バッジ)
* 付与されているロール
* <span style="color: red"> ニックネーム </span>
* <span style="color: red"> サーバー上でのアイコン画像 </span>
* <span style="color: red"> ブースト開始日 </span>
* <span style="color: red"> タイムアウトが終了する時間 (`メッセージを管理`権限をもつユーザーのみ閲覧可能) </span>

## /info server
コマンドを実行したサーバーの情報を表示します。

![](/static/features/info/2.png)

### 引数
> このコマンドに引数はありません。

### 表示される項目

* サーバー名
* サーバーアイコン
* サーバーID
* サーバーのオーナー
* メンバー数
* チャンネル数
* ブースト数
* サーバーのステータス (公開サーバー、パートナーサーバーなど)
* ロール (`ロールを管理`権限をもつユーザーのみ閲覧可能)
