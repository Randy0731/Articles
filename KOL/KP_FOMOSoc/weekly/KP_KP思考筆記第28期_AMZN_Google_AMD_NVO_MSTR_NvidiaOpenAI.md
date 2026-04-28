# KP 思考筆記第28期：Amazon / Google / AMD / NVO / MSTR 與 AI 基建權力重平衡

- **來源 KOL**：KP / FOMOSoc
- **原文標題**：亞馬遜這次是在賭什麼？比特幣大規模清算來了？搜索已死已成偽命題？ - KP思考筆記(第28期)
- **原始來源**：https://www.fomosoc.com/p/kp28
- **source_id**：KP_FOMOSoc-20260207-kp-thinking-note-28-amazon-google-amd-nvo-mstr-nvidia-openai-spacex-xai-fe4e3d99
- **raw 路徑 / URL**：URL（未另存 raw；Jina Reader Markdown）
- **內容雜湊**：Jina Reader Markdown SHA256 `fe4e3d9964ab96d37ddece43c6677d7e99cddabe9c143ddaeb17ec7bdffa63d9`
- **OCR 狀態**：不適用
- **發文時間**：2026-02-07 02:45 UTC（台北 10:45）
- **整理日期**：2026-04-29
- **文章類型**：Substack 公開週報 / KP 思考筆記 / AI 基建 / 雲端財報 / GLP-1 / Bitcoin treasury
- **完整性檢查**：Jina Reader Markdown 完整可讀；正文開頭明確自稱第28期，文內列出商品 / 礦業股、Nvidia / OpenAI、SpaceX / xAI、Google Search、AMD、Amazon / AWS、Novo Nordisk、MicroStrategy 八個主題，結尾有宣傳段落與 KP 署名，未偵測截斷。

## 一句話總結

KP 第28期的共同主軸是：市場先用價格恐慌或亢奮投票，但真正要檢查的是生意實體。這期把「價格只是影子、企業才是實體」作為投資框架，接著用 Google Search、AWS、AMD CPU、Novo GLP-1、MSTR 債務結構與 Nvidia / OpenAI 關係，示範如何把股價波動拆回 business quality、資本開支、供應鏈、定價權、融資能力與執行風險。

## 主題地圖

| 主題 | 核心觀點 | 主要 ticker / 產業 | 入庫判定 |
|---|---|---|---|
| 市場波動與投資方法 | 價格是影子，生意是實體；大漲與大跌都要回到 thesis check | 全市場 | 新增 KP 框架 |
| 商品 vs 礦業股 | 商品買趨勢，礦業股買槓桿；礦企會放大利潤、儲量與財務修復，也會放大成本、治理與地緣風險 | 大宗商品 / miners | 主題與框架，不新增單一 ticker |
| Nvidia / OpenAI | 雙方公開否認衝突，但背後是 OpenAI 去 Nvidia 化與 Nvidia 重新評估綁定風險的權力重平衡 | **NVDA**, **AMD**, **AVGO** | watchlist / ticker 補強 |
| SpaceX / xAI | 太空 AI data center 是宏大敘事，但合併更像用 SpaceX IPO story 包裝 xAI 燒錢需求的金融工程 | **TSLA**；SpaceX / xAI 未上市 | **TSLA** watchlist 補強 |
| Google Search | AI 沒有殺死搜尋，而是把 query 長度、場景與商業意圖擴張，並可能讓 Google 進入交易閉環 | **GOOG**, **GOOGL**, **AMZN** | **GOOGL** 已追蹤個股 L3 |
| AMD Q4 | 市場賣的是過高預期，不是業務崩壞；EPYC CPU 是盾，Instinct GPU 是矛 | **AMD**, **INTC**, **TSM** | **AMD** watchlist；**INTC** 已追蹤個股 L2 對照 |
| Amazon / AWS | AWS growth 再加速、AI 服務與自研晶片有 revenue，capex 背後有 backlog 收據 | **AMZN** | 已追蹤個股 L3 |
| Novo Nordisk | GLP-1 藥王遭遇價格權、產能、Lilly 與 Hims 複方藥多重夾擊，口服 Wegovy 是關鍵反擊 | **NVO**, **LLY**, **HIMS** | watchlist 補強 / 新增 HIMS |
| MicroStrategy | 所謂清算價是偽命題；真正風險在 2028 maturity wall 與再融資能力，而非 BTC 跌破成本本身 | **MSTR**, **BTC** | watchlist / ticker 補強 |

