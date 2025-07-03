#  Postman Collection - API 測試
##  用途
針對[https://api.practicesoftwaretesting.com] 設計的測試集合，驗證產品 API 是否符合預期的資料結構與行為

##  API 規格簡要說明

###  GET `/products`
查詢產品列表，可加入以下查詢參數：

| 參數             | 說明                         | 範例                           |
|------------------|------------------------------|--------------------------------|
| `between`        | 篩選價格範圍                 | `between=price,1,50`           |
| `sort`           | 排序欄位與方式               | `sort=name,asc` 或 `name,desc` |
| `page`           | 分頁（每頁9筆）              | `page=2`                        |

---

###  POST `/messages`
建立一筆聯絡訊息（送出表單）
--------------------------------
##  使用方式

1. 將本 repo 匯入 Postman：
   - 透過 Postman 的 `Import` 功能匯入 JSON 集合檔。
2. 根據測試步驟逐一執行請求。
3. 檢查測試是否通過、確認 API 回應符合預期。
--------------------------------

## 🛠️ 技術工具
- [Postman](https://www.postman.com/) 測試工具
- JavaScript 測試語法（內建 `pm.*`）
