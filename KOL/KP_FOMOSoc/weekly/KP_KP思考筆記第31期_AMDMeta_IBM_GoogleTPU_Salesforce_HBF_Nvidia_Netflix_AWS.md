# KP 思考筆記第31期：AMD / Meta、IBM、Google TPU、Salesforce、HBF、Nvidia、Netflix 與 AWS

## Metadata

- **來源 KOL**：KP / FOMOSoc
- **原文標題**：Nvidia還可以怎樣？SanDisk的HBF是甚麼？奈飛終於放棄了？ - KP思考筆記(第31期)
- **原始來源**：https://www.fomosoc.com/p/nvidiasandiskhbf-kp31
- **source_id**：KP_FOMOSoc-20260228-kp-thinking-note-31-amd-meta-ibm-google-tpu-salesforce-hbf-nvidia-netflix-openai-aws-5e901705
- **發文時間**：2026-02-28 03:51 UTC（台北 11:51）
- **整理日期**：2026-04-29
- **raw 路徑 / URL**：URL（未另存 raw；Jina Reader Markdown）
- **Jina Markdown SHA256**：5e9017058a5fe85281158df4fa8ff9669e070d08cf4a59c41811bad1415b0e3d
- **OCR 狀態**：不適用
- **文章類型**：Substack 公開週報 / KP 思考筆記 / AI 基建 / 企業軟體 / Memory / 串流併購 / 雲端基建
- **完整性檢查**：Jina Reader Markdown 完整可讀；正文開頭明確自稱第31期，文內列出 AMD / Meta、IBM、Google TPU、Salesforce、SanDisk / SK Hynix HBF、Nvidia 財報、Netflix / WBD、OpenAI / Amazon 八個主題，結尾有宣傳段落與 KP 署名，未偵測截斷。

---

## 總結

第31期的主軸是 AI 熱潮進入預期消化期後，市場開始分辨「誰有真實物理資產、分銷能力、企業流程控制權和可驗證 ROI」。KP 先用 HALO 交易說明資金短期偏好 hard assets；接著拆 AMD 以 warrants 換 Meta 6GW AI 算力大單、Anthropic / Claude Code 對 IBM mainframe / COBOL moat 的侵蝕、Google 透過 FluidStack 把 TPU 推出圍牆、Salesforce 用 Agentforce / AWU 挑戰 seat-based SaaS、SanDisk / SK Hynix HBF 填補 HBM 與 SSD 之間的記憶體斷層、Nvidia 完美財報後仍需新敘事、Netflix 放棄 WBD 收購後的資本紀律與成長缺口，以及 OpenAI / Amazon 用 Frontier + Bedrock + Stateful Runtime 搶企業 AI 作業系統層。

整理者判定：**IBM** 為已追蹤個股 L2-L3 風險補強，需同步 `Stocks/IBM/`；**GOOG** / **GOOGL** 為已追蹤個股 L3，需同步 Google TPU 外部化 / FluidStack / Meta TPU lease；**AMZN** 為已追蹤個股 L3，需同步 OpenAI / AWS Frontier distribution / Stateful Runtime。**CRM** 與 **000660.KS** 新增 watchlist；**SNDK**, **NFLX**, **WBD**, **AMD**, **META**, **NVDA**, **MU**, **MSFT** 等為既有 watchlist / ticker 補強；OpenAI、Anthropic、FluidStack、SK Hynix 若採 ADR / foreign ticker 以索引輔助，不建立正式 `Stocks/`。

---

## 主題地圖

