# 綠能環保主題官方母體盤點與候選子題草案

日期：2026-07-14
狀態：官方母體盤點 / 規格草案 / 候選子題切分；**不是正式第一版**。

## 1. 查詢依據

- V5 DB：`/run/user/1000/gvfs/smb-share:server=nas-816.local,share=finmind/v5/data/db/finmind_data.db`，表 `TaiwanStockInfo`。
- DB 條件：`industry_category IN ('綠能環保', '綠能環保類') AND type IN ('twse', 'tpex')`。
- TWSE 官方公司基本資料：`https://openapi.twse.com.tw/v1/opendata/t187ap03_L`，產業別 `35`。
- TPEx 官方公司基本資料：`https://www.tpex.org.tw/openapi/v1/mopsfin_t187ap03_O`，產業別 `35`。
- 官方 OpenAPI 出表日期：`2026-07-13`。

## 2. 母體結果

- TWSE / TPEx 官方母體：45 檔。
- V5 DB 對應母體：41 檔。
- 合併後盤點清單：46 檔。
- 市場分布：TWSE 27, TPEx 19
- 來源交叉檢查：official_and_v5_db 40, official_only 5, v5_db_only 1
- 顯示名稱處理：`綠能環保` 與 `綠能環保類` 視為同一大主題 `綠能環保`，但資料表保留原始分類欄位。

## 3. 候選子題切分（低信心，待正式查證）

| 候選子題 | 檔數 | 下一批查證重點 |
|---|---:|---|
| 太陽能 / 再生能源開發與售電服務 | 14 | 下一批需逐家公司查證產品頁、年報、法說或官方資料。 |
| 環境工程 / 水處理 / 廢棄物處理服務 | 13 | 下一批需逐家公司查證產品頁、年報、法說或官方資料。 |
| 循環經濟 / 資源回收 / 再生材料 | 8 | 下一批需逐家公司查證產品頁、年報、法說或官方資料。 |
| 待正式分類 | 6 | 下一批需逐家公司查證產品頁、年報、法說或官方資料。 |
| 風電 / 海事工程 / 複材材料 | 3 | 下一批需逐家公司查證產品頁、年報、法說或官方資料。 |
| 半導體清洗 / 製程環保服務 | 1 | 下一批需逐家公司查證產品頁、年報、法說或官方資料。 |
| 濾材 / 水處理設備 / 環境耗材 | 1 | 下一批需逐家公司查證產品頁、年報、法說或官方資料。 |

## 4. 官方母體清單

