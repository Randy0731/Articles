# KP 思考筆記第39期：ASML High-NA、ASTS FCC、Google TPU 8、Intel、ServiceNow 與 JPM 私募信貸

- **來源 KOL**：KP / FOMOSoc
- **原始來源**：https://www.fomosoc.com/p/asmlintel-kp39
- **source_id**：KP_FOMOSoc-20260425-kp-thinking-note-39-asml-high-na-asts-tpu8-intel-servicenow-jpm-private-credit-6995e281
- **raw 路徑 / URL**：URL（未另存 raw；Jina Reader Markdown 完整可讀）
- **OCR 狀態**：不適用
- **類型**：Substack 公開電子報 / KP 思考筆記 / 週報
- **發文時間**：2026-04-25 03:06 UTC（台北 11:06）
- **整理日期**：2026-04-29
- **文章完整性檢查**：Jina Reader Markdown 共 563 行；正文開頭明確自稱第 39 期，列出六個主題，六個主題均完整展開，結尾有宣傳段落與 KP 署名，未偵測核心正文截斷。
- **主題 / 母題標籤**：#投資與投機 #AI基建 #雲端基建 #半導體設備 #先進封裝 #太空通訊 #軟體SaaS #金融流動性 #財報 #競爭風險 #執行風險 #估值風險 #ReRating #產品節點

## 一句話結論

KP 這期的主線是「技術敘事回到經濟性與執行驗證」：台積電拒用 High-NA 量產代表先進製程從純技術領先轉向成本有效；ASTS 一顆衛星失敗不及 FCC 商業執照重要；Google TPU 8 顯示 Google 已從晶片設計者升級為系統定義者；Intel 的 DCAI / 18A / 14A / 先進封裝讓轉機敘事升級，但仍要看外部客戶與虧損收斂；ServiceNow 則說明 SaaS 巨頭在 AI 時代必須用數據證明自己不是被顛覆者；JPM 進軍私募信貸則代表大銀行用 origination 與機構資金回到信貸本質。

## 相關 ticker 與交會等級

| Ticker | 交會等級 | 方向 | 摘要 |
|---|---:|---|---|
| **ASML**, **TSM**, **INTC**, **005930.KS** | **ASML** / **TSM** watchlist L3；**INTC** tracked context | High-NA / WFE / foundry economics | KP 認為 TSMC 不在 A16 / A14 / A13 量產導入 High-NA，把 ASML 2030 600 億歐元故事往後推 2-3 年；TSMC 的資本紀律與 low-NA multi-patterning / DTCO 能力被再次驗證。 |
| **ASTS**, **T**, **VZ** | **ASTS** watchlist L3 | Satellite D2D / regulation | BlueBird 7 發射失敗因保險、生產線與發射商多元化而影響有限；FCC SCS 商業執照才是關鍵，風險從監管是否通過轉為執行與 burn rate。 |
| **GOOG**, **GOOGL**, **AVGO**, **2454.TW**, **MRVL**, **TSM**, **INTC** | **GOOGL** tracked stock L3 | TPU / custom silicon / memory wall | Google TPU 8t / 8i 用更高 HBM、SRAM 與多供應商分工，讓 Google 從單純設計 TPU 轉為控制 memory stack、封裝、成本與供應鏈的系統定義者。 |
| **INTC**, **TSLA**, **AMD**, **ARM**, **NVDA**, **TSM** | **INTC** tracked stock L3 | DCAI / Foundry / 14A / packaging | Intel Q1 beat、DCAI +22%、18A 良率提前、14A PDK 進度、Tesla TeraFab 口徑與先進封裝訂單，讓敘事從「能不能做」轉向「什麼時候做成」；但 Foundry 外部收入仍只有 1.74 億美元且虧損高。 |
| **NOW**, **PANW**, **CRWD**, **CYBR** | **NOW** watchlist L3 | SaaS AI proof burden | ServiceNow beat and raise 但股價跌，KP 認為核心是市場需要看到 AI revenue、cRPO、retention、margin 與 consumption pricing 連續驗證，而非只聽 AI tailwind 敘事。 |
| **JPM**, **BX**, **APO**, **ARES**, **OWL**, **BLK** | **JPM** watchlist L3 | Private credit / bank origination | JPM 一邊警告私募信貸，一邊用商業銀行 origination 與機構資金建立自家 private-credit 平台；KP 將其解讀為私募信貸第三波：大銀行帶著資產負債表與風控回場。 |

