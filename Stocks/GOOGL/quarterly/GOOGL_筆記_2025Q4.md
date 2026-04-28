# GOOGL 筆記 2025Q4

此檔用於收錄 2025Q4 的一般 **GOOGL** / **GOOG** 筆記。里程碑事件放 `Stocks/GOOGL/milestones/`，長文深度分析放 `Stocks/GOOGL/longform/`。

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
