# 居家生活主題官方母體盤點與候選子題草案

日期：2026-07-13
狀態：官方母體盤點 / 規格草案 / 候選子題切分；**不是正式第一版**。

## 1. 查詢依據

- V5 DB：`/run/user/1000/gvfs/smb-share:server=nas-816.local,share=finmind/v5/data/db/finmind_data.db`，表 `TaiwanStockInfo`。
- DB 條件：`industry_category IN ('居家生活', '居家生活類') AND type IN ('twse', 'tpex')`。
- TWSE 官方公司基本資料：`https://openapi.twse.com.tw/v1/opendata/t187ap03_L`，產業別 `38`。
- TPEx 官方公司基本資料：`https://www.tpex.org.tw/openapi/v1/mopsfin_t187ap03_O`，產業別 `38`。
- 官方 OpenAPI 出表日期：`2026-07-12`。

## 2. 母體結果

- 官方母體：35 檔。
- FinMind DB 對應：33 檔。
- 合併後：35 檔。
- 市場分布：TPEx 24、TWSE 11
- 顯示名稱處理：`居家生活` 與 `居家生活類` 視為同一大主題 `居家生活`，但資料表保留原始分類欄位。

## 3. 候選子題切分（低信心，待正式查證）

| 候選子題 | 檔數 | 下一批查證重點 |
|---|---:|---|
| 家居建材 / 五金 / 門窗 | 5 | 候選範圍含門鎖、五金、窗飾、家用建材與相關居家耐用品；下一批需逐家公司官網產品頁確認。 |
| 居家零售 / 通路 / 生活百貨 | 11 | 候選範圍含便利商店、生活百貨、家電通路、服飾 / 生活消費通路；下一批需區分通路型與製造型公司。 |
| 家具 / 寢具 / 家飾 | 6 | 候選範圍含家具、寢具、家飾、收納與外銷居家用品；下一批需以公司產品頁 / 年報確認。 |
| 廚衛 / 衛浴 / 家電周邊 | 5 | 候選範圍含廚具、衛浴、烘焙器具、廚房設備與家電相關產品；下一批需拆清楚製造與品牌通路。 |
| 清潔 / 日化 / 居家消耗品 | 3 | 候選範圍含家用清潔、日化、香氛、生活消耗品或相關居家用品；部分公司跨化學工業，需避免重複貼標。 |
| 寵物 / 生活服務 | 1 | 候選範圍含寵物通路、寵物照護與生活服務；本批僅作候選，不以產業分類直接判定核心。 |
| 設計 / 裝修 / 空間工程 | 1 | 候選範圍含室內設計、商空 / 居家空間工程與裝修服務；下一批需確認收入來源與主要客群。 |
| 待正式分類 | 3 | 官方產業母體已確認，但本批不硬拆；需先查官網產品頁 / 年報。 |

## 4. 官方母體清單

