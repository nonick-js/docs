---
icon: dot
order: 98
---

# メッセージURL展開
## 概要
DiscordのメッセージURLを含むメッセージを送信すると、そのURLに対応したメッセージのテキストや画像を展開します。
リンクにアクセスすることなく、メッセージの内容を簡単に閲覧することができます。

!!!info
BOTが送信したメッセージURLや、送信するサーバー以外のメッセージURLを送信した場合は展開されません。
!!!

![](/static/features/message-expansion/1.png)

展開するメッセージに複数の画像や埋め込みが含まれている場合、NoNICK.jsはメッセージの一部のみを表示します。
展開した埋め込みの下部にあるボタンをクリックすると、表示するコンテンツを切り替えることができます。

!!!warning
ボタンによる表示切り替えは、メッセージURLを送信した本人のみが変更できます。
!!!

![](/static/features/message-expansion/2.png)