| 股票 | 名稱 | 市場 | 官方原始產業 | V5 DB 原始產業 | 候選子題 | 官網 | 來源狀態 |
|---|---|---|---|---|---|---|---|
| 2072 | 世紀風電 | TWSE | 綠能環保 | 綠能環保 | 風電 / 海事工程 / 複材材料 | [link](http://www.cwptw.com) | official_and_v5_db |
| 3073 | 天方能源 | TPEx | 綠能環保類 | 綠能環保類 | 太陽能 / 再生能源開發與售電服務 | [link](https://www.tpenergy.com.tw) | official_and_v5_db |
| 3551 | 世禾 | TPEx | 綠能環保類 | 綠能環保類 | 半導體清洗 / 製程環保服務 | [link](http://www.sht.com.tw) | official_and_v5_db |
| 3708 | 上緯投控 | TWSE | 綠能環保 | 綠能環保 | 風電 / 海事工程 / 複材材料 | [link](http://www.swancor.com/tw/) | official_and_v5_db |
| 3713 | 新晶投控 | TPEx | 綠能環保類 | 綠能環保類 | 太陽能 / 再生能源開發與售電服務 | [link](http://www.hsinjing-holding.com.tw) | official_and_v5_db |
| 4582 | 聚恆-創 | TWSE | 綠能環保 | - | 太陽能 / 再生能源開發與售電服務 | [link](https://www.hengs.com) | official_only |
| 4924 | 欣厚-KY | TPEx | 綠能環保類 | - | 待正式分類 | [link](http://www.hsihou.com/) | official_only |
| 5205 | 中茂 | TPEx | 綠能環保類 | 綠能環保類 | 環境工程 / 水處理 / 廢棄物處理服務 | [link](http://www.twget.com.tw/) | official_and_v5_db |
| 5292 | 華懋 | TWSE | 綠能環保 | 綠能環保 | 環境工程 / 水處理 / 廢棄物處理服務 | [link](https://www.dtech.com.tw) | official_and_v5_db |
| 5432 | 新門 | TPEx | 綠能環保類 | 綠能環保類 | 太陽能 / 再生能源開發與售電服務 | [link](https://www.solomon-es.com.tw) | official_and_v5_db |
| 6581 | 鋼聯 | TWSE | 綠能環保 | 綠能環保 | 循環經濟 / 資源回收 / 再生材料 | [link](https://www.tsutw.com.tw/) | official_and_v5_db |
| 6624 | 萬年清 | TPEx | 綠能環保類 | 綠能環保類 | 環境工程 / 水處理 / 廢棄物處理服務 | [link](http://www.ever-clear.com.tw/) | official_and_v5_db |
| 6641 | 基士德-KY | TWSE | 綠能環保 | 綠能環保 | 環境工程 / 水處理 / 廢棄物處理服務 | [link](https://www.gsd.net.tw/) | official_and_v5_db |
| 6692 | 進能服 | TPEx | 綠能環保類 | 綠能環保類 | 太陽能 / 再生能源開發與售電服務 | [link](http://www.acmepointes.com) | official_and_v5_db |
| 6771 | 平和環保-創 | TWSE | 綠能環保 | 綠能環保 | 環境工程 / 水處理 / 廢棄物處理服務 | [link](http://www.pinghounion.com.tw) | official_and_v5_db |
| 6803 | 崑鼎 | TPEx | 綠能環保類 | 綠能環保類 | 環境工程 / 水處理 / 廢棄物處理服務 | [link](http://www.ecove.com) | official_and_v5_db |
| 6806 | 森崴能源 | TWSE | - | 綠能環保 | 太陽能 / 再生能源開發與售電服務 | - | v5_db_only |
| 6869 | 雲豹能源 | TWSE | 綠能環保 | 綠能環保 | 太陽能 / 再生能源開發與售電服務 | [link](http://www.jv-holding.com/) | official_and_v5_db |
| 6873 | 泓德能源 | TWSE | 綠能環保 | 綠能環保 | 太陽能 / 再生能源開發與售電服務 | [link](https://www.hdrenewables.com/) | official_and_v5_db |
| 6887 | 寶綠特-KY | TWSE | 綠能環保 | 綠能環保 | 循環經濟 / 資源回收 / 再生材料 | [link](https://bo-re-tech.group/) | official_and_v5_db |
| 6894 | 衛司特 | TPEx | 綠能環保類 | 綠能環保類 | 環境工程 / 水處理 / 廢棄物處理服務 | [link](http://www.recotech.com.tw) | official_and_v5_db |
| 6923 | 中台 | TWSE | 綠能環保 | 綠能環保 | 環境工程 / 水處理 / 廢棄物處理服務 | [link](https://www.chinalab.com.tw/index.html) | official_and_v5_db |
| 6944 | 兆聯實業 | TWSE | 綠能環保 | 綠能環保 | 環境工程 / 水處理 / 廢棄物處理服務 | [link](http://www.megaunion-tw.com/) | official_and_v5_db |
| 6951 | 青新-創 | TWSE | 綠能環保 | 綠能環保 | 環境工程 / 水處理 / 廢棄物處理服務 | [link](https://www.chin-hsin.com.tw/) | official_and_v5_db |
| 6969 | 成信實業*-創 | TWSE | 綠能環保 | 綠能環保 | 待正式分類 | [link](https://www.transcene.com.tw) | official_and_v5_db |
| 6971 | 惠民實業 | TPEx | 綠能環保類 | 綠能環保類 | 環境工程 / 水處理 / 廢棄物處理服務 | [link](https://www.huimin.com.tw) | official_and_v5_db |
| 6994 | 富威電力 | TWSE | 綠能環保 | 綠能環保 | 太陽能 / 再生能源開發與售電服務 | [link](https://www.fwp.com.tw) | official_and_v5_db |
| 7610 | 聯友金屬-創 | TWSE | 綠能環保 | 綠能環保 | 循環經濟 / 資源回收 / 再生材料 | [link](http://www.lianyoucorp.com) | official_and_v5_db |
| 7715 | 裕山 | TPEx | 綠能環保類 | 綠能環保類 | 環境工程 / 水處理 / 廢棄物處理服務 | [link](http://www.yseec.com) | official_and_v5_db |
| 7740 | 熙特爾-創 | TWSE | 綠能環保 | 綠能環保 | 太陽能 / 再生能源開發與售電服務 | [link](https://www.seetel-energy.com) | official_and_v5_db |
| 7786 | 東方風能 | TWSE | 綠能環保 | 綠能環保 | 風電 / 海事工程 / 複材材料 | [link](https://www.dfo.com.tw/) | official_and_v5_db |
| 7818 | 溢泰實業 | TWSE | 綠能環保 | - | 濾材 / 水處理設備 / 環境耗材 | [link](https://www.kemflogroup.com) | official_only |
| 7820 | 立盈 | TPEx | 綠能環保類 | - | 環境工程 / 水處理 / 廢棄物處理服務 | [link](https://www.lept.com.tw) | official_only |
| 7842 | 天能綠電 | TPEx | 綠能環保類 | - | 太陽能 / 再生能源開發與售電服務 | [link](https://greenet.com.tw/) | official_only |
| 8087 | 麗升能源 | TPEx | 綠能環保類 | 綠能環保類 | 太陽能 / 再生能源開發與售電服務 | [link](http://www.leadsun-green.com) | official_and_v5_db |
| 8171 | 天宇 | TPEx | 綠能環保類 | 綠能環保類 | 太陽能 / 再生能源開發與售電服務 | [link](http://www.feii.com.tw) | official_and_v5_db |
| 8341 | 日友 | TWSE | 綠能環保 | 綠能環保 | 循環經濟 / 資源回收 / 再生材料 | [link](http://www.sunnyfriend.com.tw/) | official_and_v5_db |
| 8390 | 金益鼎 | TPEx | 綠能環保類 | 綠能環保類 | 循環經濟 / 資源回收 / 再生材料 | [link](http://www.jyd.com.tw) | official_and_v5_db |
| 8422 | 可寧衛* | TWSE | 綠能環保 | 綠能環保 | 待正式分類 | [link](http://www.cleanaway.tw) | official_and_v5_db |
| 8423 | 保綠-KY | TPEx | 綠能環保類 | 綠能環保類 | 循環經濟 / 資源回收 / 再生材料 | [link](http://www.pgr.com.tw) | official_and_v5_db |
| 8438 | 昶昕 | TWSE | 綠能環保 | 綠能環保 | 待正式分類 | [link](https://www.persee.com.tw) | official_and_v5_db |
| 8440 | 綠電 | TPEx | 綠能環保類 | 綠能環保類 | 太陽能 / 再生能源開發與售電服務 | [link](http://www.eer.com.tw) | official_and_v5_db |
| 8473 | 山林水 | TWSE | 綠能環保 | 綠能環保 | 循環經濟 / 資源回收 / 再生材料 | [link](http://www.mfw.com.tw) | official_and_v5_db |
| 8476 | 台境* | TWSE | 綠能環保 | 綠能環保 | 循環經濟 / 資源回收 / 再生材料 | [link](http://www.tesc.com.tw) | official_and_v5_db |
| 9930 | 中聯資源 | TWSE | 綠能環保 | 綠能環保 | 待正式分類 | [link](http://www.chc.com.tw) | official_and_v5_db |
| 9955 | 佳龍 | TWSE | 綠能環保 | 綠能環保 | 待正式分類 | [link](http://www.sdti.com.tw) | official_and_v5_db |

## 5. 本批邊界

- 本批只建立官方母體、規格草案與候選子題；未合併正式 `data/company_profile.csv` / `data/theme_tags.csv`。
- 候選子題不是正式分類，不得視為 core / adjacent / candidate。
- 官方產業別 `35` 是母體錨點；正式化仍需逐家公司查證官網產品頁、年報、法說或其他官方公開資料。
- ETF 成分股未用於本批貼標；後續若使用 ETF，只能作輔助佐證。

## 6. 下一步建議

建議下一批只正式化一個小題，優先順序：

1. `太陽能 / 再生能源開發與售電服務`：能源案場、售電、儲能與 EPC 邊界相對清楚，但需確認各公司實際角色。
2. `環境工程 / 水處理 / 廢棄物處理服務`：公司數適中，與官方產業別關聯明確，適合建立 3–6 檔正式樣板。
3. `循環經濟 / 資源回收 / 再生材料`：可與塑膠工業 / 化學工業跨主題連結，但需避免只因名稱或產業別直接重複貼標。
