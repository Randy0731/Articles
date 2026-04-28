# GPU 和 TPU的辯論錯在哪？羅賓漢線上賭場上線啦!諾和諾德為甚麼大起大落？ - KP思考筆記（第18期，原標題寫第17期）

- **source_id**：`KP_FOMOSoc-20251129-kp-thinking-note-18-gpu-tpu-novo-dell-deere-hood-zscaler-bytedance-a772be14`
- **KOL / 來源**：KP / FOMOSoc Substack
- **原文連結**：https://www.fomosoc.com/p/gpu-tpu-kp17
- **發文時間**：2025-11-29 02:45 UTC（台北 10:45）
- **入庫日期**：2026-04-29
- **類型**：Substack 公開電子報 / KP 思考筆記 / 週報
- **Substack post id**：未取得（整理時 direct domain / API 被本機 website filter 阻擋；Jina Reader 公開頁可讀）
- **raw / OCR**：URL（未另存 raw）；OCR 不適用
- **相關 ticker**：**NVDA**, **GOOG**, **GOOGL**, **TSM**, **MSFT**, **META**, **NOK**, **NVO**, **LLY**, **DELL**, **HPQ**, **HPE**, **MU**, **005930.KS**, **000660.KS**, **DE**, **HOOD**, **CZR**, **CME**, **COIN**, **DKNG**, **SCHW**, **ZS**, **CRWD**, **PANW**, **BIDU**, **BABA**, **TCEHY**, **688256.SS**；ByteDance / Huawei / Kalshi / Polymarket / FanDuel / Susquehanna / Red Canary 未上市或非本專案 ticker
- **主題 tags**：#AI基建 #雲端基建 #生技醫療 #Memory #消費成長 #財報 #投資與投機 #軟體SaaS #地緣政治 #政策風險 #競爭風險 #執行風險 #估值風險 #供應鏈風險 #ReRating

## 入庫檢查

- Jina Reader Markdown 完整可讀，保留原文標題、發文時間與 canonical URL。
- 原文標題與 URL slug 寫「第17期 / kp17」，但正文開頭明確寫「歡迎來到第18期的思考筆記」，且文內也稱筆記已來到第18期；本專案依正文自我標示記為第18期，並在 metadata 保留標題筆誤。
- 正文有開頭、七個主題、結尾宣傳段落與 KP 署名，未偵測截斷。
- 本文橫跨 GPU / TPU 辯論、Novo Nordisk 臨床數據、Dell / HP 記憶體風暴、Deere 指引、Robinhood 預測市場、Zscaler 成長危機與 ByteDance 去 Nvidia 化；整理時按已追蹤股票、watchlist 與主題 read-through 分流。
- **GOOG** / **GOOGL** 因主題一直接討論 Google TPU 對 Nvidia GPU 的替代程度、inference workload 與 AI 基建策略，判定為已追蹤個股歷史 L2+ 補強，補入 `Stocks/GOOGL/`。
- 本文沒有提供正式目標價或買賣點；涉及「最佳買點」、分析師目標價、股價反應、估值與選擇權時，均保留為 KP 的框架或市場敘事，不轉成本專案建議。

## 一句話總結

KP 本期反覆拆解二分法：GPU 與 TPU 不是「誰殺死誰」，而是在快速擴大的 AI 算力宇宙中互相替代一部分、共同擴張更大市場，Nvidia 的核心風險反而是 CoWoS 與電力等物理瓶頸；Novo Nordisk 的 V 型股價說明製藥估值常被臨床試驗的 0 / 1 開關改寫；Dell 和 HP 面對同一場記憶體風暴，市場卻願意給有 AI server 敘事的 Dell 估值保護傘；Deere 的壞指引被一部分投資人解讀成穿越週期的低標設定；Robinhood 正從券商變成受監管的數位賭場；Zscaler 即使 beat 也因 billings、整合與競爭壓力被重估；ByteDance 禁用 Nvidia GPU 則代表中美 AI 生態分裂加速。

## 本期主題索引

