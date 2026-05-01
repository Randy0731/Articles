# 最近的心裡話：AI token 狂燒、算力稀缺與估值失靈

## Metadata

| 欄位 | 內容 |
|---|---|
| KOL | Bytc |
| 來源 | [Bytc Substack](https://btyc.substack.com/p/178?triedRedirect=true) |
| 類型 | Substack 文章 / AI Agent / token burn / compute scarcity / startup valuation / SaaS repricing / social bottleneck |
| 發文時間 | 2026-04-30（Substack HTML 顯示 Apr 30, 2026；使用者提供 PDF UI 顯示 May 01, 2026，推估為時區 / 顯示差異） |
| 整理日期 | 2026-05-01 |
| source_id | `Bytc-20260430-recent-thoughts-ai-token-scarcity-valuation-35987aef` |
| raw 備份 | `KOL/Bytc/raw/20260430_Bytc_recent_thoughts_ai_token_scarcity_valuation_Bytc-20260430-recent-thoughts-ai-token-scarcity-valuation-35987aef.pdf` |
| OCR / 完整性 | 不適用（Substack HTML 正文完整可讀；使用者提供 7 頁 image-only PDF 作 raw 備份，p.1-p.6 為核心正文，p.7 為文末與 comments / footer，未偵測截斷） |
| 相關 ticker | **NVDA**, **META**, **GOOG**/**GOOGL**, **CRWV**, **NBIS**, **SNOW**, **CRM**, **NOW**, **WDAY**, **BTC** |
| Tags | `#AI基建` `#軟體SaaS` `#估值風險` `#供應鏈風險` `#競爭風險` `#投資與投機` |

## 主旨

Bytc 這篇不是單一公司財報文，而是把近期 YC W26 交流、AI Agent 創業潮、Claude Code / Vibe Coding 普及、token 使用量暴增、GPU / API / data center 稀缺、以及 AI startup 估值混亂串成一套「AI 週期正在加速、舊估值框架失靈」的反思。

核心不是簡單說 AI 公司都很貴或都泡沫，而是：當市場用週為單位重估公司、當軟體工作逐步變成可並行消耗 token 的 AI labor，真正的瓶頸會從「誰會寫 code / 誰有 pitch」轉到「誰拿得到穩定算力、穩定 API、便宜 token、電力、資料中心、人才與社會容忍度」。

本文沒有提供買點、賣點或目標價；比較像 Bytc 的 AI infrastructure / startup valuation / investment psychology 框架更新。

## Ticker 分流

| Ticker | 判定 | 入庫處理 |
|---|---|---|
| **NVDA** | L2-L3 watchlist 補強。Bytc 把 Nvidia 放在 AI 算力配給與 chip allocation 的核心位置，認為真正稀缺的是 GPU、穩定供給、API uptime 與 data center buildout，而不是單純模型 demo。 | 更新 ticker / theme / framework / catalyst / watchlist；不建立 `Stocks/NVDA/`。 |
| **META** | L2 watchlist 語境。文章用 Meta 內部工具 `myclaw` 與後來允許 Claude Code 的例子，說明大型平台在 AI coding speed 與 security boundary 之間重新取捨。 | 更新 ticker / watchlist；不建立 `Stocks/META/`。 |
| **GOOG** / **GOOGL** | L1-L2 tracked-stock context。Google / DeepMind / Anthropic on Google Cloud 被用來說明 trust boundary、內部 coding tools、model-trains-models 與 Waymo 式 re-rating 類比，但不是新的 Alphabet 財務模型。 | 更新 ticker / theme；不同步 `Stocks/GOOGL/`，避免把框架案例寫成單股 thesis。 |
| **CRWV**, **NBIS** | L2 watchlist 補強。CoreWeave / Nebius 被放在 GPU cloud / neocloud / chip allocation / stable compute scarcity 的公開市場例子中。 | 更新 ticker / watchlist / catalyst；不建立 `Stocks/CRWV/` 或 `Stocks/NBIS/`。 |
| **SNOW**, **CRM**, **NOW**, **WDAY** | L1-L2 SaaS repricing context。Bytc 認為 AI agent 可能一邊幫 SaaS 客戶提高效率，一邊壓縮企業員工 / seat 數，迫使 seat-based SaaS 重新證明 AI revenue、usage pricing 與 margin。 | 更新 ticker / theme / framework；**CRM** / **NOW** 既有 watchlist 補充；不新增 `Stocks/`。 |
| **BTC** | L1 類比。Bytc 用早期 BTC 價差被 bot 快速套利的經驗，類比 AI 時代投資敘事與公司競爭的 re-pricing 速度。 | 只更新 ticker index 作框架類比；不作 crypto 交易觀點。 |

## 結構化重點

| 主題 | Bytc 觀點整理 | 投資含義 |
|---|---|---|
| AI Agent 創業速度 | Vibe Coding 和 Claude Code 讓基本產品 / 工程能力快速商品化，YC 類早期投資更難只看 deck 或傳統創業者履歷。 | AI-native startup 的 revenue ramp 可能很快，但 moat 也可能很短；投資人要更快檢查資料、distribution、workflow lock-in 和 compute access。 |
| Token burn | AI coding / agent adoption 會讓每位工程師背後的 token 使用量快速放大，AI 工具支出從 subscription 變成近似新 payroll / API budget。 | 評估 AI 公司時不能只看 headcount，要看 token cost、inference cost、usage caps、gross margin 與是否能把 AI labor 變現。 |
| 外部工具 vs 安全邊界 | Meta 先嘗試內部工具，後來允許外部 Claude Code；Google 因 Anthropic / cloud trust 關係有不同邊界。 | 大型平台若為 speed 放寬工具邊界，security / compliance / IP leakage 會成為新的治理成本。 |
| Stable API 溢價 | Claude API outages 圖被用來說明穩定 output 比 API access 更稀缺；若供應商能提供高 uptime，可能收取 premium。 | Cloud / neocloud / GPU provider 的價值不只看 GPU 數量，也看 uptime、SLA、routing、capacity reservation 和 enterprise trust。 |
| Chip allocation | AI 公司在 2028 前都不一定能自由取得足夠晶片；誰有 allocation 可能決定誰能活下來。 | **NVDA** / neocloud / hyperscaler 生態的核心檢查點是 GPU quota、power、data center commissioning、長約與客戶付款能力。 |
| Data center / power / politics | AI 算力短缺不是產品不夠好，而是現實中的電力、資料中心建設與地方社會容忍度跟不上。 | AI capex thesis 要加入 zoning、power interconnect、local backlash、permit、utility PPA 與 construction delay。 |
| SaaS repricing | SaaS 公司若用 AI agent 幫客戶減少員工，可能反過來打擊自身 seat-based model。 | **CRM** / **NOW** / **SNOW** / **WDAY** 等要用 AI ARR、usage revenue、retention、cRPO、margin 證明 AI 是淨增量。 |
| 估值雙軌 | 好 founder / 好關係 / 有資源的公司可用較低成本拿資源；後進投資人可能在更高估值、較差條款買入。 | AI private market 需要看 liquidation preference、ratchet、control terms、round quality、resource access，而不是只看 headline valuation。 |
| 心理衝擊 | Bytc 承認速度太快會讓研究者感到焦慮，但結論不是放棄，而是保持好奇、謙卑、想像力與紀律。 | 研究流程要接受 moving target：每季重估，不用單一靜態 fair value 裝作確定。 |

## 個股 / 資產觀點

| 標的 | 觀點方向 | 需要追蹤 |
|---|---|---|
| **NVDA** | 偏正面結構地位，但不是單篇估值文。Bytc 將 Nvidia 放在 AI 算力、chip allocation、GPU ecosystem 和穩定供給的中心。 | Blackwell / Rubin allocation、data center revenue、cost per token、gross margin、CSP / enterprise AI factory demand、neocloud financing quality、power / data center bottleneck。 |
| **META** | 中性偏觀察。Meta 的例子顯示 AI coding 工具已強到能改變大型科技公司的內部工程流程與安全邊界。 | 內部 AI coding tools adoption、external model cost / dependency、security policy、developer productivity、AI capex / depreciation、Llama / closed-source deployment。 |
| **GOOG** / **GOOGL** | 中性偏正面語境，但非新單股 thesis。Google / DeepMind / Anthropic 關係被用來說明 trust boundary 和 AI R&D flywheel。 | Gemini / DeepMind AI-generated code usage、Google Cloud AI revenue、Anthropic relationship、Waymo optionality、AI capex ROI、Search / Cloud monetization。 |
| **CRWV**, **NBIS** | 中性偏正面但高執行風險。若穩定算力和 API uptime 是 scarce product，neocloud 可能有 pricing power；但資本結構與交付風險不能忽略。 | Utilization、backlog conversion、debt cost、power / MW online、data center commissioning、customer concentration、GPU allocation、SLA / uptime。 |
| **SNOW**, **CRM**, **NOW**, **WDAY** | 中性偏風險。AI agent 會讓 SaaS 從 seat model 轉向 usage / workflow value；老 multiple 需要重新校準。 | AI ARR / revenue、consumption pricing、seat retention、customer ROI、gross margin after token cost、cRPO / NRR、workflow data moat。 |
| **BTC** | 只是市場微結構類比。Bytc 用早期 BTC 價差套利說明 feedback loop 加快，不代表本篇新增 BTC 方向。 | 無單獨 catalyst；若引用，只能作「市場重新定價速度」框架。 |

## 核心框架

### 1. Token Burn as Payroll / 算力預算框架

AI agents 讓公司花錢的方式從「多聘一個人」變成「讓 AI 並行跑更多任務」。這種支出不像傳統 SaaS subscription 有清楚上限，因為 AI 可以 24/7 工作，也可以同時開多條任務線。評估 AI-native 公司時，應把 token / inference / API spend 視為 quasi-payroll，檢查它是否真的帶來 revenue、product velocity、margin 或 customer retention。

觀察指標：tokens per engineer、API spend / employee、AI subscription tier、inference cost、usage caps、gross margin、AI product revenue、workflow completion rate。

### 2. 算力配給 / 穩定輸出溢價框架

模型 access 變得相對容易，但穩定、低延遲、高 uptime、可預約的算力仍然稀缺。若供應商能提供穩定 API 或有可靠 GPU / power / data center allocation，就可能比單純賣 commodity compute 更有 pricing power。

觀察指標：GPU quota、MW online、SLA / uptime、API outage hours、capacity reservation、take-or-pay contract、customer prepayment、data center commissioning、power interconnect。

### 3. AI 估值雙軌 / 快速重定價框架

AI startup valuation 不再只有 revenue multiple；resource access、founder quality、relationship、chip allocation、round terms 與 capital partner 都會影響真實價格。headline valuation 可能掩蓋 liquidation preference、ratchet 或 control terms，後進投資人和員工承擔的風險可能完全不同。

觀察指標：round structure、liquidation preference、ratchet、secondary discount、strategic investor、GPU allocation terms、ARR quality、burn multiple、gross margin after token cost。

## 風險與反例

| 風險 | 說明 |
|---|---|
| Moat 快速消失 | 人人都能用 AI 快速 build 時，初期 product velocity 變快，但功能差異可能很快被追平。 |
| Token cost 反噬 | AI labor 若沒有轉成 revenue 或 retention，token burn 會變成新的 cost black hole。 |
| Data center 社會阻力 | 電力、土地、用水、噪音、地方政治與環境反彈可能讓 AI infrastructure 建設比財務模型慢。 |
| SaaS seat cannibalization | AI agent 幫客戶縮減人力時，傳統 per-seat SaaS 可能同時失去 pricing base。 |
| Neocloud 資本結構 | GPU cloud 有需求不代表股東一定賺錢；若 debt cost、utilization、customer concentration 或 capex delay 失控，operating leverage 會反向放大。 |
| Private market 條款風險 | AI startup headline valuation 可能很好看，但實際 economics 被 preference / ratchet / control terms 重塑。 |

## 延伸追蹤

| 頻率 / 事件 | 追蹤問題 | 相關標的 |
|---|---|---|
| 每季 | Token / inference spend 是否轉成收入與毛利，而不是只放大 burn？ | AI software / AI-native startups / CSPs |
| 每季 | GPU allocation、data center MW online、API uptime 與 customer SLA 是否改善？ | **NVDA**, **CRWV**, **NBIS**, hyperscalers |
| 每季 | SaaS AI revenue 是否能抵消 seat / subscription 壓力？ | **CRM**, **NOW**, **SNOW**, **WDAY** |
| 每次地方政策更新 | Data center zoning、power interconnect、community opposition 是否延遲 AI capex？ | AI infrastructure chain |
| 每輪融資 | AI startup valuation 是否有 structured terms、preference 或 resource tie-in？ | private AI startups / strategic investors |

## 與既有 Bytc 框架的關聯

- 延續 Bytc 2026-03-17《GTC 2026 AI 基建時代的總包工頭》：本篇把 **NVDA** 從 AI factory / GPU platform 延伸到 chip allocation / stable compute / API uptime 的稀缺權力。
- 延續 Bytc 2026-03-18《AI 自主憲法與算力需求》：先前談 agent governance / token demand，本篇更聚焦 token burn、AI coding workflow 和 startup valuation。
- 呼應近期多篇 AI capex / 四巨頭雲端需求 Note：不是單純 CAPEX 越大越好，而是要問 spending 是否買到 capacity、revenue、uptime、pricing power 和可持續 margin。

## 整理者備註

本文判定為 Bytc 長文 / 框架型文章。雖然涉及多個公開 ticker，但主軸是 AI 產業結構、算力稀缺、SaaS 定價與投資心理，不是任一公司的完整單股研究，因此本次不新增 `Stocks/` 專案，也不把 Bytc 的私募估值或資源配置描述寫成公開股目標價或買賣建議。
