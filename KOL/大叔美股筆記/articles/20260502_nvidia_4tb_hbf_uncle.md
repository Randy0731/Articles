# 大叔美股筆記：NVIDIA 拒絕 4TB 巨無霸記憶體 HBF？

- **來源 KOL**：大叔美股筆記
- **原文 URL**：https://unclestocknotes.substack.com/p/nvidia-4tb-hbf
- **參考來源**：https://wccftech.com/nvidia-not-interested-in-hbf-memory-despite-4tb-stacks-dwarfing-hbm/；https://www.sandisk.com/en-gb/company/newsroom/press-releases/2025/2025-07-24-sandisk-forms-hbf-technical-advisory-board-to-guide-development-and-strategy-for-high-bandwidth-flash-memory-technology；https://documents.sandisk.com/content/dam/asset-library/en_us/assets/public/sandisk/collateral/company/Sandisk-HBF-Fact-Sheet.pdf
- **source_id**：大叔美股筆記-20260502-nvidia-4tb-hbf-ai-memory-hierarchy-73bf0f60
- **raw 路徑**：`KOL/大叔美股筆記/raw/20260502_大叔美股筆記_nvidia_4tb_hbf_大叔美股筆記-20260502-nvidia-4tb-hbf-ai-memory-hierarchy-73bf0f60.pdf`
- **發文時間**：2026-05-02（Substack 頁面 / PDF 顯示 May 02, 2026；時區未確認）
- **整理日期**：2026-05-02
- **OCR 狀態**：不適用（Substack HTML 正文可讀；使用者提供 10 頁截圖 PDF 作 raw 備份）
- **交會等級**：**SNDK** L3 tracked-stock follow-up；**GOOG** / **GOOGL** L2 tracked-stock context；**NVDA**, **AVGO**, **MRVL**, **MU**, **WDC**, **000660.KS**, **005930.KS**, **BESI.AS**, **BESIY**, **AMAT**, **LRCX**, **LPKFF**, **KLAC**, **FORM**, **ONTO** 為 ticker / supply-chain context
- **主題 tags**：#Memory #AI基建 #雲端基建 #先進封裝 #半導體設備 #ReRating #競爭風險 #估值風險 #執行風險

## 一句話結論

大叔將 Wccftech「NVIDIA 對 4TB HBF 不感興趣」的標題拆成 AI memory hierarchy 的分流問題：這不是 HBF 打敗 HBM，也不是 NVIDIA thesis 立刻破裂，而是 AI 系統可能分成 NVIDIA 的 HBM / NVLink / CUDA 高頻寬路線，以及 Google TPU / hyperscaler custom ASIC 更願意實驗的大容量、低成本記憶體層。

對 **SNDK** 而言，這篇是 HBF optionality 的後續補強：SanDisk 若能把 NAND 從 storage 延伸到 AI memory capacity tier，敘事會從 enterprise SSD / NBM 再往 AI memory layer 擴張。但 Google first customer、NVIDIA non-interest 等訊息主要來自 Wccftech 報導，尚非 Google / NVIDIA / SanDisk official 客戶公告。

## 核心脈絡

| 問題 | 大叔解讀 |
|---|---|
| HBF 是什麼？ | High Bandwidth Flash，把 NAND flash 用接近 HBM 的堆疊 / 封裝思路推向高頻寬、大容量記憶體層；它比較像介於 HBM 與 SSD 之間的新樓層，不是 HBM 直接替代品。 |
| 為何 4TB 引人注目？ | 現有 GPU HBM 容量仍受成本與封裝限制；若 HBF 可做到 4TB class capacity，可能讓大型模型 weights、long context 與 KV cache 更靠近 accelerator，降低外部 storage / PCIe / NVMe data movement bottleneck。 |
| 為何 NVIDIA 不感興趣？ | 大叔認為合理：NVIDIA 的 moat 在 GPU + HBM + NVLink / NVSwitch + CUDA 的封閉高頻寬系統。HBF 若成為便宜大容量層，可能弱化 HBM 容量稀缺與 GPU premium narrative；且 training workload 仍更需要 HBM 的低延遲 / 高頻寬。 |
| 為何 Google 可能感興趣？ | Google 擁有 TPU、compiler、Gemini workload 與 data center full stack，可針對 inference / long-context / cost-per-token 設計 memory hierarchy。Wccftech 稱 Google reportedly locked as first customer，需標「媒體報導 / 未確認」。 |
| 投資含義 | 不是「NVIDIA 被 HBF 打敗」，而是 AI 架構分流：NVIDIA 繼續守 training / high-bandwidth compute path，Google / hyperscalers 可能在 inference 與 custom ASIC 上嘗試 capacity-optimized memory tier。 |

