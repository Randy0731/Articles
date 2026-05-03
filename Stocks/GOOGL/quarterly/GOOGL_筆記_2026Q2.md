# GOOGL 筆記 2026Q2

此檔用於收錄 2026Q2 的一般 **GOOGL** / **GOOG** 筆記。里程碑事件放 `Stocks/GOOGL/milestones/`，長文深度分析放 `Stocks/GOOGL/longform/`。

## 文章索引（按發文時間倒序）

| 發文時間 | 整理日期 | 標題 | source_id | 相關 ticker | 主題 tags | 備註 |
|---|---|---|---|---|---|---|
| 2026-05-02 03:06 UTC（台北 11:06） | 2026-05-03 | KP / FOMOSoc 對 **GOOGL** 的觀點摘要：Google Cloud +63%、TPU 外部化與 AI capex 變現能見度 | KP_FOMOSoc-20260502-kp-thinking-note-40-big-tech-earnings-ai-capex-2f19bb36 | **GOOG**, **GOOGL**, **AMZN**, **MSFT**, **META**, **AAPL**, **NVDA** | #AI基建 #雲端基建 #財報 #ReRating #估值風險 #執行風險 | L3；KP 將 Google 寫成本輪 big-tech 財報中 AI capex 變現能見度最高的公司：Cloud +63%、Search engagement、企業 AI paid usage、TPU direct sales / 客戶機房部署與 backlog 支撐 2026-2027 capex |
| 2026-05-02（Substack 頁面 / PDF 顯示；時區未確認） | 2026-05-02 | 大叔美股筆記 對 **GOOGL** 的觀點摘要：Google reportedly first HBF customer 與 TPU / inference memory hierarchy | 大叔美股筆記-20260502-nvidia-4tb-hbf-ai-memory-hierarchy-73bf0f60 | **GOOG**, **GOOGL**, **SNDK**, **NVDA**, **AVGO**, **MRVL** | #Memory #AI基建 #雲端基建 #先進封裝 #競爭風險 #ReRating | L2；Wccftech 稱 Google reportedly locked as first HBF customer，需標未確認；大叔把 HBF 放進 Google TPU / inference / cost-per-token memory hierarchy，而非 NVIDIA thesis break |
| 2026-04-30 05:34（Substack 頁面顯示；時區未確認） | 2026-05-01 | 大叔美股筆記 對 **GOOGL** 的觀點摘要：Search 查詢創高、Cloud +63%、Gemini / Waymo momentum | 大叔美股筆記-20260430-google-q1-search-cloud-gemini-waymo-8f5e7392 | **GOOG**, **GOOGL** | #AI基建 #財報 #ReRating #競爭風險 | L3；大叔回顧 170 以下開始接 Google，並以 Q1 Search / Cloud / Gemini / Waymo 數據補強 Search not dead thesis；無新買點或目標價 |
| 2026-04-29 22:53 UTC | 2026-05-01 | Bytc 對 **GOOGL** 的觀點摘要：Google capex 上修至 1850 億與四巨頭 AI 基建加碼 | Bytc-20260429-four-giants-capex-710b-ai-infra-9c630e13 | **GOOG**, **GOOGL**, **AMZN**, **MSFT**, **META** | #AI基建 #財報 #ReRating #估值風險 | L2；Google `$185B` 為 Bytc 口徑，Alphabet official release 校準 Q1 capex `$35.7B`，full-year range 待 official transcript / 10-Q 校準 |
| 2026-04-29 21:29 UTC | 2026-05-01 | Bytc 對 **GOOGL** 的觀點摘要：Google Cloud、四巨頭財報與 AI capex 泡沫論校驗 | Bytc-20260429-four-giants-cloud-ai-capex-4b825039 | **GOOG**, **GOOGL**, **AMZN**, **MSFT**, **META**, **NVDA** | #AI基建 #財報 #ReRating #估值風險 | L2；Google Cloud / backlog 數字按 Bytc Note 口徑入庫，待 official filing 校準 |
| 2026-04-25 03:06 UTC | 2026-04-29 | KP / FOMOSoc 對 **GOOGL** 的觀點摘要：Google TPU 8、HBM / SRAM、供應鏈分工與系統定義者 | KP_FOMOSoc-20260425-kp-thinking-note-39-asml-high-na-asts-tpu8-intel-servicenow-jpm-private-credit-6995e281 | **GOOG**, **GOOGL**, **AVGO**, **2454.TW**, **MRVL**, **TSM**, **INTC** | #AI基建 #雲端基建 #Memory #先進封裝 #競爭風險 #執行風險 #ReRating | L3；Google TPU 8 memory stack / supplier split 將 Google 從 chip designer 升級為 system definer |
| 2026-04-18 02:45 UTC | 2026-04-29 | KP / FOMOSoc 對 **GOOGL** 的觀點摘要：Google / Marvell SRAM inference engine、Gemini latency 與 custom silicon second source | KP_FOMOSoc-20260418-kp-thinking-note-38-tsla-ai5-google-marvell-amzn-globalstar-tsmc-coreweave-luxury-1323d111 | **GOOG**, **GOOGL**, **MRVL**, **AVGO**, **TSM** | #AI基建 #雲端基建 #競爭風險 #執行風險 #ReRating | L2；Google Cloud AI inference TCO / memory hierarchy / supplier diversification 補強 |
| 2026-04-11 02:54 UTC | 2026-04-29 | KP / FOMOSoc 對 **GOOGL** 的觀點摘要：Google / Intel Xeon + IPU 與 AI balanced system | KP_FOMOSoc-20260411-kp-thinking-note-37-intel-claude-ai-amazon-capex-e8155b80 | **GOOG**, **GOOGL**, **INTC**, **AMD**, **ARM**, **NVDA** | #AI基建 #雲端基建 #競爭風險 #執行風險 #ReRating | L2；Google Cloud AI infrastructure TCO / CPU + IPU 合作補強 |
| 2026-04-04 03:10 UTC | 2026-04-29 | KP / FOMOSoc 對 **GOOGL** 的觀點摘要：平台設計責任、Google Quantum AI 與 crypto PQC 倒數 | KP_FOMOSoc-20260404-kp-thinking-note-36-nvidia-marvell-google-quantum-intel-nike-buffett-11812b9b | **GOOG**, **GOOGL**, **META**, **BTC**, **ETH**, **SOL**, **IBM**, **IONQ** | #監管審批 #政策風險 #量子運算 #加密貨幣 #競爭風險 #執行風險 #估值風險 | L2；平台設計責任 / Section 230 繞道與 Google Quantum AI / PQC 遷移 read-through |

