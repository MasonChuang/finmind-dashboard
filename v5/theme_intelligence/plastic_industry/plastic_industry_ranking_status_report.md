# 塑膠工業排行狀態維護

- 主題：塑膠工業 (`plastic_industry`)
- 本次使用最新排行：是
- 排行來源資料日：2026-08-11
- 排行來源 mtime：2026-08-11T21:53:09+08:00
- 熱力圖可見列 / 分歧摘要位置：第 1
- prior_rank：1（2026-07-27 強勢輪動第 1）
- rank_change：`shifted_from_strong_rotation_top1_on_2026_07_27_to_divergence_position_1_on_2026_08_11`
- rank_status：`latest_funding_price_divergence_position_1_retained_existing_formal_companies`

## 依據

強勢輪動：油電燃氣業、創新板股票、農業科技業、電腦及週邊設備業；弱勢/降溫：居家生活、金融業、綠能環保、貿易百貨 等 5 類；資金/價格分歧：資金強但價格未同步：塑膠工業、食品工業、貿易百貨、金融保險。

## 本批處理

本批只刷新 `plastic_industry_theme_latest.json` 的大主題 `ranking_context` 與既有 25 檔公司的 per-company `ranking_context`，並更新 `theme_ranking_status.csv`。不新增公司、不刪除公司、不更動 Mason 持股狀態。

## 限制

目前 `industry_rotation_radar.html` 是產業層級報表，未提供塑膠工業個股前 20 排名，因此本批不補個股缺口，也不標記單一股票退出前 20。

## 下一步

若下一批仍無個股前20，可避免重複刷新塑膠工業；改處理同一份 2026-08-11 分歧摘要中的食品工業 / 貿易百貨 / 金融保險，或挑塑膠工業的一個產品子題逐家公司補官方來源。