| 主題 | KP 核心判斷 | 投資資料庫處理 |
|---|---|---|
| GPU vs TPU | 兩邊都錯在非黑即白；TPU / ASIC 可在特定 workload 替代 GPU，但 AI TAM 若持續擴大，Nvidia 仍可能掌握 AI factory 主導權 | **NVDA** watchlist 補強；**GOOG**/**GOOGL** 已追蹤個股歷史 L2+；新增「GPU / ASIC 非零和替代框架」 |
| Novo Nordisk | Semaglutide 阿茲海默三期失敗移除夢想溢價，Amycretin 二期成功又加入新 pipeline optionality；製藥估值常是 0 / 1 開關 | **NVO** 既有 watchlist 補強；新增「製藥 0/1 臨床開關框架」 |
| Dell / HP | 同樣承受記憶體成本風暴，Dell 因 AI server 敘事與供應鏈執行獲估值保護，HPQ 則更像純 PC 成本壓力暴露 | **DELL** 既有 watchlist 補強；**HPQ** 新增 L3 watchlist；**HPE** / memory makers 為 context |
| Deere | 2026 淨利指引遠低於預期，但市場也可解讀為 management kitchen-sink、設定週期底部與 2027 復甦彈性 | **DE** 新增 L3 watchlist；新增「穿越週期 kitchen-sink 指引框架」 |
| Robinhood | HOOD 透過 MIAXdx / LedgerX 進入預測市場基礎設施，從金融民主化轉向投機娛樂化 / 受監管數位賭場 | **HOOD** 新增 L3 watchlist；**CME**, **COIN**, **DKNG**, **CZR**, **SCHW** 為競爭 / 對照 context |
| Zscaler | Revenue / EPS beat 不足以支撐高估值；billings 放慢、Red Canary 變現不透明與 Palo Alto SASE 競爭讓市場重新定價成長預期 | **ZS** 新增 L3 watchlist；**CRWD**, **PANW** 為 sector context；新增「高估值 SaaS 預期重設框架」 |
| ByteDance 去 Nvidia 化 | 中國監管禁用 Nvidia GPU 不是單一新聞，而是強迫國內巨頭轉向華為、百度、寒武紀等本土晶片，全球 AI 生態分裂加速 | **NVDA** watchlist 補強；**BIDU**, **BABA**, **TCEHY**, **688256.SS** 為中國 AI 生態 context；新增「AI 生態脫鉤 / 軟體補硬體框架」 |

## Ticker 分流

| Ticker | 文章角色 | 訊號強度 | 處理 |
|---|---|---|---|
| **NVDA** | GPU / TPU 辯論、GTC 2025 `5000億美元` bookings、AI factory 全棧、ByteDance 禁令與中國收入已被定價 | 既有 watchlist L3 補強 | 更新 watchlist、ticker/theme/catalyst；不建立 `Stocks/NVDA/` |
| **GOOG**, **GOOGL** | Google TPU / ASIC 成功在特定 inference workload 具替代性；但不是 Nvidia thesis break，而是 AI workload 分工 | 已追蹤個股歷史 L2+ 補強 | 更新 `Stocks/GOOGL/`、ticker/theme/catalyst；不重複整篇 KOL 筆記 |
| **TSM**, **NOK**, **MSFT**, **META** | TSMC CoWoS 是 Nvidia physical bottleneck；Nokia / 6G、hyperscalers 為 Nvidia TAM / 客戶 context | L1-L2 context | 更新 ticker/theme；**MSFT**/**META** 不同步 `Stocks/` |
| **NVO**, **LLY** | Semaglutide 阿茲海默三期失敗與 Amycretin 二期數據；Lilly 為 GLP-1 競爭外部壓力 | **NVO** 既有 watchlist L3 補強；**LLY** sector context | 更新 watchlist、ticker/theme/catalyst；不建立 `Stocks/NVO/` |
| **DELL** | AI server 敘事給 Dell 對抗記憶體成本風暴的估值保護傘；短期可能是跌深反彈與鬆一口氣 | 既有 watchlist L3 補強 | 更新 watchlist、ticker/theme/catalyst；不建立 `Stocks/DELL/` |
| **HPQ**, **HPE** | HPQ 作純 PC / printer 成本壓力暴露；HPE 將公布企業伺服器財報，可驗證真正賣鏟人對決 | **HPQ** 新增 L3 watchlist；**HPE** L2 context | 更新 watchlist / ticker / catalyst；不建立 `Stocks/HPQ/` |
| **MU**, **005930.KS**, **000660.KS** | Micron、Samsung、SK Hynix 為 HBM / DRAM / NAND 供應與產能轉移 context | L1-L2 memory chain | 更新 ticker/theme；不新增 watchlist |
| **DE** | 2026 guide down、tariff cost、cycle trough、inventory reduction、construction / forestry 與 precision agriculture optionality | 新增 L3 watchlist | 更新 watchlist、ticker/theme/catalyst；不建立 `Stocks/DE/` |
| **HOOD** | MIAXdx acquisition / prediction market infrastructure；投機娛樂化、broker + exchange economics、regulatory gray zone | 新增 L3 watchlist | 更新 watchlist、ticker/theme/catalyst；不建立 `Stocks/HOOD/` |
| **CZR**, **CME**, **COIN**, **DKNG**, **SCHW** | Caesars 為 S&P 500 替換對照；CME / Coinbase / DraftKings / Schwab 為競爭或傳統券商對照 | L1-L2 context | 更新 ticker/theme；不新增 watchlist |
| **ZS** | Beat 後暴跌；billings +約 15.5%、Red Canary integration、AI security ARR +80%、Palo Alto SASE 壓力 | 新增 L3 watchlist | 更新 watchlist、ticker/theme/catalyst；不建立 `Stocks/ZS/` |
| **CRWD**, **PANW** | CrowdStrike / Palo Alto 是資安預算放緩與平台競爭 context；PANW 的 SASE bundling 侵蝕 Zscaler moat | L1-L2 context；**PANW** 既有 watchlist 競爭補強 | 更新 ticker/theme；不新增 `Stocks/` |
| **BIDU**, **BABA**, **TCEHY**, **688256.SS** | 中國 AI 巨頭與本土晶片 ecosystem context；Baidu Kunlun、阿里、騰訊、寒武紀承接 ByteDance / 國內需求 | L1-L2 China AI ecosystem context | 更新 ticker/theme/catalyst；不新增 watchlist |