## 0. 先看生意，不追影子

KP 將 2026 年初的市場波動拆成情緒鐘擺：一月的上漲未必代表基本面突然變好，二月初的下跌也未必代表企業價值瞬間崩壞。整理者將本期開場抽象成「價格影子 / 生意實體框架」：

| 面向 | KP 的判斷 | 操作上的資料庫含義 |
|---|---|---|
| 股價 | 反映情緒、資金與預期，短期可被拉長或壓縮 | 不把單日反應寫成 KOL 買賣建議 |
| 生意 | 公司產品、競爭力、管理層、供應鏈、資本配置才是核心 | 入庫時優先整理 thesis、證據、風險與後續驗證 |
| 恐慌與 FOMO | 都可能讓價格偏離企業實體 | 將「價格波動」與「企業價值改變」分欄處理 |

## 1. 商品 vs 礦業股：趨勢與槓桿不是同一件事

KP 認為黃金、白銀、銅、鋁、鋰、稀土等商品走強時，投資人不能只問「看多商品要買什麼」，還要問自己要的是純粹價格 exposure，還是礦業公司股權槓桿。

### 核心拆解

| 槓桿類型 | 作用 | 例子 / 檢查 |
|---|---|---|
| 營運槓桿 | 固定成本相對穩定時，商品價格上漲會更大幅推升每單位利潤 | 銅價從每磅 3.5 美元到 4.5 美元，商品漲約 28%，但若成本維持 3 美元，單位利潤可從 0.5 美元到 1.5 美元 |
| 資產槓桿 | 商品價格上升可把原本不具經濟價值的低品位礦床重估為可開採儲量 | reserve / resource update、AISC、mine plan |
| 財務槓桿 | 高負債礦企在商品熊市被視為困境資產，價格回升時 equity value 修復可不成比例 | debt maturity、interest cost、refinancing、credit rating |

### 風險與階段

KP 提醒，礦業股不是商品價格的無摩擦放大器。成本通膨、管理層在高點做壞併購、罷工 / 環保事故與加稅 / 國有化，都可能讓礦業股落後商品本身。走勢上則常有兩段：早期懷疑期礦股可能落後商品；趨勢確認且價格跨過 AISC 後，才可能出現利潤與 multiple 同時擴張的 Davis double play。

整理者判定：本節不具名單一礦企，不新增 watchlist；但新增「商品趨勢 / 礦業股槓桿分流框架」。

## 2. Nvidia / OpenAI：公開親密，私下重新談權力平衡

KP 將 WSJ / Reuters 對 Nvidia 與 OpenAI 關係的互相放話拆成一場權力重平衡。Nvidia 並沒有簽下不可撤回的 1000 億美元承諾；早前只是非約束性意向書，讓 Nvidia 保留觀察期。真正觸發 Nvidia 重估的，是 OpenAI 與 **AMD** 具約束力合作協議釋出的去 Nvidia 化信號。

### KP 的推論

| 面向 | 整理 |
|---|---|
| Nvidia 的退 | 從深度基建綁定轉為重新評估風險，避免為可能扶持競爭對手的客戶搭獨家舞台 |
| Nvidia 的留 | OpenAI 若出事會動搖整個 AI 產業鏈，Nvidia 仍可能用純股權投資維持 exposure |
| OpenAI 的反擊 | 對外釋出 Nvidia inference 成本 / 速度不夠好的敘事，合理化 AMD、自研晶片、Broadcom、Cerebras、Groq 等替代方案 |
| 公開否認 | Huang 與 Altman 都必須維持「最重要合作夥伴」敘事，因為決裂會傷害整個 AI 生態信心 |

整理者判定：**NVDA**, **AMD**, **AVGO** 更新 watchlist / ticker；OpenAI、Cerebras、Groq 未上市或非本專案 ticker。新增「戰略性脫鉤 / 供應商融資重定價框架」。

## 3. SpaceX / xAI：太空 AI 願景與金融工程同時存在

KP 認為 SpaceX 收購 xAI 可以從兩層看：第一層是 Musk 帝國的超級垂直整合，第二層是 xAI 燒錢壓力下的資本市場包裝。

### 垂直整合脈絡

