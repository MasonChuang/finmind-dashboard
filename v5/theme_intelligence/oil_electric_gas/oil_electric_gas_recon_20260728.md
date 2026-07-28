# 油電燃氣業官方母體盤點與排行背景（2026-07-28）

## 摘要
- 熱力圖資料日：`2026-07-27`；mtime：`2026-07-27T21:48:06+08:00`。
- 強勢輪動摘要：`塑膠工業、油電燃氣業、創新板股票、其他 等 5 類`；`油電燃氣業` 為摘要第 `2` 項。
- 官方母體錨點：TWSE / TPEx 公司基本資料產業別 `23`。
- 官方母體 12 檔；V5 DB 交叉檢查 12 檔；合併 12 檔。
- 本批未寫入正式 `company_profile.csv` / `theme_tags.csv`；候選子題只作後續查證排程。
- 目前報表未提供股票層級前20，因此不補個股缺口、不標記單一股票退出前20。

## 候選子題分布
- 加油站 / 油品通路 / 運輸能源: 3
- 石油煉製 / 石化燃料: 1
- 天然氣 / 城市瓦斯: 6
- 汽電共生 / 電力服務: 2

## 公司清單
| 代號 | 名稱 | 市場 | 來源狀態 | 候選子題 | 備註 |
|---|---|---|---|---|---|
| 2616 | 山隆 | TWSE | official_and_v5_db | 加油站 / 油品通路 / 運輸能源 | 官方產業母體盤點；正式化前需逐家公司查證。 |
| 6505 | 台塑化 | TWSE | official_and_v5_db | 石油煉製 / 石化燃料 | 官方產業母體盤點；正式化前需逐家公司查證。 |
| 8908 | 欣雄 | TPEx | official_and_v5_db | 天然氣 / 城市瓦斯 | 官方產業母體盤點；正式化前需逐家公司查證。 |
| 8917 | 欣泰 | TPEx | official_and_v5_db | 天然氣 / 城市瓦斯 | 官方產業母體盤點；正式化前需逐家公司查證。 |
| 8926 | 台汽電 | TWSE | official_and_v5_db | 汽電共生 / 電力服務 | 官方產業母體盤點；正式化前需逐家公司查證。 |
| 8927 | 北基 | TPEx | official_and_v5_db | 加油站 / 油品通路 / 運輸能源 | 官方產業母體盤點；正式化前需逐家公司查證。 |
| 8931 | 大汽電 | TPEx | official_and_v5_db | 汽電共生 / 電力服務 | 官方產業母體盤點；正式化前需逐家公司查證。 |
| 9908 | 大台北 | TWSE | official_and_v5_db | 天然氣 / 城市瓦斯 | 官方產業母體盤點；正式化前需逐家公司查證。 |
| 9918 | 欣天然 | TWSE | official_and_v5_db | 天然氣 / 城市瓦斯 | 官方產業母體盤點；正式化前需逐家公司查證。 |
| 9926 | 新海 | TWSE | official_and_v5_db | 天然氣 / 城市瓦斯 | 官方產業母體盤點；正式化前需逐家公司查證。 |
| 9931 | 欣高 | TWSE | official_and_v5_db | 天然氣 / 城市瓦斯 | 官方產業母體盤點；正式化前需逐家公司查證。 |
| 9937 | 全國 | TWSE | official_and_v5_db | 加油站 / 油品通路 / 運輸能源 | 官方產業母體盤點；正式化前需逐家公司查證。 |

## 主要來源
- TWSE OpenAPI：`https://openapi.twse.com.tw/v1/opendata/t187ap03_L`
- TPEx OpenAPI：`https://www.tpex.org.tw/openapi/v1/mopsfin_t187ap03_O`
- V5 DB：`/run/user/1000/gvfs/smb-share:server=nas-816.local,share=finmind/v5/data/db/finmind_data.db`
- 產業輪動報表：`/run/user/1000/gvfs/smb-share:server=nas-816.local,share=finmind/v5/reports/daily/industry_rotation_radar.html`

## 下一步
下一批建議只選一個邊界清楚的小題正式化，例如 `天然氣 / 城市瓦斯` 或 `汽電共生 / 電力服務`；逐家公司查證官網、年報或法說後才寫入正式資料表。