---

## KP / FOMOSoc 對 **GOOGL** 的觀點摘要：Google Cloud +63%、TPU 外部化與 AI capex 變現能見度

- **來源 KOL**：KP / FOMOSoc
- **原文主整理**：`KOL/KP_FOMOSoc/weekly/KP_KP思考筆記第40期_五大巨頭財報_AI資本支出變現能見度.md`
- **原始來源**：https://www.fomosoc.com/p/5-kp40；推廣 Note：https://substack.com/@fomosoc/note/c-252923956
- **source_id**：KP_FOMOSoc-20260502-kp-thinking-note-40-big-tech-earnings-ai-capex-2f19bb36
- **raw 路徑 / URL**：URL（未另存 raw；Jina Reader Markdown 完整可讀）
- **OCR 狀態**：不適用
- **類型**：Substack 公開電子報 / KP 思考筆記 / 週報 / 五大巨頭財報 / AI capex
- **發文時間**：2026-05-02 03:06 UTC（台北 11:06）
- **整理日期**：2026-05-03
- **交會等級**：L3
- **事件類型**：Google Q1 earnings / Google Cloud / TPU externalization / Search AI / AI capex visibility
- **主題 / 母題標籤**：#AI基建 #雲端基建 #財報 #Memory #ReRating #估值風險 #執行風險

### 對 **GOOGL** 的影響

KP 在第40期將 Google 寫成本輪 big-tech 財報中最能回答「AI capex 是否有回收路徑」的公司。Google Cloud revenue `$20B`、+63%，企業 AI 產品首次成為 cloud growth 的主要驅動；Gemini Enterprise paid MAU +40% q/q，超過 2,800 家企業與 8M paid seats；330 個 cloud customers 過去 12 個月處理超過 1T tokens，35 個客戶達 10T tokens 里程碑。

Search 端，KP 延續「AI 沒有殺死搜尋」的框架：Search & other revenue `$60.4B`、+19%，query volume 創高；AI Mode / AI Overviews 被視為增加使用場景與頻率，而不是立即 cannibalize paid clicks。這與 KP 第28期 AI Search expansion、大叔 2026-04-30 Search queries ATH / Cloud +63% Note 同方向。

本文最大增量在 TPU 外部化。KP 認為 Google 已將最新 TPU 8t / 8i 從內部雲端優勢推向外部客戶與客戶機房部署，讓 TPU 從 cost advantage 變成可能的 independent hardware revenue line，2027 後可能有更明顯收入貢獻。Cloud margin 由 17.8% 升至 32.9%，加上 KP 口徑 backlog 約 `$462B`，使市場更願意接受 2026 capex `$180B-$190B` 與 2027 更高 capex。

### 觀點摘要

| 面向 | 內容 |
|---|---|
| **立場** | 偏正面 L3；Google 是 KP 本文中 AI capex 變現能見度最高的 hyperscaler |
| **Cloud / enterprise AI** | Google Cloud revenue `$20B`、+63%；Gemini Enterprise paid MAU +40% q/q；2,800+ companies、8M paid seats |
| **Search** | Search & other revenue `$60.4B`、+19%，query volume 創高；AI Mode / AI Overviews 被寫成 usage expansion，而非 immediate cannibalization |
| **TPU 外部化** | KP 認為 TPU 8t / 8i 直接賣給外部客戶並部署到客戶 data center，使 TPU 從內部成本優勢變成潛在硬體 revenue line |
| **Capex / backlog** | KP 口徑 backlog 約 `$462B`；2026 capex `$180B-$190B`，2027 顯著更高；需用 Cloud AI revenue / margin / FCF 驗證 |

### 風險表

| 風險 | 風險等級 | 觸發條件 | 觀察指標 | 出處 |
|---|---|---|---|---|
| Backlog / TPU 外部化口徑需校準 | 高 | KP 口徑 backlog 或 TPU 外售與 official filing / transcript 定義不一致 | Alphabet 10-Q / transcript、RPO、Cloud backlog、TPU customer disclosure | KP 第40期；整理者判斷 |
| AI Search 成本高於 monetization | 高 | AI Mode / AI Overviews 拉高 compute cost，但 paid clicks / ad ROI / conversion 沒有同步提升 | Search revenue、paid clicks、AI ad formats、capex、depreciation、cost per query | KP 第40期；既有 GOOGL framework |
| Capex / depreciation 壓 FCF | 高 | 2026-2027 capex 上升後，Cloud AI revenue / Search monetization 不足以吸收折舊與能源成本 | capex、depreciation、FCF、Cloud margin、power cost | KP 第40期 |
| TPU external adoption 不及預期 | 中高 | 外部客戶仍偏好 Nvidia / CUDA，TPU 主要停留在 Google internal workload | external TPU revenue、developer tooling、customer wins、Cloud AI margin | KP 第40期；第39期 |

### 呼應連結

> 呼應 KP 第39期 TPU 8 system definer、第38期 Marvell SRAM inference engine、第31期 TPU 外部化、第29期 century bond / Apollo OCS 與第28期 AI Search expansion：第40期把這些線索拉回到財報與 capex ROI 的季度驗證。

---

## 大叔美股筆記 對 **GOOGL** 的觀點摘要：Google reportedly first HBF customer 與 TPU / inference memory hierarchy

- **來源 KOL**：大叔美股筆記
- **原文主整理**：`KOL/大叔美股筆記/articles/20260502_nvidia_4tb_hbf_uncle.md`
- **原始來源**：https://unclestocknotes.substack.com/p/nvidia-4tb-hbf；https://wccftech.com/nvidia-not-interested-in-hbf-memory-despite-4tb-stacks-dwarfing-hbm/
- **source_id**：大叔美股筆記-20260502-nvidia-4tb-hbf-ai-memory-hierarchy-73bf0f60
- **raw 路徑 / URL**：`KOL/大叔美股筆記/raw/20260502_大叔美股筆記_nvidia_4tb_hbf_大叔美股筆記-20260502-nvidia-4tb-hbf-ai-memory-hierarchy-73bf0f60.pdf`
- **OCR 狀態**：不適用（Substack HTML 正文完整可讀；PDF 作 raw 備份）
- **類型**：Substack 文章 / HBF / AI memory hierarchy / Google TPU / inference TCO
- **發文時間**：2026-05-02（Substack 頁面 / PDF 顯示 May 02, 2026；時區未確認）
- **整理日期**：2026-05-02
- **交會等級**：L2
- **事件類型**：HBF reported customer / Google TPU memory hierarchy / inference capacity tier
- **主題 / 母題標籤**：#Memory #AI基建 #雲端基建 #先進封裝 #競爭風險 #ReRating

