# KP 思考筆記第38期：Tesla AI5、Google Marvell、Amazon Globalstar、TSMC 與 CoreWeave

- **來源 KOL**：KP / FOMOSoc
- **原始來源**：https://www.fomosoc.com/p/ai5-kp38
- **source_id**：KP_FOMOSoc-20260418-kp-thinking-note-38-tsla-ai5-google-marvell-amzn-globalstar-tsmc-coreweave-luxury-1323d111
- **raw 路徑 / URL**：URL（未另存 raw；Jina Reader Markdown 完整可讀）
- **OCR 狀態**：不適用
- **類型**：Substack 公開電子報 / KP 思考筆記 / 週報
- **發文時間**：2026-04-18 02:45 UTC（台北 10:45）
- **整理日期**：2026-04-29
- **文章完整性檢查**：Jina Reader Markdown 共 423 行；正文開頭明確自稱第 38 期，列出六個主題，六個主題均完整展開，結尾有宣傳段落與 KP 署名，未偵測核心正文截斷。
- **主題 / 母題標籤**：#投資與投機 #AI基建 #雲端基建 #先進封裝 #太空通訊 #消費成長 #地緣政治 #併購 #競爭風險 #執行風險 #估值風險 #ReRating #產品節點

## 一句話結論

KP 這期主線是「市場風險解除後，真正的 Alpha 回到產業瓶頸」：Tesla 用 AI5 tape-out 修復 Physical AI 敘事，Google 找 Marvell 補推理記憶體 / interconnect 短板，Amazon 透過 Globalstar 買 D2D 頻譜與落地許可，TSMC 財報確認 AI 晶圓與先進封裝仍是高價值瓶頸，CoreWeave / Jane Street 則證明華爾街也把算力視為生存資源。

## 相關 ticker 與交會等級

| Ticker | 交會等級 | 方向 | 摘要 |
|---|---:|---|---|
| **TSLA**, **TSM**, **000660.KS**, **NVDA** | **TSLA** watchlist L3 | Physical AI / edge inference | AI5 已 tape-out，KP 視為 Tesla 把市場注意力從交車 / 毛利壓力拉回 Optimus、Robotaxi、Dojo 與 Physical AI 的敘事橋樑；但至少 12-18 個月才可能產生營收貢獻。 |
| **GOOG**, **GOOGL**, **MRVL**, **AVGO**, **TSM** | **GOOGL** L2 tracked；**MRVL** watchlist L3 | SRAM / custom AI silicon | Google 與 Marvell 擬合作 SRAM 運算引擎，KP 解讀為 Google 在 TPU / Gemini 推理上補記憶體延遲與 TCO，同時維持對 Broadcom 的供應鏈議價力。 |
| **AMZN**, **GSAT**, **ASTS**, **AAPL**, SpaceX / Starlink | **AMZN** L3 tracked；**ASTS** watchlist | Satellite / D2D | Amazon 以約 115.7 億美元收購 Globalstar，KP 將其視為用頻譜和落地許可買 D2D 全球通行證，讓 Amazon Leo 從衛星寬頻延伸到手機直連。 |
| **TSM**, **AMAT**, **ASML**, OSAT peers | **TSM** watchlist L3 | Foundry / advanced packaging | TSMC Q1 gross margin 66.2%、Q2 guide 66.5%、HPC 61%、先進製程 74%；KP 認為毛利稀釋是投資期正常現象，真正要追 AI demand、CoWoS capacity、2nm ramp。 |
| **CRWV**, **NVDA**, **META**, Anthropic | **CRWV** watchlist L3 | Neocloud / AI compute | Jane Street 與 CoreWeave 70 億美元交易，其中 60 億美元算力、10 億美元股權，KP 解讀為頂級客戶必須同時成為投資人以鎖晶片配額。 |
| **MC.PA**, **RMS.PA**, **KER.PA** | Luxury watchlist L3 | Luxury demand / geopolitics | 中東戰爭透過海灣富豪旅行與跨境消費重創奢侈品，KP 認為這是安全資產神話破裂，但若衝突穩定，需求更像推遲而非取消。 |

## 開場：情緒亢奮與便宜保險