| 主題 | KP 核心觀點 | 相關 ticker | 入庫判定 |
|---|---|---|---|
| AMD / Meta 6GW deal | AMD 用最高 10% warrants 綁定 Meta，換取 ROCm / Instinct 大規模驗證與二號供應商地位 | **AMD**, **META**, **NVDA**, **TSM** | AMD / META / NVDA watchlist 補強 |
| IBM / Claude Code | AI legacy modernization 會壓縮 IBM COBOL / mainframe / consulting 的知識不對稱 moat，但 mainframe 穩定性仍給 IBM 緩衝期 | **IBM**, **AMZN**, **MSFT** | IBM L2-L3 同步 |
| Google TPU 外部化 | Google 透過 FluidStack / Meta TPU lease 複製 Nvidia neocloud 影子戰爭，把 TPU 從成本中心推向利潤中心 | **GOOG**, **GOOGL**, **META**, **NVDA**, **CRWV**, **NBIS**, **HUT**, **WULF** | GOOGL L3 同步；neocloud ticker index |
| Salesforce Agentforce | Salesforce 主動拆 seat-based pricing，改用 Flex Credits / AWU 對 AI agent 完成工作收費，但收入與毛利仍未證明 | **CRM**, **MSFT**, **NOW**, **DDOG**, **PANW** | CRM 新增 watchlist |
| SanDisk / SK Hynix HBF | HBF 是 NAND Flash 版 HBM，試圖成為 HBM 與 SSD 之間的新記憶體層；成敗取決於 Nvidia / OCP / CoWoS 生態接納 | **SNDK**, **000660.KS**, **005930.KS**, **MU**, **NVDA**, **AMD**, **TSM** | SNDK 補強；000660.KS 新增 watchlist |
| Nvidia 財報 | 財報很強但已成市場基本預期；接下來要證明客戶 ROI、sovereign AI、inference cost 與 GTC 2027 敘事 | **NVDA**, **META**, **MSFT**, **GOOG**, **GOOGL**, **AMZN** | NVDA watchlist 補強 |
| Netflix / WBD | 放棄 WBD 收購展現資本紀律、移除過度支付風險，但也留下下一個增長引擎問題 | **NFLX**, **WBD**, **PARA** | NFLX / WBD watchlist 補強 |
| OpenAI / Amazon | Amazon 用 500 億美元投資、1380 億美元 AWS spend、Frontier 分銷權與 Bedrock Stateful Runtime，買企業 AI 作業系統入口 | **AMZN**, **MSFT**, **NVDA**, **GOOG**, **GOOGL** | AMZN L3 同步 |

---

## 0. HALO 交易：買硬不買軟的預期重置

KP 開場用 Nvidia 財報後市場仍不滿足，說明 AI 預期已高到需要時間消化。華爾街開始流行 HALO（Heavy Assets, Low Obsolescence），也就是偏向 hard assets、低淘汰風險、被市場期待較低但基本面正在改善的資產。

這不是單純看空科技，而是資金在 AI 軟體顛覆風險不清楚時，先轉向實體資產、能源、銅、重工業、半導體上游與日本商社等「被忽視但不可替代」的資產。整理者判定：本段是 macro / style framework，不直接新增 ticker；可與第30期 copper / hard asset thesis 交叉比對。

---

## 1. AMD 為何要送股：用未來換 Meta 現在入場券

KP 將 AMD 與 Meta 的 AI 算力協議視為挑戰者的非常規作戰。Meta 承諾採購最高 6GW AMD Instinct GPU，協議規模約 600 億美元；AMD 則提供最高 10% 股權認股權證，讓 Meta 未來可在條件達成時取得最高約 1.6 億股 AMD 股票。

條件分兩層：Meta 必須實際完成 1GW 到 6GW 的採購 / 部署；AMD 股價也必須達到指定門檻，KP 口徑最終目標約 600 美元。這讓 Meta 從客戶變成命運共同體：若 AMD 因大單與平台驗證重估，Meta 可分享股權收益，甚至部分抵銷硬體採購成本。

對 AMD，重點不是只賣 GPU，而是取得旗艦級超大規模客戶，證明 ROCm / Instinct 能在 scale-out 場景穩定運行，並提高向 TSMC / CoWoS 預訂產能的底氣。對 Meta，這是扶植 Nvidia 之外二號供應商，降低單一供應商風險，並用 PyTorch 主導權替 AMD 填平 CUDA 軟體鴻溝。KP 認為 Nvidia 短期霸主地位不動搖，但長期所有 hyperscaler 都會扶植第二供應商。