### 對 **GOOGL** 的影響

大叔把 Wccftech 報導中的「Google reportedly locked as first HBF customer」放進 Google TPU / inference memory hierarchy 脈絡，而不是寫成 Google 已取得 official design win。若後續被官方或供應鏈交付驗證，HBF 可能補上 Google 在 large model residency、long context、KV cache 與 cost-per-token 的大容量記憶體層。

這和既有 **GOOGL** thesis 呼應：KP 2026-04-25 TPU 8 討論 HBM / SRAM / MPU 與多供應商分工，KP 2026-04-18 Google / Marvell SRAM inference engine 討論 low-latency memory hierarchy，KP 2026-03-28 TurboQuant 則討論 KV cache 壓縮。大叔這篇新增的是「HBF 作為 HBM 與 SSD 之間的 capacity tier」，把 Google 的 Cloud AI TCO / Gemini latency / TPU memory stack 追蹤題再往 NAND / HBF 延伸。

### 觀點摘要

| 面向 | 內容 |
|---|---|
| **立場** | L2 infrastructure context；不改變 Search / Cloud / capex 主 thesis，但補強 Google system-level AI infrastructure 路線 |
| **Google reported customer** | Wccftech 稱 Google reportedly locked as first HBF customer；本專案標未確認，不寫成 official Google / SanDisk disclosure |
| **為何 Google 合理** | Google 有 TPU、compiler、Gemini workload 與 data center full stack，可按 inference / long-context workload 設計 memory tier |
| **與 NVIDIA 的差異** | NVIDIA 路線仍偏 high-bandwidth HBM / NVLink / CUDA；Google 可在 custom ASIC / inference economics 上更積極測試 capacity-optimized memory |
| **主要驗證點** | Google / SanDisk official confirmation、TPU roadmap、HBF sampling / qualification、Cloud AI margin、Gemini latency、cost per token |

### 風險表

| 風險 | 風險等級 | 觸發條件 | 觀察指標 | 出處 |
|---|---|---|---|---|
| Google first customer 未被驗證 | 高 | Wccftech 報導未進一步得到 Google / SanDisk / supply-chain confirmation | official release、TPU roadmap、sampling / qualification、supplier commentary | 大叔 / Wccftech；整理者判斷 |
| HBF 技術未轉 production | 高 | bandwidth、latency、endurance、thermal、controller / software stack 未達 production workload 需求 | HBF spec、customer qualification、HBF revenue, package yield | SanDisk HBF materials；整理者判斷 |
| GOOGL 投資含義過度外推 | 中高 | HBF 只作 internal prototype 或 niche workload，未轉 Cloud AI revenue / margin | Cloud AI revenue、Cloud margin、cost per token、Gemini latency、external TPU adoption | 整理者判斷 |

### 呼應連結

> 呼應 KP TPU 8 / SRAM engine / TurboQuant / Apollo OCS 的 memory hierarchy 線索：Google 的 AI infrastructure moat 正從單顆 TPU 擴展到 memory stack、interconnect、compiler、data center power 與供應鏈共同定義的 system-level TCO。

---

## 大叔美股筆記 對 **GOOGL** 的觀點摘要：Search 查詢創高、Cloud +63%、Gemini / Waymo momentum

- **來源 KOL**：大叔美股筆記
- **原文主整理**：`KOL/大叔美股筆記/notes/大叔美股筆記.md`
- **原始來源**：https://substack.com/@unclestocknotes/note/c-251398779；https://io.google/2026/
- **source_id**：大叔美股筆記-20260430-google-q1-search-cloud-gemini-waymo-8f5e7392
- **raw 路徑 / URL**：URL（未另存 raw；Substack Note 文字可讀）
- **OCR 狀態**：不適用
- **類型**：Substack Note / Google CEO Q1 statement / Search / Cloud / Gemini / Waymo
- **發文時間**：2026-04-30 05:34（Substack 頁面顯示；時區未確認）
- **整理日期**：2026-05-01
- **交會等級**：L3
- **事件類型**：Google Q1 Search / Cloud / AI usage / Waymo / Google I/O
- **主題 / 母題標籤**：#AI基建 #財報 #ReRating #競爭風險

### 對 **GOOGL** 的影響

大叔回顧一年前市場擔心 Google Search 被 OpenAI 取代時，他從 170 以下開始接 Google，並把這筆操作視為自己的「驕傲之舉」之一。這是大叔對 **GOOGL** / **GOOG** 的持倉 conviction 補強；頁面當前可讀內容沒有新買點、目標價或加碼指令。

這則 Note 的增量在於 Q1 口徑：Search queries reached all-time high、Google Cloud revenue +63%、Gemini / AI subscriptions / AI Mode engagement 創高、Search daily AI interactions 超過 5B，以及 Waymo fully autonomous miles `2.1M`、y/y +300%。這些資料共同補強「AI 沒有殺死 Search，反而可能擴大 engagement 與 Cloud / Gemini monetization」的 thesis；仍需用 Alphabet official filing / transcript 校準 Cloud 口徑、Search monetization 與 capex / FCF 壓力。

### 觀點摘要

| 面向 | 內容 |
|---|---|
| **立場** | 偏多 / conviction 補強；大叔歷史買入語境是 170 以下開始接，非當前買賣建議 |
| **Search** | CEO 口徑稱 Search queries 創歷史新高，反駁 Search 被 AI 直接替代的敘事 |
| **Cloud / Gemini** | Google Cloud revenue +63%；Gemini momentum、consumer AI subscriptions 與 AI Mode engagement 創高 |
| **Waymo** | fully autonomous miles `2.1M`、y/y +300%，補強 Alphabet real-world AI optionality |
| **近程催化** | Google I/O 2026 官方日期為 2026-05-19 至 2026-05-20，需追 AI Search / Gemini / Cloud roadmap 與 monetization 線索 |

