# 油電燃氣業排行狀態維護報告

- 產出日期：2026-08-16
- 主題：油電燃氣業
- 排行來源：`v5/reports/daily/industry_rotation_radar.html`
- HTML 內可辨識資料日：2026-08-14
- 報表 mtime：2026-08-15T22:04:38+08:00
- 報表大小：77581 bytes
- JSON/CSV 版：本次檢查未見 `industry_rotation_radar.json` / `industry_rotation_radar.csv`

## 最新產業輪動摘要

- 強勢輪動：電腦及週邊設備業
- 弱勢 / 降溫：居家生活、綠能環保、油電燃氣業、食品工業 等 5 類
- 資金 / 價格分歧：資金強但價格未同步：油電燃氣業、塑膠工業、居家生活、創新板股票

## 本批處理

本批只刷新既有正式主題的排行背景：油電燃氣業在 2026-08-14 報表仍列弱勢 / 降溫第 3 項，且維持資金 / 價格分歧第 1 項。

- rank_status：`latest_weak_cooling_position_3_and_funding_price_divergence_position_1_retained_existing_formal_companies`
- rank_change：`moved_from_weak_cooling_visible_on_2026_08_13_to_weak_cooling_position_3_on_2026_08_14_and_divergence_position_1_retained`
- stock_level_top20_status：`not_available_from_current_industry_rotation_report`

## 邊界

目前產業輪動報表仍為產業層級，未提供油電燃氣業個股前 20，因此本批不補個股缺口、不標記單一股票退出前 20；不新增公司、不刪除公司、不寫入 Mason 持股資料。

## 驗證項目

- `data/oil_electric_gas_theme_latest.json`：JSON 可解析，rank_source_date=2026-08-14。
- `data/oil_electric_gas_ranking_status_latest.json`：JSON 可解析，rank_status 已更新。
- `data/theme_ranking_status.csv`：油電燃氣業列已更新至資料日 2026-08-14。
- V5-facing copy：同步至 `v5/data/processed/theme_intelligence/oil_electric_gas/`、`v5/reports/theme_intelligence/oil_electric_gas/` 與 `v5/reports/daily/`。