整理者判定：**AMD**, **META**, **NVDA** 為既有 watchlist 補強；這篇是第30期 Meta 先綁 Nvidia 後扶植 AMD 的連續篇，核心追 Meta 是否真的把 PyTorch / Llama / data center 工程資源投入 ROCm，AMD 是否把 6GW deal 轉成 revenue、margin、customer diversification 與軟體生態可信度。

---

## 2. IBM 的護城河漏水：AI 把 COBOL 知識不對稱變透明

KP 用 Anthropic Claude Code 進入 COBOL modernization 說明 **IBM** 的傳統 moat 被重新定義。IBM 長期依靠大型主機、COBOL 系統穩定性與昂貴 consulting，掌握金融、政府、保險、航空等最核心 legacy system。這些系統的真正鎖定不是語言本身，而是風險、不可停機、沒人敢重寫的知識不對稱。

Claude Code / AWS Transform 類工具若能讀懂數十萬行 COBOL、分析商業邏輯、繪製依賴圖並協助轉成 Java / Python，IBM 的 consulting 費與 mainframe lock-in 都會被壓縮。KP 但也校準風險：code translation 不等於完整 system modernization，銀行等零停機場景仍需要 governance、compliance、system integration 與 mainframe stability。

整理者判定：**IBM** 已追蹤個股 L2-L3 風險補強。這不推翻大叔 2026-04-23 對 IBM software / hybrid cloud / enterprise AI 現金流化的正面 thesis，但把「consulting 是 AI 導入前鋒」補上一個反身性風險：AI 工具也可能壓縮傳統 modernization consulting economics。後續追 consulting bookings / margin、mainframe renewals、watsonx / Claude / AWS Transform 類工具是否把 legacy workload 搬上 AWS / Azure，以及 IBM 能否把 moat 從知識不對稱轉成速度與整合能力。

---

## 3. Google TPU 走出圍牆：從內部成本中心到外部利潤中心

KP 認為 Google 正在複製 Nvidia 的 neocloud 影子戰爭。Google 考慮投資 FluidStack，並提供數十億美元租賃擔保，讓這類輕資產 neocloud 利用 Hut 8、TeraWulf 等閒置礦場 / 電力資源轉成 AI data center，再把 TPU 帶出 Google Cloud 圍牆。

此舉的標誌性事件是 Meta 與 Google 簽下數十億美元 TPU lease，甚至考慮未來直接購買 TPU 放進自家 data center。KP 認為這代表 Google TPU 不只是 inference 省錢工具，而開始挑戰 training 場景；如果 Meta 願意用 TPU 訓練模型，表示 JAX / XLA / TorchTPU 軟體門檻正在下降。

但 KP 明確列出兩座山：

| 山 | 內容 |
|---|---|
| CUDA 軟體護城河 | PyTorch / CUDA 慣性仍強，TorchTPU 至少需要 12-18 個月證明 production readiness |
| CoWoS 產能瓶頸 | TPU 與 Nvidia GPU 都依賴 TSMC advanced packaging，Google 2026 TPU 出貨約 310-360 萬片，外部供應量可能只有 Nvidia 外部 GPU 的 20-30% |

整理者判定：**GOOGL** L3 同步。這篇延續第21期 TorchTPU、第28期 AI Search、第29期 OCS / HBM、第30期 clean baseload；Google TPU thesis 從內部成本效率，進一步升級成外部 commercial distribution / neocloud financing。後續追 FluidStack deal terms、lease guarantee、Meta TPU lease / direct purchase、TorchTPU readiness、Cloud AI revenue、TPU supply / CoWoS allocation 與 Nvidia 反制。

---

## 4. Salesforce Agentforce：從人頭稅到數位勞動力稅

KP 將 Salesforce 的 Agentforce 放進 SaaS 模式重塑。傳統 SaaS 靠 seat-based pricing，如果 AI agent 可取代 10 個人的工作，企業未必需要 10 個帳號；Salesforce 因此用 Flex Credits / AWU（Agentic Work Units）嘗試把收費對象從人頭改成完成的工作。

