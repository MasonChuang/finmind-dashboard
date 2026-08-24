# 造紙工業排行狀態維護報告

- 產出時間：2026-08-24T13:03:00+08:00
- 排行來源：`/run/user/1000/gvfs/smb-share:server=nas-816.local,share=finmind/v5/reports/daily/industry_rotation_radar.html`
- 來源 mtime：`2026-08-23T22:04:59+08:00`
- HTML 內資料日：`2026-08-21`
- 本次使用最新排行：否（週一 13:00 仍早於 V5 夜間交易日更新；使用最後可驗證排行作背景）
- 排名範圍：產業層級；目前無股票層級前 20
- 造紙工業是否出現在 HTML：`False`

## 判斷

`industry_rotation_radar.html` 已重新生成到 `2026-08-23T22:04:59+08:00`，但 HTML 內資料日仍為 `2026-08-21`。本批視為同資料日再生成 / 無新交易日資料，不空轉等待，依 Mason 規則做既有主題低消耗維護。

## 摘要證據

- 強勢輪動摘要：航運業、電腦及週邊設備業
- 弱勢 / 降溫摘要：居家生活、金融業、油電燃氣業、其他電子類 等 5 類
- 資金 / 價格分歧：資金強但價格未同步：居家生活、油電燃氣業、塑膠工業、創新板股票
- 造紙工業：未出現在 HTML 可辨識文字。

## 本批動作

- 刷新 `paper_industry_theme_latest.json` 中既有 7 檔正式公司的 `ranking_context`。
- 更新 `paper_industry_ranking_status_latest.json` 與 `theme_ranking_status.csv` 的造紙工業列。
- 同步 V5-facing JSON / HTML / Markdown copies。
- 不新增公司、不刪除公司、不更動 Mason 持股資料。

## 下一步

下一批若仍無個股前 20，可避免重複刷新造紙工業；改維護尚未用 `2026-08-21` 摘要刷新過的既有主題，或挑造紙工業剩餘官方來源補強。
