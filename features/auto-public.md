---
icon: dot
order: 95
---

# 自動アナウンス公開
## 概要
アナウンスチャンネルにメッセージが投稿されると、そのメッセージを自動で公開状態にする機能です。
自動公開するチャンネルは設定から選択でき、予め設定することでメッセージの公開漏れを防ぐことができます。

![](/static/features/auto-public/1.png)

!!!
BOTやWebhook、NoNICK.js自身が送信したメッセージは自動で公開されません。
!!!

!!!warning レート制限
アナウンスチャンネルは**1時間につき10回までメッセージの公開を行うことができます**。
この制限を超えると、NoNICK.jsはクールダウンが終了するまでメッセージの公開を行わなくなります。
!!!

## 設定
+++ 一般設定
> 自動アナウンス公開機能を利用する上で必要な設定です。

- [x] **有効化・無効化**  
自動アナウンス公開機能の状態を切り替えます。

- [x] **チャンネルを選択**  
メッセージを自動で公開するアナウンスチャンネルを変更します。
+++