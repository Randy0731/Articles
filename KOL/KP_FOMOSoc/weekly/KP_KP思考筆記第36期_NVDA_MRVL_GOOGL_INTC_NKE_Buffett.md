# KP 思考筆記第36期：Nvidia / Marvell、Google 量子、Intel Fab 34、Nike 與 Buffett

- **來源 KOL**：KP / FOMOSoc
- **原始來源**：https://www.fomosoc.com/p/nvidiamarvellgoogleintel-kp36
- **source_id**：KP_FOMOSoc-20260404-kp-thinking-note-36-nvidia-marvell-google-quantum-intel-nike-buffett-11812b9b
- **raw 路徑 / URL**：URL（未另存 raw；Jina Reader Markdown 完整可讀）
- **OCR 狀態**：不適用
- **類型**：Substack 公開電子報 / KP 思考筆記 / 週報
- **發文時間**：2026-04-04 03:10 UTC（台北 11:10）
- **整理日期**：2026-04-29
- **文章完整性檢查**：Jina Reader Markdown 共 407 行；正文開頭明確自稱第 36 期，列出六個主題，六個段落均完整展開，結尾有宣傳段落與 KP 署名，未偵測核心正文截斷。
- **主題 / 母題標籤**：#投資與投機 #AI基建 #雲端基建 #量子運算 #加密貨幣 #消費成長 #監管審批 #政策風險 #競爭風險 #執行風險 #估值風險 #ReRating

## 一句話結論

KP 這期的主線是「不要崇拜預言，回到情境分析」：平台設計訴訟、Nike 中國本土化、Nvidia 用 NVLink Fusion 收編 custom ASIC / 光互連、Intel 贖回 Fab 34、Google 量子白皮書迫使 crypto 加速 PQC 遷移，以及 Buffett 訪談中的耐心與自我認知，都是在檢查商業模式的核心是否被真正動到。

## 相關 ticker 與交會等級

| Ticker | 交會等級 | 方向 | 摘要 |
|---|---:|---|---|
| **GOOG**, **GOOGL**, **META** | L2 | 平台責任風險 | 洛杉磯成癮式設計判決繞過 Section 230，短期仍是訴訟成本，真正風險是未來 12-24 個月若強制拆掉 infinite scroll / autoplay / recommendation 導致 engagement 下滑。 |
| **NKE** | L3 watchlist | Turnaround 風險 | 北美 Win Now 有效，但中國 Q4 指引 -20%，KP 認為問題是全球模板不適配中國本土文化與供應鏈競爭。 |
| **NVDA**, **MRVL**, **AVGO**, **AMZN**, **MSFT**, **GOOG**, **GOOGL**, **META**, **QCOM**, **LITE**, **COHR** | L2-L3 watchlist / context | AI 基建 | Nvidia 以 20 億美元投資 Marvell，是用 NVLink Fusion 把 custom ASIC、矽光子與 scale-up networking 收進 Nvidia 專有互連 / 軟體生態。 |
| **INTC** | L3 tracked stock | 轉型補強 | Intel 以 142 億美元買回 Fab 34 49% 股權，KP 解讀為從 2024 斷臂求生轉向收回 AI PC / Xeon 6 利潤的自信訊號；已同步 `Stocks/INTC/`。 |
| **GOOG**, **GOOGL**, **BTC**, **ETH**, **SOL**, **IBM**, **IONQ** | L2 tracked stock / crypto context | 量子 / PQC | Google Quantum AI 白皮書將 ECDSA 量子破解資源估計下修約 20 倍至約 50 萬 physical qubits；crypto 不是今天被破解，但 2029-2032 遷移窗口變得嚴肅。 |
| **BRK.A**, **BRK.B**, **AAPL** | L2-L3 watchlist / context | 投資哲學 | Buffett 訪談強調 5% 回調只是雜訊、賣早但買更早、買好公司並持有要建立在真正理解公司與自身條件上。 |

## 投資流程：反先知與情境分析

KP 開場提醒，市場轉折往往和主流情緒相反；投資人容易在恐慌中尋找「先知」，但專業方法不是猜精確底部，而是做 scenario analysis。這裡的可複用框架是：先看推論過程，再看結論；把不確定性與波動視為成本，事先定義 A / B 情境下的應對，而不是用高勝率敘事安撫焦慮。

### 框架：場景分析 / 反先知框架