| 資產 | 角色 |
|---|---|
| X | 全球即時對話與文化 / 新聞 / 意見數據流 |
| xAI / Grok | 模型與智能層，吸收 X 的即時資料 |
| SpaceX / Starlink | 發射、太空通信、全球覆蓋與軌道基礎設施 |
| Tesla | 法律上未合併，但可作物理世界接口：車隊數據、能源、Optimus 實體執行 |

### 太空 data center 的現實摩擦

KP 沒有把太空 AI data center 寫成已可落地的短期 thesis。他列出三個硬問題：真空只能靠熱輻射散熱，可能需要巨大散熱板；發射成本要低到每公斤 200 美元以下才具競爭力；硬體 3-5 年一換代，太空維修與升級難度極高。

### 金融工程判斷

KP 更直接的判斷是：xAI 每月 cash burn 極高，季度虧損約 14.6 億美元；SpaceX 雖是 Musk 帝國最成功資產，但約 150 億美元營收也難單獨支撐 xAI 燒錢規模。因此合併可能是把 xAI 綁進 SpaceX IPO 故事，用太空 AI 作為募資敘事，為極大規模資本開支找資金。

整理者判定：**TSLA** 更新 watchlist，因其扮演物理世界接口 / Optimus / energy / data adjacency；SpaceX、xAI、X 未上市，不建立 ticker。

## 4. Google Search：AI 沒有殺死搜尋，反而擴張搜尋

Alphabet Q4 2025 的 Search revenue 達 631 億美元、年增 17%。KP 將此解讀為 AI Search 「擴張性時刻」：AI 沒有讓使用者離開搜尋，而是增加 query 長度、對話式後續追問、語音 / 圖片入口，以及更高商業意圖的長尾查詢。

### 對 GOOGL 的影響

| 面向 | 內容 |
|---|---|
| Search demand | AI Mode query doubled，查詢長度約為傳統搜尋 3 倍，近六分之一來自語音或圖片 |
| 廣告效率 | Gemini 進入 ad quality system，提升意圖匹配與無效廣告過濾 |
| 商業閉環 | Direct Offers / Universal Commerce Protocol 可能把 Google 從流量入口推進交易平台 |
| Capex 合理性 | 2026 capex 1750-1850 億美元雖高，但若 Search revenue 仍能維持 15%+ 成長並提高 ad ROI，這是規模與效率軍備競賽的入場券 |
| 對 AMZN 的外溢 | AI 對話內直接優惠與下單，可能挑戰 Amazon 商品搜尋與交易入口 |

