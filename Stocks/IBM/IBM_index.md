# IBM Index

此檔追蹤 **IBM** 正式個股專案中的筆記、儀表板與跨 KOL 觀點變化。原文主整理仍以 `KOL/` 為 source of truth。

## 檔案總覽

| 類型 | 路徑 | 說明 |
|---|---|---|
| 儀表板 | `Stocks/IBM/IBM_儀表板.md` | 當前追蹤摘要、風險、催化劑與持倉判斷依據 |
| 季度筆記 | `Stocks/IBM/quarterly/IBM_筆記_2026Q2.md` | 2026Q2 一般 **IBM** 筆記 |
| KOL 主整理 | `KOL/大叔美股筆記/articles/20260423_ibm_2026_q1_uncle.md` | 大叔 2026Q1 IBM 財報長文整理 |

## 時間序列

| 發文日期 | 路徑 | KOL | 主題 | Tags | 交會等級 | 摘要 |
|---|---|---|---|---|---|---|
| 2026-04-23 | `Stocks/IBM/quarterly/IBM_筆記_2026Q2.md`；`KOL/大叔美股筆記/articles/20260423_ibm_2026_q1_uncle.md` | 大叔美股筆記 | IBM 2026Q1 財報、混合雲、watsonx、企業級 AI 現金流化、FCF / DCF | #財報 #AI基建 #軟體SaaS #ReRating #估值風險 | L3 | 大叔把 **IBM** 由舊科技 / 低毛利 IT 服務印象重寫為高毛利軟體、混合雲與企業級 AI 平台；Q1 double beat、`57.7%` gross margin、`22.2 億美元` FCF 與 `45 億美元` AI 訂單構成第一篇完整 **IBM** thesis |

## 升級後歷史回查

| 日期 | 來源 | 既有紀錄 | 交會等級 | 回查處理 |
|---|---|---|---|---|
| 2026-03-17 | Bytc / GTC 2026 AI 基建文章 | **IBM** 作為 watsonx.data / enterprise data platform 與 AI ecosystem 背景案例 | L1 | 已在 `indexes/ticker_index.md`；不補入 `Stocks/IBM/quarterly/` |
| 2026-04-02 | Bytc / Google 量子 Bitcoin 文章 | **IBM** 作為大型科技量子計算背景與觀察籃子 | L1 | 已在 `indexes/ticker_index.md`；不補入 `Stocks/IBM/quarterly/` |
| 2026-04-18 | Bytc / 宏觀數據週報 | **IBM** 只作 2026-04-20 週財報 calendar 觀察事件之一 | L1 | 已在 `indexes/ticker_index.md` 與 `indexes/catalyst_index.md`；不補入 `Stocks/IBM/quarterly/` |

## 目前母題

| 母題 | 當前判斷 | 主要來源 | 後續追蹤 |
|---|---|---|---|
| 高毛利軟體與混合雲轉型 | Software 年增 `11%`，Red Hat / OpenShift、Data & AI、Automation 與 Transactional Software 是轉型核心 | 大叔 2026-04-23 | Red Hat / OpenShift adoption、software margin、recurring revenue |
| 企業級 AI 現金流化 | `45 億美元` 生成式 AI book of business，約 `75%` 來自 consulting；重點是 AI 訂單能否轉成 software / infrastructure revenue | 大叔 2026-04-23 | AI order conversion、watsonx adoption、software attach |
| Consulting 前鋒與景氣拖累並存 | Consulting Q1 低於預期，是市場懲罰點；但仍是 enterprise AI 導入入口 | 大叔 2026-04-23 | Consulting bookings、margin、short-cycle contracts |
| Infrastructure / z16 超級週期 | Infrastructure 年增 `15%`，z16 / storage 需求使傳統硬體週期被重新定價 | 大叔 2026-04-23 | z16 cycle、storage demand、mainframe renewals |
| FCF / 股息 / 防禦性成長 | 大叔以 P/FCF 約 `19.6x`、股息殖利率約 `2.7%` 與 2026 FCF 約 `120 億美元`，把 **IBM** 寫成防禦 + 成長交集 | 大叔 2026-04-23 | FCF、dividend coverage、debt refinancing |
| 補強型併購 | Apptio、webMethods、HashiCorp 補強 hybrid cloud、automation 與 cloud security，但整合風險需追 | 大叔 2026-04-23 | HashiCorp integration、retention、Red Hat / Ansible synergy |

## 待補 / 待查

- 後續 **IBM** Q2 財報入庫時，檢查 consulting 是否止穩、software / infrastructure 是否延續 Q1 強勢。
- 若 **IBM** 披露 watsonx revenue、AI book conversion 或 HashiCorp 整合進度，更新 `Stocks/IBM/IBM_儀表板.md` 與 `indexes/catalyst_index.md`。
- 若後續 Bytc 或其他 KOL 對 **IBM** 有 L2+ 觀點，再補入季度檔；L1 生態 / calendar 提及只維持在 ticker index。
