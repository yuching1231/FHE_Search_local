# FHE_Search_local

=== Client-end ===

$ npm start

// open a window let user generate key and encrypt the query and secret keys.

=== Server-end ===

$node server.js

// start the server



**Keygen**

產生金鑰，金鑰成功產生之後，使用者需要在彈出的對話匡中設定密碼。

密碼會將私鑰進行加密，並在欲解密計算結果時輸入密碼以存取私鑰。」

**Encrypt**

輸入合法的 Query 後進行加密，隨後使用者需將 required.zip 上傳至伺服器端。

**Search**

使用者需連線至伺服器提供服務的頁面，上傳需要搜尋的 csv 檔案、required.zip，

並且選擇需要搜尋的 csv 檔案，點擊搜尋；執行完畢後使用者需自行下載結果，

在電腦上自行解密。

**Decrypt**

點擊解密後，首先，使用者『需先輸方才設定的密碼。』

接著，為了隱私安全，使用者必須再『重新設定新的密碼保護金鑰。』

搜尋後的結果即顯示在頁面下方。
