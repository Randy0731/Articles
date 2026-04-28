# GOOGL 筆記 2025Q4

此檔用於收錄 2025Q4 的一般 **GOOGL** / **GOOG** 筆記。里程碑事件放 `Stocks/GOOGL/milestones/`，長文深度分析放 `Stocks/GOOGL/longform/`。

---

## KP / FOMOSoc：Google Cloud 與 AWS 多雲互連，補強跨平台治理但也挑戰傳統 lock-in

- **source_id**：`KP_FOMOSoc-20251206-kp-thinking-note-19-aws-google-mstr-robotics-nvidia-synopsys-intel-netflix-alab-crdo-2e8b672a`
- **來源**：KP / FOMOSoc Substack 週報
- **原文**：https://www.fomosoc.com/p/netflixcrdoalab-kp19
- **發文時間**：2025-12-06 03:43 UTC（台北 11:43）
- **整理日期**：2026-04-29
- **交會等級**：L2+（已追蹤個股歷史補強）
- **主題 tags**：#雲端基建 #AI基建 #競爭風險 #執行風險 #ReRating

### 主旨

KP 在第 19 期將 Google Cloud 與 AWS 的 private multicloud networking / open interoperability spec 視為雲端競爭規則轉變：企業已經多雲化，AWS outage 後備援架構更重要，雲端供應商的價值不只在單一雲內的服務深度，也在誰能提供跨雲網路、治理、監控與合規。對 **GOOGL**，這補強 Google Cloud 以開放標準切入 enterprise architecture 的機會，但也提醒 Google Cloud 的差異化要能轉成 adoption / revenue / margin。

### 個股觀點

| 面向 | KP 觀點 | 對 **GOOGL** 的資料庫含義 |
|---|---|---|
| Google Cloud positioning | 雲端第三名與第一名合作，讓 Google Cloud 不只靠追趕功能，而是參與制定多雲互通規則 | 補強 Google Cloud enterprise relevance；從 TPU / AI compute 擴展到 networking / governance |
| 多雲現實 | KP 記錄 89% customers already multi-cloud，代表客戶架構已經跨雲 | Google Cloud 可用 open interconnect 降低 adoption 摩擦，承接非全量 migration 的 workload |
| AWS outage catalyst | Outage 讓 backup / resilience / cross-cloud architecture 從可選項變成必修題 | 延續 Cloud AI / TPU thesis：AI workload 若跨雲，需要低延遲、高可靠資料移動 |
| Microsoft 缺席 | Azure Arc 想當 cloud operating system / central control plane，AWS + Google 偏 point-to-point private interconnect / open spec | 對 Google 是機會也是風險：若 enterprise control plane 被 Microsoft 取得，Google 的互通標準可能只是一層網路功能 |
| AI workload placement | AI 基建投資將走向跨平台治理、資料主權與 workload placement | 與既有 TPU / Cloud AI / Anthropic / capex thesis 串接，需追 Cloud AI revenue 與 AI workload split |

### 延伸追蹤

| 事件 | 追蹤重點 |
|---|---|
| Google Cloud 財報 | revenue growth、operating margin、backlog conversion、AI compute revenue、networking / multicloud product commentary |
| Multicloud interconnect adoption | enterprise customer wins、AWS / Google co-selling、regulated industry use cases、latency / egress economics |
| AI workload split | Anthropic / Gemini / TPU / GPU workload placement、data movement cost、Cloud AI margin |
| Microsoft response | Azure Arc adoption、enterprise control plane share、hybrid / multicloud management wins |

### 風險與限制

- KP 的判斷是 Google Cloud 用 open multicloud interconnect 增加 enterprise relevance，不是說 Google Cloud 已追上 AWS 或 Azure。
- 多雲互通同時削弱單一雲 lock-in；Google Cloud 若無法把互通變成 paid workload / high-margin service，可能只幫客戶降低轉換摩擦。
- Azure Arc 若成為企業 control plane，Google Cloud 的互連標準需要靠實際 adoption 和 AI workload 來證明價值。
- 本文不是買賣建議。

---

## KP / FOMOSoc：GPU vs TPU 非零和競爭，補強 Google TPU 但不外推成 Nvidia thesis break