### 風險表

| 風險 | 風險等級 | 觸發條件 | 觀察指標 | 出處 |
|---|---|---|---|---|
| Search engagement 不等於 monetization | 高 | AI Mode / AI answers 提升 usage，但 ad load、paid clicks、conversion 或 RPM 下降 | Search revenue、paid clicks、TAC、AI ad formats、conversion attribution | 大叔 Note / 既有 Bytc thesis |
| Cloud +63% 需 official 口徑校準 | 高 | Note / CEO excerpt 與 10-Q / transcript 定義或 growth base 不一致 | Google Cloud revenue、operating margin、RPO / backlog、capex | 大叔 Note / 整理者判斷 |
| Capex / depreciation 壓力 | 高 | Search / Cloud AI usage 成長但 FCF / margin 被 compute cost 吃掉 | capex、depreciation、FCF、Cloud margin、cost per query | 大叔 / Bytc / KP 既有 thesis |
| Waymo optionality 尚未變成可量化 earnings | 中 | autonomous miles 成長但 unit economics / revenue 未披露 | rides、revenue、cost per mile、insurance / safety incidents、regulatory approvals | 大叔 Note / 整理者判斷 |

### 呼應連結

> 呼應大叔 2026-02-21 Alphabet capex / 百年債 / AI 基建護城河 thesis，以及 Bytc 2026-04-29 Google Cloud demand / capex 上修：大叔這則補上自身持倉 conviction 與 Q1 後 Search / Cloud / Gemini / Waymo engagement 驗證。

---

## KP / FOMOSoc 對 **GOOGL** 的觀點摘要：Google TPU 8、HBM / SRAM、供應鏈分工與系統定義者

- **來源 KOL**：KP / FOMOSoc
- **原文主整理**：`KOL/KP_FOMOSoc/weekly/KP_KP思考筆記第39期_ASML_HighNA_ASTS_TPU8_INTC_ServiceNow_JPM_PrivateCredit.md`
- **原始來源**：https://www.fomosoc.com/p/asmlintel-kp39
- **source_id**：KP_FOMOSoc-20260425-kp-thinking-note-39-asml-high-na-asts-tpu8-intel-servicenow-jpm-private-credit-6995e281
- **raw 路徑 / URL**：URL（未另存 raw；Jina Reader Markdown 完整可讀）
- **OCR 狀態**：不適用
- **類型**：Substack 公開電子報 / KP 思考筆記 / 週報
- **發文時間**：2026-04-25 03:06 UTC（台北 11:06）
- **整理日期**：2026-04-29
- **交會等級**：L3
- **事件類型**：Google custom AI silicon / TPU 8 / memory hierarchy / supplier split / Cloud AI TCO
- **主題 / 母題標籤**：#AI基建 #雲端基建 #Memory #先進封裝 #競爭風險 #執行風險 #ReRating

### 對 **GOOGL** 的影響

KP 將 Google TPU 8 解讀為 Google 從「晶片設計者」升級為「系統定義者」的 L3 訊號。重點不是單一 FLOPS，而是 memory wall 下的 HBM / SRAM / interconnect / supplier split：TPU 8t Sunfish 偏 training，TPU 8i Zebrafish 偏 inference / agents，兩者用不同記憶體與供應鏈設計，讓 Google 能依 workload 控制 latency、cost per token、power 與供應鏈風險。

對 **GOOGL** 的投資含義是 Cloud AI infrastructure moat 更完整：Broadcom 負責 8t full package，MediaTek 負責 8i high-volume / lower-cost path，Marvell 做 memory pooling unit，Intel CPU / infrastructure 也在同一 stack 裡。Google 的優勢從單顆 TPU 擴到「定義整套 AI factory」；但仍需用 Google Cloud revenue / margin、external TPU adoption、cost per token 與 workload split 驗證。

### 觀點摘要

| 面向 | 內容 |
|---|---|
| **立場** | L3 infrastructure moat 補強；不改變 Search / capex 主 thesis，但提高 TPU / Cloud AI monetization 權重 |
| **TPU 8t** | Sunfish 偏 training；Superpod 9,600 chips / 121 exaFLOPS；單晶片 216GB HBM，Superpod shared memory 約 2PB |
| **TPU 8i** | Zebrafish 偏 inference / agents；單晶片 288GB HBM、SRAM 3x；pod HBM 從 49TB 升到 331TB |
| **供應鏈分工** | Broadcom 做 8t full package；MediaTek 做 8i lower-cost / high-volume path；Marvell 做 MPU；Intel 提供 CPU / infrastructure support |
| **主要驗證點** | Google Cloud AI revenue / margin、cost per token、Gemini latency、TPU 8 deployment、external customer adoption、Broadcom / MediaTek / Marvell workload split |

### 關鍵證據

| 證據 | 解讀 |
|---|---|
| TPU 8t Superpod 9,600 chips / 121 exaFLOPS / 2PB shared memory | Google 把 training cluster 的 bottleneck 從 chip compute 擴到 shared memory / system scale |
| TPU 8i 288GB HBM、3x SRAM、pod HBM 49TB -> 331TB | Inference / agent workload 的關鍵是 latency、memory bandwidth 與 context handling |
| Broadcom / MediaTek / Marvell / Intel 各自分工 | Google 不是單純買 ASIC，而是在定義多供應商 AI infrastructure stack |
| 8t / 8i 分流 | Training 與 inference 的 cost structure 分開管理，可能改善 Google Cloud AI margin 與 Gemini cost per token |

### 風險表

| 風險 | 風險等級 | 觸發條件 | 觀察指標 | 出處 |
|---|---|---|---|---|
| TPU 8 系統優勢未轉成 Cloud AI revenue | 中高 | TPU 8 提升內部效率，但外部客戶 / Cloud AI revenue / margin 未同步改善 | Cloud AI revenue、Cloud operating margin、external TPU adoption、cost per token | KP 第39期；整理者判斷 |
| 多供應商整合複雜度 | 中 | Broadcom / MediaTek / Marvell / Intel 分工提高 roadmap / tooling / yield / integration friction | workload split、supplier guidance、deployment schedule、reliability | KP 第39期；整理者判斷 |
| Memory stack 成本未下降 | 中 | HBM / SRAM / MPU 提升效能，但 power / capex / depreciation 吃掉 margin | HBM allocation、power cost、capex、depreciation、Cloud margin | KP 第39期 |
| CUDA / GPU ecosystem inertia | 中 | 外部客戶仍偏好 Nvidia GPU / CUDA，TPU 8 主要留在 Google 內部 | external TPU workloads、TorchTPU adoption、customer wins、developer tooling | KP 第39期；整理者延伸 |

