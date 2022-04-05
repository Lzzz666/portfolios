---
marp: true
title: 1101-DBMS-Final-Step1
date: 2021-12-12
paginate: true
---

# 1101-DBMS-Final
## step1


---
# 組員
- 106703043 資科四 林琖崴
- 107703004 資科四 李元亨
- 107703006 資科四 楊永靖
- 108703009 資科三 陳威愷
- 108703029 資科三 江宗樺
- 108703031 資科三 李宇晴 
- 108703052 資科三 劉鎮宇
---
# 主題
## 實聯制登記系統

---
# 主題說明
實聯制登記：配合現在疫情，做出另一款實聯制登記系統


---
# 資料需求分析
因為我們分成三種登記方式：手機、場所、實聯登記

所以需要的資料有：

(1) 手機登記：手機號碼、身分證號碼、姓名

(2) 場所登記：場所id、地址

(3) 實聯登記：手機號碼、場所id、時間

---
# 系統功能分析

前端： 讓使用者輸入、查詢資料

有一個主選單和四個頁面，分別是

(1) 手機登記 (輸入手機號碼、身分證號碼、姓名)

(2) 場所登記 (輸入場所id、地址)

(3) 實聯登記 (輸入手機號碼、場所id、時間)

(4) 疫調查詢 (輸入身分證號碼，查詢過去14天接觸過的場所地址或接觸過的身分證號碼)

後端：連接資料庫做資料的儲存、擷取、運算
