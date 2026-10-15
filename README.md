# 高併發搶票系統設計

10 萬人同時搶票的架構設計草案：入口削峰、Redis Lua 原子扣票、庫存分片與 Reaper 補回、報名抽籤制。含 5 張流程圖。

## 線上閱讀

https://bartester1.github.io/high_concurrency_ticketing/

## 內容

- `high_concurrency_ticketing_flow.html`：完整文件（單一 HTML，無外部依賴）
- `index.html`：根網址轉址到上面的文件

> 本文為設計草案，Lua 腳本與各項參數均未實測。