- **source_id**：`KP_FOMOSoc-20251129-kp-thinking-note-18-gpu-tpu-novo-dell-deere-hood-zscaler-bytedance-a772be14`
- **來源**：KP / FOMOSoc Substack 週報
- **原文**：https://www.fomosoc.com/p/gpu-tpu-kp17
- **發文時間**：2025-11-29 02:45 UTC（台北 10:45）
- **整理日期**：2026-04-29
- **交會等級**：L2+（已追蹤個股歷史補強）
- **主題 tags**：#AI基建 #雲端基建 #競爭風險 #ReRating #供應鏈風險

### 主旨

KP 在第 18 期校準 Google TPU / Nvidia GPU 爭論：TPU / ASIC 可在特定 inference workload 替代 GPU，尤其對 Google 自家或 Google Cloud 圍牆花園內的 workload 有成本效率；但若 AI TAM 持續指數級擴張，ASIC 成功未必等於 Nvidia thesis break，而是讓算力市場走向 workload 分工。對 **GOOGL**，這補強 TPU / Cloud AI 的差異化，但也要求後續用 revenue、utilization、cost per token 與外部 adoption 驗證。

### 個股觀點

| 面向 | KP 觀點 | 對 **GOOGL** 的資料庫含義 |
|---|---|---|
| 局部替代 | GPU 與 ASIC / TPU 技術架構不同，但商業應用上可在特定場景互相替代 | Google TPU 對 inference / internal workload 有真實競爭力；不可寫成「TPU 完全不影響 GPU」 |
| TAM 擴張 | 若算力市場固定，Google ASIC 會傷 Nvidia；若 TAM 快速擴大，ASIC 可能只拿走部分邊際利潤 | GOOGL thesis 要追 AI workload 總量與 TPU share，而不是只看 GPU vs TPU 二分法 |
| Nvidia anchor | KP 記錄 Nvidia 2025-2026 confirmed bookings 約 `$500B`，約 `$150B` 已交付、約 `$350B` backlog 至 2026 年底 | 對 GOOGL 是競爭邊界提醒：TPU 補強 Google Cloud，但不能外推成 Nvidia AI factory 生態已被瓦解 |
| Google TPU role | KP 承認 Google 自研 ASIC 在自家推論工作有成本效益和吸引力 | 與第 15 期 Ironwood TPU / 第 13 期 Anthropic TPU 脈絡串接，補強 Google TPU commercial validation |
| Physical bottleneck | KP 認為 Nvidia 真風險更偏 TSMC CoWoS 與全球電力基建，而非單純需求不足 | 對 GOOGL 的 AI infra 也同樣適用：Cloud AI 成長要看電力、data center、capex 和 depreciation |

### 延伸追蹤

| 事件 | 追蹤重點 |
|---|---|
| Google Cloud / TPU 財報線索 | TPU revenue visibility、Cloud AI revenue、Anthropic workload split、cost per token、gross margin、external customer adoption |
| Nvidia / TPU 競爭 | CUDA lock-in、GPU demand resilience、Nvidia AI factory backlog、Google Cloud 圍牆花園是否限制 TPU adoption |
| AI physical bottlenecks | CoWoS / advanced packaging、data center delivery、power availability、capex / depreciation、Cloud operating margin |
| Workload split | training vs inference、latency、cost、developer framework support、JAX / TensorFlow / CUDA ecosystem |

### 風險與限制

- KP 的判斷是 TPU / ASIC 具局部替代性，但不是 Google TPU 已全面取代 Nvidia GPU。
- 對 **GOOGL** 是歷史 L2+ 補強，不改變目前 dashboard 以 2026 capex / Search / Cloud AI monetization 為主的最新追蹤重心。
- Google TPU 若主要留在 Google Cloud 圍牆花園，commercial adoption 與 revenue conversion 仍需驗證。
- 本文不是買賣建議。

---

## KP / FOMOSoc：Waymo 高速公路與 Berkshire 買入 Alphabet，補強非 Search 選擇權與價值股框架

- **source_id**：`KP_FOMOSoc-20251115-kp-thinking-note-16-meta-waymo-coreweave-amd-softbank-nvo-google-e4ce0077`
- **來源**：KP / FOMOSoc Substack 週報
- **原文**：https://www.fomosoc.com/p/nvdaaimeta-kp16
- **發文時間**：2025-11-15 02:56 UTC（台北 10:56）
- **整理日期**：2026-04-29
- **交會等級**：L3（已追蹤個股歷史補強）
- **主題 tags**：#產品節點 #AI基建 #消費成長 #ReRating #競爭風險 #估值風險