### 呼應連結

> 呼應第38期 Google / Marvell SRAM inference engine、第37期 Google / Intel Xeon + IPU balanced system、第35期 TurboQuant、第29期 Apollo OCS 與第31期 TPU 外部化：KP 對 Google Cloud AI infra 的觀察已從單顆 TPU，擴展成 CPU、IPU、HBM、SRAM、OCS、MPU 與供應鏈分工共同組成的 system-level moat。

## KP / FOMOSoc 對 **GOOGL** 的觀點摘要：Google / Marvell SRAM inference engine、Gemini latency 與 custom silicon second source

- **來源 KOL**：KP / FOMOSoc
- **原文主整理**：`KOL/KP_FOMOSoc/weekly/KP_KP思考筆記第38期_TSLA_AI5_Google_Marvell_AMZN_Globalstar_TSMC_CoreWeave_Luxury.md`
- **原始來源**：https://www.fomosoc.com/p/ai5-kp38
- **source_id**：KP_FOMOSoc-20260418-kp-thinking-note-38-tsla-ai5-google-marvell-amzn-globalstar-tsmc-coreweave-luxury-1323d111
- **raw 路徑 / URL**：URL（未另存 raw；Jina Reader Markdown 完整可讀）
- **OCR 狀態**：不適用
- **類型**：Substack 公開電子報 / KP 思考筆記 / 週報
- **發文時間**：2026-04-18 02:45 UTC（台北 10:45）
- **整理日期**：2026-04-29
- **交會等級**：L2
- **事件類型**：Google custom AI silicon / Marvell SRAM engine / inference TCO / supply chain diversification
- **主題 / 母題標籤**：#AI基建 #雲端基建 #競爭風險 #執行風險 #ReRating

### 對 **GOOGL** 的影響

KP 將 Google 與 Marvell 的 SRAM-based compute engine 傳聞，解讀為 Google Cloud / Gemini 在 inference latency、memory hierarchy 與 cost per token 上的 L2 補強。這不是 Google 拋棄 Broadcom；KP 反而強調 Broadcom / Google 長約仍到 2031，Marvell 更像第二供應商與架構補位，用 2nm custom SRAM、SerDes、optics / interconnect 能力降低 HBM latency / power bottleneck。

對 **GOOGL** 的投資含義是：Google 的 AI infrastructure moat 不只在 TPU FLOPS，也在系統級 TCO。若 Gemini real-time inference 越來越重，SRAM / LPU-like engine、IPU offload、OCS、TurboQuant 這些分層技術會共同決定 Cloud AI margin 與 latency。但目前來源仍是供應鏈報告，需要後續官方、財報或產品化訊號驗證。

### 觀點摘要

| 面向 | 內容 |
|---|---|
| **立場** | L2 infrastructure efficiency 補強；不改變 Search / Cloud / capex 主 thesis |
| **核心訊號** | Google 可能與 Marvell 開發 SRAM-based compute engine，用於 Gemini real-time inference 的低延遲 / 低功耗需求 |
| **基本面含義** | Google 維持 Broadcom 主供應鏈，同時用 Marvell 做 memory hierarchy / second source / system TCO 補位 |
| **驗證點** | Gemini latency、Cloud AI margin、cost per token、Marvell custom silicon / optics revenue、Broadcom / Marvell split、TPU roadmap |
| **主要風險** | 供應鏈報告未轉官方 design win；second source revenue 小；架構複雜度未轉成 Cloud AI monetization |

### 風險表

| 風險 | 風險等級 | 觸發條件 | 觀察指標 | 出處 |
|---|---|---|---|---|
| SRAM engine 未產品化 | 中 | 供應鏈傳聞沒有進入 Gemini / Cloud production workload | Marvell guidance、Google TPU roadmap、latency / cost disclosure | KP 第38期 |
| Second source 經濟性有限 | 中 | Marvell 只做小量 prototype 或補位，無法影響 GOOGL margin / MRVL revenue | custom silicon revenue、design win size、Broadcom share、gross margin | KP 第38期；整理者判斷 |
| Broadcom / Marvell 多供應商複雜度 | 中 | 多晶片 / 多供應商增加 integration cost 或 roadmap friction | workload split、tooling、yield / schedule、Google Cloud margin | KP 第38期；整理者判斷 |

### 呼應連結

> 呼應第37期 Google / Intel Xeon + IPU balanced system、第35期 TurboQuant、第29期 Apollo OCS：KP 對 Google Cloud AI infra 的觀察逐步從單顆 TPU 擴到 CPU、IPU、memory hierarchy、optical switching 和 inference cost stack。

---

## KP / FOMOSoc 對 **GOOGL** 的觀點摘要：平台設計責任、Google Quantum AI 與 crypto PQC 倒數

- **來源 KOL**：KP / FOMOSoc
- **原文主整理**：`KOL/KP_FOMOSoc/weekly/KP_KP思考筆記第36期_NVDA_MRVL_GOOGL_INTC_NKE_Buffett.md`
- **原始來源**：https://www.fomosoc.com/p/nvidiamarvellgoogleintel-kp36
- **source_id**：KP_FOMOSoc-20260404-kp-thinking-note-36-nvidia-marvell-google-quantum-intel-nike-buffett-11812b9b
- **raw 路徑 / URL**：URL（未另存 raw；Jina Reader Markdown 完整可讀）
- **OCR 狀態**：不適用
- **類型**：Substack 公開電子報 / KP 思考筆記 / 週報
- **發文時間**：2026-04-04 03:10 UTC（台北 11:10）
- **整理日期**：2026-04-29
- **交會等級**：L2
- **事件類型**：平台責任 / 監管訴訟 / 量子運算 / 加密貨幣安全
- **主題 / 母題標籤**：#監管審批 #政策風險 #量子運算 #加密貨幣 #競爭風險 #執行風險 #估值風險