## 對 **SNDK** 的影響

大叔這篇讓 **SNDK** 的 HBF optionality 從「KP 前史提到的新記憶體樓層」變成更具體的後續追蹤題：SanDisk official 已有 HBF 技術顧問委員會與 HBF fact sheet，支撐 HBF 不是單純市場傳言；但 Google 客戶鎖定與 NVIDIA 不採用仍以 Wccftech 報導為準，不能寫成 official design win / design loss。

對 SNDK thesis 的增量是：

| 面向 | 含義 |
|---|---|
| 產品邊界 | SNDK 不只被看作 NAND / enterprise SSD / NBM，也可能被看作 AI memory hierarchy supplier。 |
| 客戶驗證 | 若 Google reported first customer 後續被官方或供應鏈交付驗證，HBF optionality 會升級；未驗證前只能作 reported catalyst。 |
| Re-rating 路徑 | HBF 若進入 AI accelerators / custom ASIC ecosystem，SanDisk 可能從 storage capacity supplier 取得更高 multiple；但仍需規格、量產、良率、成本與實際 revenue 佐證。 |
| 風險 | HBF 可能只服務 niche inference / model-residency workload；若 bandwidth / latency / endurance / thermal / software stack 不達標，就難以突破概念股敘事。 |

## 對 **GOOG** / **GOOGL** 的影響

這篇對 **GOOGL** 是 L2 memory hierarchy 補強，與既有 Google TPU 8、Google / Marvell SRAM engine、TurboQuant、Apollo OCS 等線索一致：Google 的 AI infrastructure moat 不是單顆 TPU，而是 search / Gemini / Cloud workload、compiler、memory stack、interconnect、data center power 與供應鏈一起定義的 system-level TCO。

Wccftech 報導的「Google first customer」若被驗證，可能代表 Google 在 TPU / inference 系統上願意嘗試 HBF 作為大容量記憶體層。這和 KP 先前對 TPU 8 HBM / SRAM / MPU 分層、Google / Marvell SRAM inference engine、TurboQuant KV cache 壓縮的觀察相呼應：Google 不是只追最高 FLOPS，而是在追 cost per token、latency、model residency 與 Cloud AI margin。

## 對 **NVDA** 的影響

大叔沒有把 NVIDIA 對 HBF 不感興趣寫成利空。反而，他認為 NVIDIA 的選擇符合現有商業模式：

- Training 與最高效能 accelerator 仍高度依賴 HBM 低延遲 / 高頻寬。
- NVIDIA 的整套價值鏈在 GPU、CUDA、NVLink / NVSwitch、HBM allocation 與 AI factory system design。
- 若 HBF 主要解決 capacity tier / inference serving 問題，短期不會取代 NVIDIA training moat。
- 但若 hyperscaler custom ASIC + HBF 在 inference economics 上被證明有效，長期會削弱「所有 AI workload 都必須走 NVIDIA HBM-centric stack」的單一路徑敘事。

## 可能受惠供應鏈