KP 延續第 37 期的 tail risk 排除觀點：市場不需要危機完全解除才反彈，只要確認最壞情境已經過去，就會重新定價。但當 VIX 從 30 多快速回落至 20 以下，短期情緒可能過熱；KP 會考慮在波動率便宜時用 put spread 替組合買保險。

### 框架：風平浪靜買保險 / Volatility Insurance 框架

- **定義**：當市場已排除 tail risk、波動率下跌、情緒重新樂觀時，保險成本反而便宜，適合檢查組合是否需要 downside hedge。
- **適用情境**：war / policy relief rally、VIX 快速回落、投資人重新 risk-on 但基本面驗證未完成。
- **觀察指標**：VIX、skew、put spread cost、position concentration、cash ratio、earnings calendar、主要持倉的 downside scenario。

## 主題一：Tesla AI5 與 Physical AI 敘事橋樑

KP 記錄 Elon Musk 宣布 Tesla 下一代客製化 AI 晶片 AI5 已正式 tape-out，且展示實體封裝。AI5 使用 12 顆 HBM，規格相較 AI4 提升：算力約 8 倍、記憶體 9 倍、頻寬 5 倍；單顆 AI5 約等於 5 顆 AI4，特定 Tesla neural network 任務接近 Nvidia H100 級別，但因 ASIC 去除通用功能，目標是更低成本與功耗。

KP 強調 AI5 不是為了現在的 FSD，而是 Tesla 下一章 Physical AI：Optimus、人形機器人本地推理、Robotaxi / Cybercab 大規模車隊、Dojo 訓練與推理。Musk 稱 AI5 對 Tesla 未來具「existential」重要性。

但這不解決短期交車疲弱、電動車競爭、毛利與降價問題。AI5 至少還需要 12-18 個月才可能進入產品線並貢獻營收。KP 將它定位為情緒修復與敘事橋樑：把市場焦點從「本季賣幾台車」拉回「未來機器人大腦」。

### 框架：Physical AI 敘事橋樑 / 硬體里程碑框架

- **定義**：當公司短期財務指標承壓時，關鍵硬體里程碑可延長市場對遠期平台的想像，但仍需轉成產品、收入與 margin。
- **適用情境**：Tesla AI chips、robotics、autonomy、edge inference、founder-led narrative repair。
- **觀察指標**：AI5 silicon validation、yield、TSMC tape-out / production schedule、HBM supply、Optimus production、Robotaxi rollout、FSD take rate、auto gross margin、capex / FCF。

## 主題二：Google / Marvell SRAM 運算引擎與推理 TCO

KP 引用 FundaAI 4 月 14 日報告與 J.P. Morgan 4 月 16 日供應鏈調查，指出 Google 正與 Marvell 洽談一款基於 SRAM 的運算引擎，概念類似 Groq LPU，目標是優化 Gemini 等模型的即時推理服務。KP 認為這不是 Marvell 取代 Broadcom，而是 Google 的多元供應鏈策略。

Marvell 的價值在高速 SerDes、光學與 2nm 客製化高密度 SRAM。若更多記憶體能靠近推理晶片，就能降低 HBM 往返造成的延遲與功耗，改善 inference cost / latency。Google 與 Broadcom 已簽到 2031 年的 TPU / networking 長約，因此短期 Broadcom 核心地位仍穩；Marvell 更像第二供應來源與特定技術補強。

### 框架：SRAM LPU / 系統級推理 TCO 框架

- **定義**：AI 推理競爭從 FLOPS 轉向 memory hierarchy、latency、power、interconnect 與 total cost of ownership；SRAM on-chip / near-chip engine 可降低 HBM 依賴。
- **適用情境**：Gemini inference、custom ASIC、Groq LPU 類架構、hyperscaler supplier diversification。
- **觀察指標**：Marvell design win、Google TPU / Gemini inference latency、SRAM capacity、HBM attach、Broadcom / Marvell revenue mix、Cloud AI margin、cost per token。

## 主題三：Amazon / Globalstar 與 D2D 頻譜圈地

Amazon 宣布以約 115.7 億美元、每股 90 美元併購 Globalstar。KP 認為 Amazon 不是單純補 Project Kuiper / Amazon Leo，而是買進入 D2D 手機直連衛星市場最稀缺的資產：MSS 頻譜與全球落地許可。Globalstar 在 120 多個國家有頻譜授權，並支撐 Apple iPhone Emergency SOS；現有約 24 顆衛星，下一代星座預計擴至 54 顆。