## 主題整理

### 1. GPU vs TPU：真正的問題不是誰取代誰，而是市場有多大

KP 先反駁市場上兩種極端說法：一派認為 TPU 將取代 GPU、Nvidia 好日子結束；另一派則說 GPU 與 ASIC / TPU 完全不同、井水不犯河水。KP 的判斷介於兩者之間：技術架構確實不同，但在商業應用上，資本會追求效率，因此特定 workload 必然存在替代性。

差異在蛋糕大小。如果 AI 算力市場是固定蛋糕，Google 自研 TPU 成功當然會侵蝕 Nvidia；但如果 AI TAM 正在指數級膨脹，ASIC 成功可能只拿走 Nvidia 的部分邊際利潤，而不是改寫整場盛宴的主導者。

KP 用 Jensen 在 2025 年 10 月 GTC 提到的 `5000億美元` confirmed bookings 作為硬錨：2025-2026 日曆年間已確認基建訂單中，約 `1500億美元` 已交付，仍有約 `3500億美元` backlog 等待 2026 年底前完成。對比當時華爾街 2026 年 revenue consensus 約 `3040億美元`，KP 認為 Nvidia 已用現有 backlog 鎖定高可見度收入。

更重要的是 bookings 組成不只是 GPU，而包括 Blackwell、Rubin、Spectrum-X Ethernet、NVLink switches 等 AI factory 全棧解決方案。KP 將 Nvidia moat 從「賣晶片」提升到「交付 AI 工廠」：硬體、networking、software library、CUDA ecosystem、developer tools 和 deployment know-how 都是競爭的一部分。

對 **GOOG** / **GOOGL**，本文也補上一個重要界線：Google TPU 在自家 inference workload 具成本效率與吸引力，確實會衝擊 Nvidia 的某些市場，但 KP 沒有把它寫成 Nvidia thesis break。這比較像 AI workload 分工：Google 用 closed TPU empire 優化自家與 Google Cloud 場景，Nvidia 用 open arms dealer / AI factory 生態服務更廣泛的 hyperscaler、主權 AI、工業、電信與汽車市場。

整理者判斷：這段對 **GOOGL** 達 L2+，因為它直接延續第 15 期 Ironwood TPU thesis，並補上「替代是局部、競爭是程度、TAM 是關鍵」的校準。後續 GOOGL 應追 TPU allocation、Cloud AI revenue、cost per token、Anthropic / other workload split、developer framework adoption；NVDA 則追 CoWoS、電力、Blackwell / Rubin delivery 與 AI factory backlog conversion。

### 2. Novo Nordisk：製藥估值不是旋鈕，是 0 / 1 開關

Novo Nordisk 本週股價先因 Semaglutide 阿茲海默症三期試驗失敗暴跌約 10%，創四年新低；之後又因 Amycretin 二期數據亮眼收復大部分跌幅。KP 把這 48 小時視為製藥估值的教科書。

