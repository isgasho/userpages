雙因認證又被攻陷，這次連 Gmail 也受害
#####################################

:date: 2018-12-20T08:19+08:00
:tags: 轉錄, 開源中國, 網路安全
:category: 轉錄
:author: h4cd(開源中國)
:summary: 6 月份 Reddit 系統遭到黑客入侵，在該事件中，攻擊者繞開了 Reddit 通過短信實現的雙因認證系統，給仍在使用短信來部署雙因認證的互聯網服務敲響了警鐘。而近日，Gmail 的雙因認證系統也被攻陷。
:og_image: https://oscimg.oschina.net/oscnet/20c56ad5b0d421e156d18daa5fd6df776a2.jpg

6 月份 Reddit 系統遭到黑客入侵，在該事件中，攻擊者繞開了 Reddit 通過短信實現的雙因認證系統，給仍在使用短信來部署雙因認證的互聯網服務敲響了警鐘。而近日，Gmail 的雙因認證系統也被攻陷。

雙因認證（2FA）是一種身份認證機制，與單因認證只需要用戶提供密碼不同，2FA 需要用戶提供兩種不同的認證因子來證明自己的身份，其中一個因子是密碼，另一個因子通常情況下是一個安全令牌或生物識別因子，比如指紋。

cnbeta 報導，安全專家表示，近期網絡釣魚活動日益猖獗，並且利用技術手段 `繞過了被 Gmail 和 Yahoo Mail 廣泛使用的雙因認證保護系統`_ 。

安全公司 Certfa Lab 的研究人員指出，黑客收集了攻擊目標的詳細信息，並利用了這些信息撰寫了相應的釣魚網絡郵件。這些郵件中包含一張隱藏照片，在攻擊目標瀏覽該信息的時候就會自動激活。

用戶在虛假的 Gmail 或者 Yahoo 安全頁面輸入密碼之後，攻擊者會根據輸入憑證轉向到真實的登陸頁面。如果目標帳戶受到 2FA 的保護，則攻擊者會將目標重定向到請求一次性密碼的新頁面，如給用戶發送短信驗證碼。

.. image:: https://oscimg.oschina.net/oscnet/20c56ad5b0d421e156d18daa5fd6df776a2.jpg
   :alt: 雙因認證又被攻陷，這次連 Gmail 也受害
   :align: center

研究人員解釋，攻擊者會在自己的服務器上實時檢查受害者的用戶名和密碼，而且即使攻擊目標啟用了例如短信、認證 APP 或者一鍵式登陸的雙因認證，也仍然會被欺騙並漏洞信息。

目前 Certfa Lab 發言人稱他們已經證實該技術能夠成功入侵基於 SMS 短信雙因保護的谷歌賬號，但無法確認其能否通過 Google Authenticator 或者 Duo Security 配套 APP 傳輸一次性密碼。

.. highlights::

  | 本站文章除註明轉載外，均為本站原創或編譯。歡迎任何形式的轉載，但請務必註明出處，尊重他人勞動共創開源社區。
  | 轉載請註明：文章轉載自 開源中國社區 [https://www.oschina.net]
  | 本文標題：雙因認證又被攻陷，這次連 Gmail 也受害
  | 本文地址：https://www.oschina.net/news/102854/2fa-bypass

.. _繞過了被 Gmail 和 Yahoo Mail 廣泛使用的雙因認證保護系統: https://www.cnbeta.com/articles/tech/799243.htm
