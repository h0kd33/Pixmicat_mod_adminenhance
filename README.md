針對 Pixmicat！ 圖咪貓貼圖版程式的增強型管理套件  
========

這是什麼？  
-------------
針對 Pixmicat！ 圖咪貓貼圖版程式的增強型管理套件  
<br>
支援文字過濾（ WordFilter ）功能  
支援文字過濾（ WordFilter ）功能觸發使用者封鎖  
支援推文模組（ mod_pushpost ）的文字過濾功能  
支援推文模組（ mod_pushpost ）的發言封鎖功能，藉由儲存在用戶端之資料（ Cookie ）  
支援圖片封鎖（ MD5 Confirm ）功能  
支援圖片封鎖（ MD5 Confirm ）功能觸發使用者封鎖  
支援圖片封鎖（ MD5 Confirm ）功能觸發使用者封鎖，藉由儲存在用戶端之資料（ Cookie ）可自定義使用者封鎖時間  
<br>
請注意，因使用儲存在用戶端之資料（ Cookie ） 執行封鎖功能，因此無法更改已封鎖使用者的封鎖時間  
<br>
支援藉由符合網域與 IP 位址的使用者封鎖功能  
<br>
提供指定 DNSBL 伺服器清單來對付使用公開代理伺服器（ OpenProxy ）與洋蔥路由器（ The Onion Router ）的惡意使用者  
<br>
檔案說明
---------
config.php | 針對 Pixmicat！ 預設的封鎖功能與 DNSBL 相關設定作更改  
DENY-INFO | 建議的封鎖資料  
mod_adminenhance.php | 增強型管理套件  
mod_pushpost.php | 增強型推文模組  
README.md | 說明文件  
<br>
系統需求
------------
需要 Pixmicat!-PIO 8th.Release.3 之版本或以上  
<br>
開發目的
---------
跟智障還有鬧板廚講理是沒用的這點聰明人都知道，所以這種模組是必要的  
![ScreenShot](http://i.imgur.com/uVkyMfN.gif)  
<br>
資源
---------
- 特別感謝 & 開發協力 https://github.com/ssk7833<br>
- 管理套件之參照 https://github.com/scribetw/pixmicat_modules/tree/develop/mod_adminenhance  
- 在 GitHub 了解圖咪貓貼圖版程式 https://github.com/scribetw/pixmicat/  
- 維基百科上的 DNSBL 伺服器列表 https://en.wikipedia.org/wiki/Comparison_of_DNS_blacklists 
- 由第三方提供的 DNSBL 伺服器封鎖查詢 http://www.dnsbl.info/dnsbl-database-check.php