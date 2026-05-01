# SNDK 投資儀表板

> 最後更新：2026-05-01（由大叔 2026-05-01 SNDK fiscal Q3 長文升級為正式 `Stocks/SNDK/`；歷史回查補入 KP HBF、Melius re-rating 與 Samsung supply-risk 三筆 L2+ 前史）

## 當前立場快照

- **綜合立場**：**SNDK** 的追蹤核心是「AI storage infrastructure + NBM 長約」。大叔認為 SanDisk 正從 NAND 景氣循環股轉向 AI infrastructure storage capacity supplier。
- **大叔最新立場**：偏多 L3；重點是 fiscal Q3 revenue `$5.950B`、non-GAAP gross margin `78.4%`、datacenter revenue `$1.467B` / q/q +233%、FQ4 guide `$7.75B-$8.25B` revenue 與 `$30-$33` non-GAAP EPS。
- **資料限制**：大叔原文來自 10 頁 image-only Substack 截圖 PDF，OCR 狀態標「部分」；核心正文 p.1-p.7 人工檢視完整，p.8-p.10 comments / footer 不作 KOL 觀點。

## 關鍵數字追蹤

| 類型 | 數字 | 來源 | 解讀 |
|---|---|---|---|
| FQ3 revenue | `$5.950B` | SanDisk official / 大叔文章 | q/q +97%、y/y +251%，超過 guide。 |
| GAAP / non-GAAP EPS | `$23.03` / `$23.41` | SanDisk official | `$23.41` 是 non-GAAP diluted EPS，不可寫成 GAAP。 |
| Gross margin | `78.4%` | SanDisk official | AI storage / NBM re-rating 的核心品質指標。 |
| Datacenter revenue | `$1.467B` / q/q +233% | SanDisk official | AI infrastructure demand 直接證據。 |
| Adjusted FCF | `$2.955B` | SanDisk official | 大叔「cash flow machine」敘事支點。 |
| Long-term debt | `$0` | SanDisk official | spin-off 後 balance sheet 重置。 |
| FQ4 revenue guide | `$7.75B-$8.25B` | SanDisk official | 下一個高強度驗證點。 |
| FQ4 non-GAAP EPS guide | `$30-$33` | SanDisk official | 大叔年化 EPS 模型的來源。 |
| Share repurchase authorization | `$6B` | SEC 8-K | 不代表保證執行；timing 取決於 market conditions。 |

## 目前母題

| 母題 | 當前判斷 | 主要來源 | 後續追蹤 |
|---|---|---|---|
| NBM 長約 | 3 份 FQ3 signed agreements + FQ4 2 份新 agreement，使收入可見度與 pricing power 高於傳統 NAND cycle | 大叔 / SanDisk official | agreement 數量、customer commitments、contract liabilities、renegotiation |
| Enterprise SSD / TLC | AI inference 的 KV cache / local NVMe demand 讓 high-end TLC enterprise SSD 具定價權 | 大叔 / KP HBF 前史 | Datacenter revenue、TLC / QLC mix、ASP、AI server storage attach |
| Zero debt + buyback | 零長債與 `$6B` repurchase authorization 讓 FCF 可轉成資本回報 | 大叔 / SanDisk official / SEC 8-K | buyback pace、share count、cash、FCF |
| HBF / memory hierarchy | KP 前史將 SanDisk 放在 HBM 與 SSD 中間層 optionality | KP / FOMOSoc | OCP standard、Nvidia design-in、SK Hynix roadmap |
| Memory supply tightness | Melius / Samsung union 前史補強 NAND / AI data demand 與 supply-risk sentiment | 大叔 / Melius / SemiAnalysis | NAND pricing、competitor capacity、Samsung labor event |

## 關鍵風險清單

| 風險 | 等級 | 觀察指標 | 來源 |
|---|---|---|---|
| NBM 長約 renegotiation | 高 | 客戶 capex cuts、contract language、customer concentration | 大叔 |
| Gross margin 回落 | 高 | non-GAAP gross margin、ASP、competitor high-end TLC capacity | 大叔 / 整理者 |
| AI architecture 變化 | 中高 | KV cache reliance、CXL / memory expansion、DRAM / pooled memory adoption | 大叔 / 整理者 |
| 高基期與 multiple compression | 高 | revenue growth deceleration、EPS revision、P/E | 大叔 |
| 口徑混淆 | 中 | GAAP vs non-GAAP EPS、annualized guide assumptions | 整理者 |
| Macro / liquidity pressure | 中高 | rates、risk appetite、fund flows、profit-taking | 大叔 |

## 近期追蹤

| 日期 / 區間 | 事件 | 追蹤重點 |
|---|---|---|
| 2026FQ4 | SanDisk FQ4 guide check | revenue `$7.75B-$8.25B`、gross margin `79%-81%`、non-GAAP EPS `$30-$33` |
| 每季 | NBM execution | signed agreements、contract liabilities、customer commitments、revenue visibility |
| 每季 | Datacenter enterprise SSD / TLC mix | datacenter revenue、TLC / QLC mix、enterprise SSD ASP、gross margin |
| 每季 | Capital return | `$6B` buyback execution、share count、cash、FCF |
| 2026-05-21 起（若未解決） | Samsung union event | NAND / DRAM supply impact、pricing、customer pull-in |
| 2026-2027 | HBF / memory hierarchy | OCP standard、Nvidia design-in、SK Hynix / SanDisk roadmap |

## 追蹤依據

| 來源 | 權重 | 對 thesis 的作用 | 路徑 |
|---|---|---|---|
| 大叔 2026-05-01 SNDK fiscal Q3 | 高 | 正式升級觸發；建立 NBM / AI storage / valuation scenario / risk map | `KOL/大叔美股筆記/articles/20260501_sandisk_sndk_2026_q3_uncle.md`；`Stocks/SNDK/quarterly/SNDK_筆記_2026Q2.md` |
| SanDisk official fiscal Q3 2026 release | 高 | 校準 revenue、EPS、gross margin、datacenter revenue、FQ4 guidance、FCF、debt | SanDisk official investor / newsroom |
| SEC 8-K 2026-04-30 | 高 | 校準 `$6B` repurchase authorization 與執行彈性 | SEC filing |
| KP 2026-02-28 HBF | 中 | 補強 SanDisk 在 AI memory hierarchy 的 product optionality | `Stocks/SNDK/quarterly/SNDK_筆記_2026Q1.md` |
| 大叔 2026-04-28 / 2026-04-30 前史 | 中 | 補強 memory re-rating 與 supply-risk sentiment | `Stocks/SNDK/quarterly/SNDK_筆記_2026Q2.md` |

## 索引

- `Stocks/SNDK/SNDK_index.md`
- `Stocks/SNDK/quarterly/SNDK_筆記_2026Q1.md`
- `Stocks/SNDK/quarterly/SNDK_筆記_2026Q2.md`
- `KOL/大叔美股筆記/articles/20260501_sandisk_sndk_2026_q3_uncle.md`
