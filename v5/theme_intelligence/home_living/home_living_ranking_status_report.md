# 居家生活排行狀態維護

- 主題：居家生活 (`home_living`)
- 本次使用最新排行：是（HTML 內可辨識資料日 `2026-08-10`）
- 排行來源資料日：2026-08-10
- 排行來源 mtime：mtime_unavailable_via_terminal_approval; html_data_date_verified_2026-08-10
- 弱勢 / 降溫摘要位置：第 1 項
- rank_change：`changed_from_not_visible_on_2026_07_24_to_weak_cooling_summary_position_1_on_2026_08_10`
- rank_status：`latest_weak_cooling_summary_position_1_retained_existing_formal_companies`

## 依據

`industry_rotation_radar.html` 內可辨識資料日為 `2026-08-10`；未發現 JSON/CSV sidecar。產業輪動摘要強勢輪動為「油電燃氣業、創新板股票、農業科技業、金融保險 等 5 類」；弱勢 / 降溫為「居家生活、金融業、汽車工業、其他 等 5 類」；資金 / 價格分歧為「塑膠工業、食品工業、貿易百貨、半導體業」。

## 本批處理

本批只做低消耗欄位維護：更新 `home_living_theme_latest.json` 的大主題 `ranking_context`，並替既有正式公司刷新 per-company `ranking_context`。不新增公司、不刪除公司、不更動 Mason 持股資料。

## 限制

目前報表仍是產業層級，未提供居家生活個股前 20 排名；因此本批不補個股缺口、不標記單一股票退出前 20，避免把產業層級弱勢摘要誤解為個股排名變化。

## 下一步

若後續仍無個股前20，避免重複刷新居家生活；可改處理 2026-08-10 分歧摘要中的食品工業 / 塑膠工業 / 貿易百貨，或回到造紙工業未完成官方來源補強。
