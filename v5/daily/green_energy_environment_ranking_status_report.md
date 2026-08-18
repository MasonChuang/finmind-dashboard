# 綠能環保排名狀態維護報告

- 產生時間：2026-08-18T13:02:51+08:00
- 主題：綠能環保
- 排行來源：`/run/user/1000/gvfs/smb-share:server=nas-816.local,share=finmind/v5/reports/daily/industry_rotation_radar.html`
- 排行資料日：2026-08-17
- 來源 mtime：2026-08-17T21:50:36+08:00
- 本次使用最新排行：是
- 目前狀態：弱勢 / 降溫第 2；未列資金 / 價格分歧
- 排名變化：由 2026-08-14 弱勢 / 降溫第 2 維持為 2026-08-17 弱勢 / 降溫第 2
- 處理範圍：刷新既有正式公司 28 檔的 `ranking_context`
- 本批限制：產業輪動報表仍為產業層級，未提供股票層級前 20；因此不新增公司、不刪除公司、不標記個股退出前 20。

## 摘要證據

2026-08-17 產業輪動報表摘要列強勢輪動：電腦及週邊設備業；弱勢/降溫：居家生活、綠能環保、紡織纖維、食品工業 等 5 類；資金/價格分歧：資金強但價格未同步：油電燃氣業、塑膠工業、居家生活、創新板股票。本批只維護綠能環保既有正式公司的排名背景；因報表未提供股票層級前20，不新增、不刪除、不更動 Mason 持股。

## 驗證

- JSON 可解析：`green_energy_environment_theme_latest.json`、`green_energy_environment_ranking_status_latest.json`
- CSV：`theme_ranking_status.csv` 欄位寬度一致
- HTML / V5-facing copy：排程腳本已同步至 V5 daily 與 theme_intelligence 目錄
