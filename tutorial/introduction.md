---
icon: tools
order: 100
---

# BOTを導入する
BOTを使用するためには、まずは自分のサーバーにBOTを導入する必要があります。以下の手順に従って、BOTをサーバーに招待してください。

!!!success
BOTをサーバーに招待するには、そのサーバーの`サーバーの管理`権限を所有している必要があります。
!!!

### 1. BOTの招待リンクにアクセスする
NoNICK.jsは[こちら](https://discord.com/api/oauth2/authorize?client_id=970849754298863706&permissions=1186216467632&scope=bot%20applications.commands)、
NoNICK.statsは[こちら](https://discord.com/api/oauth2/authorize?client_id=1059120695205953577&permissions=274877925376&scope=bot%20applications.commands)
からBOTの招待リンクにアクセスできます。  
サポートサーバーに参加している場合は、メンバーリストの一番上にあるBOTのプロフィールから直接招待リンクにアクセスできます。

![](/static/tutorial/introduction/1.png)

### 2. 要求された権限を確認し、認証する
招待リンクにアクセスし、どのサーバーに追加するか選択すると、BOTが必要としている権限の一覧が表示されます。
全て確認し、問題がなければ「認証」を選択すると、BOTがサーバーに参加し、使用できるようになります。

![](/static/tutorial/introduction/2.png)

!!!danger
要求された権限は、**全てBOTの動作に必要な権限です**！権限を剥奪すると、一部機能の使用が制限される場合があります。
また、更新の度に要求する権限が増える場合があります。その際はこの手順をもう一度繰り返すことで、BOTを退室させることなく権限を更新することができます。
!!!