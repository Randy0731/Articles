# KP 思考筆記第29期：Google OCS、HBM4、AMAT、OpenAI / Cerebras、Microsoft 與 ASTS

## Metadata

- **來源 KOL**：KP / FOMOSoc
- **原文標題**：三星HBM4逆襲了？OpenAI新模型不用NVDA？谷歌用光取代HBM？- KP思考筆記(第29期)
- **原始來源**：https://www.fomosoc.com/p/hbm4openainvdahbm-kp29
- **source_id**：KP_FOMOSoc-20260214-kp-thinking-note-29-alphabet-century-bond-ai-disruption-google-ocs-hbm4-amat-openai-cerebras-msft-asts-cc671a80
- **發文時間**：2026-02-14 02:30 UTC（台北 10:30）
- **整理日期**：2026-04-29
- **raw 路徑 / URL**：URL（未另存 raw；Jina Reader Markdown）
- **Jina Markdown SHA256**：cc671a805c7d8e89488b42705bc0fe0cd16e16f2c75bed99aee27630e4783b75
- **OCR 狀態**：不適用
- **文章類型**：Substack 公開週報 / KP 思考筆記 / AI 基建 / HBM / 半導體設備 / AI 代理 / 可轉債
- **完整性檢查**：Jina Reader Markdown 完整可讀；正文開頭明確自稱第29期，文內列出 Alphabet 百年債、AI 脫媒、Google OCS、Samsung HBM4、AMAT / TSMC、OpenAI / Cerebras、Microsoft AI 自給自足、ASTS 可轉債八個主題，結尾有宣傳段落與 KP 署名，未偵測截斷。

---

## 總結

第29期的核心不是單一公司，而是 AI 基建進入「物理、資本結構與垂直整合」三重驗證期。KP 先用 Alphabet 百年債說明 AI 軍備競賽需要把科技公司融資邏輯推向公用事業化；再用 AI 代理衝擊保險、財富管理、物流、地產中介，說明軟體正在吞掉分銷成本；接著以 Google OCS、Samsung HBM4、AMAT / TSMC、OpenAI / Cerebras、Microsoft 自給自足、ASTS 可轉債，拆解 AI 時代的瓶頸如何從 GPU 逐步擴散到光互聯、記憶體、無塵室、推理架構、算力定價與資本市場跑道。

整理者判定：**GOOG** / **GOOGL** 為已追蹤個股 L3 補強，需同步 `Stocks/GOOGL/`；**AMAT**、**LITE** 新增 watchlist；**MU**、**TSM**、**ASML**、**NVDA**、**AMD**、**AVGO**、**MSFT**、**ASTS** 為既有 watchlist / ticker 補強；**AON**、**WTW**、**LPLA**、**RJF**、**SCHW**、**CHRW**、**RXO**、**CBRE**、**JLL** 為 AI 脫媒籃子，不在本篇建立正式 `Stocks/`。

---

## 主題地圖

| 主題 | KP 核心觀點 | 相關 ticker | 入庫判定 |
|---|---|---|---|
| 投資研究與執行 | 研究可以外包，conviction 與風險控制不能外包 | 無 | 框架補強 |
| Alphabet 百年債 | Alphabet 用 100 年英鎊債把自己定位成數位公用事業，為 AI capex 借到「時間」 | **GOOG**, **GOOGL**, **MSFT**, **AMZN** | GOOGL L3 |
| AI 脫媒交易 | 保險、財管、物流、CRE 中介遭 AI agent 壓縮，但責任背書 / 信任仍是傳統機構緩衝 | **AON**, **WTW**, **LPLA**, **RJF**, **SCHW**, **CHRW**, **RXO**, **CBRE**, **JLL** | ticker index / 主題 |
| Google OCS | Apollo OCS 用全光交換把 AI data center 的神經系統升級，但 TPU v8 完全捨棄 HBM 的傳聞不合理 | **GOOG**, **GOOGL**, **LITE**, 中際旭創, 新易盛 | GOOGL L3；LITE watchlist |
| HBM4 競局 | Samsung HBM4 讓 HBM 從 SK Hynix 一家獨大走向兩強，Micron 則受益 DRAM 超級週期 | **005930.KS**, **000660.KS**, **MU**, **NVDA**, **AVGO**, **GOOG**, **GOOGL** | watchlist / ticker |
| AMAT / TSMC | 2026 半導體瓶頸是無塵室與前段建設；AMAT 受益 FEOL、HBM / CoWoS 與工序複雜度增加 | **AMAT**, **TSM**, **ASML**, **INTC**, **005930.KS** | AMAT watchlist；TSM / ASML 補強 |
| OpenAI / Cerebras | OpenAI 以 Cerebras 作推理奇兵，代表 AI 基建進入訓練 / 推理異構雙戰場 | **NVDA**, **AMD**, **AVGO**；Cerebras 未上市 | watchlist 補強 |
| Microsoft 自給自足 | Microsoft 既要降低 OpenAI / Nvidia 依賴，又要維持開放平台，關鍵在 AI margin deadlock | **MSFT**, **NVDA**, **GOOG**, **GOOGL**, **AMZN** | MSFT watchlist |
| ASTS 可轉債 | ASTS 大跌不是業務出事，而是用昂貴換債清理 cap table、買 2036 前的商業化時間 | **ASTS** | watchlist 補強 |

