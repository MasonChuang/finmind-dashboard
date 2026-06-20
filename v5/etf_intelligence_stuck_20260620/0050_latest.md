# 0050 元大台灣50 — ETF Intelligence Report（Phase 1 範例）

## 狀態

此檔是 Phase 1 的合約範例檔，用於驗證：

- `data/processed/etf_intelligence/0050_latest.json` 的 schema
- Python intelligence loader
- 未來 dashboard 連結與 HTML 報告格式

## 重要限制

資料品質：`sample`

此檔**尚未**由 Gideon 使用官方來源查核 0050 成分股後產出，不可視為正式 ETF 成分股分析，也不可作為投資依據。

## 後續正式報告應包含

1. 官方資料來源與查詢時間
2. 前十大成分股
3. 台積電權重、前 5 / 10 / 20 大集中度
4. 產業與區域曝險
5. 與 Mason 目前 ETF 持倉的重疊關係
6. 成分股異動後的延遲觀察事項

## Phase 1 驗證目標

若 dashboard 或 loader 能讀到此檔並顯示「範例資料 / 尚待正式查核」，即表示 Phase 1 合約成立。
