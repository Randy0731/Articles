# #ONDS 估值模型全拆解

- **KOL**：大叔美股筆記
- **來源**：[Substack 原文](https://unclestocknotes.substack.com/p/onds-82f)；使用者提供網頁截圖 PDF；[Ondas 2026-01-16 官方新聞稿](https://ir.ondas.com/press-releases/detail/273/ondas-hosts-oas-investor-day-ups-2026-revenue-target-to)；[OAS Investor Event January 2026 PDF](https://d1io3yog0oux5.cloudfront.net/_6fb2f7340ac4fc701b5608d4e6f2d25e/ondas/db/575/4819/pdf/OAS+Investor+Event+January+2026.pdf)
- **類型**：Substack 付費文章 / Investor Day 估值模型 / DCF / 國防科技平台框架
- **發文時間**：2026-01-18（Substack metadata：2026-01-18T07:11:37+00:00；PDF 顯示 Jan 18, 2026）
- **整理日期**：2026-04-26
- **source_id**：大叔美股筆記-20260118-onds-valuation-model-82f-fe62dde1
- **raw 路徑**：`KOL/大叔美股筆記/raw/20260118_大叔美股筆記_onds_valuation_model_大叔美股筆記-20260118-onds-valuation-model-82f-fe62dde1.pdf`
- **OCR 狀態**：部分；PDF 為 6 頁 image-only 截圖，p.1-p.4 為核心正文 / 圖表 / 參考連結，p.5-p.6 為推薦文章與留言區，未寫成 KOL 觀點；Substack metadata 與 Ondas 官方 PR / investor deck 已交叉確認核心數字
- **相關 ticker**：**ONDS**
- **主題 tags**：#國防科技 #ReRating #估值風險 #執行風險 #稀釋風險 #增發融資 #空地一體 #DualUse

## 主旨

大叔把 Ondas 2026-01-16 OAS Investor Day 的財務指引、system-of-systems 戰略與 slide 59 的長期市值路徑拆成一套風險調整估值模型。核心結論是：若 2030 年 `$1.5B+` revenue 與 30% EBITDA margin 路徑可信，使用較保守的 20x EV/EBITDA、15% discount rate 與 4 億 fully diluted shares，可推得 2026 風險調整合理值約 `$14.25` / 股。

本專案將其記為 **ONDS** L4 估值模型里程碑。需要分清楚：`$14.25` 是大叔依假設推導出的風險調整合理值，不是公司 guidance、券商目標價或本專案買賣建議；官方 investor deck slide 59 寫的是 `$15+ billion market cap` path，而大叔文中的 DCF 用較保守口徑折到 2026 約 `$5.7B` equity value。

## 個股觀點

| 股票代號 | 立場 | 訊號強度 | 價位性質 | 備註 |
|---|---|---|---|---|
| **ONDS** | 看多 / thesis 強化 | 明確觀點 | `$14.25` 為大叔 DCF 風險調整合理值；`$20` 是 bullish sentiment / DDP 超預期突破情境與權證供給壓力區；`$16.45` 是前文 Jan 2026 機構成本參考；`$9-$12` 是大叔提到的平均成本區語境 | 大叔把 Investor Day 指引、現金、OAS 平台整合與 2030 財務目標串成 re-rating 模型，但同文列出 M&A、政府合約、warrant overhang 與 cash burn 風險 |

## Investor Day 重點

| 項目 | 數字 / 事件 | 大叔解讀 | 官方交叉確認 |
|---|---|---|---|
| 2025Q4 revenue estimate | `$27M-$29M` | 2025 年收尾超越原先預期 | Ondas 2026-01-16 PR 確認 |
| 2026 revenue target | `$170M-$180M` | 較先前 `$140M` 目標上修 25%，顯示 OAS / Roboteam / backlog 開始轉成 scale story | Ondas 2026-01-16 PR 確認 |
| Backlog | `$65.3M` at 2025-12-31，從 2025-11-13 `$23.3M` 增加 180% | 需求從意向轉成可追蹤訂單池 | Ondas 2026-01-16 PR 確認 |
| Pro forma cash | 超過 `$1.5B` | 支撐大叔的「cash fortress」與後續產業整合 / M&A thesis | Ondas 2026-01-16 PR 確認 |
| 2030 long-term target | revenue `$1.5B+`、EBITDA margin 30% | 估值模型的核心終局假設 | OAS investor deck p.59 確認 |
| 市值路徑 | 官方 slide 59 為 `$15+ billion market cap` path | 大叔另用 20x EBITDA 推出 2030 equity value 約 `$10B` 的保守情境 | OAS investor deck p.59 確認官方口徑；DCF 為 KOL 模型 |

## 系統之系統框架

| 能力層 | 資產 / 公司 | 大叔文中角色 | 後續驗證 |
|---|---|---|---|
| 空中 ISR / drone-in-a-box | American Robotics / Airobotics / Optimus | 24/7 自動化 ISR、critical infrastructure perimeter security、drone first responder | deployment count、Blue List 轉 task order、OAS revenue / margin |
| 地面機器人 | Roboteam / Apeiro Motion | 戰術 UGV、四足機器人、光纖線軸與抗干擾地面能力 | 2026 revenue、gross margin、existing orders 交付 |
| Counter-UAS soft kill | Sentrycs | Cyber-over-RF / protocol-layer takeover，負責非動能接管層 | 與 Iron Drone / Mistral / OAS 任務系統整合後的 program awards |
| Counter-UAS hard kill | Iron Drone Raider | 自主攔截 / 撒網捕捉，補上偵測後的硬殺層 | airport / military deployments、repeat orders、gross margin |
| 陸空即戰力艦隊 | ROBOX / Apeiro / OAS platform | 把空中與地面自主平台接成可部署任務包 | demo、合約、C2 integration、service / maintenance attach |

## DCF 估值模型

| 步驟 | 假設 / 公式 | 推導結果 | 風險標籤 |
|---|---|---|---|
| 2026 revenue base | `$170M-$180M` guidance midpoint | 約 `$175M` | guidance 需逐季驗證 |
| 2030 revenue | Investor Day target `$1.5B+` | 2026-2030 CAGR 約 71% | 高成長假設，仰賴 organic + M&A |
| 2030 EBITDA | `$1.5B * 30%` | `$450M` EBITDA | margin 需整合成功與 operating leverage |
| Exit multiple | 20x EV/EBITDA | 2030 EV 約 `$9B` | multiple 壓縮風險 |
| Net cash | 假設 M&A 消耗 `$1B` 後仍有 `$1B` net cash | 2030 equity value 約 `$10B` | cash deployment ROI / burn rate |
| Discount rate | 15% WACC | 2026 present value 約 `$5.7B` | 高風險折現仍可能不足 |
| Shares | 4 億 fully diluted shares | `$14.25` / 股 | warrant / M&A 對價股可能改變分母 |

## 價位與催化劑

| 類型 | 數字 / 日期 | 來源 | 正確讀法 |
|---|---|---|---|
| KOL 風險調整合理值 | `$14.25` | 大叔 DCF 模型 | 不是正式目標價、買點或本專案建議；取決於 `$5.7B` PV 與 4 億股假設 |
| bullish 情境 / 供給壓力區 | `$20` | 大叔文中情緒轉多、DDP 超預期或市場給 30x multiple 的情境 | 不是公司 guidance；也接近既有 warrant / 技術供給需留意 |
| 機構成本參考 | `$16.45` | 大叔前文 Jan 2026 financing | 事件成本與 KOL 推論錨，不是支撐線 |
| 平均成本區語境 | `$9-$12` | 大叔結論段 | KOL 個人語境；不可寫成建倉建議 |
| Investor Day | 2026-01-16 | Ondas 官方 PR / deck | 已發生；提供 revenue target、cash、backlog 與 2030 path |
| DDP / Initial DoW orders | 2026-02（原文催化劑語境） | 大叔文 | 待官方文件與實際 order 驗證；原文用 DoW / DDP，術語與日期需後續核對 |
| EBITDA positive checkpoint | 2026Q3 product company layer | OAS deck / 大叔風險段 | 若未如期轉正，會削弱 margin / DCF 假設 |

## 大叔結論與框架

| 框架 | 大叔邏輯 | 本專案記錄方式 |
|---|---|---|
| Cash floor | `$1.5B+` cash 讓下行具硬資產支撐 | 記為 KOL inference；cash 可能被 M&A / burn 消耗，不保證股價 floor |
| Defense integrator upside | 若 DDP 落地、M&A 成功，**ONDS** 有機會成為 multi-domain defense autonomy integrator | 記為 L4 thesis 升級；需用 orders、revenue、gross margin、OCF 與 integration demo 驗證 |
| 左側布局語境 | 大叔認為在 cash cost zone / below 可分批看待 | 只保留為 KOL 個人觀點，不寫成本專案建議 |
| 估值要在數學內 | 文章不是單純信仰敘事，而是把 2030 revenue / EBITDA / multiple / shares 拆成模型 | 查詢時同時呈現假設與風險，不只保留結論價 |

## 風險與反例

| 風險 | 風險等級 | 觸發條件 | 觀察指標 |
|---|---|---|---|
| M&A 整合風險 | 高 | 20+ acquisition / investment pipeline 無法整合成單一可交付任務系統 | goodwill impairment、gross margin、OPEX、交付延誤、product bundle adoption |
| 政府合約不確定性 | 高 | DDP / Project Hives / Initial DoW orders 延後、落空或被 Anduril 等競爭者切入 | awards、USAspending、8-K、backlog、program scope、customer disclosure |
| warrant / share overhang | 高 | 股價接近 `$20` 或 `$28` 附近出現技術供給與行權 / resale 壓力 | shares outstanding、warrant exercise、424B5 / 424B7、trading volume |
| Cash burn | 高 | EBITDA positive 前 R&D、整合、製造與銷售成本高於預期 | operating cash flow、cash balance、OPEX、gross margin |
| 模型分母風險 | 高 | 4 億 fully diluted shares 假設低估未來稀釋 | fully diluted shares、M&A 對價股、RSU、warrants |
| multiple 壓縮 | 中高 | 市場不願給 defense tech 高成長 multiple 或收入品質不佳 | EV/Sales、EV/EBITDA、gross margin、recurring revenue mix |
| OCR / 可視讀限制 | 中 | PDF 無文字層，核心內容來自可視讀與官方交叉確認 | 若取得文字版原文，可補修逐段數字 |

## 關鍵證據

| 證據 | 來源 | 對 thesis 的作用 |
|---|---|---|
| Substack metadata | `https://unclestocknotes.substack.com/p/onds-82f` | 確認標題、發文時間、付費文章、摘要與 truncated body |
| PDF p.1-p.4 | 使用者提供網頁截圖 PDF | 支撐大叔的 Investor Day 摘要、DCF、風險與結論 |
| Ondas 2026-01-16 PR | Ondas IR | 確認 `$170M-$180M` 2026 target、`$27M-$29M` Q4 estimate、`$65.3M` backlog、`$1.5B+` pro forma cash |
| OAS Investor Event deck p.59 | Ondas official PDF | 確認 official 2030 revenue `$1.5B+`、30% EBITDA margin、`$15+ billion market cap` path |

## 延伸追蹤

| 日期 / 狀態 | 事件 | 相關 ticker | 追蹤重點 |
|---|---|---|---|
| 2026-02（原文語境，待官方核對） | DDP / Initial DoW orders | **ONDS** | 是否出現官方 award、program scope、initial PO、backlog、delivery schedule |
| 2026Q3 | product company layer EBITDA positive checkpoint | **ONDS** | 是否達成 OAS deck 中的 EBITDA+ 目標 |
| 2026-12-31（推估） | 2026 revenue target `$170M-$180M` 回頭檢查 | **ONDS** | quarterly revenue、OAS / Roboteam / Sentrycs / Mistral contribution、gross margin、cash burn |
| 2030-12-31（推估） | 2030 `$1.5B+` revenue / 30% EBITDA margin long-term model | **ONDS** | revenue scale、EBITDA margin、market cap path、fully diluted shares、cash deployment ROI |
| 未定 | warrant / fully diluted shares refresh | **ONDS** | `$20` / `$28` warrant zones、行權、resale、share count |

## 整理者判定

這篇是 **ONDS** 從「事件與併購拼圖」進入「可計算估值模型」的 L4 節點：它把 2025Q3 revenue inflection、2026-01 `$1B` 資本結構、OAS Investor Day、system-of-systems 與 2030 revenue / EBITDA 目標接起來。查詢時應同時保留大叔的 bullish model 與四個硬風險：政府訂單、M&A 整合、稀釋 / warrant overhang、cash burn；不可只摘 `$14.25` 或 `$20` 當成孤立價格。