| 類別 | 相關 ticker | 大叔文中含義 |
|---|---|---|
| HBF / NAND / memory producers | **SNDK**, **WDC**, **000660.KS**, **005930.KS**, **MU** | HBF 將 NAND 推向 AI memory layer；HBM 供應商未必被替代，但 memory hierarchy 會更複雜。 |
| Hyperscaler custom ASIC / IP | **GOOG** / **GOOGL**, **AVGO**, **MRVL** | Google 若採用 HBF，Broadcom / Marvell 等 ASIC / interface / custom silicon partner 可能受益於 HBF + HBM hybrid architecture。 |
| 先進封裝與設備 | **BESI.AS**, **BESIY**, **AMAT**, **LRCX**, **LPKFF**, **KLAC**, **FORM**, **ONTO** | HBF 若需要堆疊 NAND、TSV / hybrid bonding、metrology、probe / test 與先進封裝，設備與封裝鏈會取得 read-through。 |

上述供應鏈多數只是 L1-L2 context，不代表大叔對每檔都有獨立買點、目標價或完整 thesis。

## 新增框架：AI 架構分流 / 記憶體樓層分工框架

HBF 的重點不是取代 HBM，而是讓 AI memory stack 從「HBM vs SSD」變成更多樓層：

| 樓層 | 角色 | 可能適用 |
|---|---|---|
| HBM / SRAM | 最熱、最低延遲、最高頻寬工作區 | training、attention hot path、compute-near-memory |
| HBF | 高容量、較低成本、靠近 accelerator 的 model-residency / cold-warm tier | inference、long context、model weights、KV cache / memory expansion |
| SSD / NVMe / storage | 更低成本的大容量 storage | dataset、checkpoint、低頻 access |

投資檢查不是問「誰取代誰」，而是問 workload 是否真的願意把 weights / context / cache 分層，且軟體 stack、controller、interconnect、封裝與功耗是否支撐 production deployment。

## 風險與待驗證

| 風險 | 等級 | 觀察指標 |
|---|---|---|
| Google first customer 仍為媒體報導 | 高 | Google / SanDisk / supply-chain official confirmation、sampling / qualification、TPU roadmap disclosure |
| NVIDIA non-interest 被過度解讀 | 中高 | NVIDIA roadmap、HBM capacity、NVLink / memory pooling strategy、future HBF-like response |
| HBF 規格與 economics 未證明 | 高 | bandwidth、latency、endurance、thermal、power、controller / software stack、cost per GB / bandwidth |
| 封裝與製造難度 | 中高 | TSV / hybrid bonding yield、stack height、probe / test、metrology、thermal management、capex |
| SNDK re-rating 過度前置 | 高 | HBF revenue timeline、customer concentration、NBM / enterprise SSD 是否已被高估、gross margin durability |
| 對 HBM / NAND demand 的錯誤外推 | 中 | HBM bit demand、NAND pricing、enterprise SSD attach、HBF 是否真的擴大總 memory TAM |

## 後續追蹤

| 時間 / 頻率 | 事件 | 追蹤重點 |
|---|---|---|
| 2026H2 / 每次 official update | HBF sampling / customer verification | Google 是否被 official / supply chain 確認；SanDisk 是否披露 HBF sampling, qualification, capacity roadmap |
| 每季 | SNDK HBF / NBM / datacenter storage | HBF commentary、datacenter revenue、enterprise SSD ASP、NBM agreements、gross margin、FCF |
| 每次 Google TPU / Cloud AI update | Google memory hierarchy | TPU roadmap、HBM / SRAM / HBF / MPU stack、cost per token、Cloud AI margin、Gemini latency |
| 每次 NVIDIA architecture update | NVIDIA HBF stance | Rubin / next-gen memory strategy、HBM roadmap、NVLink memory pooling、software stack response |
| 每季 | 封裝與設備供應鏈 | hybrid bonding / TSV / metrology / probe demand、BESI / AMAT / LRCX / KLAC / FORM / ONTO commentary |

## 邊界

本文是 KOL 文章整理與來源校準，不提供買賣建議。Wccftech 的 Google / NVIDIA 客戶狀態必須標為 reported / 未確認；SanDisk official 只能用來支持 HBF 技術方向與 advisory board / fact sheet，不能反推已取得 Google design win。