- **定義**：不追求精準預測拐點，而是基於資料、商業邏輯與風險條件，建立可調整的情境樹。
- **適用情境**：戰爭 / 政策 / 財報 / 流動性造成的高波動市場；KOL 或社群大量宣稱精準抄底 / 清倉時。
- **觀察指標**：推論鏈是否可回溯、是否明確列出錯誤條件、部位是否可承受波動、現金 / 槓桿 / 集中度是否匹配 thesis。

## 主題一：Meta / Google 成癮式設計訴訟

洛杉磯陪審團判賠 600 萬美元，金額本身對 **META** / **GOOG** 幾乎無足輕重，但 KP 認為真正重要的是法律攻擊路徑：原告不是控告平台上的內容，而是控告產品設計本身，包括 infinite scroll、autoplay、algorithmic recommendation、notification 等成癮式設計。

這使案件繞過 Section 230 的內容免責護盾，轉向「平台是否明知設計有害仍未警告」。KP 用菸草訴訟作類比：若後續成千上萬件案件複製勝訴劇本，平台可能面對財務和產品設計雙重壓力。

KP 的判斷仍偏校準：現在還不是基本面被擊穿，而是要追 12-24 個月訴訟走向。真正的紅線不是賠款，而是法院或和解是否迫使平台拆除 / 限制推薦、無限滾動、自動播放，使使用時長、ad impressions 和 retention 大幅下滑。

### 框架：平台設計責任 / Section 230 繞道框架

- **定義**：平台風險從「使用者內容責任」轉成「平台是否用工程設計誘導成癮」，監管和訴訟可直接攻擊 engagement engine。
- **適用情境**：social media、short video、YouTube / Reels / TikTok、未成年人保護、平台產品責任訴訟。
- **觀察指標**：class action 數量、上訴判決、settlement language、minor safety controls、engagement minutes、ad impressions、family-safety product redesign。

## 主題二：Nike 的 Win Now 為何無法奏效

Nike Q3 北美營收 +3%、鞋類 +6%，但 Q4 指引總營收 -2% 至 -4%，大中華區 -20%，股價於 2026-04-01 大跌 15.5%。KP 認為市場不是只看單季 beat，而是看不到「造血」引擎。

Elliott Hill 的 Win Now 在北美有效：減少促銷、聚焦跑步、修復批發通路，批發業務 +11%。但同一套全球模板到中國失效。Adidas 以「在中國，為中國」策略、本地設計佔比約 60%，2025 年大中華區 +13%；安踏、李寧等本地品牌合計市佔近 56%，用文化認同、性價比與敏捷供應鏈改寫競爭。

KP 將 Nike 中國問題定義為「去神格化」：過去 logo 即身分，現在年輕消費者更重視本土文化與價格 / 功能。這不是單純庫存清理，而是品牌重新本土化的手術。

### 框架：全球模板 vs 本土化手術框架

- **定義**：全球品牌的通用 turnaround playbook 只能修復渠道與庫存，若當地消費文化 / 供應鏈 / 價格帶改變，必須重新做本土化產品與品牌語言。
- **適用情境**：global consumer brands、China / emerging market turnaround、品牌老化、local champions 擠壓。
- **觀察指標**：regional revenue、local product mix、inventory、wholesale recovery、brand heat、local competitor share、gross margin / tariff drag。

## 主題三：Nvidia 投資 Marvell 與 NVLink Fusion

Nvidia 向 Marvell 投資 20 億美元，透過可轉換優先股取得戰略股權，最初可轉換約 2180 萬股普通股。KP 認為這不是財務投資，而是 Nvidia 面對 hyperscaler custom silicon 反撲的生態收編。

Google TPU、Amazon Trainium、Microsoft Maia、Meta MTIA 都在把 inference 工作負載從通用 GPU 拉向 custom ASIC；ASIC 在特定推理場景可能便宜 30%-50%。Nvidia 的風險不是被完全取代，而是被邊緣化到高階訓練。

NVLink Fusion 的策略是：客戶可以用自己的 XPU / CPU，但必須接入 Nvidia 的 NVLink、networking 與 software stack。Marvell、MediaTek、Qualcomm、Fujitsu、Samsung Foundry 等合作夥伴可授權 NVLink IP，但每個部署都需要 Nvidia 元件，且 CUDA / NCCL / Nvidia AI Enterprise 仍保留軟體鎖定。

Marvell 的特殊性在三點：一是和 Broadcom 同為 custom ASIC 兩大設計公司，與 AWS / Microsoft / Google 關係深；二是高速類比、optical DSP、silicon photonics 領先；三是具 telecom networking 能力，可切入 AI-RAN。Marvell 2025 年收購 Celestial AI 的 Photonic Fabric 技術，KP 記錄可達 16 Tbps optical chipset，對 gigawatt AI factory 重要。

