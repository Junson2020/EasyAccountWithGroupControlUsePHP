# EasyAccountWithGroupControlUsePHP
#A Simple Http Account&Group Control (簡單的網頁帳號權限與群組管理系統)

Requirement: (需要軟體)

apache

php(mysqli)

mariadb

Setup: (安裝與設定)

include/

commonJunson.inc.php

globalJunson.inc.php

html/

accountedit.php, accountlist.php, accountupt.php, chklogin.php, groupedit.php, grouplevel.php, groupleveledit.php, grouplevelupt.php, grouplist.php, groupupt.php, index.php, jquery.multi-select.js, leveledit.php, levellist.php, levelmenu.php, levelupt.php, login.php, logout.php, mesgprint.php, multi-select.css, pencil.png, randimg.php, switch.png, userlevel.php, userleveledit.php, userlevelupt.php

sql/

EasyAccountDB.sql

note: (備註)

multiselect refer to url: http://loudev.com/#usage

多項選取是參考網頁: http://loudev.com/#usage

mariadb databaesname/username/password need (simple)encode (textencode.php) before config into globalJunson.inc.php

mariadb 資料庫名稱/帳號/密碼 在設定前須先經過(textencode.php)簡單編碼

mariadb connection databaesname/username/password config into globalJunson.inc.php 

mariadb 連接 資料庫名稱/帳號/密碼 設定於 globalJunson.inc.php

need to truncate table randpswd/userlicenseall/randkey eyery day
   
最好每天清除randpswd/userlicenseall/randkey資料表內的資料
