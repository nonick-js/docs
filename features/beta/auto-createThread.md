---
icon: dot
order: 100
---

# 自動スレッド作成
!!!warning
この機能は、正式実装までに仕様が変更される可能性があります。
!!!

## 概要
テキストチャンネルにメッセージが投稿されると、自動でそのメッセージにスレッドを作成する機能です。

![](/static/features/auto-createThread/1.png)

!!!
BOTやWebhook、NoNICK.js自身が送信したメッセージにはスレッドは作成されません。
!!!

## 設定
+++ 一般設定
> 自動アナウンス公開機能を利用する上で必要な設定です。

- [x] **有効化・無効化**  
自動スレッド作成機能の状態を切り替えます。

- [x] **チャンネルを選択**  
スレッドを自動で作成するテキストチャンネルを変更します。
+++