KP 也把 Nvidia 對 Lumentum、Coherent 各 20 億美元投資放在同一脈絡：Nvidia 正把離散光學元件、矽光子、custom silicon 與 scale-up networking 垂直收編。

### 框架：NVLink Fusion / 開放式收編框架

- **定義**：平台 leader 表面開放第三方晶片進入，實際上用互連、授權與軟體 stack 把 heterogenous compute 收進自家控制層。
- **適用情境**：AI rack architecture、custom ASIC、GPU vs XPU、hyperscaler self-build、interconnect standards。
- **觀察指標**：NVLink Fusion design wins、third-party XPU attach、Nvidia component attach、CUDA / NCCL usage、UALink competitive response、hyperscaler custom ASIC adoption。

### 框架：矽光子垂直整合 / 光學供應鏈收編框架

- **定義**：AI cluster 放大到數十萬 / 百萬 accelerator 後，互連功耗、距離、頻寬密度成為瓶頸，leader 會投資 optical components、DSP、silicon photonics 和 custom silicon 來控制下一代 data center fabric。
- **適用情境**：1.6T / 3.2T optics、CPO、silicon photonics、NVLink / Ethernet scale-up networking、AI-RAN。
- **觀察指標**：optical DSP revenue、1.6T+ design wins、Rubin reference design、CPO / co-packaged optics timing、LITE / COHR / MRVL qualification、component margin。

## 主題四：Intel 30 億美元贖金與 Fab 34

Intel 將以 142 億美元從 Apollo 買回愛爾蘭 Fab 34 的 49% 股權。KP 將其拆成：2024 年以 112 億美元出售是「斷臂求生」，2026 年願意多付約 30 億美元溢價贖回，表示管理層認為現金流、成本控制和業務動能已改善，不再需要外部財務拐杖。

Fab 34 生產 Intel 4 / Intel 3，是 Core Ultra AI PC 與 Xeon 6 AI server 的核心製程。KP 的解讀是，Intel 現在想完整捕捉 AI PC / AI inference demand 的利潤，不願再把 Fab 34 收割期分給 Apollo。Intel 表示此交易 2027 年起對 EPS 增益，即使新增約 65 億美元債務，也看好獨佔利潤高於融資成本。

這與擴張性收購不同，KP 將其定義為從「做大」轉向「做強」：Intel 不新增 wafer capacity，但拿回高利潤資產控制權，從收縮防禦轉向自信進攻。真正答案要看 2027 財報。

### 框架：Fab 34 贖回 / 從斷臂求生到利潤收回框架

- **定義**：公司在資金壓力高點出售核心資產求生，若後續願意溢價買回，代表管理層認為該資產進入收割期且內部資金狀況足以承擔控制權。
- **適用情境**：semiconductor fabs、sale-leaseback / joint venture unwind、capital-intensive turnaround。
- **觀察指標**：Fab utilization、Intel 3 / Intel 4 margin、DCAI / CCG demand、EPS accretion、new debt cost、FCF、Foundry external customers。

## 主題五：Google Quantum AI 與 crypto PQC 倒數

Google Quantum AI 與 Ethereum Foundation、Stanford 共同完成白皮書，KP 記錄其將破解 ECDSA 所需資源估計下修約 20 倍，從數百萬 / 千萬 physical qubits 降到約 50 萬 physical qubits。一台達標 CRQC 理論上可在約 9 分鐘破解等待打包的 Bitcoin transaction，讓 on-spend attack 從理論變得可討論。

KP 同時做了風險校準：Google Willow 只有 105 個 physical qubits，IBM Heron 約 133-156 個，距離 50 萬還差數千倍。真正變化不是今天能破解，而是 quantum error correction 讓 roadmap 加速。IBM / IonQ 等將 2029 年視為數千至數萬 logical qubits 的關鍵節點，Google 也把內部 PQC 遷移 deadline 提前到 2029。

解法是 post-quantum cryptography，例如 Falcon、XMSS 等。技術方案已存在，但去中心化鏈的瓶頸是治理共識。Ethereum 有 Foundation 參與白皮書與 PQC roadmap，Solana 測試 Winternitz vault；Bitcoin 則因 governance 和早期 public key exposure / dormant coins 遷移更難。

KP 的結論是：crypto 沒有今天被破解，但 2029-2032 是嚴肅窗口；這是死亡判決書之前，更像進化催化劑。

