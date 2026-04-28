# Lam Research **LRCX** Q3 2026 財報分析

- **KOL**：大叔美股筆記
- **來源**：[大叔美股筆記 Substack](https://unclestocknotes.substack.com/p/lam-research-lrcx-q3-2026)；[Lam Research official FY2026 Q3 results](https://investor.lamresearch.com/2026-04-22-Lam-Research-Corporation-Reports-Financial-Results-for-the-Quarter-Ended-March-29%2C-2026?asPDF=)
- **類型**：Substack 文章 / 財報分析 / 半導體設備 / 記憶體設備 / AI 硬體底層
- **發文時間**：2026-04-24（使用者提供 PDF / Substack 登入頁面顯示 Apr 24, 2026；公開未登入頁面顯示 Apr 23, 2026，可能為時區差異）
- **整理日期**：2026-04-28
- **原始檔案 / URL**：https://unclestocknotes.substack.com/p/lam-research-lrcx-q3-2026；本機原始路徑見 `private/raw_manifest.local.yaml`（未同步）
- **source_id**：大叔美股筆記-20260424-lam-research-lrcx-q3-2026-0726485d
- **raw 路徑 / URL**：`KOL/大叔美股筆記/raw/20260424_大叔美股筆記_lam_research_lrcx_q3_2026_大叔美股筆記-20260424-lam-research-lrcx-q3-2026-0726485d.pdf`
- **OCR 狀態**：部分（8 頁 image-only Substack 截圖 PDF；p.1-p.6 上半為核心正文、links 與免責聲明，p.6 下半起為 discussion / recommended posts / footer；頁面影像清楚，無文字層，核心數字以視覺讀取與 Lam official PR 校準）
- **相關 ticker**：**LRCX**, **NVDA**, **MU**, **INTC**, **TSM**, **GOOG**, **GOOGL**, **005930.KS**, **000660.KS**
- **主題 tags**：#財報 #半導體設備 #Memory #AI基建 #估值風險

## 主旨

大叔把 Lam Research 2026 財年第三季解讀成「Double Beat + Raise」與 AI 驅動 WFE 上行循環中段的驗證。文章核心不是單季財報 beat，而是把 **LRCX** 的刻蝕、沉積、TSV、3D NAND / HBM 與 GAA 製程設備放進「AI 從算力轉向記憶體與儲存密度升級」的底層架構裡。

這篇是 **LRCX** L3 主題個股文，並將 **LRCX** 升級為正式追蹤個股。大叔立場是隱含偏多 / 長期核心持有候選，但同時提醒短期仍有中國市場需求正常化、地緣政治與高估值壓縮風險；本文不是買賣建議。

## Ticker 分流

| Ticker | 文章角色 | 交會等級 | 動作 | 理由 |
|---|---|---|---|---|
| **LRCX** | 主角 / 半導體設備與 AI 記憶體製程底層 | L3 | KOL 長文獨立整理；建立 `Stocks/LRCX/` 專案、季度筆記、儀表板與 index | 整篇圍繞 **LRCX** Q3 財報、Q4 指引、NAND / HBM / GAA / 先進封裝、DCF 情境估值與風險 |
| **NVDA**, **GOOG**, **GOOGL** | AI GPU / TPU / ASIC 算力需求背景 | L1 | ticker index | 文章用 NVIDIA GPU、Google TPU 與自研 AI 晶片說明 HBM / TSV 與製程複雜度，不形成這些 ticker 的獨立 thesis |
| **MU**, **005930.KS**, **000660.KS** | HBM / DRAM / NAND 客戶群或受益脈絡 | L1 | ticker index | 文章提到 Micron、Samsung、SK Hynix 是 HBM / DRAM 設備需求來源，但主旨仍是 **LRCX** 設備銷售 |
| **INTC**, **TSM** | GAA / foundry 先進製程客戶脈絡 | L1 | ticker index | 文章提到台積電、Intel 推進 2nm 以下製程與 GAA，作為 **LRCX** selective etch / ALD 需求背景 |

## 官方校準

| 項目 | 大叔文章 / PDF 口徑 | Lam official PR 校準 | 整理者處理 |
|---|---|---|---|
| Q3 revenue / EPS | Revenue `58.4 億美元`；Non-GAAP EPS `$1.47` | Revenue `$5.841B`；Non-GAAP EPS `$1.47` | 一致，作為財報基準 |
| Q3 margin | Non-GAAP gross margin `49.9%`；operating margin `35.0%` | Non-GAAP gross margin `49.9%`；operating margin `35.0%` | 一致，作為財報基準 |
| Q4 revenue / EPS guide | Revenue `62 億` 至 `70 億美元`，中位數 `66 億美元`；EPS `$1.50` 至 `$1.80`，中位數 `$1.65` | Revenue `$6.60B +/- $400M`；EPS `$1.65 +/- $0.15` | 一致，作為財報基準 |
| Q4 gross / operating margin guide | PDF 視覺讀取有不一致風險 | Official PR：gross margin `50.5% +/- 1%`；operating margin `36.5% +/- 1%` | margin 指引用 official PR，不把 OCR / 圖像疑似讀值寫成結論 |
| 區域營收 | PDF / 圖表寫中國 `42%`、韓國 `18%`、台灣 `13%` | Official PR：China `34%`、Korea `23%`、Taiwan `23%`、Japan `8%`、U.S. `6%`、Southeast Asia `4%`、Europe `2%` | 區域比例以 official PR 作財報基準；PDF 口徑保留為待核對，不外推成官方數字 |

## 結構化分析

| 面向 | 大叔整理的重點 | 對 **LRCX** thesis 的含義 | 追蹤重點 |
|---|---|---|---|
| 財報雙擊 | Q3 revenue `58.4 億美元`，季增 `9%`；Non-GAAP EPS `$1.47`；Q4 revenue midpoint `66 億美元`、EPS midpoint `$1.65` | 大叔認為財報已從 cyclical recovery 進入 AI 驅動的 WFE 上行循環中段 | Q4 revenue / EPS / margin 是否兌現，H2 revenue 是否高於 H1 |
| 系統設備與 CSBG | Systems revenue 受 AI server high-capacity enterprise SSD、HBM 與記憶體 capex 重啟拉動；CSBG 提供設備升級、耗材與維護 recurring revenue | 新設備與客戶支援雙輪驅動，降低單一系統出貨波動 | Systems / CSBG mix、deferred revenue、Japan acceptance revenue |
| NAND | AI inference、多模態 AI 與 enterprise SSD 帶動高容量儲存；Cryo 3.0 是 3D NAND 往 300 層 / 400 層推進的關鍵刻蝕技術 | NAND 復甦不是單純價格週期，而是 AI 儲存密度升級帶來的 process intensity 增加 | NAND capex、300+ layer transition、Cryo 3.0 adoption |
| DRAM / HBM | HBM 需要 TSV 堆疊 DRAM；Lam 的 Syndion 刻蝕與 SABRE 3D 電鍍設備受惠於 Samsung、SK Hynix、Micron 的 HBM 擴產 | AI GPU / TPU / ASIC 的 HBM 需求把 **LRCX** 拉進 AI 記憶體供應鏈 | HBM capacity, TSV tools, memory customer capex |
| Foundry / Logic | GAA 需要 selective etch 與 ALD，台積電 / Intel 等先進製程節點推升資本密集度 | GAA transition 讓 **LRCX** 不只受 memory cycle 影響，也受 foundry process complexity 拉動 | 2nm / below ramp、GAA yields、selective etch / ALD share |
| 先進封裝 | 2.5D / 3D packaging 延續算力成長；dry resist 與高深寬比金屬化設備市佔提升 | 先進封裝讓 **LRCX** 的設備機會從 wafer process 延伸到 packaging intensity | Advanced packaging capex, CoWoS / HBM stack demand |
| 地緣與區域 | 中國需求仍重要，但 export controls 限制先進設備；成熟製程、IoT、車用半導體與美歐本土 fab 建設提供再平衡 | 中國是風險與現金流來源；美歐 CHIPS / 在地化是後續接力 | Export controls, China mix, U.S. / Europe fab tool migration |

## 價位與催化劑

| Ticker | 價位 | 價位性質 | 來源 / 說話者 | 時間 | 備註 |
|---|---|---|---|---|---|
| **LRCX** | `$270` | 大叔估值計算使用的文章當下股價 / 事件價位 | 大叔文章 | 2026-04-24 | 非目標價 |
| **LRCX** | FY2026 EPS `$6.20` 至 `$6.50` | 大叔估值假設 | 大叔文章 | 2026-04-24 | 以 `$6.35` 估 forward P/E 約 `42.5x` |
| **LRCX** | Forward P/E 約 `42.5x` | 估值倍數 | 大叔文章 | 2026-04-24 | 大叔認為偏貴，但可由 3D NAND / HBM 核心地位解釋部分溢價 |
| **LRCX** | Forward P/S 約 `12.8x` | 估值倍數 | 大叔文章 | 2026-04-24 | 以全年 revenue 約 `$25B` 與 market cap 約 `$322.195B` 推算 |
| **LRCX** | `$180.00` 至 `$210.00` | DCF 悲觀情境內在價值 | 大叔文章 | 2026-04-24 | 中國營收斷崖、Edge AI 換機落空、HBM 供給過剩 |
| **LRCX** | `$250.00` 至 `$265.00` | DCF 基準情境內在價值 | 大叔文章 | 2026-04-24 | NAND 300 層轉換順利、HBM 需求延續 |
| **LRCX** | `$310.00+` | DCF 樂觀情境內在價值 | 大叔文章 | 2026-04-24 | AI 手機 / PC 換機潮與 GAA 刻蝕需求超預期 |

| 日期 | 事件 | 相關 ticker | 影響方向 | 追蹤重點 | 出處 |
|---|---|---|---|---|---|
| 2026-06-28 | Lam FY2026 Q4 quarter ending，回頭檢查 Q4 guide | **LRCX** | 正面若兌現 / 上修 | Revenue `$6.60B +/- $400M`、gross margin `50.5% +/- 1%`、operating margin `36.5% +/- 1%`、EPS `$1.65 +/- $0.15` | Lam official PR / 大叔文章 |
| 2026H2-2027 | 美歐在地化晶圓廠建設與設備移入 | **LRCX**, **INTC**, **TSM** | 正面若轉成 equipment order / shipment | CHIPS Act / EU subsidy, fab tool move-in, customer acceptance, export controls | 大叔文章 |
| 2026-2027 | 300+ 層 NAND、HBM / TSV 與 GAA 節點推進 | **LRCX**, **MU**, **005930.KS**, **000660.KS**, **TSM**, **INTC** | 正面若 capex 延續 | NAND conversion, TSV capacity, selective etch / ALD demand, memory pricing | 大叔文章 |
| 2026 年底起（推估） | Edge AI PC / AI 手機換機潮是否提高終端矽含量與記憶體容量 | **LRCX**, **NVDA**, **GOOG**, **GOOGL** | 未定 | Device launch, memory content, NAND / DRAM demand, equipment bookings | 大叔文章 |

## 核心框架 / 心法

- **製程複雜度等於營收確定性**：AI 不只是買更多晶片，而是讓每片晶圓需要更多刻蝕、沉積、TSV、ALD、GAA 與封裝步驟；製程越複雜，**LRCX** 的單位晶圓設備用量越高。
- **AI 從 compute 轉向 storage / bandwidth**：早期 AI 焦點在 GPU 算力，現在 bottleneck 延伸到 HBM、NAND、enterprise SSD 與資料吞吐，讓記憶體設備重新變成 AI 供應鏈核心。
- **區域營收再平衡**：中國短期提供高營收但帶來 export-control 風險；美歐 fabs 與韓台 memory / foundry capex 是未來數季接力來源。

## 關鍵證據

| 證據 | 出處 | 解讀 |
|---|---|---|
| Q3 revenue `58.4 億美元`、Non-GAAP EPS `$1.47`、Q4 revenue guide midpoint `66 億美元` | 大叔文章 p.1；Lam official PR | 財報與指引同時超預期，是大叔認定上行循環的第一層證據 |
| Non-GAAP gross margin `49.9%`、operating margin `35.0%` | 大叔文章 p.1-p.2；Lam official PR | 高毛利與營益率顯示設備公司在復甦期有定價與營運槓桿 |
| Memory revenue share `42%`、其中 NAND `24%`、DRAM `18%`（PDF 口徑） | 大叔文章 p.2-p.3 | 大叔將 **LRCX** 的需求核心放在 NAND recovery 與 HBM / DRAM capex；比例與 official geography 不同，需區分 |
| Foundry / Logic `58%`（PDF 口徑）與 GAA / selective etch / ALD | 大叔文章 p.3 | 文章把 **LRCX** 拉出單純 memory cycle，連到先進製程複雜度 |
| DCF 基準 `$250` 至 `$265`、樂觀 `$310+`、悲觀 `$180` 至 `$210` | 大叔文章 p.5 | 價位是 KOL 情境估值，不是本專案建議 |

> 大叔（2026-04-24, 《Lam Research **LRCX** Q3 2026 財報分析》, p.1）：「AI 硬體時代的底層架構師」

> 大叔（2026-04-24, 《Lam Research **LRCX** Q3 2026 財報分析》, p.5）：「AI 價值鏈的核心底盤」

## 風險與反例

| 風險 | 相關 ticker | 風險等級 | 觸發條件 | 觀察指標 | 出處 |
|---|---|---|---|---|---|
| 中國市場正常化與 export controls | **LRCX** | 高 | 中國成熟製程 capex 降溫，或美國出口管制擴大 | China revenue mix、restricted products、customer capex、deferred revenue | 大叔文章 / Lam official PR |
| 記憶體 capex 周期反轉 | **LRCX**, **MU**, **005930.KS**, **000660.KS** | 高 | NAND / DRAM pricing 回落，HBM 供給過剩或 customer capex 削減 | NAND price、HBM supply-demand、memory customer capex、WFE spend | 大叔文章 |
| Edge AI 換機潮落空 | **LRCX**, **NVDA**, **GOOG**, **GOOGL** | 中高 | AI PC / smartphone 出貨未拉升記憶體容量與 NAND / DRAM demand | Device shipments、memory content per device、AI PC / phone adoption | 大叔文章 |
| GAA / 先進製程節點延後 | **LRCX**, **TSM**, **INTC** | 中高 | 2nm / below 節點 ramp 或 GAA yield 進度不如預期 | Foundry capex、GAA ramp、selective etch / ALD demand | 大叔文章 |
| 高估值壓縮 | **LRCX** | 高 | FY2026 EPS / FCF 或 HBM / NAND demand 無法支撐約 `42.5x` forward P/E | EPS, FCF, forward P/E, WFE outlook, order visibility | 大叔文章 |
| PDF 口徑與官方數字差異 | **LRCX** | 中 | 把 PDF 中中國 `42%` 等比例或疑似 OCR / 圖像數字直接當 official baseline | Lam official PR, 10-Q / 8-K, slides | 整理者校準 |

## 延伸追蹤

| 日期 | 事件 | 相關 ticker | 影響方向 | 追蹤重點 | 出處 |
|---|---|---|---|---|---|
| 2026-06-28 | FY2026 Q4 quarter ending | **LRCX** | 未定 | Revenue / margin / EPS guide 是否兌現；H2 是否高於 H1 | Lam official PR / 大叔文章 |
| 2026H2-2027 | 美國 / 歐洲 fab tool move-in 與中國需求正常化 | **LRCX** | 未定 | 區域 mix、export controls、成熟製程 vs 先進設備、customer acceptance | 大叔文章 |
| 2026-2027 | 300+ layer NAND、HBM TSV、GAA / ALD / selective etch capex | **LRCX** | 正面若延續 | Memory capex、foundry capex、bookings、systems revenue、CSBG revenue | 大叔文章 |

## 整理者延伸

這篇和 `KOL/大叔美股筆記/articles/20260426_next_gen_ai_datacenter_cpo_silicon_photonics_uncle.md` 呼應：CPO / 矽光子那篇處理 AI data center 資料搬運瓶頸，本文則補上 memory / storage / wafer process intensity 的設備端受益者。

這篇也呼應 `KOL/Bytc/articles/20260124_tax_reform_code_to_capacity.md`：Bytc 先前把 **LRCX** 放進 48D / advanced manufacturing investment credit 的設備鏈，本篇大叔把 **LRCX** 從政策 / capex supply-chain mapping 升級為單股財報與技術護城河 thesis。