### 對 **GOOGL** 的影響

這篇對 **GOOGL** 有兩個 L2 增量。第一，KP 將洛杉磯成癮式設計判決視為平台責任風險的新路徑：原告繞過 Section 230，不告使用者內容，而告 infinite scroll、autoplay、algorithmic recommendation、notification 等平台設計。短期仍像法律成本，但若 12-24 個月內後續案件迫使 YouTube / Google 等平台調整 engagement engine，才會成為廣告 monetization 風險。

第二，Google Quantum AI 白皮書把 ECDSA quantum attack 的資源估計下修約 20 倍，KP 將其寫成 crypto PQC 遷移倒數。這不是 **GOOGL** 當前 revenue thesis，而是 deep-tech optionality / security roadmap / crypto ecosystem read-through：Google 仍是量子路線圖的重要技術節點，但商業化和可投資含義要等 logical qubits、PQC adoption 與 quantum cloud / security product 化驗證。

### 觀點摘要

| 面向 | 內容 |
|---|---|
| **立場** | L2 風險與選擇權補強；不改變目前 Search / Cloud / AI infra 主 thesis |
| **平台責任** | KP 認為 600 萬美元判賠本身不重要，重點是 product design liability 可能繞過 Section 230 |
| **量子運算** | Google Quantum AI 與 Ethereum Foundation / Stanford 共同白皮書，KP 記錄 ECDSA 量子破解資源估計降至約 50 萬 physical qubits |
| **關鍵時間窗** | 平台訴訟追 12-24 個月；PQC 遷移追 2029-2032 |
| **催化劑 / 風險** | 訴訟是否要求改變 recommendation / infinite scroll；量子路線圖是否轉成 security / cloud 商業化；crypto governance 是否能完成 PQC migration |

### 關鍵證據

| 證據 | 解讀 |
|---|---|
| 洛杉磯陪審團判賠 600 萬美元，並接受產品設計疏忽論點 | 金額小，法律路徑重要：平台責任從內容免責轉向產品設計責任 |
| KP 提到無限滾動、自動播放、演算法推薦和通知提醒 | 這些功能直接連到 engagement time / ad impressions / ad revenue |
| Google Quantum AI 白皮書將 ECDSA 所需 physical qubits 估計下修約 20 倍至約 50 萬 | 量子威脅時間表從「十年後」變成「數年尺度」的治理問題 |
| Google Willow 105 qubits、IBM Heron 133-156 qubits | KP 同時校準：離 50 萬 physical qubits 仍有數千倍差距，不是今日破解 |
| Google 將內部 PQC 遷移 deadline 提前到 2029 | 對 Alphabet 是 security / infra hygiene 訊號，也提示 crypto / custody ecosystem 的遷移時鐘 |

### 風險表

| 風險 | 風險等級 | 觸發條件 | 觀察指標 | 出處 |
|---|---|---|---|---|
| 平台設計責任擴散 | 中高 | 類似案件勝訴或和解要求平台改變 recommendation / infinite scroll / autoplay | youth-safety lawsuits、settlement language、YouTube engagement、ad impressions、product redesign | KP 第36期 |
| 廣告 engagement engine 被削弱 | 中高 | 監管或法院要求限制未成年人推薦、自動播放或通知 | YouTube watch time、ad load、ad revenue growth、retention | KP 第36期；整理者延伸 |
| 量子路線圖被過度短線化 | 中 | 市場把 Google 白皮書誤讀為 crypto 今日可被破解或 GOOGL 立即變現 | physical / logical qubits、error correction、quantum cloud revenue、security product disclosure | KP 第36期 |
| PQC governance delay | 中 | Bitcoin / crypto ecosystem 無法在 2029-2032 前完成安全遷移 | Ethereum / Solana upgrades、Bitcoin BIP、custody migration, dormant coins exposure | KP 第36期 |

### 後續追蹤

| 時間 / 頻率 | 事件 | 追蹤重點 |
|---|---|---|
| 12-24 個月 | 平台成癮式設計訴訟 | 上訴、class action、settlement、未成年人產品限制、YouTube engagement impact |
| 每季 / 每次產品更新 | YouTube / Google youth safety product changes | family controls、autoplay / recommendation defaults、watch time / ad impressions |
| 2029 前 | Google PQC internal migration | Google security blog / cloud security disclosure、PQC standards adoption |
| 2029-2032 | Crypto PQC migration | Ethereum Foundation roadmap、Solana Winternitz vault、Bitcoin BIP / wallet migration、custody policy |

### 呼應連結

> 呼應 `Stocks/GOOGL/quarterly/GOOGL_筆記_2025Q3.md` 的 Google antitrust / Chrome / Ad Tech 監管風險，也呼應 `Stocks/GOOGL/quarterly/GOOGL_筆記_2025Q4.md` 的 Quantum Echoes / Willow deep-tech optionality；本篇新增的是 platform design liability 與 PQC governance clock，不改寫 Search / Cloud / capex 主 thesis。

---

## KP / FOMOSoc 對 **GOOGL** 的觀點摘要：Google / Intel Xeon + IPU 與 AI balanced system

- **來源 KOL**：KP / FOMOSoc
- **原文主整理**：`KOL/KP_FOMOSoc/weekly/KP_KP思考筆記第37期_INTC_Claude_Mythos_Meta_MuseSpark_AMZN.md`
- **原始來源**：https://www.fomosoc.com/p/intelclaudeai-kp37
- **source_id**：KP_FOMOSoc-20260411-kp-thinking-note-37-intel-claude-ai-amazon-capex-e8155b80
- **raw 路徑 / URL**：URL（未另存 raw；Jina Reader Markdown 完整可讀）
- **OCR 狀態**：不適用
- **類型**：Substack 公開電子報 / KP 思考筆記 / 週報
- **發文時間**：2026-04-11 02:54 UTC（台北 10:54）
- **整理日期**：2026-04-29
- **交會等級**：L2
- **事件類型**：Google Cloud AI infrastructure / CPU / IPU / TCO
- **主題 / 母題標籤**：#AI基建 #雲端基建 #競爭風險 #執行風險 #ReRating

### 對 **GOOGL** 的影響