整理者判定：**GOOG**/**GOOGL** 為已追蹤個股 L3，補入 `Stocks/GOOGL/quarterly/GOOGL_筆記_2026Q1.md`；**AMZN** 作為競爭 read-through。

## 5. AMD：估值重塑，不是故事結束

AMD Q4 2025 revenue 達 102.7 億美元、adj EPS 1.53 美元，均高於預期，但 Q1 revenue guide midpoint 98 億美元，約季減 5%，讓市場失望。KP 的判斷是：市場原本已把「AI 時代季節性已死」寫入估值，財報沒有打破季節性就觸發 valuation reset；這不是業務崩壞。

### 「矛與盾」結構

| 結構 | 內容 | 驗證 |
|---|---|---|
| 盾：EPYC CPU | Data center revenue 創新高 54 億美元、年增 39%；Turin 已占 server revenue 一半以上；AI agents / complex workflows 讓 CPU 重新重要 | EPYC orders、Turin share、server CPU revenue q/q、pricing、share |
| 矛：Instinct GPU | 爭奪 AI accelerator 增量，但受 HBM、CoWoS、export control 與客戶集中限制，收入更塊狀 | MI roadmap、supply allocation、customer deployment、gross margin |
| 雙引擎 | CPU 提供穩定高毛利底座，GPU 提供 upside optionality | Data center revenue mix、FCF、EPS revision |

### AMD vs Intel 缺貨差異

KP 將 AMD 的缺貨稱為提前鎖定 TSMC 產能後的「幸福煩惱」：賣光能拿到的貨，挑戰是取得更多 share。Intel 的缺貨則源於需求預測失誤與 IDM 體系不夠敏捷，屬內部流程與製造彈性問題。

整理者判定：**AMD** 更新 watchlist；**INTC** 只作已追蹤個股 L2 對照補充，不把 AMD 財報段落寫成 Intel 新 thesis；**TSM** 為 supply context。

## 6. Amazon / AWS：capex 恐慌背後有 backlog 收據

Amazon 財報後大跌，市場焦點放在 2026 capex 可能達 2000 億美元、FCF 壓到 112 億美元、年減逾 70%。KP 認為更重要的是：AWS growth 重新加速到約 24%，是 13 個季度以來最快；在 1420 億美元 annualized revenue base 上再加速，代表 AWS 沒有在 AI 雲端戰中掉隊。

### AWS 的三個驗證點

| 驗證點 | 內容 |
|---|---|
| AI services | Bedrock customer spend q/q +60%，年化已達數十億美元；超過 10 萬家公司使用 AWS AI services |
| Enterprise agents | Kiro、AWS Security Agent 等產品讓 AWS 從模型 / 算力延伸到企業 workflow |
| Custom silicon | Trainium + Graviton 合計 annualized revenue 超過 100 億美元，三位數增長，支撐 cost / performance moat |

### Capex 的「收據」

Andy Jassy 表示 AWS 若不是 capacity constrained，growth 可以更快；AWS 2025 新增 GW capacity 多於競爭者，Q4 單季新增 1.2GW。KP 將 2440 億美元 backlog、年增 40%，視為這輪 capex 的收據：Amazon 回到建設模式，用長期投資與延遲滿足換下一輪 infrastructure moat。

整理者判定：**AMZN** 已追蹤個股 L3，補入 `Stocks/AMZN/quarterly/AMZN_筆記_2026Q1.md`；與宋分 2026-04 AMZN capital cycle / ROIC x Organic Growth thesis 呼應，但本篇屬歷史財報驗證補強。

## 7. Novo Nordisk：GLP-1 藥王的中年危機

KP 將 Novo Nordisk 的 2026 年困境拆成四條壓力線：指引連續下修、價格權喪失、Lilly 正面競爭、Hims & Hers 複方藥游擊戰。

### 壓力分解

| 壓力 | KP 的判斷 |
|---|---|
| Growth reset | 2026 sales 可能下滑最高 13%，這是 Ozempic 上市以來首次面臨負增長恐懼 |
| Pricing power | Wegovy 在美國政策壓力下從 1350 美元降到約 350 美元，核心市場定價權受損 |
| Lilly comparison | Tirzepatide 效果更強、產能擴張更果決，能在降價環境中用 volume growth 消化壓力 |
| Hims & Hers | 49 美元 / 月口服複方藥利用 personalization 灰色地帶，對 Semaglutide 造成直接壓力；FDA 可能出手，但傷害已形成 |
| 反擊牌 | Oral Wegovy 是 NVO 重新搶回消費者基礎的關鍵，但研發、審批、產能與上市節奏都不能再犯錯 |

整理者判定：**NVO**、**LLY** 更新 watchlist；**HIMS** 新增 watchlist 候選，作 GLP-1 compounded / telehealth disruptor 線索。本文不建立 `Stocks/NVO/`。

## 8. MSTR：清算價是偽命題，真正看融資能力

KP 認為「MicroStrategy / Strategy 清算價」在現階段是錯誤敘事。公司債務主要是無擔保可轉換優先票據，BTC 不是抵押品；債權人不能因 BTC 跌破成本就強制賣幣。利息多在 0%-2.25% 區間，軟體業務現金流可支應。

### 真正的風險

| 常見敘事 | KP 校準 |
|---|---|
| BTC 跌破平均成本就清算 | 成本價約 76,052 美元只是心理與會計壓力，不是法律清算線 |
| 174 億美元 operating loss 是現金危機 | 主要受 fair value accounting 影響，是紙上損益，需和現金流分開 |
| BTC price 是唯一風險 | 真正風險在 2028 年初大額 convert maturity、再融資 / 增發能力與資本市場窗口 |
| 無限坐穩 | 若 BTC 長期低迷、股價低於 conversion price 且無法以債養債或增發，才可能被迫賣 BTC |

整理者判定：**MSTR** / **BTC** 更新 watchlist / ticker；新增「Bitcoin treasury 可轉債防火牆 / maturity wall 框架」。本文不是買賣建議。

## 新增 / 補強框架

| 框架 | 一句話定義 | 主要應用 |
|---|---|---|
| 價格影子 / 生意實體框架 | 短期價格像影子，真正研究對象是企業生意本體、競爭力與資本配置 | 全市場、回撤 / FOMO 檢查 |
| 商品趨勢 / 礦業股槓桿分流框架 | 買商品是買趨勢，買礦業股是買營運、資產與財務槓桿，也同時買進成本 / 治理 / 地緣風險 | commodity cycle、miners、critical minerals |
| 戰略性脫鉤 / 供應商融資重定價框架 | 當關鍵客戶尋找替代供應商，上游可從深度基建綁定轉為股權 exposure 或更保守承諾 | Nvidia / OpenAI、AMD、Broadcom、自研晶片 |
| 太空 AI 金融工程 / 垂直整合框架 | 宏大太空 AI 願景可同時是工程 road map 和募資敘事，需分開驗證技術可行性與資金需求 | SpaceX / xAI / TSLA adjacency |
| AI Search 擴張 / 商業意圖再商品化框架 | AI 不是只給答案，也可擴大搜尋場景、拉長互動、提升意圖理解並把長尾 query 變成廣告 / 交易機會 | Google Search、AI ads、commerce protocol |
| CPU-GPU 雙引擎 / 估值重塑框架 | AI server 公司不只靠 GPU upside，CPU 可成為高毛利、穩定成長與 GPU 投資的防守底座 | AMD、Intel、ARM server CPU |
| AWS 建設模式 / backlog 收據框架 | 高 capex 若背後有 backlog、capacity constraint 與高毛利 AI / chip revenue，可被視為建設期投資而非單純黑洞 | AMZN / AWS、cloud AI capex |
| GLP-1 定價權失守 / 複方游擊框架 | 監管降價、療效差距、產能與低價複方藥會共同壓縮原創藥王的 pricing moat | NVO、LLY、HIMS |
| Bitcoin treasury 可轉債防火牆 / maturity wall 框架 | BTC treasury 公司的短期清算風險取決於抵押與利息，不是成本價；真正壓力在債務到期與再融資窗口 | MSTR / BTC |

## 後續追蹤

| 追蹤事項 | 相關 ticker | 檢查點 |
|---|---|---|
| Google AI Search 是否轉成 Search revenue、ad ROI 與 commerce transaction layer | **GOOG**, **GOOGL**, **AMZN** | AI Mode usage、query length、ad load、Direct Offers / UCP rollout、Search revenue growth、capex / depreciation |
| AWS capex 是否由 backlog / AI services / Trainium-Graviton revenue 支撐 | **AMZN** | AWS growth、operating margin、Bedrock spend、Trainium / Graviton revenue、RPO / backlog conversion、FCF |
| AMD EPYC 是否延續 CPU cycle，並與 Instinct GPU 形成雙引擎 | **AMD**, **INTC**, **TSM** | EPYC q/q growth、Turin adoption、server CPU share、MI roadmap、TSMC allocation、Intel DCAI response |
| OpenAI / Nvidia 是否進一步脫鉤或重簽合作 | **NVDA**, **AMD**, **AVGO** | OpenAI cloud / chip commitments、Nvidia equity investment terms、AMD deployment、Broadcom ASIC roadmap、inference cost disclosures |
| SpaceX / xAI / Tesla 是否把太空 AI 從募資故事推向工程里程碑 | **TSLA** | SpaceX IPO docs、xAI cash burn、Starship launch cost、radiator / orbital servicing design、Tesla Optimus / energy integration |
| NVO 是否用 oral Wegovy 反擊 Lilly 與 Hims | **NVO**, **LLY**, **HIMS** | oral Wegovy approval / capacity、Wegovy net price、Tirzepatide sales、HIMS GLP-1 users / regulatory action、FDA compounded-drug enforcement |
| MSTR 是否維持融資通道 | **MSTR**, **BTC** | convert maturities、interest expense、cash balance、BTC price vs conversion price、debt / equity issuance cost、mNAV |

## 風險與資料庫註記

- 本文是 KOL 觀點整理，不提供買賣建議。
- 文中多個數字採 KP 原文口徑，後續若作正式投資判斷，需用公司 filings、earnings call、官方公告或監管文件校準。
- SpaceX、xAI、OpenAI、Cerebras、Groq 未上市或非本專案 ticker；僅保留產業與供應鏈脈絡。
- **GOOGL** / **AMZN** 同步 `Stocks/` 為 L3，因本期包含明確財報與 business thesis；**INTC** 僅因 AMD 段落中的供應鏈 / IDM 對照補入 L2，不放大成獨立正負 thesis。