Semaglutide 的 Alzheimer thesis 本來有很漂亮的科學故事：阿茲海默與大腦胰島素阻抗相關，GLP-1 又能調節代謝、抗發炎，甚至可能影響 amyloid / Tau 類病理路徑。市場因此給了這張「樂透彩券」一些夢想溢價。

但試驗結果雖改善 biomarkers，沒有轉成延緩患者認知下降的臨床效果。KP 的判斷是：實驗室數據叫好不叫座，主要終點沒過，夢想溢價被市場收回。

Amycretin 的二期數據則反方向把另一個開關打開：皮下注射 36 週體重下降 `14.5%`，且沒有看到減重平台期。這使 Novo 在下一代 obesity pipeline 仍有扳回 GLP-1 戰局的想像。

整理者判斷：**NVO** 既有 watchlist 補強。本文不是說 Novo 的總價值沒變，而是風險地圖改變：Alzheimer optionality 暫時歸零，Amycretin optionality 上升。後續追 Amycretin Phase 3 設計、CagriSema / next-gen pipeline、Wegovy / Ozempic share、Lilly 競爭、pricing / Medicare access 與治理改革是否真的提升 execution。

### 3. Dell / HP：同一場記憶體風暴，市場給了不同劇本

KP 將 Dell 與 HP 的反差放在「記憶體風暴」裡看：HBM 需求因 AI 爆發，擠壓普通 DRAM / NAND 產能，讓 PC、手機、汽車等傳統電子產品也面對缺貨與漲價。Dell COO Jeff Clarke 稱這是 unprecedented，KP 也提到小米調漲手機價格、聯想囤庫存，以及分析師預期記憶體價格到明年年中可能上漲約 50%。

差異在公司敘事。HPQ 是 PC / printer 為主，當記憶體成本升高時，投資人看到的是成熟市場中的 margin squeeze；Dell 則同時擁有 PC 與 enterprise / AI server，市場願意把 AI server 當作估值保護傘。

KP 認為 Dell 的市場反應包含兩層：一是 AI server 讓投資人容忍短期毛利壓力，把成本上升視為成長代價；二是 Dell 財報前已從高點回落近 30%，HP 約 20%，所以 Dell 的大漲可能也有跌深後鬆一口氣的成分。

對 **HPQ**，這篇比第 17 期更明確：它不只是 Dell context，而是「純 PC / printer 暴露在記憶體成本風暴下」的主角之一。整理者因此將 **HPQ** 新增 L3 watchlist，重點不是看空，而是標記一個 PC hardware margin squeeze / memory supercycle candidate。

對 **DELL**，本文延續既有 watchlist：AI server story 可提供估值保護，但仍需用 gross margin、AI backlog、inventory hedge、memory pass-through 與 customer concentration 驗證。下週 HPE 財報則是觀察企業 server 同業是否同樣具備「賣鏟人」保護傘的重要節點。

### 4. Deere：壞指引也可以被市場解讀成週期底部

Deere 給出 2026 財年淨利 `40億至47.5億美元`，中位數約 `43.7億美元`，明顯低於市場預期 `53.1億美元`。管理層也點出兩個壓力：關稅成本約 `12億美元`，以及大型農業設備需求疲弱。直覺上這是壞消息，股價卻只跌約 5%，部分投行甚至上調目標價。

KP 認為分歧在解讀方式。悲觀者看 2026 pain；樂觀者看 management 是否把關稅、需求與成本壓力一次放進指引，設定底部、創造未來 beat 空間。這是一種 through-the-cycle 投資哲學：市場不是買 2026 年，而是買 2027 年及以後的復甦。

Deere 還有兩個緩衝：一是過去一年去庫存約 `26億美元`，經銷商壓力降低；二是公司不是只有大型農機。農業設備預期下滑 5%-10%，但 Construction & Forestry 受基建法案與 AI data center 建設帶動，形成分裂經濟下的另一條成長腿。

最後是科技服務化：Precision Agriculture、自動駕駛拖拉機、AI 視覺除草與長期 10% recurring revenue 目標，讓 Deere 有機會從週期鋼鐵公司逐步轉成高附加值技術服務商。即將到來的投資者日，是市場驗證這個科技王牌的重要節點。

整理者判斷：**DE** 新增 L3 watchlist。這不是把「壞指引」寫成買點，而是記錄一個「週期底部 + kitchen-sink guide + precision ag recurring revenue」框架。後續追 tariffs、large ag demand、used equipment prices、inventory、Construction & Forestry、Precision Ag revenue、recurring revenue mix 與 investor day。

