# 塑膠工業排行狀態維護

- 主題：塑膠工業 (`plastic_industry`)
- 本次使用最新排行：是
- 排行來源資料日：2026-07-22
- 排行來源 mtime：2026-07-22T21:42:15+08:00
- 資金強度排行：第 1
- 熱力圖可見列：第 1
- rank_status：`new_latest_strong_rotation_top1_per_company_context_added`

## 依據

產業輪動摘要列「強勢輪動：塑膠工業、油電燃氣業、創新板股票、紡織纖維 等 5 類」；資金強度排行圖 y 軸第一列為塑膠工業。

## 本批處理

本批將排行狀態從大主題層級補入 `plastic_industry_theme_latest.json` 的 `ranking_context`，並為既有 25 檔公司補入 per-company `ranking_context`。不新增公司、不更動 Mason 持股狀態。

## 限制

目前 `industry_rotation_radar.html` 是產業層級報表，未提供塑膠工業個股前 20 排名，因此本批不補個股缺口，避免把產業排行誤作個股排行。

## 下一步

若下一批仍未取得個股前 20，可只做塑膠工業報表呈現細節或等待最新報表；若報表再更新，先比較 rank_change。