## 開場：18 連漲後仍回到正確資產

KP 先談停戰後市場快速反彈，半導體指數連續 18 個交易日上漲。他承認自己曾判斷最壞情況大概率過去，但沒有預測到這種速度。重點不是猜下一天漲跌，而是長期持有正確底層資產、理解產業邏輯，避免被短期 FOMO 或回調牽著走。

### 框架：長線樂觀 / 正確標的研究框架

- **定義**：短線高點與回調很難精準預測，長期報酬更依賴底層資產品質、研究深度與持有時間。
- **適用情境**：relief rally、FOMO 追價焦慮、錯過反彈後的再進場壓力。
- **觀察指標**：thesis clarity、business quality、earnings power、position sizing、drawdown tolerance、cash / leverage、錯誤條件。

## 主題一：TSMC 不買 High-NA 與成本有效摩爾定律

KP 解讀台積電再次表態不在 A16 / A14 / A13 量產使用 ASML High-NA EUV。High-NA 技術上能一次印出更細線寬，但單機約 4 億歐元、曝光區域只有低 NA 一半，大型 GPU / AI chip 需要拼接，單次曝光成本約低 NA 的 2-2.5 倍。

KP 認為台積電不是不懂 High-NA，而是用成熟低 NA EUV、multi-patterning 與 DTCO 達成夠用良率 / 效能時，沒有必要替 ASML 攤提昂貴研發成本。10 台 High-NA 就是約 40 億歐元，若投到現有產能、CoWoS、SoIC，邊際效益可能更高。

對 ASML，短期低 NA 仍受 AI demand 支撐，2026 / 2027 舊款機台量仍可強；但中期 High-NA 高毛利爆發期延後，2030 年 600 億歐元營收目標需要打問號。KP 的核心判斷是：摩爾定律從「誰能做更小電晶體」轉向「誰能用最低成本做出夠用電晶體」。

### 框架：High-NA 延後 / 成本有效摩爾定律框架

- **定義**：leading-edge winner 不只比技術極限，更比良率、成本、ROIC 與供應穩定性；最先進工具若不具經濟性，採用可被延後。
- **適用情境**：ASML High-NA、TSMC / Intel / Samsung 製程競爭、AI accelerator foundry economics、WFE cycle。
- **觀察指標**：High-NA order / delivery、low-NA EUV 出貨、multi-patterning / DTCO 能力、CoWoS / SoIC capex、ASML 2030 target、TSMC gross margin / ROIC、Intel 14A yield。

## 主題二：ASTS 一顆衛星失敗，FCC 執照更重要

AST SpaceMobile 的 BlueBird 7 因 Blue Origin New Glenn 第三次發射問題未進入預定軌道。KP 認為單顆衛星損失比市場想像小：衛星有保險、生產線未停，BlueBird 8-10 接近完成，8-32 在不同生產階段，目標 2026 年底前每月 6 顆；發射商也有 SpaceX Falcon 9、印度 LVM3、Blue Origin New Glenn 等備援。

真正關鍵是 2026-04-21 FCC SCS 商業執照。這讓 ASTS 可合法使用 AT&T / Verizon 低頻頻譜與普通手機連線，解鎖 Verizon 剩餘 4,500 萬美元商業預付款與 FirstNet 里程碑付款，也讓海外電信商更容易把 MOU 升級為正式合約。

