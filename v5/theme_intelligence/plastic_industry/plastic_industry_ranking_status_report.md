# 塑膠工業排行狀態維護

- 主題：塑膠工業 (`plastic_industry`)
- 本次使用最新排行：是
- 排行來源資料日：2026-07-23
- 排行來源 mtime：2026-07-23T21:42:41+08:00
- 資金強度排行：第 1
- 熱力圖可見列：第 1
- prior_rank：1
- rank_change：`unchanged_top1`
- rank_status：`latest_strong_rotation_top1_rank_unchanged_per_company_context_refreshed`

## 依據

產業輪動摘要列「強勢輪動：塑膠工業、油電燃氣業、創新板股票、紡織纖維 等 5 類」；資金強度排行圖 y 軸第一列為塑膠工業；相較 2026-07-22，塑膠工業維持第 1。

## 本批處理

本批只刷新 2026-07-23 產業層級排行狀態，並同步 `plastic_industry_theme_latest.json` 的 `ranking_context` 與既有 25 檔公司的 per-company `ranking_context`。不新增公司、不更動 Mason 持股狀態。

## 限制

目前 `industry_rotation_radar.html` 是產業層級報表，未提供塑膠工業個股前 20 排名，因此本批不補個股缺口，避免把產業排行誤作個股排行。

## 下一步

若下一次熱力圖仍維持塑膠工業 top1 且沒有個股前 20，可轉往其他既有主題低消耗維護；若後續報表提供個股排名，再補 `stock_rank`、`rank_change` 與 `top20_exit` 類欄位。
