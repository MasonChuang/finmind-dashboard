# 造紙工業：1902 台紙 V5 DB-only 差異複查

- 產出時間：`2026-07-22T11:05:20+08:00`
- 本次是否使用最新熱力圖排行：否。`industry_rotation_radar.html` 仍為最後可驗證資料日 `2026-07-09`，mtime `2026-07-12 18:56:22 +0800`。
- 本批性質：既有主題低消耗維護；不新增正式公司、不新增正式 theme tag。

## 複查結論

`1902 台紙` 目前維持為 `v5_db_only_verified_difference`。

本批確認：

1. V5 `TaiwanStockInfo` 仍有 `1902 / 台紙 / twse / 2026-04-23 / 造紙工業`。
2. TWSE 現行上市公司基本資料 `t187ap03_L` 未見 `1902`；造紙工業現行官方母體為 `1903, 1904, 1905, 1906, 1907, 1909, 6790`。
3. TPEx 現行上櫃公司基本資料 `t187ap03_O` 未見 `1902`。
4. TWSE `STOCK_DAY_ALL` 當日全市場資料未見 `1902`；TWSE 個股日成交資訊針對 `1902` 的 2026-07 與 2026-04 查詢回覆「沒有符合條件的資料」。

## 本批決策

不將 `1902 台紙` 寫入正式 `company_profile.csv` 或 `theme_tags.csv`。  
理由：官方現行上市櫃基本資料與交易資料未能確認它仍屬現行可交易造紙工業母體；目前較像 V5 / FinMind `TaiwanStockInfo` 殘留或資料源差異。

## 已更新

- `data/paper_industry_official_universe.csv`：將 1902 標記為 `v5_db_only_verified_difference`。
- `data/paper_industry_1902_v5_db_only_latest.json`
- `reports/paper_industry_1902_v5_db_only_report.md/html`
- V5-facing copies。

## 下一步

若熱力圖仍未更新，下一小批可正式化 `特殊紙 / 紙品材料` 或 `循環紙材 / 回收紙相關` 中證據清楚者；1902 則等待後續資料同步或另查 MOPS / 交易所異動公告。