### 5. Robinhood：金融民主化外衣下的數位賭場

Robinhood 在 2025 年 9 月取代 Caesars Entertainment 進入 S&P 500，KP 用這個符號開場：新的線上賭場取代老派賭場公司。本週 HOOD 聯手 Susquehanna 收購 MIAXdx，等於正式把預測市場基礎設施納入自己掌控。

MIAXdx 前身是 FTX 旗下 LedgerX，屬 FTX 廢墟中的「乾淨」資產。Robinhood 過去像流量分銷商，把用戶導向 Kalshi 等預測市場平台；KP 提到 Kalshi 超過一半業務量來自 Robinhood referral。收購交易所後，HOOD 不只給賭桌，而是自己建賭場。

戰略意義在四個層面：控制產品設計、上架、交易與清算；同時賺 broker 和 exchange fees；在 CME、Coinbase 等對手也進入預測市場時建立受監管交易所 moat；並把用戶體驗與高頻交易效率鎖在自身生態。

風險也同樣放大。DraftKings、FanDuel、Polymarket 等都在搶同一條「投資與博彩模糊地帶」賽道；內華達州法官將 Kalshi 體育合約納入博彩監管，顯示這類產品的法律邊界仍在變動。

整理者判斷：**HOOD** 新增 L3 watchlist。核心不是傳統券商估值，而是「投機娛樂化、娛樂金融化」的平台 economics 與監管風險。後續追 MIAXdx deal close、CFTC / state gambling regulation、prediction market volume、per-contract revenue uplift、Kalshi / CME / Coinbase / DraftKings competition、options / crypto mix 與 customer quality。

### 6. Zscaler：高估值公司 beat 還不夠，必須繼續超高速

Zscaler 財報 revenue `$7.88億`、年增 26%，EPS `$0.96`，都超預期；但股價跌超過 13%，從一個月高點已回落約 25%。KP 的重點是：高估值 SaaS 看的是前方，不是後照鏡。

第一個前瞻信號是 billings growth 約 15.5%，低於 Zscaler 歷史水準。Billings 代表已簽合約但尚未認列的未來收入，是 SaaS 需求信心指標；放慢會讓市場擔心 enterprise security budget 變保守。

第二個是 Red Canary 收購。Zscaler 近 `7億美元` 買下 Red Canary，但財報未清楚說明它會貢獻多少 revenue，導致市場質疑 integration 與 monetization。

第三個是競爭格局。2025 年企業資安預算平均增長率從 8% 降至 4%，為五年低點；CrowdStrike、Palo Alto 等也面臨增長放緩疑問。Zscaler 自身的 zero trust moat 也被 Palo Alto SASE bundle 與更完整平台侵蝕。

唯一亮點是 AI security：ARR 同比增長 80%，提前三個季度達成目標。KP 把它視為王牌也是豪賭。若 Zscaler 能定義並主導 AI security，可抵消核心業務放緩；若競爭者快速跟進，該市場變紅海，高 P/S 會面臨更嚴格考驗。

整理者判斷：**ZS** 新增 L3 watchlist。後續追 billings、RPO、AI security ARR、Red Canary revenue / retention、SASE competitive win rate、gross margin、budget environment、PANW / CRWD read-through 與 valuation multiple 是否從 hypergrowth 轉成 quality growth。

### 7. ByteDance 去 Nvidia 化：AI 平行宇宙加速成形

The Information 報導中國監管機構禁止 ByteDance 在新建數據中心使用 Nvidia GPU。KP 認為重點不是 Nvidia 少一個客戶，而是北京選擇對 2025 年中國最大 Nvidia 晶片買家開刀，強迫最需要頂級算力的科技巨頭轉向國產晶片陣營。

這等於給華為昇騰、百度崑崙、寒武紀等本土供應商建立 protected hunting ground。它們不必在開放市場直接面對 Nvidia 降維打擊，而是在國家意志保護下服務 ByteDance、阿里、騰訊等真實需求，快速迭代。

對 Nvidia 股價，KP 認為市場反應平淡很合理：出口管制下，中國 revenue 已降至約 0%-2%，華爾街早已把這部分故事歸零；Nvidia 到 2026 年底的 `5000億美元` orders 也幾乎不含中國。因此禁令更像預期內的靴子落地，地緣緩和反而成為免費看漲期權。

