# 電源 / BBU / UPS 主題 30% 初版評估

- 日期：2026-07-09
- 狀態：30% 初版 / pilot
- 主題群：AI 基礎建設 / 電力基礎設施 / 資料中心
- 正式公司樣板：6 檔
- 主題標籤：11 筆
- 候選母體：15 檔

## 一、評估結論

這個主題適合獨立建立，不能混在「記憶體」或「AI Server」裡。原因是 AI 資料中心的限制逐漸從算力/記憶體延伸到供電、備援與能源密度，供應鏈角色包含 PSU、power shelf、UPS、BBU、電池模組與電源管理 IC，分類邏輯與記憶體完全不同。

30% 初版先採「高可信核心樣板」策略：先放入可由公司官網或 TWSE/TPEx 官方資料支持的 6 檔，不把單純新聞熱門、ETF 成分股或 AI Server 整機廠直接寫成核心。

## 二、正式樣板

| 代號 | 公司 | scope | 最高分 | 主要角色 | 來源品質 |
|---|---|---|---:|---|---|
| 2301 | 光寶科 | core | 90 | 伺服器電源 / Server Power；電源模組 / Power Supply Module | high |
| 2308 | 台達電 | core | 92 | 電源管理 / Power and System；資料中心電力平台 | high |
| 6282 | 康舒 | adjacent/core | 86 | 伺服器 / 資料中心 PSU；工業 / 通訊 / EV 電源 | medium |
| 6409 | 旭隼 | core | 95 | UPS / 不斷電系統 | high |
| 6412 | 群電 | core | 86 | 伺服器 / 雲端電源；交換式電源 / Switching PSU | high |
| 6781 | AES-KY | adjacent/core | 90 | BBU / Battery Backup Solution；鋰電池模組 / 儲能 | high |

## 三、候選母體

| 代號 | 公司 | tier | 理由 |
|---|---|---|---|
| 2308 | 台達電 | formal_core | 電源管理、資料中心與能源基礎設施平台；本批已建正式 rows。 |
| 2301 | 光寶科 | formal_core | Data Center Power Supply System、Server Power、Networking Power；本批已建正式 rows。 |
| 6282 | 康舒 | formal_core | 企業/工業/資料中心 PSU 與 EV/通訊電源；本批已建正式 rows，但官網 403，需補強來源。 |
| 6412 | 群電 | formal_core | 交換式電源、伺服器/雲端/資料中心電源應用；本批已建正式 rows。 |
| 6409 | 旭隼 | formal_core | UPS / 不斷電系統核心；本批已建正式 rows。 |
| 6781 | AES-KY | formal_core | Battery Backup Solution / 電池備援與鋰電池模組；本批已建正式 rows。 |
| 2457 | 飛宏 | next_candidate | 電源供應器、adapter、EV charger 相關；待查證是否列 core 或 adjacent。 |
| 3323 | 加百裕 | next_candidate | 電池模組供應商；可能屬 BBU/儲能 adjacent，需查資料中心 BBU 證據。 |
| 6121 | 新普 | next_candidate | 電池模組供應商；需與 BBU / 資料中心備援關聯分開查證。 |
| 3211 | 順達 | next_candidate | 電池模組/電池包供應鏈候選；需查證 BBU 相關產品與資料中心客戶。 |
| 3015 | 全漢 | next_candidate | 電源供應器公司候選；需查證工業/伺服器/資料中心比重。 |
| 2436 | 偉詮電 | adjacent_candidate | 電源管理 IC / USB-PD 控制等可能 adjacent；不是 PSU/BBU/UPS 本體。 |
| 6415 | 矽力*-KY | adjacent_candidate | 電源管理 IC 公司；屬 power management IC adjacent，需避免與電源系統核心混同。 |
| 3443 | 創意 | watch_excluded_likely | 若出現在 AI 供應鏈，偏 ASIC/IP，不是本主題核心。 |
| 6669 | 緯穎 | watch_adjacent | AI server / rack system 應用端，可能與 BBU/電源櫃整合相關，但不是電源供應器本體。 |

## 四、30% 之後的缺口

- 補 2457 飛宏、3015 全漢電源供應器正式樣板。
- 補 3323 加百裕、6121 新普、3211 順達 BBU/電池模組候選查證。
- 補康舒/群電 high-power server PSU、power shelf 或資料中心電源證據來源。
- 若要到 60%，加入 ETF/主題產品佐證與互動 HTML 篩選。

## 五、資料品質註記

- 台達電、光寶科、群電、旭隼、AES-KY：已有可讀官方頁或 TWSE 基本資料支持。
- 康舒：官網產品頁直連遇到 403，本批暫用官方 URL + 搜尋片段 + TWSE 資料，confidence 設為 medium；下一批要補年報/法說或可讀官方頁。
- AI 資料中心 BBU、GB200、power shelf 等高熱度敘事，本批不直接寫成事實；後續需公司官方、法說或可信來源補證。