對 Amazon，Globalstar 讓 Amazon Leo 能跳過頻譜申請與多年研發，在 2028 年切入下一代高頻寬、低延遲 D2D 服務。對 Apple，Globalstar 被 Amazon 接手可能讓 iPhone 衛星服務更穩。對 **ASTS**，Amazon 進場是壓力，但也等於承認 D2D 市場價值；ASTS 技術進度仍領先，窗口期約 1-2 年。

KP 同時提醒：Amazon 仍是太空追趕者。交易預計 2027 年完成，Starlink 可能已推進全球 D2D 商業化；Globalstar deal spread 約 10%-12%，反映等待期、支付結構、衛星部署里程碑與稅務因素。

### 框架：衛星 D2D 頻譜圈地 / Connectivity Control 框架

- **定義**：衛星通訊的核心護城河不是衛星數量本身，而是頻譜、落地許可、終端生態與發射 / 補網能力的組合。
- **適用情境**：Amazon Leo、Starlink D2D、AST SpaceMobile、Apple satellite services、IoT / industrial connectivity。
- **觀察指標**：deal close、regulatory approvals、HIBLEO / deployment milestones、D2D rollout、Apple / MNO agreements、spectrum rights、satellite count、pricing、Amazon Leo capex / revenue。

## 主題四：TSMC 財報與先進封裝瓶頸

TSMC Q1 2026 gross margin 66.2%，Q2 guide 中位數 66.5%，全年營收成長從接近 30% 上調至超過 30%。KP 認為下半年 2nm ramp、海外廠與特殊氣體 / 化學品成本造成的毛利率稀釋不是壞消息，而是投資期正常現象；66% 毛利率就算被稀釋 2-3pp 仍是頂尖水準。

更重要的是 mix：HPC 佔營收 61%、季增 20%，7nm 以下先進製程佔晶圓營收 74%，3nm 佔 25%。KP 解讀為 TSMC 賣的是更高價值晶圓。庫存天數從 74 天升到 80 天，但若搭配毛利創高，較像為 2nm / 3nm ramp 備高價值庫存。

KP 也強調台灣生態系不可替代：最先進 2nm / A16 仍優先在台灣量產，海外廠更像成熟製程與地緣保險。CoWoS 仍非常吃緊，下一代 CoPoS 預計 2028 左右量產；封裝已成 AI 晶片護城河。

### 框架：毛利率稀釋 vs 高價值 mix / 先進製程投資期框架

- **定義**：先進製程與海外廠初期會稀釋毛利，但若高價值 HPC / AI mix 與封裝瓶頸同步提升，稀釋是投資期成本而非競爭力惡化。
- **適用情境**：TSMC earnings、2nm / A16 ramp、CoWoS / CoPoS、AI accelerator foundry。
- **觀察指標**：HPC revenue mix、advanced node share、gross margin bridge、inventory days、CoWoS monthly capacity、2nm yield / wafer starts、Arizona / Japan / Germany cost gap。

## 主題五：Jane Street / CoreWeave 與算力長約股權化

Jane Street 與 CoreWeave 簽下約 70 億美元交易：60 億美元買未來數年 GPU 算力，包括 Nvidia Vera Rubin，另 10 億美元買 CoreWeave 股票，成為第五大股東。KP 解讀現代量化交易已變成 AI 軍備競賽，頂級客戶不只租算力，也要用股權換優先配額與合作深度。

對 Jane Street，股權可對沖未來算力成本；對 CoreWeave，10 億美元股權現金在 2026 年 350 億美元 capex 擴張期是及時雨，也向債權人證明 demand quality。KP 同時指出同週 CoreWeave 也與 Meta、Anthropic 簽大約，顯示 AI compute demand 已從矽谷延伸到華爾街。

### 框架：算力長約 + 股權對沖 / 客戶即投資人框架

- **定義**：當算力成為稀缺生產資料，大客戶會同時成為資本提供者，以股權或預付款換產能優先權，並用持股對沖未來算力成本。
- **適用情境**：neocloud、AI labs、quant trading、hyperscaler supplier financing、GPU capacity scarcity。
- **觀察指標**：customer concentration、contract duration、GPU generation allocation、equity dilution、debt cost、capex funding、utilization、gross margin、FCF。