| 股票 | 名稱 | 市場 | 原始產業顯示 | 候選子題 | 官網 |
|---|---|---|---|---|---|
| 2062 | 橋椿 | TWSE | 居家生活 | 家居建材 / 五金 / 門窗 | [link](http://www.sunspring.com.tw) |
| 2230 | 泰茂 | TPEx | 居家生活類 | 待正式分類 | [link](http://www.ctico.com.tw/) |
| 2916 | 滿心 | TPEx | 居家生活類 | 居家零售 / 通路 / 生活百貨 | [link](https://www.munsin.com.tw) |
| 2924 | 宏太-KY | TPEx | 居家生活類 | 居家零售 / 通路 / 生活百貨 | [link](http://www.ggalactica.com) |
| 2937 | 集雅社 | TPEx | 居家生活類 | 居家零售 / 通路 / 生活百貨 | [link](https://www.gseven.com.tw) |
| 2941 | 米斯特 | TPEx | 居家生活類 | 居家零售 / 通路 / 生活百貨 | [link](https://www.life8.com.tw) |
| 2947 | 振宇五金 | TPEx | 居家生活類 | 家居建材 / 五金 / 門窗 | [link](https://www.ald.com.tw) |
| 2948 | 寶陞 | TPEx | 居家生活類 | 居家零售 / 通路 / 生活百貨 | [link](https://www.bausen.com/) |
| 3067 | 全域 | TPEx | 居家生活類 | 待正式分類 | [link](https://www.twphonic.com) |
| 3171 | 炎洲流通 | TPEx | 居家生活類 | 居家零售 / 通路 / 生活百貨 | [link](https://www.ycdist.com/) |
| 3557 | 嘉威 | TWSE | 居家生活 | 清潔 / 日化 / 居家消耗品 | [link](https://www.jiaweils.com) |
| 4609 | 唐鋒 | TPEx | 居家生活類 | 廚衛 / 衛浴 / 家電周邊 | [link](https://www.airlux.com.tw) |
| 4702 | 中美實 | TPEx | 居家生活類 | 清潔 / 日化 / 居家消耗品 | [link](http://www.aicgroup.com.tw) |
| 5902 | 德記 | TPEx | 居家生活類 | 居家零售 / 通路 / 生活百貨 | [link](http://www.tait.com.tw) |
| 5903 | 全家 | TPEx | 居家生活類 | 居家零售 / 通路 / 生活百貨 | [link](https://www.family.com.tw) |
| 5904 | 寶雅 | TPEx | 居家生活類 | 居家零售 / 通路 / 生活百貨 | [link](https://www.poya.com.tw) |
| 6195 | 詩肯 | TPEx | 居家生活類 | 家具 / 寢具 / 家飾 | [link](https://ir.scanteak.com.tw/) |
| 6616 | 特昇-KY | TPEx | 居家生活類 | 家具 / 寢具 / 家飾 | [link](https://www.techcential-international.com/) |
| 6629 | 泰金-KY | TPEx | 居家生活類 | 待正式分類 | [link](https://www.thai-kin.com) |
| 6671 | 三能-KY | TWSE | 居家生活 | 廚衛 / 衛浴 / 家電周邊 | [link](https://www.sannenggroup.com/) |
| 6728 | 上洋 | TPEx | 居家生活類 | 廚衛 / 衛浴 / 家電周邊 | [link](http://www.upyoung.com.tw) |
| 6754 | 匯僑設計 | TWSE | 居家生活 | 設計 / 裝修 / 空間工程 | [link](https://www.richhonour.com) |
| 6807 | 峰源-KY | TWSE | 居家生活 | 家具 / 寢具 / 家飾 | [link](https://www.fy-grp.com) |
| 6968 | 萬達寵物 | TPEx | 居家生活類 | 寵物 / 生活服務 | [link](https://www.wonderpet.asia/) |
| 7782 | 光速火箭 | TPEx | 居家生活類 | 居家零售 / 通路 / 生活百貨 | [link](https://www.speeding-rocket.com) |
| 7794 | 宏碁智新 | TPEx | 居家生活類 | 居家零售 / 通路 / 生活百貨 | [link](https://www.acerpure.com/tw) |
| 8066 | 來思達 | TPEx | 居家生活類 | 家具 / 寢具 / 家飾 | [link](https://www.lifestyle-global.com) |
| 8433 | 弘帆 | TPEx | 居家生活類 | 清潔 / 日化 / 居家消耗品 | [link](http://www.bonfame.com/) |
| 8464 | 億豐 | TWSE | 居家生活 | 家居建材 / 五金 / 門窗 | [link](http://www.nienmade.com.tw/) |
| 8482 | 商億-KY | TWSE | 居家生活 | 家具 / 寢具 / 家飾 | [link](http://www.shaneglobal.com.tw) |
| 8941 | 關中 | TPEx | 居家生活類 | 家具 / 寢具 / 家飾 | [link](https://www.grandhall.com.tw) |
| 9911 | 櫻花 | TWSE | 居家生活 | 廚衛 / 衛浴 / 家電周邊 | [link](https://www.sakura.com.tw) |
| 9924 | 福興 | TWSE | 居家生活 | 家居建材 / 五金 / 門窗 | [link](https://www.fuhsing.com.tw) |
| 9934 | 成霖 | TWSE | 居家生活 | 廚衛 / 衛浴 / 家電周邊 | [link](https://tw.globeunion.com/) |
| 9935 | 慶豐富 | TWSE | 居家生活 | 家居建材 / 五金 / 門窗 | [link](http://www.chingfeng.com) |

## 5. 本批邊界

- 本批只建立官方母體、規格草案與候選子題；未合併正式 `data/company_profile.csv` / `data/theme_tags.csv`。
- 候選子題不是正式分類，不得視為 core / adjacent / candidate。
- 下一批正式化時，需逐家公司查證官網產品頁、年報 / 法說或官方公開資料；營收曝險未揭露者用 qualitative / unknown。

## 6. 下一步建議

目前母體規模依官方 OpenAPI 最新出表動態計算，足以進入下一批正式子題。建議下一批先做一個小題：

1. `家居建材 / 五金 / 門窗`：產品邊界相對清楚，適合先建立 3–5 檔正式樣板。
2. 或 `廚衛 / 衛浴 / 家電周邊`：可拆品牌、製造與通路，對居家生活主題辨識度高。
3. `居家零售 / 通路 / 生活百貨` 檔數較多且商業模式差異大，建議放在第二或第三批。
