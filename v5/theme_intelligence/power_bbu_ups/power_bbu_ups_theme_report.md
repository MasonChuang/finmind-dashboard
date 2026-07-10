# 電源 / BBU / UPS 主題股票資料庫 第一版

- 日期：2026-07-09
- 狀態：第一版完成
- 正式公司：13 檔
- 主題標籤：19 筆
- 候選/觀察母體：15 檔

## 一、結論

「電源 / BBU / UPS」適合獨立成為 AI 基礎建設子主題。第一版已完成可查找的公司主檔、主題標籤、JSON 資料層與 HTML 閱讀層。此版本重點是把 PSU / UPS / BBU / 電池模組 / 電源管理 IC 分層，避免把所有 AI Server 相關公司混在一起。

## 二、正式公司樣板

| 代號 | 公司 | scope | 最高分 | 主要 sub_theme | confidence |
|---|---|---|---:|---|---|
| 2301 | 光寶科 | core | 90 | 伺服器電源 / Server Power；電源模組 / Power Supply Module | high |
| 2308 | 台達電 | core | 92 | 電源管理 / Power and System；資料中心電力平台 | high |
| 2436 | 偉詮電 | adjacent | 66 | 電源管理 IC | high |
| 2457 | 飛宏 | core | 78 | 電源供應器 / Power Supply | medium |
| 3015 | 全漢 | candidate/core | 84 | AC/DC 電源 / UPS / ESS；伺服器 / Cloud Power adjacent | high |
| 3211 | 順達 | adjacent | 70 | 鋰離子電池模組 / Cloud server adjacent | medium |
| 3323 | 加百裕 | adjacent | 72 | 鋰電池模組 / ESS | high |
| 6121 | 新普 | adjacent | 74 | 電池模組 / ESS | high |
| 6282 | 康舒 | adjacent/core | 86 | 伺服器 / 資料中心 PSU；工業 / 通訊 / EV 電源 | medium |
| 6409 | 旭隼 | core | 95 | UPS / 不斷電系統 | high |
| 6412 | 群電 | core | 86 | 伺服器 / 雲端電源；交換式電源 / Switching PSU | high |
| 6415 | 矽力*-KY | adjacent | 72 | 電源管理 IC / Battery Management IC | high |
| 6781 | AES-KY | adjacent/core | 90 | BBU / Battery Backup Solution；鋰電池模組 / 儲能 | high |

## 三、候選 / 觀察母體

| 代號 | 公司 | tier | 理由 |
|---|---|---|---|
| 2308 | 台達電 | formal_core | 電源管理、資料中心與能源基礎設施平台。 |
| 2301 | 光寶科 | formal_core | Data Center Power Supply System、Server Power、Networking Power。 |
| 6282 | 康舒 | formal_core | 企業/工業/資料中心 PSU 與 EV/通訊電源；需補更佳官方頁。 |
| 6412 | 群電 | formal_core | 交換式電源、伺服器/雲端/資料中心電源應用。 |
| 6409 | 旭隼 | formal_core | UPS / 不斷電系統核心。 |
| 6781 | AES-KY | formal_core | Battery Backup Solution / 電池備援與鋰電池模組。 |
| 2457 | 飛宏 | formal_core_medium | 電源供應器、PoE、AC/DC、EV charger；資料中心關聯待補。 |
| 3015 | 全漢 | formal_core | AC/DC 電源、UPS、ESS、battery charger。 |
| 3323 | 加百裕 | formal_adjacent | Li-ion battery pack、HV ESS、ESS；BBU 上游/相鄰。 |
| 6121 | 新普 | formal_adjacent | 電池模組解決方案、ESS；AI data center BBU 待補證。 |
| 3211 | 順達 | formal_adjacent_medium | 鋰離子電池模組，應用含雲端伺服器片段；待補更明確來源。 |
| 2436 | 偉詮電 | formal_adjacent | Power Management、USB PD、wireless power controller。 |
| 6415 | 矽力*-KY | formal_adjacent | Battery Management ICs、Power Modules、AI Data Center / Data Center Power Supply 應用。 |
| 6669 | 緯穎 | watch_adjacent | AI server/rack 應用端，非電源本體；暫不寫入正式資料。 |
| 2382 | 廣達 | watch_adjacent | AI server/rack 應用端，非電源本體；暫不寫入正式資料。 |

## 四、資料品質註記

- 第一版完成代表本主題具備可閱讀報表與可維護資料層，不代表全市場窮盡。
- 康舒、飛宏、順達部分來源受動態頁/403/片段限制，confidence 保守設為 medium。
- AI data center BBU、GB200 BBU、power shelf 等敘事未在無官方/法說佐證時寫成高信心事實。
- 電源管理 IC 與電池模組保留 adjacent 分層，避免與 PSU/UPS/BBU 系統本體混淆。

## 五、後續維護

- 補公司年報/法說的營收分部與 AI server 高功率電源證據。
- 若找到專用電源/資料中心/AI infrastructure ETF，再建立 etf_theme_holdings 輔助佐證。
- 未來主題可接續散熱、AI Server、機櫃/機構件、高速傳輸。