KP 的結論是：ASTS 仍是高風險故事，但風險已從「監管會不會過」變成「能不能執行、燒錢多快」。接下來要看 2026 年底 45 顆衛星、第一個商業收入與實際手機通話。

### 框架：監管執照 > 單次發射 / 太空執行風險重分類框架

- **定義**：太空通訊公司若已取得核心商業執照，單次發射失敗的投資含義會低於產能、保險、發射多元化與商業化節奏。
- **適用情境**：AST SpaceMobile、Starlink D2D、衛星星座部署、pre-revenue infrastructure。
- **觀察指標**：FCC / SCS license、MNO agreements、satellite production cadence、launch provider mix、insurance coverage、commercial revenue、cash burn。

## 主題三：Google TPU 8 與系統定義者

Google 2026-04-22 發表 TPU 8，分成訓練版 TPU 8t Sunfish 與推理 / agent 版 TPU 8i Zebrafish。KP 認為市場不該只看 performance-per-watt，而要看記憶體牆與供應鏈設計。

TPU 8t Superpod 達 9,600 顆晶片、121 exaFLOPS；TPU 8i 用 Boardfly topology 降低全域同步延遲。記憶體方面，TPU 8t 每顆 216GB HBM、Superpod 2PB shared memory；TPU 8i 每顆 288GB HBM，on-chip SRAM 是前代 3 倍，pod HBM capacity 從 49TB 跳到 331TB。KP 認為這強化 HBM supercycle 與 inference memory hierarchy thesis。

供應鏈上，KP 將 Google 的分工解讀為系統控制：Broadcom 負責高難度 TPU 8t full-package design / memory / packaging，MediaTek 負責高量 TPU 8i 以降低 20-30% 成本，Marvell 參與記憶體處理單元，Intel 提供 CPU / infrastructure 支援。重點是 Google 自己控制每條產品線的 cost / pricing / supply structure。

對 **GOOGL**，這是 L3：Google 已從晶片設計者升級為「系統定義者」。單位成本、Cloud margin、供應風險、TSMC 2nm 議價力與 Gemini / agent 推理經濟性，都要一起追。

### 框架：TPU 系統定義者 / 記憶體牆供應鏈控制框架

- **定義**：AI 基建競爭從單顆晶片性能擴大到 HBM / SRAM、互連、封裝、供應商分工、成本與議價權的系統級控制。
- **適用情境**：Google TPU、hyperscaler custom ASIC、Gemini inference、2nm / HBM / SRAM capacity planning。
- **觀察指標**：HBM per chip / pod、on-chip SRAM、cost per token、Cloud margin、Broadcom / MediaTek / Marvell split、TSMC 2nm capacity、Gemini latency。

## 主題四：Intel 轉機敘事升級，但 Foundry 還要證明

Intel Q1 營收 136 億美元，超過市場預期 124 億美元；調整後 EPS 0.29 美元，市場預期 0.01 美元。DCAI 營收 51 億美元，年增 22%，比預期高約 7 億美元。KP 將其解讀為供應問題改善與 AI inference / agentic architecture 讓 CPU 回到 control plane 的雙重驗證。

Foundry 的故事更複雜：營收 54 億美元、q/q +20%、y/y +16%，但外部客戶收入只有 1.74 億美元，營業虧損仍 24 億美元。市場興奮點在良率：Intel 4 / 3 / 18A yield 均優於預期，18A 進度提前 3-6 個月。

14A 是決戰點：Intel 第一個大規模 High-NA advanced logic node，第二代 RibbonFET、PowerDirect backside power，目標比 18A perf/watt +15%-20%、density +30%。Intel 也說若沒有大型外部客戶，14A 後先進節點可能暫停或取消。KP 特別記錄 Elon Musk 在 Tesla 電話會上稱 TeraFab 將採用 Intel 14A；這是高能見度外部客戶背書，但訂單金額與時程仍不清楚。

