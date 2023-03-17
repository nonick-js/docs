---
icon: dot
author: 
- name: NoNICK
  avatar: https://media.discordapp.net/attachments/958791423161954445/975266759529623652/-3.png?width=663&height=663
order: 296
---
# AutoMod Plus
AutoMod Plusは、設定したフィルターに検知されたメッセージを自動で削除する機能です。
Discord標準のワードフィルターであるAutoModでは設定が困難なフィルターが用意されており、あわせて使用することでサーバーのセキュリティを向上させることができます。  

![](/static/features/autoModPlus_1.png)
 
## フィルターの種類
!!!
`サーバー管理`権限を持っているユーザーやBOTからのメッセージは、例外設定に関わらずこのフィルターから常時除外されます。
!!!
* **このサーバー以外の招待リンク** ... 送信先のサーバー以外のDiscordサーバーの招待リンクを含むメッセージをブロックします。
* **Discordトークン** ... あらゆる形式のDiscordトークンを含むメッセージをブロックします。
* **短縮URL** ... 有名な短縮URLサービスのリンクを含むメッセージをブロックします。

## 設定
=== 一般設定
* <span style="color: orange; ">有効化 / 無効化</span>  
AutoMod Plusの状態を切り替えます。  

* <span style="color: orange; ">有効にするフィルタ</span>  
有効にするメッセージフィルタを選択します。各フィルタの詳細は上記を参照してください。
=== ログ設定
メッセージがブロックされた際にログを送信します。  

* <span style="color: orange; ">有効化 / 無効化</span>  
ログ機能の状態を切り替えます。

* <span style="color: orange; ">送信先</span>  
ログの送信先を設定します。  
=== 例外設定
* <span style="color: orange; ">チャンネル</span>  
フィルタに影響しないチャンネルを設定します。   

* <span style="color: orange; ">ロール</span>  
フィルタに影響しないロールを設定します。  
===