KP 將 Google 與 Intel 深化合作，解讀為 AI 基礎設施進入「平衡系統」階段：GPU / TPU 火力之外，CPU 負責 Agentic AI 的推理調度、低延遲協調與通用計算，IPU 則卸載 networking、storage、security 等基礎設施雜事。對 **GOOGL** 的影響是 L2：這不是改寫 Alphabet 主 thesis 的單篇事件，但補強 Google Cloud AI TCO、infrastructure efficiency 與 multichip strategy。

Google 已有 TPU、AMD EPYC、自研 Arm Axion，仍公開承諾未來多代 Intel Xeon 並擴大客製 IPU，說明 Google 的算力策略不是單一架構勝出，而是按 workload 分層。後續需要用 Cloud AI revenue、margin、TPU / CPU / IPU utilization 與 capex / depreciation 來驗證。

### 觀點摘要

| 面向 | 內容 |
|---|---|
| **立場** | L2 infrastructure efficiency 補強；不改變 Search / Cloud / AI infra 主 thesis |
| **核心訊號** | Google 承諾未來數年導入多代 Intel Xeon（包括 Xeon 6），並擴大客製 IPU 合作 |
| **基本面含義** | Google Cloud AI infrastructure 需要 CPU + IPU + TPU / GPU 的 workload 分層，降低整體 TCO |
| **驗證點** | Google Cloud revenue / margin、IPU offload、CPU:GPU / TPU ratio、Axion / Xeon coexistence、capex efficiency |
| **主要風險** | Intel partnership 是供應多元化而非 Google Cloud revenue 加速；CPU / IPU efficiency 未轉成 external AI revenue 或 margin |

### 風險表

| 風險 | 風險等級 | 觸發條件 | 觀察指標 | 出處 |
|---|---|---|---|---|
| Balanced system 未轉 monetization | 中 | CPU / IPU / TPU 效率補強沒有反映在 Google Cloud AI revenue 或 margin | Cloud revenue、Cloud operating margin、AI customer wins、cost per token | KP 第37期 |
| 多架構複雜度 | 中 | TPU、Axion、Xeon、AMD EPYC、GPU / IPU 並存提高軟硬整合與供應鏈複雜度 | utilization、developer tooling、capex efficiency、reliability | KP 第37期；整理者判斷 |
| Intel 依賴只是供應安全，不是差異化 | 中 | Xeon / IPU 採用只代表備援或既有合作延續，沒有創造 Cloud differentiation | workload split、customer adoption、TCO disclosure、competitive benchmarking | KP 第37期；整理者判斷 |

### 呼應連結

> 呼應 `Stocks/GOOGL/quarterly/GOOGL_筆記_2026Q1.md` 的 TPU externalization、Google OCS、TurboQuant 與 Google Cloud security thesis：本篇補上的不是單一產品，而是 Google Cloud AI infrastructure 中 CPU / IPU / TPU / GPU 分層設計的另一塊。

---

## Bytc 對 **GOOGL** 的觀點摘要：Google Cloud、四巨頭財報與 AI capex 泡沫論校驗

- **來源 KOL**：Bytc
- **原文主整理**：`KOL/Bytc/notes/bytc筆記.md`
- **原始來源**：https://substack.com/@btyc/note/c-251237472
- **source_id**：Bytc-20260429-four-giants-cloud-ai-capex-4b825039
- **raw 路徑 / URL**：URL（未另存 raw）
- **OCR 狀態**：不適用
- **類型**：Substack Note / 四大科技財報 / Google Cloud / AI capex / cloud demand
- **發文時間**：2026-04-29 21:29 UTC（台北 2026-04-30 05:29）
- **整理日期**：2026-05-01
- **交會等級**：L2
- **事件類型**：Q1 earnings / Google Cloud growth / AI capex validation
- **主題 / 母題標籤**：#AI基建 #財報 #ReRating #估值風險 #執行風險

### 對 **GOOGL** 的影響

Bytc 將 Google 放進四大科技財報橫向比較，核心是 Google Cloud revenue 與 cloud backlog 被用來反證 AI capex 泡沫論。這篇對 **GOOGL** 是 L2 增量：它補強 Google Cloud / TPU / AI infrastructure 的需求端，與既有 KP TPU 8、Google / Marvell inference TCO、大叔 Alphabet capex / energy moat thesis 相互呼應，但沒有改寫單股主框架。

資料限制：本次未抓到可直接校準的 Alphabet official Q1 2026 URL，因此 Google revenue、EPS、Google Cloud revenue 與 backlog 數字按 Bytc Note 口徑入庫。後續若取得 Alphabet 10-Q / earnings release，需回頭校準 cloud backlog / RPO 定義與數字。

### 觀點摘要

| 面向 | 內容 |
|---|---|
| **立場** | 偏正面 L2；Bytc 認為 Google Cloud 與四巨頭財報資料讓他很難相信 AI 泡沫論 |
| **核心訊號** | Bytc 記錄 total revenue `$109.9B`、EPS `$5.11`、operating profit `$39.7B`、Google Cloud revenue `$20.0B`、cloud backlog `$460B` / +63% |
| **基本面含義** | Google Cloud 若持續高增且 backlog 夠大，可支撐 Alphabet AI capex / TPU / data center investment，不只是短期費用壓力 |
| **驗證點** | Google Cloud revenue / margin、backlog / RPO conversion、capex、depreciation、FCF、AI Search monetization、TPU external adoption |
| **主要風險** | 數字需 official filing 校準；Cloud growth 若無法轉 operating margin / FCF，仍可能被 capex 和 depreciation 抵銷 |

### 關鍵證據

| 證據 | 解讀 |
|---|---|
| Bytc 記錄 Google Cloud revenue `$20.0B`、cloud backlog `$460B` / +63% | 支撐 Google Cloud demand 與 AI infrastructure utilization 仍強，但待 official filing 校準 |
| Bytc 將 Google Cloud +63% YoY 與 Azure / AWS / Meta growth 並列 | Google 不是孤立財報 beat，而是 hyperscaler cloud demand mosaic 的一部分 |
| H100 rental price `$1.70` -> `$2.35` / +40% | 算力稀缺仍在定價，間接支撐 Cloud AI capacity 供不應求；不是 **GOOGL** 單獨收入 |

### 風險表