Agentforce ARR 從 5 億美元增到 8 億美元，顯示企業願意嘗試數位勞動力。但 KP 也提醒，FY2026 Salesforce revenue 約 415 億美元，Agentforce 佔比約 1.9%，還不足以抵消核心 CRM 7-8% 增長放緩。AI agent 也會帶來 token / compute 成本，雖然 non-GAAP operating margin 仍有 34.2%，但 AI 業務提高到 10% 或 20% revenue mix 時，毛利是否維持尚無實證。

Salesforce 用 500 億美元回購授權、144 億美元 FCF 與 2030 年 630 億美元 revenue target 安撫市場；真正 moat 則在 Data 360、Informatica 和企業客戶數據。KP 的核心是：沒有數據的 AI 只是聊天機器人，擁有客戶全貌數據的 AI 才是 agent。

整理者判定：**CRM** 新增 watchlist。後續追 Agentforce ARR、Flex Credits / AWU pricing、gross margin、AI compute cost、Data 360 usage、Informatica integration、core subscription growth、operating margin 與 buyback 是否只是成熟期防禦。

---

## 5. SanDisk / SK Hynix HBF：Memory hierarchy 的新樓層

KP 將 HBF（High Bandwidth Flash）定義為 Flash 版 HBM。HBM 速度快但容量小、價格高；SSD 容量大但速度慢。SanDisk 想用 CBA 晶圓鍵合把 NAND Flash 垂直堆疊，做出接近 HBM 頻寬但具 SSD 容量的中間層，用來放大型模型權重、長上下文與 KV cache，降低 GPU 因 HBM 容量不足而閒置。

HBF 不是取代 HBM，而是在記憶體金字塔裡擠出新樓層。成敗取決於三件事：Nvidia 是否納入下一代 GPU reference design；SK Hynix 能否用 HBM 市場關係與 TSMC / CoWoS 產能話語權替 HBF 取得進場券；OCP 開放標準能否讓 HBF 不是 SanDisk 單家公司產品。

KP 同時記錄競爭路徑：Samsung 傾向自研 HBF，目標 2027 年量產；Micron 當下更專注 HBM4，是否加入 OCP 是變數。短期 HBF 可能擠壓 NAND / SSD 供應，2026-2027 年頂級 NAND 更緊；長期若 HBF 分擔 HBM 的 storage load，反而可能釋放部分 HBM 供給給 training。

整理者判定：**SNDK** 既有 watchlist 補強，**000660.KS** / SK Hynix 新增 HBF / HBM-to-NAND extension watchlist；**005930.KS**, **MU**, **NVDA**, **AMD**, **TSM** 進 ticker / theme context。後續追 HBF prototype / standard、Nvidia design-in、OCP adoption、CoWoS allocation、NAND pricing、SSD shortage、SK Hynix / Samsung / Micron roadmap。

---

## 6. Nvidia 財報：完美數字也需要新故事

KP 認為 Nvidia 財報再次漂亮：營收年增 73%、毛利率約 75%、指引高於市場預期。但股價仍弱，因為「超越預期」已成基本預期。市場現在問的是 AI 是否能成為數年級別結構性 supercycle，而不只是短期 capex bubble。

第一個驗證是客戶 ROI。Microsoft、Google、Amazon、Meta 四大客戶佔 Nvidia 近半營收，Nvidia 命運與這些客戶能否把 AI 轉成 revenue / net income 綁在一起。KP 提到 Meta 透過 GEM 模型讓 Facebook ad click-through rate 提高 3.5 倍，這是正面例子，但單一 Meta 不足以回答整個產業 ROI。

第二個驗證是需求擴散。Nvidia CFO 披露 sovereign AI 在 FY2026 貢獻超過 300 億美元 revenue，說明需求從大科技擴散到國家層級。第三個驗證是 inference。Jensen 將 Grace Blackwell 稱為 inference king，KP 記錄 SemiAnalysis benchmark 顯示 Blackwell 每瓦性能提升 50 倍、每 token cost 下降 35 倍，但市場仍要看 GTC 的真實場景與 2027+ 敘事。

