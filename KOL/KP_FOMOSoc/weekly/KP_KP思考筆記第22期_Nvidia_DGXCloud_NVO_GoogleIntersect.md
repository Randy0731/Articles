# KP / FOMOSoc：KP 思考筆記第22期 - Nvidia DGX Cloud、AGI 路線、口服 Wegovy 與 Google Intersect Power

- **source_id**：`KP_FOMOSoc-20251227-kp-thinking-note-22-nvidia-dgx-lepton-agi-novo-wegovy-google-intersect-power-259e9726`
- **KOL / 來源**：KP / FOMOSoc
- **原文標題**：口服減重藥時代正式開啟？Nvidia不搞雲端了？- KP思考筆記(第22期)
- **原文 URL**：https://www.fomosoc.com/p/nvidia-kp22
- **發文時間**：2025-12-27 03:00 UTC（台北 11:00）
- **整理日期**：2026-04-29
- **資料取得方式**：Jina Reader public Markdown；URL source，未另存 raw。
- **原始資料 hash**：`259e9726dfd3879ed4029c86b85adc29e2a0b8b7e1f35b95202f6c5a6cf993f2`
- **OCR / 擷取狀態**：不適用；Markdown 完整可讀。
- **完整性檢查**：正文開頭明確自稱第 22 期，文內有 Nvidia DGX Cloud / Lepton、LeCun vs Hassabis AGI 路線、Novo Nordisk 口服 Wegovy、Google / Intersect Power 四個主題，結尾有宣傳段落與 KP 署名，未偵測截斷。
- **關聯個股**：**NVDA**, **AMZN**, **MSFT**, **GOOG**, **GOOGL**, **CRWV**, **META**, **NVO**, **LLY**, **FSLR**, **TSLA**
- **主題 tags**：#AI基建 #雲端基建 #生技醫療 #能源電力 #併購 #產品節點 #競爭風險 #執行風險 #估值風險 #ReRating

---

## 一句話總結

KP 在第 22 期把 AI 與 GLP-1 的競爭都拆成「路線選擇與時間成本」：Nvidia 從 DGX Cloud 正面經營雲端後撤，改押 Lepton 聚合 GPU 供給，但同時會碰到客戶關係與 neocloud 價格商品化的邊界；Google 一邊用 Hassabis 的 scaling 路線對照 Meta / LeCun 的 world model 長期路線，一邊直接買 Intersect Power 的開發團隊、許可與 10.8GW pipeline，用能源熟地換 AI data center 的時間。Novo 則用低價口服 Wegovy 搶禮來 Orforglipron 前的六個月空窗，但必須面對服藥依從性與 API 產能黑洞。

---

## 主題地圖

