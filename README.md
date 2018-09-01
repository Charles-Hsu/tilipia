
# tilipia
台灣鯛的英文名字, 生存能力強, 詳見 Wikipedia [Tilapia](https://en.wikipedia.org/wiki/Tilapia).


POST("/login")
POST 取得 token

// GetUserList 取得用戶清單
// API: /user/list
// 方法: GET
// 呼叫方式: /usr/list?page=0&user-num-per-page=25 傳回 25 筆資料, 由第1筆到第25筆
// 未指定時 page 預設值為 0, user-num-per-page 預設值為 25
// 回傳值: total: 用戶總數, result: 用戶清冊

| 方法 | API | 說明 | 範例 |
| --- | --- | --- | --- |
| `POST` | /login | username, password 取得 token ||
| `GET` | /params | 取回全部的系統參數設定 ||
| `GET` | /param/lotteries | 取得全部的彩種設定 ||
| `GET` | /lottery-name-list | 取得全部彩種名稱清單 ||
| `GET` | /lottery/time | 取得單一彩票時間設定表 | /lottery/time?gameid=A001, 取回 gameid 為 A001 的時間設定清單 |
| `GET` | /user/list | 取得用戶清單 | /usr/list?page=0&user-num-per-page=10, 第0頁, 每頁10筆, 預設值:page=0,user-num-per-page=25|
| `GET` | /lottery-name-list | 取得全部彩種名稱清單 | /lottery-name-list?is-all=1 包含六合彩, 如果未設則不包括六合彩的彩種名單 |
| `POST` | /lottery/time/:gameID | 更新彩票時間設定 | /lottery/time/A001 表示更新 A001 的 actionNo(期數), actionTime(開獎時間), 放在 ajax 的 data 裡 |






| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| POST   | git status     | git status    |
| git diff     | git diff       | git diff      |


| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |

Kevin 的電子郵件 sasdj2418@gmail.com
Penny 的電子郵件 lyly0221@gmail.com


