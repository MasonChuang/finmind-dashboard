# 高速傳輸 / 連接器 / 線纜主題報告

- 更新：2026-07-11T22:08:43+08:00
- 狀態：第一版完成；AI 基礎建設大主題階段完成
- 正式公司：8 檔（core 5、adjacent 3）

## 分層原則

- core：官方頁直接明列高速連接器、高速線纜、cable assembly、server/data-center interconnect 等。
- adjacent：PCB / CCL / 一般線束等相鄰供應鏈，未硬塞 core。
- 暫緩：官方直接證據不足或本批未查證完整者。

## 正式納入名單

### 3665 貿聯-KY｜core｜資料中心線纜 / DAC / Server Connectors

- 角色：AI 資料中心高速互連線纜、Server Connectors 與 DAC 供應商
- 分數 / 信心：95 / high
- 依據：官方 Data Center Solutions 與 AI Data Center 頁明列 Server Connectors、Server Cables、DAC、Data Center Raw Wires & Cables 等，直接符合本小主題。
- 來源：https://www.bizlinktech.com/ | https://www.bizlinktech.com/industry/ai-data-center | https://www.bizlinktech.com/product-categories/server-connectors | https://www.bizlinktech.com/product-categories/server-cables | https://openapi.twse.com.tw/v1/opendata/t187ap03_L

### 3533 嘉澤｜core｜MCIO / PCIe 高速線纜與連接器

- 角色：MCIO Cable、PCIe Gen 4/5 cable assembly 與 server/data-center connector 供應商
- 分數 / 信心：94 / high
- 依據：官方 MCIO X8 Flat Cable 頁列 PCIe Gen4/5，Application 為 AI Server / Data Center / Switch / Storage；屬直接證據。
- 來源：https://www.lotes.cc/en | https://www.lotes.cc/en/product.php?act=list&cid=3 | https://www.lotes.cc/en/product.php?act=view&id=1174 | https://openapi.twse.com.tw/v1/opendata/t187ap03_L

### 6197 佳必琪｜core｜AI/GPU Server cabling / PCIe Gen6

- 角色：AI/GPU Server、Data Center Cabling、MCIO / PCIe Gen6 cable and connector 供應商
- 分數 / 信心：92 / high
- 依據：官方頁列 AI/GPU Server、Data Center Cabling，以及 MCIO / PCIe Gen6 Cable / Connector 產品分類，屬直接證據。
- 來源：https://www.jpcco.com/ | https://www.jpcco.com/lang/en/solution/DNT/AI_GPU_Server | https://www.jpcco.com/lang/en/solution/DNT/Datacenter | https://openapi.twse.com.tw/v1/opendata/t187ap03_L

### 3605 宏致｜core｜Cloud / Server 高速連接器與線束

- 角色：MCIO Cable Assembly、QSFP family 與 Cloud/Server connector 供應商
- 分數 / 信心：90 / high
- 依據：官方首頁與 Cloud & Server 應用頁列 MCIO Cable Assembly、QSFP family、High Speed connector，直接符合本小題。
- 來源：https://www.acesconn.com/ | https://www.acesconn.com/app/Cloud%20Computing%20%20Server/2 | https://www.acesconn.com/cn/series_list/MCIO/119 | https://openapi.twse.com.tw/v1/opendata/t187ap03_L

### 2392 正崴｜core｜Data center cables / connector manufacturing

- 角色：Data center cables 與連接器設計、驗證、製造供應商
- 分數 / 信心：82 / medium
- 依據：官方頁明列 data center cables 以及 connector / cable 核心能力；因公開產品細節較少，confidence 保守為 medium。
- 來源：https://www.foxlink.com/web/ | https://openapi.twse.com.tw/v1/opendata/t187ap03_L

### 3023 信邦｜adjacent｜Cable assembly / 線束製造（相鄰）

- 角色：客製化 cable assembly 與線束製造服務商；可支援相鄰供應鏈，但未驗證為資料中心高速互連核心
- 分數 / 信心：62 / medium
- 依據：官方頁定位為 Complete Manufacturing & Custom Cable Assembly；未找到足以升 core 的 AI Server / Data Center 高速互連頁，保守列 adjacent。
- 來源：https://www.sinbon.com/ | https://openapi.twse.com.tw/v1/opendata/t187ap03_L

### 2383 台光電｜adjacent｜高速 PCB 材料 / CCL（相鄰）

- 角色：PCB 基材 / CCL 供應商，作為高速傳輸板材上游使能者
- 分數 / 信心：58 / medium
- 依據：官方頁確認 Copper Clad Laminates / advanced base materials；屬高速傳輸板材上游，不是線纜 / connector / backplane 本體，保守列 adjacent。
- 來源：https://www.emctw.com/en-global | https://www.emctw.com/en-global/product_name/index | https://openapi.twse.com.tw/v1/opendata/t187ap03_L

### 2368 金像電｜adjacent｜Server / networking PCB（相鄰）

- 角色：PCB 製造供應商，屬高速訊號互連相鄰載板環節
- 分數 / 信心：54 / medium
- 依據：官方頁確認 PCB 製造定位；PCB 是高速傳輸相鄰載板，不是連接器 / 線纜本體，保守列 adjacent。
- 來源：https://www.gce.com.tw/ | https://openapi.twse.com.tw/v1/opendata/t187ap03_L

## 暫緩 / 排除觀察

- 2313 華通：官方頁可確認 PCB / 高密度板等產品，但本小題聚焦高速連接器、線纜、cable assembly、server/data-center interconnect；PCB 僅相鄰，且本批未取得足以比 2383/2368 更明確的 data-center 高速證據，暫緩。
- 3715 定穎投控：官方 / TWSE 可確認電子零組件與 PCB 相關屬性，但本批未找到足以列入高速傳輸 / 資料中心互連的直接官方產品證據，暫緩。
- 6274 台燿：常被視為高速材料供應鏈候選，但本次 TWSE/TPEx 基本資料與官方頁查證未完整收斂；不以市場印象硬寫，留待下一批重新查證。
- 6290 良維：線材 / power cord 類候選；本題聚焦高速資料傳輸與 data-center interconnect，本批未找到官方高速互連直接證據，暫緩。

## 資料品質註記

- 本報告不是投資建議，也不是自動選股。
- ETF / 新聞 / 市場印象不作為本版核心分類依據。
- 若後續公司法說或產品頁揭露更明確的 AI data center 高速互連證據，可調整 scope 與分數。