## 主題六：Luxury 與地緣傳導的非線性

KP 用 Hermes / Kering / LVMH 暴跌說明中東戰爭對奢侈品的傳導不是供應端，而是需求端。海灣高淨值消費者原本是 2025 年行業寒冬中的少數亮點，但戰爭後杜拜 mall 客流腰斬、UAE 專櫃銷售跌 30%-50%、LVMH 指海灣銷售暴跌約五成，並削去整體有機增長約 1pp。

Hermes 的脆弱性在於刻意稀缺：不能折扣、不能快速清庫存，也缺少 LVMH 那樣的 75 品牌組合分散。KP 認為這不代表 Hermes / LVMH 長期邏輯破裂，而是「避風港」神話被打破；若衝突穩定，海灣富豪需求更像推遲而非取消，但 Q2 / Q3 同比壓力仍可能難看。

### 框架：地緣傳導 / Luxury Demand Multiplier 框架

- **定義**：地緣風險可透過旅遊、跨境高淨值消費、心理預期與旗艦店流量非線性傳導到看似無關的消費品類。
- **適用情境**：luxury、travel retail、Middle East high-net-worth demand、tourist spending。
- **觀察指標**：Middle East sales、Europe flagship traffic、tourist spending、organic growth、F&LG margin、inventory / discounting、travel confidence、conflict duration。

## 對已追蹤個股的同步判定

- **AMZN**：L3；Globalstar / Amazon Leo 是宋分 AMZN capital cycle / connectivity thesis 的直接補強，已同步 `Stocks/AMZN/quarterly/AMZN_筆記_2026Q2.md`、`AMZN_index.md`、`AMZN_儀表板.md`。
- **GOOG / GOOGL**：L2；Google / Marvell SRAM engine 是 Cloud AI inference TCO / supplier diversification 補強，已同步 `Stocks/GOOGL/quarterly/GOOGL_筆記_2026Q2.md`、`GOOGL_index.md`、`GOOGL_儀表板.md`。
- **AMKR**：本篇只提 OSAT 夥伴，未點名 **AMKR**，不更新 `Stocks/AMKR/`。
- **INTC / IBM / LRCX / VRT**：本篇未形成獨立同步門檻，不更新 `Stocks/`。

## 後續追蹤清單

| 時間 / 頻率 | 追蹤事件 | 相關 ticker | 重點 |
|---|---|---|---|
| 2026-2027 | AI5 silicon validation and production path | **TSLA**, **TSM**, **000660.KS** | tape-out 後 silicon bring-up、HBM supply、TSMC schedule、Optimus / Robotaxi integration |
| 每季 | Google / Marvell SRAM inference engine | **GOOG**, **GOOGL**, **MRVL**, **AVGO** | design win、Gemini inference cost / latency、Broadcom / Marvell revenue mix、Cloud AI margin |
| 2027-2028 | Amazon / Globalstar deal close and D2D rollout | **AMZN**, **GSAT**, **ASTS**, **AAPL** | closing approvals、satellite milestones、D2D launch、Apple / MNO terms、ASTS window |
| 每季 | TSMC AI demand and advanced packaging | **TSM**, **AMAT**, **ASML** | HPC mix、CoWoS capacity、2nm yield / wafer starts、gross margin bridge、inventory days |
| 每季 | CoreWeave customer-funded expansion | **CRWV**, **NVDA** | contract backlog、GPU allocation、debt cost、capex funding、utilization、customer concentration |
| 2026H2-2027 | Luxury Middle East demand recovery | **MC.PA**, **RMS.PA**, **KER.PA** | Gulf sales、Europe tourist spending、organic growth、margin、conflict duration |

## 資料品質與限制

- 本文整理自 FOMOSoc Substack 公開文章的 Jina Reader Markdown，未另存 raw；URL 可回溯來源。
- 原文包含多個供應鏈報告、新聞與公司事件的 KP 口徑轉述；本整理未逐一外部查驗，後續進入單股深度或財報驗證時需用 official filings / press release 校準。
- 本整理只記錄 KOL 觀點與投資框架，不構成買賣建議。