整理者判定：**NVDA** watchlist 補強。第31期不是 thesis break，而是「完美財報進入消化期」：短線要等 GTC / 2027 growth story、customer ROI、sovereign AI、inference economics 與 ASIC / TPU / AMD competition 的新證據。

---

## 7. Netflix 放棄 WBD：資本紀律勝利，但增長缺口仍在

KP 記錄 Netflix 放棄收購 WBD streaming / studio assets，讓 Paramount Skydance 以更高全現金條件拿下交易。Netflix 原報價每股 27.75 美元，只要 HBO / Max / Warner studio 等核心資產，要求 WBD 先剝離 CNN / TNT 等傳統 cable assets；Paramount Skydance 則提出每股 31 美元全公司收購、70 億美元 antitrust breakup fee，並代付 WBD 欠 Netflix 的 28 億美元違約金。

Netflix 拒絕跟進後股價反彈，KP 認為合理：市場移除了過度支付、重債、稀釋和傳統媒體拖累的風險，Netflix 也可恢復 buyback。但放棄交易也留下根本問題：若用戶增長進入成熟期，Netflix 的下一個增長引擎要靠廣告、遊戲、體育直播和每年 200 億美元內容預算自建，能否打造 DC / Harry Potter / HBO 等跨世代 IP 仍需驗證。

整理者判定：**NFLX** / **WBD** 既有 watchlist 補強；**PARA** 作交易方 context。這是對第19期、第25期 Netflix / WBD thesis 的反轉補充：資本紀律正面，但 IP 帝國捷徑被堵上，後續追 ad tier revenue、content ROI、sports / games traction、buyback、Paramount deal close 與 WBD breakup economics。

---

## 8. OpenAI / Amazon：AWS 買下 Frontier 分銷與 stateful AI runtime

KP 將 OpenAI / Amazon 交易視為 Amazon 在 enterprise AI control interface 的防禦性進攻。OpenAI 將未來八年高達 1380 億美元 cloud spend 承諾給 AWS，並使用 2GW 基於 Trainium 的算力；表面上是 500 億美元投資換回 cloud spend，但 KP 認為真正重點是 Frontier 的第三方雲端分銷由 AWS 獨家代理。

KP 將 enterprise AI 戰場定義為控制介面：Microsoft 有 Copilot，Anthropic 有 Claude Cowork，OpenAI 推 Frontier。如果 OpenAI 只做 API，會被雲端平台管道化；透過 AWS 作為授權總代理，它在 Azure 以外建立第二個企業分銷通路。開發者仍可用 Azure 調 API，但企業部署具記憶、長期任務、agentic workflow 的 Frontier / agent fleet 時，AWS 成為唯一第三方雲高速公路。

技術核心是 Stateful Runtime。AWS 與 OpenAI 將在 Amazon Bedrock 上打造有狀態運行環境，與 IAM、S3 等底層服務掛鉤，讓 AI 從偶爾調用工具變成企業流程中的器官。一旦企業在 AWS 上部署長期任務 agent，遷移成本會大幅提高。消費端則可能延伸到 Alexa，讓 Amazon 重新取得 voice assistant / commerce / smart home / ads 入口。

整理者判定：**AMZN** L3 同步，且比第30期 OpenAI 千億融資更具體：第30期是 Amazon 取得入場券，第31期是 AWS 取得 Frontier enterprise distribution / Stateful Runtime / Bedrock integration 的商業路徑。後續追 AWS contract terms、Frontier adoption、Bedrock revenue、Trainium utilization、AWS margin、Alexa integration、OpenAI revenue / OCF、Microsoft relationship 與 circular-financing risk。

---

## 新增 / 補強框架