---

## 0. 研究可外包，conviction 不能外包

KP 在開頭藉 Palantir 深度分析的讀者反應，重新說明 FOMO 研究院的定位：研究可以外包，執行不能外包；資訊可以交給作者整理，但 conviction、部位、風險承受度與睡眠品質只能由投資者自己負責。

這段不是單一 ticker 觀點，但對資料庫有框架價值。KP 強調深度研究未必導向買入，可能導向不買、等待、建立觀察清單或識別產業範式。整理者將此歸入「研究 / 執行分離框架」：入庫 KOL 觀點時，應保留 thesis、驗證條件與風險，不把文章整理改寫成買賣指令。

---

## 1. Alphabet 百年債：科技巨頭公用事業化

Alphabet 完成規模約 200 億美元的多幣種債券發行，其中最醒目的是以英鎊計價、期限 100 年的百年債。KP 認為這不是單純融資，而是 Alphabet 將自己從高增長科技公司重新定位成「21 世紀數位公用事業」的身份宣示。

英鎊百年債有三個結構性原因：

| 面向 | KP 解讀 |
|---|---|
| 買方需求 | 英國 DB pension / insurance liabilities 可長達 50-80 年，需要超長天期資產匹配負債 |
| 定價基準 | 英國 50 年期 Gilts 提供超長天期 anchor，美國 Treasury 沒有 30 年以上定價基準 |
| 監管效率 | Solvency II 讓保險公司持有 AA 級高信用資產時資本效率較高 |

AI capex 是融資用途核心。Alphabet 2026 capex 可能達 1750-1850 億美元，幾乎是 2025 年的一倍。KP 認為百年債讓 Alphabet 用低於股權的成本鎖定超長期資金，支應 3-5 年就需更新的 AI 晶片，等於用「百年後的承諾」換取 AI 軍備競賽中的時間。

整理者判定：這與大叔 2026-02-21 對 Alphabet capex / century bond 的 L4 里程碑同方向，本篇時間更早，對 **GOOGL** 是 AI infrastructure utility / capital structure thesis 的歷史 L3 補強。

---

## 2. AI 脫媒交易：分銷成本被壓縮

KP 將 2026-02 第二週的多個行業股價波動定義為「AI Disruption Trade」：市場看到 AI agent 進入高人力成本、高佣金、中介性質的行業，就先賣再問。

| 行業 | 事件 | 受影響 ticker |
|---|---|---|
| 保險分銷 | Insurify 在 ChatGPT 平台推出車險 / 房屋保險對話式比價，背後約 2 億條報價資料 | **AON**, **WTW** |
| 財富管理 | Altruist 旗下 Hazel 推出 AI tax planning，整合 1040、薪資單與 brokerage account，把原本需數日的 what-if tax planning 壓到數分鐘；收費約每月 60 美元 | **LPLA**, **RJF**, **SCHW** |
| 貨運經紀 | Algorhythm / SemiCab 稱可讓操作員處理貨運量提高 300%-400%，降低 empty miles | **CHRW**, **RXO** |
| CRE 服務 | 市場將 AI 脫媒恐慌擴散到商業地產服務與經紀 | **CBRE**, **JLL** |

KP 不是說 AI 會立即全面取代傳統機構。大型券商、保險經紀與地產服務商仍有資料、品牌、合規、責任背書、情感連結與複雜決策優勢。現階段 AI 更像頂尖專業人士的效率放大器，把 90% 雜事自動化，讓人類把 10% 精力放在複雜決斷與信任建立上。

整理者判定：本段不建立多個新 watchlist 專案，只寫入 ticker / theme index 作「AI 脫媒 / 分銷成本壓縮」框架。若後續有單一公司 L2+ 深度 thesis，再升級 watchlist。

---

## 3. Google OCS：AI data center 的光學神經系統