### 主旨

KP 在第 16 期從兩個方向補強 Alphabet thesis：一是 Waymo 全無人 Robotaxi 擴展至高速公路，讓自動駕駛從限定市區 demo 走向更有效率的商業服務；二是 Berkshire Hathaway 新建倉 Alphabet，將 Google Search、YouTube、Google Cloud 重新理解為具有壟斷現金流與基礎設施屬性的現代公用事業。

### 個股觀點

| 面向 | KP 觀點 | 對 **GOOGL** 的資料庫含義 |
|---|---|---|
| Waymo highway | Waymo 在三藩市、洛杉磯、鳳凰城拓展高速公路路段，使 Robotaxi 能縮短機場通勤等高價值路線時間 | 補強 Alphabet 非 Search / Cloud 的長期 real-world AI optionality，Waymo 從科研項目更靠近可估值業務 |
| 漸進主義路線 | Waymo 以 LiDAR / radar / camera redundancy、Level 4 bounded-area rollout、監管合作取得高速公路突破 | 與 Tesla 純視覺路線分流；對 **GOOGL** 是較高確定性的商業化路徑，但成本和擴張速度需驗證 |
| Robotaxi valuation | KP 認為華爾街開始用數百億甚至上千億美元估值看 Waymo，因它的價值從故事變成財報 | 後續若 Alphabet 披露 Waymo rides、revenue、unit economics 或外部融資，需提高 dashboard 權重 |
| Berkshire buys Alphabet | Berkshire 第三季度新建 Alphabet 約 `$4.3B` 倉位、成為第 10 大持倉 | 補強「科技公用事業 / 現代價值股」框架，不等於買賣建議或估值保證 |
| Apple reduction context | Berkshire 同季繼續減持 Apple，KP 視為從過度集中贏家提取利潤，轉向另一個符合價值標準的科技平台 | 對 Alphabet 是 ownership-base / value-investor recognition signal；需追 13F position change 和主業現金流 |

### 延伸追蹤

| 事件 | 追蹤重點 |
|---|---|
| Waymo rollout | highway safety incidents、service area expansion、rides / revenue disclosure、cost per ride、regulatory approvals |
| Robotaxi competition | Tesla FSD / Robotaxi rollout、純視覺安全驗證、fleet data advantage、unit economics |
| Berkshire position | 後續 13F 是否加碼 / 減碼 Alphabet、是否繼續降低 Apple concentration、接班投資人配置風格 |
| Alphabet value-stock framing | Search cash flow durability、YouTube / Cloud growth、AI capex / depreciation、antitrust / default search remedy |

### 風險與限制

- KP 的判斷是 Waymo 漸進主義路線被重大驗證，不是說 Tesla FSD 路線已失敗。
- Waymo 的長期價值仍需用 rides、revenue、unit economics、保險 / 安全事故、城市擴張速度與監管許可驗證。
- Berkshire 買入 Alphabet 是重要 ownership / framework signal，但倉位仍需後續 13F 觀察，不能寫成估值便宜或未來報酬保證。
- 本文不是買賣建議。

---

## KP / FOMOSoc：Ironwood TPU 與 Gemini / Siri，補強 Google AI infrastructure 兩條路

- **source_id**：`KP_FOMOSoc-20251108-kp-thinking-note-15-google-tpu-siri-glp1-copper-meta-e18a7b9`
- **來源**：KP / FOMOSoc Substack 週報
- **原文**：https://www.fomosoc.com/p/trumpmusktpunvda-kp15
- **發文時間**：2025-11-08 03:00 UTC（台北 11:00）
- **整理日期**：2026-04-29
- **交會等級**：L3（已追蹤個股歷史補強）
- **主題 tags**：#AI基建 #雲端基建 #軟體SaaS #ReRating #競爭風險 #估值風險

### 主旨

KP 在第 15 期用兩條線補強 Alphabet AI thesis：一條是 Google Ironwood TPU 把 AI 基建競爭推向 inference / cost per token / 垂直整合；另一條是 Apple 每年約 `$1B` 讓 Siri 採用 Gemini，驗證 Google 可把 Gemini 做成 AI-as-a-Service 並打入競爭對手的高價值 device distribution。

### 個股觀點

