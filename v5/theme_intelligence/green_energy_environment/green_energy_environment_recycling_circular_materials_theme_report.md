# 綠能環保：循環經濟 / 資源回收 / 再生材料 小主題報告

- 更新時間：2026-07-15T12:30:09+08:00
- 狀態：✅ 已正式化（NAS 本地與 V5-facing copies 已更新；未執行 GitHub Pages push）
- 原則：中立主題情報資料庫，不混入 Mason 持股，不作買賣建議；ETF 成分股未作為本批分類依據。

## 本批結論

- 正式納入：7 檔，其中 core 5、adjacent 2。
- 暫緩：`8476 台境*`，因本次官方網站可讀產品/服務證據不足。

## 正式納入公司

| 股票 | 分層 | 信心 | 主題角色 | 證據摘要 |
|---|---|---|---|---|
| `6581 鋼聯` | core | high | 電弧爐集塵灰 / 工業廢棄物資源化與鋅循環平台 | 官方首頁與產品服務直接對應資源化、鋅循環與循環經濟。 |
| `6887 寶綠特-KY` | core | high | 再生塑膠 / PET 回收清洗造粒與工程服務平台 | 官網直接描述資源再生與回收產業鏈垂直整合，列 core。 |
| `7610 聯友金屬-創` | core | high | 二次合金 / 鎢鈷稀貴金屬回收與再生材料供應商 | 官方文字直接提到閉環式循環經濟、金屬回收與再生利用；創新板新掛牌，列 high 但後續可再補公開說明書。 |
| `8390 金益鼎` | core | high | 電子廢棄物 / 貴金屬回收精鍊與資源再生服務商 | 官網主題與服務項目均直接對應電子廢棄物與貴金屬資源回收，列 core。 |
| `8423 保綠-KY` | core | high | 廢輪胎回收再利用 / 再生橡膠材料供應商 | 官網直接以廢輪胎循環經濟和再生材料為核心，列 core。 |
| `8341 日友` | adjacent | medium | 事業/醫療廢棄物處理與熱能回收相關服務商 | 更偏廢棄物處理服務，僅熱能回收與資源化相關，列 adjacent 而非 core。 |
| `8473 山林水` | adjacent | high | 環境工程平台中具廢棄物資源化與生質能源服務者 | 公司主軸仍是環境工程/水處理，但官網明列廢棄物資源化與廚餘生質能源，列 adjacent。 |

## 暫緩名單

- `8476 台境*`：官方網站本次未取得足夠可讀產品/服務文字，且候選可能橫跨環境工程、檢測或處理服務；本批不升正式。

## 更新檔案

- `data/company_profile.csv`
- `data/theme_tags.csv`
- `data/green_energy_environment_theme_latest.json`
- `data/green_energy_environment_recycling_circular_materials_theme_latest.json`
- `reports/green_energy_environment_recycling_circular_materials_theme_report.md/html`
- `reports/green_energy_environment_theme_index.html`
- V5-facing copies under `v5/data/processed/theme_intelligence/green_energy_environment/` and `v5/reports/theme_intelligence/green_energy_environment/`
- `v5/reports/daily/theme_green_energy_environment_index.html`
- `v5/dashboard/layout.json`
- `v5/wiki/index.md` and `v5/wiki/002_wiki_任務追蹤系統.md`

## 驗證項目

- CSV 欄位寬度一致。
- `theme_tags.csv` 中 `(stock_id, theme, sub_theme)` 無重複。
- JSON `status=three_subthemes_formalized` / `subtheme_formalized`，count 正確。
- HTML 報表包含本批公司且具搜尋/篩選功能。
- V5 daily report 與 Dashboard index 連結存在。