TrendForce 報告指出 Google 圍繞下一代 Ironwood TPU 部署 Apollo OCS 光學電路交換機。KP 認為 AI 瓶頸已不只在晶片，而在 data center 內部數萬顆 TPU 如何低延遲、低功耗協同。

傳統交換機需要 O-E-O 轉換，功耗可達約 3000W；Apollo OCS 透過 MEMS 微鏡直接為光訊號開點對點通道，功耗約 100W，KP 口徑節能高達 95%。當頻寬從 800G 升到 1.6T，OCS 架構可更換兩端光模組，而不用重建交換機，這讓 Google AI factory 的神經系統更可擴張。

供應鏈上，KP 引用 TrendForce 點名中際旭創與新易盛可能吃下 Google 高階光模組大單，Lumentum 則是 OCS 核心 MEMS 元件供應關鍵。整理者判定：**LITE** 新增光學互聯 watchlist，尚不建立 `Stocks/LITE/`。

### 不是「Google 用光取代 HBM」

KP 特別校準市場傳聞：TPU v8 完全拋棄 HBM、改用 OCS 連外部 DRAM memory pool，對訓練任務不合理。

| 對照 | KP 口徑 |
|---|---|
| HBM latency | 約 10-20ns |
| 光學記憶體池 latency | 即使理想情境也可能 300ns 以上 |
| TPU v7 HBM bandwidth | 約 7.4 TB/s |
| 反證 | Samsung HBM4 已通過 Google TPU v8 驗證，表示 Google 下一代晶片仍沿用 HBM |

KP 認為真正方向是記憶體分層與資源池化：training 仍需要最低延遲與最高頻寬的 HBM；inference 端則可能在部分場景使用 OCS 連接大規模 DRAM pool。對 **GOOGL** 來說，這補強 TPU / Cloud AI infrastructure 的差異化，但也要求追光模組、MEMS、HBM、功耗與 Google Cloud revenue 的實際轉化。

---

## 4. Samsung HBM4、SK Hynix 與 Micron：尖端引領 vs 務實跟隨

Samsung 在 2026-02-12 宣布量產並出貨 HBM4。KP 認為這是 Samsung 重返 AI memory 牌桌的訊號，讓 HBM 競爭從 SK Hynix 一家獨大走向兩強爭霸。

| 公司 | KP 解讀 |
|---|---|
| Samsung | HBM4 使用 1c DRAM 與 4nm logic die，速度約 11.7Gbps，比業界標準高近 50%；拿到 Nvidia Vera Rubin 首批訂單，也通過 Google TPU v8 / Broadcom 測試 |
| SK Hynix | 仍是 Nvidia 最信任供應商與主要訂單承接者，但獨佔超額利潤時代可能被 Samsung 打破 |
| Micron | HBM4 首批頂級戰役可能落後，但通用 DRAM 結構性短缺與 HBM 產能供不應求讓它成為務實受益者 |

Micron 的邏輯不是「技術第一」，而是「總供給不足」。KP 指出 HBM 市場約 200 億美元，但通用 DRAM 市場超過 1000 億美元；AI 伺服器拉動 DDR5 等通用 DRAM，2026 年價格可能大漲。即使 Samsung / SK Hynix 拿走 Nvidia / Google 的頂級訂單，AMD、Microsoft、AWS、Meta 等客戶仍需要 memory supply，讓 Micron 產能被動售罄。

整理者判定：**MU** watchlist 補強，重點是 DRAM supercycle 是否能彌補 HBM 技術落後；**005930.KS** / Samsung、**000660.KS** / SK Hynix 為 HBM 競局 ticker context。

---

## 5. AMAT / TSMC：無塵室瓶頸與前段技術後段化

Applied Materials 財報 EPS 2.38 美元、營收 70 億美元優於預期，但 KP 認為重點是管理層說出的「幸福煩惱」：2026 年限制半導體成長的瓶頸不是需求，而是 cleanroom 供應不足。

客戶台積電、Intel、Samsung 的工廠建設速度跟不上設備需求，代表 2026H1 成長受限可能是延後，不是消失。等台積電亞利桑那、德國等新廠完工，被壓抑的設備需求可能釋放。

KP 也引用 BofA 對台積電 capex 的拆解：台積電 2026 capex 約 520-560 億美元，更多砸向 FEOL 前段製程。AMAT 受益不只因為它是前段沉積 / 蝕刻 / 量測核心供應商，也因 HBM、CoWoS 與 3D stacking 讓前段技術進入後段封裝，工序增加超過 30%，形成設備需求乘數。