| 主題 | KP 核心觀點 | 相關 ticker | 資料庫處理 |
|---|---|---|---|
| Nvidia DGX Cloud / Lepton | DGX Cloud 從對外雲端服務後撤，是避免和大客戶搶生意；Lepton 想成為 GPU 算力聚合器，但會觸碰雲端與 neocloud 的價格 / 客戶關係邊界 | **NVDA**, **AMZN**, **MSFT**, **GOOG**, **GOOGL**, **CRWV** | **NVDA** 既有 watchlist / ticker 補強；**CRWV** 既有 watchlist 補充風險 |
| LeCun vs Hassabis AGI 路線 | LeCun 代表 world model / 因果理解長路線，Hassabis 代表 scaling / 通用學習架構主流路線；兩者可能在不同時間維度上同時成立 | **META**, **GOOG**, **GOOGL** | **META** / **GOOGL** 既有 ticker context；不單獨同步 `Stocks/` |
| Novo 口服 Wegovy | 口服 Wegovy 獲批 + 低價策略可搶非保險覆蓋人群，但服藥限制與 API 用量會壓 margin / supply；禮來 Orforglipron 仍是 2026 年中競爭檢查項 | **NVO**, **LLY** | **NVO**, **LLY** 既有 watchlist 補強 |
| Google / Intersect Power | Google 買的不是既有電廠收入，而是已鎖土地 / 許可 / 併網權的能源開發 pipeline 與團隊，用 47.5 億美元購買 AI data center 的時間 | **GOOG**, **GOOGL**, **FSLR**, **TSLA** | **GOOG**/**GOOGL** 已追蹤個股歷史 L3 補強；**FSLR**, **TSLA** 只作供應鏈 / 儲能 context |

---

## 1. Nvidia：DGX Cloud 後撤，Lepton 也不是無摩擦解法

KP 將 DGX Cloud 的重組解讀為 Nvidia 主動退出一場勝率不高的正面雲端競爭。DGX Cloud 原本想向 AWS 等雲端商租用伺服器、加上 Nvidia 軟硬體調校，再對外提供原廠 GPU 雲端服務；但這種「雲中雲」同時面臨營運複雜度與客戶衝突。

第一個問題是支援與標準化。DGX Cloud 不是自己從零建 data center，而是站在 AWS / Google / Microsoft 等雲端夥伴的基礎設施之上。底層環境不同，客戶出問題時難以用一套 support / SLA 流程解決。

第二個問題更根本：AWS、Google、Microsoft 是 Nvidia 雲端業務的潛在競爭者，也是 Nvidia GPU 最大客戶。KP 認為 Nvidia 不可能為了尚未成熟的 DGX Cloud 去激怒每年採購大量晶片的金主，因此 DGX Cloud 從對外產品退回內部晶片研發、模型測試與生態學習工具。

KP 進一步把 Lepton 視為 Nvidia 的新劇本：不親自當雲端業者，而是扶植 CoreWeave、Lambda 等 neocloud，並讓開發者用單一 Nvidia 帳戶在 AWS、Azure、CoreWeave 等供應商之間查詢和購買 GPU 算力。理論上，這把 Nvidia 從重資產二房東轉成輕資產平台。

但 Lepton 的問題是，它會把不同供應商的 H100 / GPU hour 放到同一張比價表上，直接推動 GPU 算力商品化。對 neocloud 而言，這可能削弱差異化服務與價格權；對雲端巨頭而言，上游晶片供應商過度介入下游客戶關係，也會讓合作關係緊張。

### 資料庫判斷

- **新增 / 補強框架**：算力聚合平台 / 客戶邊界框架。
- **對 NVDA**：L3 watchlist 補強。KP 的重點不是 Nvidia 雲端失敗，而是 Nvidia 在「不與大客戶正面衝突」下尋找平台化抽佣的邊界。
- **對 CRWV / neoclouds**：既有 watchlist 風險補充。Lepton 可帶來流量，也可能壓縮 pricing power。
- **反證指標**：Lepton adoption、neocloud gross margin / utilization、Nvidia software fee attach、hyperscaler acceptance、客戶是否繞過 Lepton 直接簽約。

---

## 2. LeCun vs Hassabis：AI 路線分歧其實是時間成本分歧

KP 將 Yann LeCun 與 Demis Hassabis 的 AGI 辯論，拆成兩種技術哲學。LeCun 否定「通用智慧」這個概念，真正反對的是把 LLM scaling 當成通往真正智慧的唯一道路。他認為 LLM 缺乏物理世界感知與因果理解，因此需要 world models，讓 AI 像嬰兒一樣透過環境互動理解世界。

Hassabis 的反駁則是，人類大腦雖然在許多任務上效率低，但具備足夠通用的學習架構；只要有時間、紙筆與資料，人類可以學習新的可計算任務。這替主流 scaling 路線提供理論支撐：模型、資料與任務足夠大時，能力會持續湧現。

KP 沒有直接判定誰對誰錯，而是把差異放在時間維度。LeCun 的 world model 可能更接近長期理想，但需要十年甚至更久；在 AI 軍備競賽裡，Meta 面臨的是產品與競爭壓力，耐心本身成為昂貴資源。Hassabis / Google DeepMind 的 scaling 路線則更符合當前資本與產品節奏。

### 資料庫判斷

- **新增 / 補強框架**：AI 路線時間成本 / Scaling vs World Model 框架。
- **對 META**：既有 watchlist context。LeCun 離開後，Meta 更偏產品化 / 閉源 / 廣告變現壓力，與第 20 期 Avocado 框架相接。
- **對 GOOGL**：既有 tracked stock context，但此段只是 AI R&D 哲學，不單獨更新 `Stocks/GOOGL/`；與 Google DeepMind / Gemini / TPU 路線可交叉。
- **反證指標**：world model 是否出現明確 product / benchmark 突破；scaling 路線是否遇到 data / compute / inference cost 瓶頸；Meta / Google AI product monetization。

---

## 3. Novo：口服 Wegovy 是市場准入戰，不只是藥效戰

KP 將口服 Wegovy 獲批視為 GLP-1 市場的重要轉折。核心不是「藥丸終於有效」這一點而已，而是 Novo Nordisk 把 Wegovy 從高溢價注射劑，推向低價、高覆蓋的基礎代謝藥物路線。

KP 記錄口服版 Wegovy 在 64 週帶來約 13.6% 平均體重下降，嚴格服藥者達 16.6%，接近注射版 Wegovy 約 15%-17% 的效果。更重要的是月費 149 美元，遠低於過去上千美元注射劑，代表 Novo 主動用毛利換滲透率，搶禮來 Orforglipron 上市前的空窗。

這個策略的目標是非保險覆蓋人群。若 Novo 能在六個月內讓大量用戶形成品牌慣性、資料依賴與處方流程，等禮來口服小分子 Orforglipron 進場時，轉換成本會提高。

風險也很清楚。口服 Wegovy 必須空腹服用且等待至少 30 分鐘才能進食飲水，真實世界依從性可能不佳。更大的問題是 API：口服吸收率低，一顆 25mg 藥丸的 API 用量遠高於每週 2.4mg 的注射劑；若放量太快，API 產能可能吞噬供應鏈與 margin。禮來的 Orforglipron 是小分子，KP 認為便利性與成本端都可能更優。

### 資料庫判斷

- **新增 / 補強框架**：口服 GLP-1 價格滲透 / API 產能約束框架。
- **對 NVO**：既有 watchlist L3 補強。與第 1 期成長故事信任危機、第 16 期治理重置、第 18 期 Amycretin / Alzheimer 0/1 clinical switch 相接。
- **對 LLY**：既有 watchlist 補強。Orforglipron 是 2026 年中競爭檢查項，不把 Novo 先發優勢寫成禮來 thesis 破裂。
- **反證指標**：oral Wegovy prescription uptake、adherence / discontinuation、API capacity、gross margin、net price、Orforglipron approval / label / pricing、market share。

---

## 4. Google：買 Intersect Power，是買能源熟地與時間

KP 將 Google 以 47.5 億美元收購 Intersect Power 解讀為 AI 基建底層競爭：Google 買的不是既有電廠現金流，而是開發團隊、許可文件、土地、併網權與未來能源 pipeline。

在美國，新 AI data center 接入公共電網往往要面對 5-7 年的排隊與審批。Intersect Power 的價值在於 behind-the-meter 模式：在 data center 旁邊開發太陽能 / battery storage，讓能源就地發電、就地使用，少走公共電網等待路徑。

KP 強調 Intersect 的護城河不是太陽能板或電池本身，而是已經取得土地租約、許可與併網權的「熟地」。這筆交易買下的是 10.8GW 未來開發管線與 Sheldon Kimber 團隊的 regulatory / ISO-RTO know-how。Google 等於為跳過多年文書與電網排隊付溢價。

這也把 Google 的 AI 基建定位推向更重資產。太陽能夜間無電，Intersect 的 dispatch optimization 和 Tesla Megapack storage 可把能源與算力調度同步；但同時，47.5 億美元投資也會永久抬高 Alphabet 的 capex 與 utility-like 屬性。

### 資料庫判斷

- **新增 / 補強框架**：AI 能源熟地 / Behind-the-Meter 時間套利框架。
- **對 GOOGL**：已追蹤個股歷史 L3 補強。與大叔 2026-02-21 Alphabet capex / energy sovereignty thesis、第 21 期 utility-rate politics 串成一條線：Google 不只買電，而是在買可點亮 AI data center 的時間。
- **對 FSLR / TSLA**：供應鏈 context。文章提及 First Solar panels 與 Tesla Megapacks，但 KP 核心 thesis 是 Google / Intersect 的能源開發能力，不單獨升級供應商。
- **反證指標**：Intersect pipeline delivery、GW / GWh energization、permits / interconnection progress、capex / depreciation、Google Cloud AI revenue、power cost、PUC / rate case friction。

---

## 新增框架

| 框架 | 一句話定義 | 觀察指標 |
|---|---|---|
| 算力聚合平台 / 客戶邊界框架 | 上游晶片供應商可嘗試把多家雲端 / neocloud GPU capacity 聚合成平台，但若平台化壓低下游客戶價格權或介入客戶關係，會碰到合作邊界 | Lepton adoption、neocloud margin、hyperscaler acceptance、GPU utilization、software fee attach、direct vs marketplace procurement |
| AI 路線時間成本 / Scaling vs World Model 框架 | AI 技術路線不只比最終理論正確性，也比誰能在資本與產品競賽允許的時間內交付可用能力 | scaling law progress、world model benchmark、product monetization、researcher retention、training / inference cost、agent reliability |
| 口服 GLP-1 價格滲透 / API 產能約束框架 | 口服減重藥若用低價換大眾滲透，成敗取決於依從性、API 產能、毛利壓力與競品便利性，而不只是臨床效果 | prescription uptake、adherence、API capacity、gross margin、net price、payer coverage、Orforglipron approval / label |
| AI 能源熟地 / Behind-the-Meter 時間套利框架 | AI data center 的稀缺資源從晶片延伸到已獲許可、可併網、可就地供電的能源項目；買熟地等於買建設時間 | GW / GWh pipeline、land leases、permits、interconnection, behind-the-meter delivery、dispatch software、capex、power cost |

---

## 需後續追蹤

| 追蹤項 | 相關 ticker | 觀察重點 |
|---|---|---|
| Nvidia Lepton / DGX Cloud 重整 | **NVDA**, **CRWV**, **AMZN**, **MSFT**, **GOOG**, **GOOGL** | Lepton usage、neocloud pricing / margin、hyperscaler response、Nvidia software monetization、DGX Cloud internal tool value |
| AI route split | **META**, **GOOG**, **GOOGL** | Meta world model / FAIR successor route、Google DeepMind scaling / Gemini product progress、researcher exits、agent reliability |
| Oral Wegovy vs Orforglipron | **NVO**, **LLY** | Oral Wegovy prescriptions、adherence、API supply、Novo gross margin、Lilly Orforglipron approval / label / pricing、share shift |
| Google Intersect Power execution | **GOOG**, **GOOGL**, **FSLR**, **TSLA** | 10.8GW pipeline conversion、permits、interconnection、Tesla Megapack deployment、First Solar panel supply、Cloud AI revenue vs capex / depreciation |

---

## 限制與備註

- 本文整理 KP 觀點與資料庫判斷，不是買賣建議。
- 本期部分資訊為 KP 對媒體報導、企業策略與監管 / 產業節點的解讀；後續需用 company filings、official releases、財報、FDA / regulatory documents 與 utility / interconnection filings 校準。
- **GOOGL** 因已是正式追蹤個股，將同步補入 `Stocks/GOOGL/`；其餘多數 ticker 先維持 watchlist / ticker index。