| 框架 | 定義 | 適用範圍 |
|---|---|---|
| HALO / 實體資產預期重置框架 | AI 軟體顛覆風險不清時，資金偏好 heavy assets、低淘汰風險與低預期但基本面改善的資產 | copper / Japan / industrials / AI power |
| 客戶 warrants / 命運共同體框架 | 挑戰者供應商用股權 upside 綁定超大客戶，換取規模驗證、產能底氣與軟體生態遷移 | AMD / Meta / OpenAI-style deals |
| Legacy IT 知識護城河反轉框架 | AI modernization 工具把 COBOL / mainframe 知識不對稱變透明，使 moat 從「只有我懂」轉為「我能最快安全整合」 | IBM / AWS Transform / enterprise IT |
| TPU 外部化 / Neocloud 影子戰爭框架 | 晶片平台用金融背書、neocloud 與租賃合約把自家加速器推出原生雲端圍牆 | GOOGL / NVDA / neoclouds |
| 數位勞動力稅 / AWU 框架 | SaaS 從 seat-based pricing 轉向按 AI agent 完成工作收費，但需驗證收入替代與 compute margin | CRM / enterprise SaaS |
| HBF 記憶體新樓層框架 | AI memory hierarchy 在 HBM 與 SSD 之間新增高頻寬 Flash 層，用容量與頻寬平衡 KV cache / model weights | SNDK / SK Hynix / memory |
| 完美財報消化期框架 | 當 beat-and-raise 成為基本預期，股價需要新敘事、customer ROI 與下一代產品節點才能再 re-rate | NVDA / AI leaders |
| 資本紀律 vs 增長缺口框架 | 放棄昂貴併購可移除短期風險，但也會暴露原本想用併購解決的長期 growth gap | NFLX / WBD / media M&A |
| Stateful Runtime / 企業 AI 作業系統框架 | AI agent 若帶記憶、身份、長任務與雲端底層服務整合，雲端平台可從 compute provider 升級為 enterprise OS layer | AMZN / MSFT / OpenAI |

---

## 後續追蹤

| 追蹤問題 | 相關 ticker | 指標 |
|---|---|---|
| AMD / Meta warrants 是否轉成真實大規模部署 | **AMD**, **META**, **NVDA** | 1GW / 6GW milestones、MI roadmap、ROCm / PyTorch support、Meta capex、warrant vesting、AMD revenue / margin |
| IBM mainframe / consulting moat 是否被 AI modernization 壓縮 | **IBM**, **AMZN**, **MSFT** | consulting bookings / margin、mainframe renewals、watsonx adoption、AWS Transform / Claude Code enterprise wins、legacy workload cloud migration |
| Google TPU 是否能走出圍牆 | **GOOG**, **GOOGL**, **META**, **NVDA** | FluidStack deal、lease guarantee、Meta TPU lease / purchase、TorchTPU readiness、TPU shipments、Cloud AI revenue、CoWoS allocation |
| Salesforce Agentforce 是否能替代 seat-based SaaS economics | **CRM** | Agentforce ARR、Flex Credits / AWU usage、AI gross margin、Data 360 growth、Informatica integration、core subscription growth |
| HBF 是否成為 AI server memory standard | **SNDK**, **000660.KS**, **005930.KS**, **MU**, **NVDA** | OCP standard、Nvidia design-in、prototype / sampling、CoWoS allocation、NAND pricing、SSD shortage、HBM capacity relief |
| Nvidia 完美財報是否續接新敘事 | **NVDA** | GTC roadmap、2027 visibility、sovereign AI revenue、Blackwell inference benchmarks、customer ROI、hyperscaler capex / AI revenue |
| Netflix 放棄 WBD 後能否自建下一曲線 | **NFLX**, **WBD**, **PARA** | ad tier revenue、content ROI、sports / games traction、subscriber growth、buyback、Paramount / WBD deal close |
| AWS / Frontier 是否形成 stateful enterprise AI moat | **AMZN**, **MSFT**, **NVDA**, **GOOG**, **GOOGL** | AWS contract terms、Frontier adoption、Bedrock revenue、Trainium utilization、IAM / S3 integration、Alexa upgrade、OpenAI OCF |

> 本文為 KOL 觀點整理與資料庫索引，不構成買賣建議。