AMAT 的 integration / co-optimization 也被 KP 視為護城河：2nm / A16 極限製程中，單一設備不再是標準化工具，而是與晶圓廠 know-how 綁定的客製化武器。

整理者判定：**AMAT** 新增 L3 watchlist；**TSM**、**ASML** 既有 watchlist 補強；**INTC** / Samsung 只作半導體產能建設 context，本篇不同步正式 `Stocks/INTC/`。

---

## 6. OpenAI / Cerebras：推理異構化與去 Nvidia 化 B 計劃

KP 延續第28期 OpenAI / Nvidia 戰略性脫鉤脈絡。Nvidia 原先對 OpenAI 的 1000 億美元投資更像談判籌碼，實際投資金額不會達到市場想像。OpenAI 則對 Nvidia 在特定高頻推理任務的速度不滿，開始多線備援：

| 路線 | 角色 |
|---|---|
| Broadcom custom ASIC | OpenAI 自研晶片 / 專用推理路線 |
| AMD MI300X | 供應商競爭壓力與替代 GPU |
| Cerebras WSE | 低延遲推理奇兵 |

OpenAI 與 Cerebras 協議價值超過 100 億美元，KP 口徑包含 750MW deployment、OpenAI 取得 Cerebras 10% 股權，以及 GPT-5.3-Codex-Spark 這類更快但功能較弱、偏程式碼互動 / 測試的模型。KP 強調這不是用 Cerebras 取代 Nvidia 訓練，而是把 Cerebras 放到最能發揮 wafer-scale engine 低延遲優勢的推理場景。

整理者判定：**NVDA** watchlist 補強，風險不是訓練王權立即消失，而是推理 market segmentation 讓 Nvidia 定價權局部被挑戰；**AMD**、**AVGO** 補強 OpenAI multi-sourcing / custom ASIC 脈絡；Cerebras 未上市。

---

## 7. Microsoft：AI 自給自足與 margin deadlock

Microsoft AI CEO Mustafa Suleyman 表示 Microsoft 必須在 AI 自給自足。KP 將這解讀為 Microsoft 對 OpenAI 與 Nvidia 依賴的系統性降風險。

三層戰略：

| 層級 | 內容 |
|---|---|
| 模型層 | MAI / Phi 作 OpenAI 之外的戰略備胎與選擇權 |
| 晶片層 | Maia / Cobalt 將 token generation economics 從 Nvidia 外部變數轉成內部工程問題 |
| 基建層 | 約 800 億美元單年投資與 AI WAN，把全球資料中心連成行星級運算機器 |

Microsoft 透過 Azure AI Foundry、Copilot Studio、BYOM 建立 Copilot Stack，目標是成為 AI 時代作業系統。與 Google 相比，Google 的 TPU + Gemini 是「長出來」的原生垂直整合；Microsoft 則是用 OpenAI 結盟買時間，同時補 MAI / Maia。KP 提醒 Microsoft 自研晶片進度仍落後 Google TPU，也不如 Amazon Trainium。

真正風險是 margin deadlock：Microsoft 用高毛利軟體固定月費模式賣成本高度變動的 AI compute。若 GPU 優先供給低 margin Copilot，而不是出租給高 margin Azure 外部客戶，市場會質疑資源配置。整理者判定：**MSFT** watchlist 補強，需追 Copilot pricing、Azure AI revenue、AI gross margin、OpenAI 分潤與 Maia / Cobalt roadmap。

---

## 8. ASTS：可轉債換血買時間

AST SpaceMobile 2026-02 宣布發行 10 億美元、2036 年到期可轉債，同時回購約 3 億美元舊債，股價兩天跌約 15%。KP 認為這不是業務出事，而是債務換血與 cap table 清理。

| 項目 | KP 口徑 |
|---|---|
| 新債 | 10 億美元、2036 到期、coupon 2.25% |
| 舊債 | 2032 到期，部分 coupon 4.25% / 2.375% |
| 利息節省 | 約 5140 萬美元 |
| 淨稀釋 | 約 115 萬股 |
| 回購代價 | 4.25% 舊債回購價約面值 381%；2.375% 舊債約面值 164% |
| 現金儲備 | 交易後約 27.8 億美元 |
| 營收 / 支出 | 2025 revenue guide 約 6300-7100 萬美元；opex 約 3.5 億美元 |

舊債轉換價低，債權人不急著讓公司贖回，因此 ASTS 必須支付高溢價。另因 registered direct offering / convertible settlement 結構，部分機構收到可立即出售的乾淨股票，形成短期賣壓。