### 框架：Quantum Countdown / PQC 治理遷移框架

- **定義**：量子威脅的投資含義不在今天被破解，而在可預期時間窗內，誰能完成 cryptographic migration、governance consensus 與使用者遷移。
- **適用情境**：Bitcoin / Ethereum / Solana、PQC migration、quantum security、digital asset custody。
- **觀察指標**：logical qubits roadmap、error correction progress、PQC standards adoption、Ethereum / Solana upgrades、Bitcoin BIP progress、exchange / custody migration policy、dormant coins exposure。

## 主題六：Buffett 訪談、波動與自我認知

Buffett 在 CNBC 訪談中對 5% 回調反應平淡，KP 將其整理為三個認知維度。第一，Berkshire 歷史上多次腰斬，波動是入場門票；真正機會是 30%-50% 的恐慌，不是 5% headline。普通投資者不能照抄「等 50% 崩盤」，但要學心理韌性。

第二，Buffett 承認 Apple 賣早，但補上「買得更早」。KP 用此提醒：投資不是完美抓頂，而是吃到主要段落、靠低成本與安全邊際讓時間複利工作。

第三，Buffett 將美國經濟比喻為大教堂，旁邊是引誘交易的賭場。買好公司並持有 50 年的前提，是你真的買到好公司；盲目複製 Buffett 而沒有巨大現金流、價值判斷力與耐心，是最危險的跟風。

### 框架：大教堂 vs 賭場 / 自我認知定力框架

- **定義**：長期投資的優勢不是預測短線，而是能分辨財富創造引擎與交易誘惑，並選擇符合自身資源和心理條件的策略。
- **適用情境**：market drawdown、value investing、portfolio turnover、brokerage gamification、FOMO / regret management。
- **觀察指標**：turnover、cost basis、holding period、business quality、cashflow cushion、drawdown tolerance、margin of safety、strategy fit。

## 對已追蹤個股的同步判定

- **INTC**：L3；Fab 34 贖回直接影響 Intel capital allocation、Intel 3/4 利潤收回、AI PC / Xeon 6 inference demand thesis，已同步 `Stocks/INTC/quarterly/INTC_筆記_2026Q2.md`、`INTC_index.md`、`INTC_儀表板.md`。
- **GOOG / GOOGL**：L2；平台設計責任訴訟與 Quantum AI / PQC whitepaper 都不是單篇核心估值重寫，但會補強 Alphabet ads / platform liability risk map 與 quantum optionality / crypto security read-through，已新建 `Stocks/GOOGL/quarterly/GOOGL_筆記_2026Q2.md` 並更新 index / dashboard。
- **IBM**：只在量子硬體同業比較中出現，屬 L1 context，不同步 `Stocks/IBM/`。
- **AMZN**：只作 hyperscaler custom ASIC / Trainium context，非本篇 AMZN thesis，不同步 `Stocks/AMZN/`。

## 後續追蹤清單

| 時間 / 頻率 | 追蹤事件 | 相關 ticker | 重點 |
|---|---|---|---|
| 12-24 個月 | 平台成癮式設計訴訟後續 | **META**, **GOOG**, **GOOGL** | appeal / settlement、minor product changes、engagement time、ad revenue impact |
| 2-3 季 | Nike 中國 turnaround | **NKE** | Greater China revenue、local product mix、inventory、gross margin、tariff mitigation |
| 2026Q3 | NVLink Fusion / Marvell semi-custom reference design | **NVDA**, **MRVL**, **LITE**, **COHR** | Rubin / 1.6T+ optical DSP integration、design wins、hyperscaler adoption |
| 2027 | Intel Fab 34 EPS accretion | **INTC** | EPS accretion、Intel 3/4 utilization、DCAI / CCG demand、debt cost、FCF |
| 2029-2032 | PQC migration window | **GOOG**, **GOOGL**, **BTC**, **ETH**, **SOL**, **IONQ**, **IBM** | logical qubits、PQC roadmap、Ethereum / Solana upgrade、Bitcoin BIP progress |

## 資料品質與限制

- 本文整理自 FOMOSoc Substack 公開文章的 Jina Reader Markdown，未另存 raw；URL 可回溯來源。
- 原文涉及多家公司與未上市實體；本整理只記錄 KOL 觀點與投資框架，不構成買賣建議。
- Marvell / Nvidia / Google quantum / Intel Fab 34 的交易與技術數字沿用 KP 文內口徑，未在本篇另行外部查驗；後續若進入單股深度或財報驗證，需再用官方 filings / press release 校準。
