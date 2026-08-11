# 油電燃氣業排行狀態維護報告

- 產出日期：2026-08-11
- 主題：油電燃氣業
- 排行來源：`v5/reports/daily/industry_rotation_radar.html`
- HTML 內可辨識資料日：2026-08-10
- 報表 mtime：本次受限於可用讀檔工具未回傳 mtime，已於資料欄位標記 `mtime_unavailable_via_read_file_tool; html_data_date_verified_2026-08-10`
- JSON/CSV 版：本次檢查未見 `industry_rotation_radar.json` / `industry_rotation_radar.csv`

## 最新產業輪動摘要

- 強勢輪動：油電燃氣業、創新板股票、農業科技業、金融保險 等 5 類
- 弱勢 / 降溫：居家生活、金融業、汽車工業、其他 等 5 類
- 資金 / 價格分歧：資金強但價格未同步：塑膠工業、食品工業、貿易百貨、半導體業

## 本批處理

本批只刷新既有正式主題的排行背景：油電燃氣業在 2026-08-10 報表仍為強勢輪動摘要第 1 項，相較前次 2026-08-03 同為第 1 項。

- rank_status：`latest_strong_rotation_summary_first_item_rank_unchanged_retained_existing_formal_companies`
- rank_change：`unchanged_strong_rotation_summary_position_1_from_2026_08_03_to_2026_08_10`
- stock_level_top20_status：`not_available_from_current_industry_rotation_report`

## 邊界

目前產業輪動報表仍為產業層級，未提供油電燃氣業個股前 20，因此本批不補個股缺口、不標記單一股票退出前 20；不新增公司、不刪除公司、不寫入 Mason 持股資料。

## 驗證項目

- `data/oil_electric_gas_theme_latest.json`：JSON 語法由寫入工具檢查通過。
- `data/oil_electric_gas_ranking_status_latest.json`：JSON 語法由寫入工具檢查通過。
- `data/theme_ranking_status.csv`：油電燃氣業列已更新至資料日 2026-08-10。
- V5-facing copy：已同步至 `v5/data/processed/theme_intelligence/oil_electric_gas/` 與 `v5/reports/theme_intelligence/oil_electric_gas/` / `v5/reports/daily/`。