| 風險 | 風險等級 | 觸發條件 | 觀察指標 | 出處 |
|---|---|---|---|---|
| Google 數字口徑需校準 | 高 | Alphabet official filing 與 Bytc Note 數字、backlog 定義或 growth rate 不一致 | Alphabet 10-Q、earnings release、Google Cloud RPO / backlog definition | Bytc Note；整理者判斷 |
| Cloud demand 未轉 monetization | 高 | Google Cloud revenue / backlog 增長無法轉成 operating margin / FCF | Cloud operating income、capex、depreciation、FCF、utilization | Bytc Note；整理者判斷 |
| AI Search / capex cannibalization | 中高 | AI Mode / AI answers 增加 compute cost，但 ads / transaction monetization 跟不上 | paid clicks、RPM / CPC / CPA、AI query cost、Search margin | 既有 Bytc / KP thesis |

### 呼應連結

> 呼應 KP 2026-04-25 Google TPU 8、KP 2026-04-18 Google / Marvell SRAM inference，以及大叔 2026-02-21 Alphabet capex / century bond thesis：Bytc 這篇補的是最新 cloud demand 橫向財報檢查點。

---

## Bytc 對 **GOOGL** 的觀點摘要：Google capex 上修至 1850 億與四巨頭 AI 基建加碼

- **來源 KOL**：Bytc
- **原文主整理**：`KOL/Bytc/notes/bytc筆記.md`
- **原始來源**：https://substack.com/@btyc/note/c-251274427；https://www.sec.gov/Archives/edgar/data/1652044/000165204426000043/googexhibit991q12026.htm
- **source_id**：Bytc-20260429-four-giants-capex-710b-ai-infra-9c630e13
- **raw 路徑 / URL**：URL（未另存 raw）
- **OCR 狀態**：不適用
- **類型**：Substack Note / 四大科技 capex / Google AI infrastructure / hyperscaler demand
- **發文時間**：2026-04-29 22:53 UTC（台北 2026-04-30 06:53）
- **整理日期**：2026-05-01
- **交會等級**：L2
- **事件類型**：AI capex guidance / Google Cloud AI infrastructure / hyperscaler spending
- **主題 / 母題標籤**：#AI基建 #財報 #ReRating #估值風險 #執行風險

### 對 **GOOGL** 的影響

Bytc 將 Google 2026 capex 從約 `$165B` 上修至約 `$185B`，並把它放進四巨頭合計 capex 約 `$710B` 的 AI infrastructure spending map。對 **GOOGL** 的增量是 L2：這補強大叔 2026-02-21 Alphabet capex / 百年債 / energy moat thesis，以及 KP TPU / Cloud AI infrastructure 系列脈絡，但仍不是單篇改寫 Search / Cloud 主 thesis 的 L3 / L4 事件。

資料限制：Bytc 的 Google `$185B` 是本次 Note 口徑；Alphabet Q1 official release 已可校準 Q1 purchases of property and equipment 約 `$35.7B`，但 full-year guidance range 仍需等 official transcript / 10-Q 或後續 IR 文件校準。本筆記先記為 Bytc 口徑，不把 `$185B` 寫成已完成 official filing 驗證的唯一數字。

### 觀點摘要

| 面向 | 內容 |
|---|---|
| **立場** | 偏正面但需驗證；Bytc 認為四巨頭 capex 持續上修代表 AI 基建仍需要更多建設 |
| **關鍵數字** | Google capex Bytc 口徑從約 `$165B` 上修至 `$185B`；四巨頭合計約 `$710B` |
| **基本面含義** | 若 Google Cloud / TPU / AI Search 能消化 capex，這支持 Alphabet AI infrastructure utility thesis；若 monetization 不及，折舊與 FCF 壓力會加重 |
| **驗證點** | capex、depreciation、FCF、Google Cloud revenue / margin、AI Search monetization、TPU external adoption、energy milestones |
| **主要風險** | Full-year capex 口徑待 official 校準；上修可能是 demand 強，也可能是 component pricing / power / data center 成本上升 |

### 關鍵證據

| 證據 | 解讀 |
|---|---|
| Bytc 記錄 Google 從約 `$165B` 上修至 `$185B` | Google 在四巨頭 capex 上修中是主要增量之一，對 GOOGL AI infra thesis 是需求端 / 建設端補強 |
| Bytc 記錄四巨頭合計從約 `$665B` 上修至約 `$710B` | Alphabet 不只是單家公司提高 AI capex，而是身處整個 hyperscaler infrastructure upcycle |
| Alphabet Q1 2026 official release 記錄 Q1 purchases of property and equipment 約 `$35.7B` | 官方可校準當季 capex run-rate，但 full-year `$185B` 仍需後續 official 文件 / transcript 校準 |

### 風險表

| 風險 | 風險等級 | 觸發條件 | 觀察指標 | 出處 |
|---|---|---|---|---|
| Full-year capex 口徑需校準 | 高 | Bytc `$185B` 與後續 official transcript / 10-Q / IR 文件不一致 | Alphabet 10-Q、IR transcript、capex guide、PPE purchases | Bytc Note；整理者判斷 |
| Capex / depreciation 壓縮 FCF | 高 | Google Cloud / AI Search / TPU monetization 無法吸收新增 capex | depreciation、FCF、Cloud operating margin、AI Search margin | Bytc Note；既有大叔 / KP thesis |
| Component pricing / power cost 上升 | 中高 | 上修來自 memory、GPU、server、data center power 成本上升，而非可售 capacity 同比增加 | component pricing、power procurement、data center cost、capex efficiency | Microsoft / Meta official commentary；整理者延伸 |
| Hyperscaler 同步擴產壓 pricing | 中 | Microsoft / Amazon / Meta 同步擴建 capacity，未來 AI compute pricing 或 utilization 壓力上升 | cloud pricing、utilization、reserved capacity、GPU rental price | Bytc Note；整理者判斷 |

### 呼應連結

> 呼應 Bytc 2026-04-29《四巨頭段考成績單》：前一則補 Google Cloud / backlog 的 demand check，本篇補 Google capex 上修與四巨頭 spending map。

> 呼應大叔 2026-02-21 Alphabet capex / 百年債 / energy moat thesis，以及 KP TPU 8 / Google Cloud AI infrastructure 系列：capex 上修會提高 moat 的可能性，也同時提高折舊、FCF 與 ROIC 的驗證壓力。

---