但大格局是全球 AI ecosystem 分裂加速。西方陣營以 CUDA、TSMC 先進製程與矽谷創新速度為核心；東方陣營以華為昇騰、百度崑崙、寒武紀與中國國家隊 / 科技巨頭為核心。中國單晶片效能落後，但可用更便宜電力、更大 cluster 與 DeepSeek 類軟體優化彌補。

整理者判斷：這段補強 **NVDA** watchlist 與中國 AI ecosystem read-through。後續追 China export controls、Nvidia China revenue / compliant chip policy、Huawei Ascend / Baidu Kunlun / Cambricon deployments、ByteDance AI capex、DeepSeek 類 software efficiency、TSMC / advanced node access 與中美 AI stack compatibility。

## 框架沉澱

| 框架 | 一句話定義 | 主要觀察 |
|---|---|---|
| GPU / ASIC 非零和替代框架 | 專用晶片可在特定 workload 替代 GPU，但投資判斷要同時看替代比例、TAM 擴張速度與平台生態控制權 | inference share、cost per token、GPU / TPU utilization、AI factory backlog、CUDA / software ecosystem、CoWoS / power bottleneck |
| 製藥 0/1 臨床開關框架 | 製藥公司的 pipeline value 常由臨床結果二元切換，市值表面回到原點時，內部風險地圖可能已完全改變 | primary endpoint、biomarker vs clinical benefit、phase transition、pipeline probability、competitive standard of care、market size |
| AI server 估值保護傘 / PC 成本暴露框架 | 同樣承受記憶體成本上升，有 AI server 成長敘事的硬體商可能獲估值保護，純 PC 暴露則更容易被 margin squeeze 定價 | DRAM / NAND / HBM pricing、AI server backlog、PC mix、inventory hedge、gross margin、pass-through pricing |
| 穿越週期 kitchen-sink 指引框架 | 週期公司可能把壞消息集中放進低指引以設定底部，市場是否買單取決於資產負債表、庫存、同業週期與未來技術 optionality | guidance reset、inventory reduction、used pricing、cycle trough、tariff cost、segment divergence、investor day |
| 投機娛樂化 / 受監管數位賭場框架 | 金融平台若同時控制用戶流量、交易所與清算，可能把投資行為娛樂化並取得更高 economics，但監管與 reputational risk 同步放大 | prediction market volume、per-contract revenue、exchange ownership、liquidity provider, state gambling rules、CFTC oversight、user quality |
| 高估值 SaaS 預期重設框架 | 高成長軟體公司即使 beat earnings，只要 billings、指引或整合回報低於高預期，估值就會從 hypergrowth 轉回 quality growth | billings growth、RPO、guidance, acquired revenue contribution、ARR growth、competitive bundling、P/S multiple |
| AI 生態脫鉤 / 軟體補硬體框架 | 出口管制與本土替代會推動 AI stack 分裂，落後晶片可用電力、cluster scale 與演算法優化部分彌補單晶片差距 | export policy、domestic chip deployment、power cost、cluster size、software efficiency、CUDA compatibility、supply-chain sovereignty |

## 風險與備註

- **標題期數**：原文標題與 URL slug 寫第17期，但正文開頭與語境寫第18期；本專案記為第18期，並保留來源筆誤註記。
- **Substack post id**：本次未能從 direct domain / API 穩定取得 post id；Jina Reader 公開頁內容完整，故以 public URL 與 hash `a772be14` 入庫。
- **NVDA / GOOGL**：本文不是說 TPU 不會衝擊 Nvidia，也不是說 TPU 已取代 GPU；KP 的核心是替代存在但不是零和，需看 TAM、workload split、ecosystem 與 physical bottlenecks。
- **NVO**：Amycretin 仍只是二期試驗，不能把 14.5% weight loss 直接寫成上市成功或 commercial win；Semaglutide Alzheimer 失敗也不代表 GLP-1 核心 obesity / diabetes franchise 失效。
- **DELL / HPQ**：記憶體成本壓力與 AI server growth 可能同時存在；Dell 短期反彈可能包含跌深與預期修復，不等於 margin risk 消失。
- **DE**：KP 提到「最佳買點」是描述分析師 through-the-cycle 邏輯，不是本專案買賣建議。
- **HOOD**：預測市場 economics 與監管風險高度不確定；Kalshi / MIAXdx / state gambling regulation 需持續校準。
- **ZS**：revenue / EPS beat 不能單獨判斷 thesis，需追 billings、RPO、AI security ARR 與 Red Canary integration。
- 本文不是買賣建議。

---