| 面向 | KP 觀點 | 對 **GOOGL** 的資料庫含義 |
|---|---|---|
| Ironwood TPU | Ironwood 單晶片 `4.6 PetaFLOPS`，可把 `9,216` 顆組成 `42.5 ExaFLOPS` Pod，核心敘事是 inference era | 補強 Google TPU / Google Cloud 不只是訓練輔助，而是推理成本與規模效率的差異化 |
| Anthropic validation | Anthropic 訂購 `100萬顆` Ironwood TPU，多年期、數十億美元訂單，KP 視為市場用腳投票 | 與第 13 / 14 期 Anthropic / Google Cloud 線索串起來，形成 TPU commercial validation |
| Full-stack moat | Google 控制 Ironwood、Jupiter network、JAX / TensorFlow，可做全局軟硬整合 | 補強 Alphabet 垂直整合 AI infrastructure moat，但也要追 Google Cloud 圍牆花園 adoption 限制 |
| Nvidia comparison | Nvidia 是 open arms dealer / CUDA moat，Google 是 closed empire builder | 對 **GOOGL** 是差異化正面，對 **NVDA** 是競爭脈絡；不可寫成 Nvidia moat 已破 |
| Siri + Gemini | Apple 每年約 `$1B` 授權 Gemini 作 Siri 核心智能，模型約 `1.2萬億` 參數，將在 Apple private cloud 上運行 | Google 取得 18 億+ Apple devices 的 AI distribution；Gemini 從模型產品升級成 AI infrastructure service |
| AIaaS revenue | KP 認為交易驗證 AI-as-a-Service，並把 OpenAI 從 Siri brain 降成 optional app | 補強 Alphabet 搜尋廣告之外的 AI monetization optionality，也提高 antitrust / partner-dependence 檢查權重 |

### 延伸追蹤

| 事件 | 追蹤重點 |
|---|---|
| Google Cloud / TPU 財報線索 | TPU revenue visibility、Cloud AI revenue、Anthropic workload split、cost per token、gross margin |
| Apple enhanced Siri launch | 2026 launch timing、Gemini licensing durability、Apple private cloud privacy claims、user adoption |
| Nvidia / TPU 競爭 | CUDA lock-in、GPU demand resilience、Google Cloud 圍牆花園是否限制 Ironwood adoption |
| AI-as-a-Service | Gemini enterprise / platform revenue、external licensing deals、OpenAI competitive displacement |

### 風險與限制

- KP 的判斷是 Google 取得 inference 時代的有效進攻路徑，不是說 TPU 已全面取代 Nvidia GPU。
- Ironwood 目前仍在 Google Cloud 圍牆花園內，若外部 workload 遷移摩擦大，commercial adoption 會受限。
- Apple / Gemini deal 對 Google 是 distribution win，但合約條款、收入認列、隱私架構與 Apple 後續自研進度仍需校準。
- 本文不是買賣建議。

---

## KP / FOMOSoc：Google Cloud 從追趕者變成高利潤 AI 雲端挑戰者

- **source_id**：`KP_FOMOSoc-20251101-kp-thinking-note-14-meta-cloud-nvo-fiserv-cmg-nvidia-e81ba8c3`
- **來源**：KP / FOMOSoc Substack 週報
- **原文**：https://www.fomosoc.com/p/metanvidiaai-kp14
- **發文時間**：2025-11-01 02:45 UTC（台北 10:45）
- **整理日期**：2026-04-29
- **交會等級**：L2（已追蹤個股歷史補強）
- **主題 tags**：#雲端基建 #AI基建 #財報 #ReRating #競爭風險

### 主旨

KP 在第 14 期將 Google Cloud 的 Q3 財報視為「逆襲」：revenue +`34%`、operating profit 約 `$2.8B` 且年增約 `133%`，顯示 Google Cloud 不再只是燒錢追趕者。Meta 約 `$10B` AI compute deal、Anthropic 選擇數百萬顆 TPU，以及 backlog 約 `$155B`，共同補強 **GOOGL** 的 Cloud AI / TPU 商業背書。

### 個股觀點

