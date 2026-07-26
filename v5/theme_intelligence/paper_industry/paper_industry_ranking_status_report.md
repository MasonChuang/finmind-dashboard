# 造紙工業排行狀態維護報告

- 產出時間：2026-07-26T11:01:34+08:00
- 排行來源：`/run/user/1000/gvfs/smb-share:server=nas-816.local,share=finmind/v5/reports/daily/industry_rotation_radar.html`
- 來源 mtime：`2026-07-25T22:01:07+08:00`
- HTML 內資料日：`2026-07-24`
- 本次使用最新排行：否（資料日未更新；使用最後可驗證排行作背景）
- 排名範圍：產業層級；目前無股票層級前 20
- 造紙工業是否出現在 HTML：`False`

## 判斷

2026-07-26 為週日，`industry_rotation_radar.html` 檔案 mtime 雖更新至 `2026-07-25T22:01:07+08:00`，但 HTML 內資料日仍為 `2026-07-24`。本批視為同資料日再生成 / 無新交易日資料，不空轉等待，依 Mason 規則做既有主題低消耗維護。

## 摘要證據

- 強勢輪動摘要：塑膠工業、油電燃氣業、創新板股票、紡織纖維 等 5 類
- 弱勢 / 降溫摘要：綠能環保、金融業、光電業、玻璃陶瓷 等 5 類
- 造紙工業：未出現在 HTML 可辨識文字。

## 本批動作

- 刷新 `paper_industry_theme_latest.json` 中既有 7 檔正式公司的 `ranking_context`。
- 更新 `paper_industry_ranking_status_latest.json` 與 `theme_ranking_status.csv` 的造紙工業列。
- 不新增公司、不刪除公司、不更動 Mason 持股資料。

## 下一步

若下一個交易日報表更新且造紙工業重新進入排行，再比較 `prior_rank=3` 與最新順位；若仍無股票層級前 20，可改做其他既有主題排名欄位一致性。
