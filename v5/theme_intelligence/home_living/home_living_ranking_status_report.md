# 居家生活排行狀態維護

- 主題：居家生活 (`home_living`)
- 本次使用最新排行：否（同資料日/週末後重生報表，資料日仍為 `2026-07-24`）
- 排行來源資料日：2026-07-24
- 排行來源 mtime：2026-07-26T22:00:46+08:00
- 資金強度排行：未出現在目前 HTML 可辨識內容
- 熱力圖可見列：未出現在目前 HTML 可辨識內容
- rank_change：`not_visible_no_prior_theme_rank_record`
- rank_status：`not_visible_in_latest_industry_summary_retained_existing_first_stage_companies`

## 依據

`industry_rotation_radar.html` 內可辨識資料日為 `2026-07-24`，mtime 為 `2026-07-26T22:00:46+08:00`；未發現 JSON/CSV sidecar：無。產業輪動摘要強勢輪動為「塑膠工業、油電燃氣業、創新板股票、紡織纖維 等 5 類」，弱勢/降溫為「綠能環保、金融業、光電業、玻璃陶瓷 等 5 類」，HTML 內未出現「居家生活」。

## 本批處理

本批只做低消耗欄位維護：更新 `home_living_theme_latest.json` 的大主題 `ranking_context`，並替既有 9 檔第一階段正式公司補入 per-company `ranking_context`。不新增公司、不刪除公司、不更動 Mason 持股資料。

## 限制

目前報表仍是產業層級，未提供居家生活個股前 20 排名；因此本批不補個股缺口、不標記單一股票退出前 20，避免把產業層級缺席誤解為個股排名變化。

## 下一步

若後續熱力圖出現「居家生活」或提供個股前 20，再比較排名升降；若仍未出現，建議不要重複刷新居家生活，改做其他既有主題欄位一致性或等待新交易日資料。