| 面向 | KP 觀點 | 對 **GOOGL** 的資料庫含義 |
|---|---|---|
| Cloud growth | Google Cloud revenue +`34%`，增速只落後 Azure | 補強 Google Cloud 不只是 Search cash flow 附屬品，而是 AI infrastructure growth leg |
| Profitability | Operating profit 約 `$2.8B`，年增約 `133%` | 追 AI capex / depreciation 高峰下，Cloud margin 能否延續 |
| Enterprise validation | Q3 簽下超過 `$1B` 的大型合約數量比過去兩年總和更多，backlog 約 `$155B` | backlog / RPO conversion 成為 Cloud AI revenue 追蹤重點 |
| Differentiation | Meta 約 `$10B` AI compute、Anthropic 數百萬 TPU 部署，證明 Vertex AI / TPU / global network 有差異化 | 與第 13 期 Anthropic TPU 分工共同補強 Google TPU 作為推理 / AI workload platform 的 thesis |

### 延伸追蹤

| 事件 | 追蹤重點 |
|---|---|
| 每季 Google Cloud 財報 | revenue growth、operating profit、margin、backlog / RPO conversion、AI customer concentration |
| Meta / Anthropic workload updates | TPU allocation、AI compute deal revenue、inference workload、cost per token、gross margin |
| 三大雲端比較 | Azure + OpenAI、AWS Rainier / Trainium、Google TPU / Vertex AI 的 relative adoption |

### 風險與限制

- KP 的判斷是 Google Cloud 已成為不可忽視的挑戰者，不是說它已全面超越 Azure / AWS。
- Backlog 與大單需要看轉收入速度、margin、customer concentration 與 capex / depreciation，否則仍可能只是高投入換規模。
- 本文不是買賣建議。

---

## KP / FOMOSoc：Quantum Echoes 與 Anthropic TPU，補強 Google deep-tech 與 AI infrastructure 選擇權

- **source_id**：`KP_FOMOSoc-20251025-kp-thinking-note-13-openai-gm-quantum-aws-tsla-intc-nflx-bd0ee08c`
- **來源**：KP / FOMOSoc Substack 週報
- **原文**：https://www.fomosoc.com/p/altmanaws-kp13
- **發文時間**：2025-10-25 02:30 UTC（台北 10:30）
- **整理日期**：2026-04-29
- **交會等級**：L2（已追蹤個股歷史補強）
- **主題 tags**：#量子運算 #AI基建 #雲端基建 #ReRating #競爭風險

### 主旨

KP 將 Google Willow / Quantum Echoes 解讀為「可驗證」量子運算的路線圖驗證，而不是短期商業化爆發；同篇 Anthropic 轉向 Google TPU 的段落，則把 Google Cloud / TPU 放入 AI 推理 workload 的重要供應商位置。這兩者都補強 **GOOGL** 的 deep-tech optionality，但仍需回到 revenue、Cloud AI、TPU utilization 與量子 commercial timeline 驗證。

### 個股觀點

| 面向 | KP 觀點 | 對 **GOOGL** 的資料庫含義 |
|---|---|---|
| Quantum Echoes | 量子突破重點是可重複驗證的數值與錯誤校正路線，而不是明天破解加密 | 加入 quantum roadmap / error correction tracking，不寫成短期收入 thesis |
| Willow error correction | 增加更多實體 qubit 後，整體錯誤率可以下降，驗證「越大越穩定」理論 | 補強 Google deep-tech R&D moat，但仍需 scale proof |
| Anthropic x TPU | Google 提供最高約 100 萬顆 TPU，主要切入推理 / 高併發 / 低延遲 workload | 補強 Google Cloud / TPU 商業背書，需追 revenue conversion |
| 對 AWS 的分工 | 這不是零和勝負，而是 training / inference 分工 | 對 GOOGL 是正面驗證，但不能外推為全面贏下 Anthropic |

### 延伸追蹤

| 事件 | 追蹤重點 |
|---|---|
| Google quantum roadmap updates | qubit scale、error correction、peer repeatability、molecular / battery demos、quantum cloud products |
| Post-quantum security updates | RSA / ECDSA threat timeline、post-quantum cryptography adoption、enterprise security demand |
| Anthropic / Google Cloud updates | TPU allocation、inference workload、Google Cloud AI revenue、customer concentration、gross margin |

### 風險與限制

- KP 明確提醒，破解主流加密仍需數百萬個穩定 qubit，現階段只是約百個量級；這不是短期營收催化。
- Anthropic / Google TPU deal 是 AI infrastructure validation，不代表 Google Cloud 全面超越 AWS / Azure。
- 本文不是買賣建議。

---