另一條快一點的收入線是先進封裝：CFO David Zinsner 稱潛在收入規模從數億美元提高到每年數十億美元，並擴建 Penang 後端設施，2027 年起貢獻。KP 認為封裝毛利較高、capex 較低、訂單轉 revenue 更快，可能在外部先進製程收入真正起飛前先支撐 Foundry narrative。

### 框架：CPU 現金牛 + Foundry 選擇權 / 轉機股執行階梯框架

- **定義**：Intel 轉機可被拆成 DCAI / CPU 現金流、18A 良率、14A 外部客戶、先進封裝收入與 Foundry 虧損收斂的階梯；敘事升級不等於執行完成。
- **適用情境**：turnaround semiconductor、IDM / foundry transition、AI inference CPU cycle、advanced packaging optionality。
- **觀察指標**：DCAI revenue、server CPU shipment、Foundry external revenue、Foundry operating loss、18A yield / tape-out、14A PDK 1.0、Tesla / TeraFab terms、packaging orders / revenue。

## 主題五：ServiceNow 暴跌與 SaaS AI 證明題

ServiceNow Q1 營收 37.7 億美元超預期，subscription revenue +22%，EPS 超預期，全年 subscription guidance 上修，AI revenue target 從 10 億美元提高到 15 億美元，但股價仍暴跌。KP 認為原因不是單一財報數字，而是市場對 AI 時代 SaaS moat 的信任被調低。

短期因素包括中東 / 伊朗衝突延遲本地部署訂單，拖累 subscription growth 約 0.75pp；Armis 77.5 億美元收購導致整合成本與 margin guide 下調。但核心是 AI 焦慮：企業客戶興奮但混亂，市場要求 ServiceNow 證明 Now Assist、AI Control Tower、Context Engine 與 22 年 workflow data 能帶來可見再加速，而不是只是補舊業務流失。

KP 記錄 Now Assist >100 萬美元 ACV 客戶 +130%、multi-product deals +70%、AI Control Tower deal value q/q 翻倍、>50% 新業務轉向非席位 / consumption-based model。但 Q2 organic cRPO guide 17%-18%，較市場期待低，retention 微降至 97%，Armis 稀釋 margin。結論是：ServiceNow 可能有 moat，但市場要連續 3-4 季數據才願意付更高估值。

### 框架：SaaS AI 證明題 / 數據與敘事落差框架

- **定義**：AI 時代的 SaaS 巨頭不能只宣稱自己是 AI 受益者，必須用 cRPO、AI revenue、usage pricing、retention 與 margin 證明 AI 是淨增量。
- **適用情境**：ServiceNow、Salesforce、SAP、enterprise workflow software、agentic AI disruption。
- **觀察指標**：subscription growth、cRPO、AI ARR / revenue、consumption mix、retention、op margin、M&A dilution、workflow data moat、model-vendor competition。

## 主題六：JPM 警告私募信貸，卻自己進場

Jamie Dimon 多次警告私募信貸市場：信用標準鬆、covenant 弱、估值不透明、PIK interest 滾雪球。但 JPM Asset Management 2026-04-23 宣布大舉進軍私募信貸。KP 將這解讀為 JPM 的標準操作：公開警告行業風險，同時用更好的 underwriting、deal flow 與機構資金去賺機會。

JPM 的差異在於 commercial bank origination。純 private-credit funds 需要找案子，JPM 自家商業銀行每天面對中型企業授信需求，可把貸款打包成 asset-management products。放貸與管錢在同一公司，資訊流、風控與定價更統一。

KP 區分 retail / HNW 半流動私募信貸基金的贖回壓力與機構鎖定資本。前者約 2,500 億美元是新聞中的流動性錯配；整體市場接近 2 兆美元，約 80% 是 pensions、insurers、sovereign wealth 等機構長錢。JPM 目標是機構，不是容易恐慌贖回的 retail wrapper。

