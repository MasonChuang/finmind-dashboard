# 居家生活排行狀態維護

- 主題：居家生活 (`home_living`)
- 本次使用最新排行：否（週日無新交易日；沿用最後可驗證資料日 `2026-08-14`，檔案 mtime 已更新為 `2026-08-15T22:04:38+08:00`）
- 排行來源資料日：2026-08-14
- 排行來源 mtime：2026-08-15T22:04:38+08:00
- 弱勢 / 降溫摘要位置：第 1 項
- 資金 / 價格分歧摘要位置：第 3 項
- rank_change：`remained_weak_cooling_position_1_from_2026_08_12_to_2026_08_14_and_divergence_position_3_retained`
- rank_status：`latest_weak_cooling_position_1_and_funding_price_divergence_position_3_retained_existing_formal_companies_weekend_same_data_date`

## 依據

`industry_rotation_radar.html` 內可辨識資料日為 `2026-08-14`；未發現 JSON/CSV sidecar。產業輪動摘要強勢輪動為「電腦及週邊設備業」；弱勢 / 降溫為「居家生活、綠能環保、油電燃氣業、食品工業 等 5 類」；資金 / 價格分歧為「資金強但價格未同步：油電燃氣業、塑膠工業、居家生活、創新板股票」。

## 本批處理

本批只做低消耗欄位維護：更新 `home_living_theme_latest.json` 的既有 formal / candidate companies `ranking_context`，並更新 ranking status JSON/CSV/MD/HTML 與 V5-facing copies。不新增公司、不刪除公司、不更動 Mason 持股資料。

## 限制

目前報表仍是產業層級，未提供居家生活個股前 20 排名；因此本批不補個股缺口、不標記單一股票退出前 20，避免把產業層級摘要誤解為個股排名變化。

## 下一步

若下一批仍無個股前20，避免連續重複刷新居家生活；可依同一份 `2026-08-14` 摘要維護塑膠工業分歧狀態，或回到造紙工業未完成官方來源補強。
