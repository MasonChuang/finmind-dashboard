# 造紙工業排行狀態維護

- 主題：造紙工業 (`paper_industry`)
- 本次使用最新排行：是
- 排行來源資料日：2026-07-24
- 排行來源 mtime：2026-07-24T21:47:32+08:00
- prior_rank：3（前次 2026-07-09 最後可驗證排行）
- rank_change：`exited_visible_top_list_from_prior_rank3`
- rank_status：`latest_report_not_visible_retained_existing_formal_companies`

## 依據

最新可驗證 `industry_rotation_radar.html` 的資料日為 2026-07-24。強勢輪動摘要為：「塑膠工業、油電燃氣業、創新板股票、紡織纖維 等 5 類」。本次 HTML 未出現「造紙工業」，因此判定造紙工業未在目前可見產業層級強勢 / 熱力圖清單內。

## 本批處理

本批只補齊 `paper_industry_theme_latest.json` 的大主題 `ranking_context`，並同步既有 7 檔正式公司的 per-company `ranking_context`。不新增公司、不刪除已收錄公司、不更動 Mason 持股資料。

## 限制

目前 `industry_rotation_radar.html` 是產業層級報表，未提供造紙工業個股前 20 排名，因此本批不補個股缺口，也不對單一股票做退出前 20 標記。

## 下一步

若後續報表仍沒有股票層級前 20，可繼續做既有主題欄位一致性維護；若造紙工業重新進入產業排行，再比較 `prior_rank=3` 與最新順位。