KP 將私募信貸分三波：第一波純私募信貸基金搶中型企業貸款；第二波散戶資金湧入帶來半流動性錯配；第三波大銀行帶著資產負債表、origination 與機構客戶關係回場。私募信貸回到本質：信用審核與資金成本。

### 框架：銀行回歸私募信貸 / Origination Advantage 框架

- **定義**：私募信貸第三波不是所有玩家一起擴張，而是大銀行用商業銀行 origination、機構資金與風控流程，重新取得低成本 deal flow 與 underwriting 優勢。
- **適用情境**：JPM private credit platform、banks vs private-credit funds、semi-liquid credit funds、retail redemption stress。
- **觀察指標**：fund AUM、commercial-bank origination、institutional vs retail mix、redemption gates、credit losses、collateral haircuts、PIK exposure、spread / cost of capital。

## 對已追蹤個股的同步判定

- **INTC**：L3；本文直接討論 Intel Q1、DCAI、Foundry、18A / 14A、Tesla TeraFab 與先進封裝，已同步 `Stocks/INTC/quarterly/INTC_筆記_2026Q2.md`、`INTC_index.md`、`INTC_儀表板.md`。
- **GOOG / GOOGL**：L3；本文直接討論 TPU 8、HBM / SRAM、Broadcom / MediaTek / Marvell 分工、TSMC 2nm bottleneck 與 Google Cloud margin / TCO，已同步 `Stocks/GOOGL/quarterly/GOOGL_筆記_2026Q2.md`、`GOOGL_index.md`、`GOOGL_儀表板.md`。
- **AMZN / AMKR / IBM / LRCX / VRT**：本文未形成正式同步門檻，不更新對應 `Stocks/`。
- **ASML**, **TSM**, **ASTS**, **NOW**, **JPM**：更新 watchlist / ticker / catalyst；暫不建立正式 `Stocks/` 專案。

## 後續追蹤清單

| 時間 / 頻率 | 追蹤事件 | 相關 ticker | 重點 |
|---|---|---|---|
| 2026-2029 | TSMC / ASML High-NA adoption and A13 / A14 / A16 node economics | **ASML**, **TSM**, **INTC** | TSMC 是否維持不量產 High-NA、ASML low-NA / High-NA order mix、Intel 14A 高 NA 良率與 cost |
| 2026 | ASTS FCC SCS commercialization and satellite cadence | **ASTS**, **T**, **VZ** | Verizon 4,500 萬美元 prepayment、FirstNet milestones、45 satellites by YE2026、commercial revenue、cash burn |
| 每季 | Google TPU 8 memory stack and supplier split | **GOOG**, **GOOGL**, **AVGO**, **2454.TW**, **MRVL**, **TSM** | HBM / SRAM、Broadcom / MediaTek / Marvell workload split、cost per token、Cloud margin、2nm capacity |
| 2026H2-2029 | Intel 18A external tape-out, 14A PDK and Tesla TeraFab | **INTC**, **TSLA**, **TSM**, **ASML** | 18A 外部客戶、14A PDK 1.0、Tesla order terms、Foundry external revenue、Foundry loss、packaging revenue |
| 每季 | ServiceNow AI proof and Armis integration | **NOW**, **PANW**, **CRWD**, **CYBR** | cRPO、AI revenue、Now Assist / AI Control Tower adoption、retention、consumption mix、operating margin |
| 每季 | JPM private-credit origination platform | **JPM**, **BX**, **APO**, **ARES**, **OWL**, **BLK** | institutional AUM、commercial-bank origination、credit quality、retail fund redemption stress、collateral haircuts |

## 資料品質與限制

- 本文整理自 FOMOSoc Substack 公開文章的 Jina Reader Markdown，未另存 raw；URL 可回溯來源。
- 原文包含多個公司事件、財報、供應鏈報告與新聞的 KP 口徑轉述；本整理未逐一外部查驗，後續進入單股深度或財報驗證時需用 official filings / press release 校準。
- 本整理只記錄 KOL 觀點與投資框架，不構成買賣建議。