KP 的結論是：財務操作買到時間，但不能解決商業化問題。若 2036 年前衛星網路按計劃運作且股價高於 116.30 美元轉換價，債務可轉股；若商業化失敗，10 億美元債務會變成壓力。真正要追的是 45-60 顆衛星的發射時程表。

整理者判定：**ASTS** watchlist 補強，核心追蹤由短期股價轉為 debt runway、cap table、BlueBird deployment、AT&T / Verizon commercial rollout 與 satellite launch cadence。

---

## 新增 / 補強框架

| 框架 | 定義 | 適用範圍 |
|---|---|---|
| 研究 / 執行分離框架 | 研究可外包，但 conviction、部位、風險承受度與決策不能外包 | KOL 文章入庫、投資流程、觀點追蹤 |
| 百年債 / AI 基建公用事業框架 | 科技巨頭用超長天期低稀釋資本，把 AI capex 包裝為數位公用事業的長期資產 | GOOGL、MSFT、AMZN、AI hyperscaler financing |
| AI 脫媒 / 分銷成本壓縮框架 | AI agent 先壓縮高佣金、高人力、高資訊不對稱中介，但責任背書與信任關係延緩完全替代 | 保險、財富管理、物流、CRE |
| OCS 光學神經系統 / HBM 分層框架 | AI data center 競爭力來自晶片、記憶體與光互聯分工；OCS 適合晶片互聯 / inference pool，不等於 training 端捨棄 HBM | GOOGL TPU、LITE、光模組、HBM |
| HBM 尖端引領 vs DRAM 務實跟隨框架 | HBM 技術領先者取得頂級客戶定義權，DRAM 供需週期受益者則靠總供給短缺變現 | Samsung、SK Hynix、MU |
| 無塵室瓶頸 / 前段技術後段化框架 | AI 晶片需求被 cleanroom、FEOL、先進封裝工序複雜度限制，設備商受益於物理建設趕工 | AMAT、TSM、ASML、LRCX |
| 推理異構化 / 架構奇兵框架 | 訓練與推理分化後，非傳統架構可在低延遲推理場景取得局部定價權 | NVDA、AMD、AVGO、Cerebras |
| AI 自給自足 / 混合生態 margin deadlock 框架 | 平台公司同時追求模型 / 晶片自研與開放生態，但 fixed-price AI software 可能被 variable compute cost 壓 margin | MSFT、GOOGL、AMZN |
| 可轉債換血 / cap table 清理框架 | 高成長、高燒錢公司可用新可轉債買時間，但短期賣壓、溢價回購與未來轉股 / 到期風險需分開看 | ASTS、space / pre-revenue infrastructure |

---

## 後續追蹤

| 追蹤問題 | 相關 ticker | 指標 |
|---|---|---|
| Alphabet 百年債與 2026 capex 是否維持資本成本優勢 | **GOOG**, **GOOGL** | bond spread、rating、capex、depreciation、Cloud AI revenue、Search revenue、FCF |
| Google Apollo OCS 是否轉成 TPU / Cloud AI 效率 | **GOOG**, **GOOGL**, **LITE** | OCS deployment、800G / 1.6T modules、power usage、TPU utilization、Cloud AI revenue、LITE MEMS / OCS revenue |
| Samsung HBM4 是否真的壓縮 SK Hynix 超額利潤 | **005930.KS**, **000660.KS**, **NVDA** | Nvidia / Google qualification、HBM4 share、pricing、yield、gross margin |
| Micron 是否把 DRAM supercycle 轉成可持續 re-rating | **MU** | DDR5 pricing、HBM4 certification、HBM revenue、gross margin、capex discipline、2026 mid-year updates |
| AMAT cleanroom / FEOL bottleneck 是否只延後不消失 | **AMAT**, **TSM**, **ASML** | AMAT orders、backlog、TSMC capex、new fab readiness、CoWoS / HBM equipment demand |
| OpenAI multi-sourcing 是否改寫 Nvidia inference 定價權 | **NVDA**, **AMD**, **AVGO** | Cerebras deployment、Broadcom ASIC milestones、AMD GPU deployment、Nvidia inference revenue / margin |
| Microsoft AI 自給自足是否解開 margin deadlock | **MSFT** | Copilot gross margin、Azure AI revenue、OpenAI revenue share、Maia / Cobalt adoption、capex / depreciation |
| ASTS 買到的時間是否足以換成商業化 | **ASTS** | satellite launches、BlueBird deployment、commercial revenue、cash burn、convert maturity / conversion price、AT&T / Verizon rollout |

> 本文為 KOL 觀點整理與資料庫索引，不構成買賣建議。
