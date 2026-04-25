# 專案工作指令

本專案是投資 KOL 文章追蹤資料庫。任何在此 repo 內處理文章、PDF、截圖、聊天室紀錄、查詢或交叉比對時，必須先遵守以下文件：

1. [PROJECT_RULES.md](PROJECT_RULES.md)
2. [kol_config.yaml](kol_config.yaml)
3. [docs/KOL_PROFILES.md](docs/KOL_PROFILES.md)
4. [docs/STOCK_PROFILES.md](docs/STOCK_PROFILES.md)
5. [docs/FORMAT_SPEC.md](docs/FORMAT_SPEC.md)
6. [docs/TAG_TAXONOMY.md](docs/TAG_TAXONOMY.md)
7. [docs/INGEST_WORKFLOW.md](docs/INGEST_WORKFLOW.md)
8. [docs/QUERY_WORKFLOW.md](docs/QUERY_WORKFLOW.md)
9. [docs/TEMPLATES.md](docs/TEMPLATES.md)

## 預設行為

- 使用者上傳新 KOL 文章、PDF、截圖、Note、聊天室紀錄時，預設執行入庫流程。
- 先判斷 KOL，再放入對應 `KOL/<KOL名稱>/` 目錄。
- 短文合併到該 KOL 主筆記；長文獨立成文。
- 若文章同時影響已追蹤個股，依 `docs/STOCK_PROFILES.md` 的 L0-L4 規則同步更新 `Stocks/<Ticker>/`，但不要重複複製整篇 KOL 主整理。
- 非 KOL、非單一個股的產業、宏觀、橫向比較資料放 `Research/`。
- 每次入庫都更新相關索引與 `logs/update_log.md`。
- 每篇新資料都建立 `source_id`；實體原始檔複製到 raw 時使用標準 raw 命名，並記錄 OCR 狀態。
- `raw/` 是本機原始檔保存層，不 commit、不同步 GitHub / Claude；筆記與索引可保留網頁 URL，但本機絕對路徑只寫入 `private/raw_manifest.local.yaml`，且該檔不入庫、不同步。
- 若偵測到文章 / PDF / 截圖 / 聊天室紀錄疑似被截斷，或核心內容不清楚到無法可靠整理，立即終止紀錄，不更新筆記、索引或 log，並通知使用者補齊或重傳。
- 查詢觀點變化時，預設只在同一 KOL 內交叉比對。
- 不提供買賣建議。

## GitHub 同步

- 本專案 remote 為 `origin`：`https://github.com/Randy0731/Articles.git`。
- 每次完成 repo 檔案更新後，若 git 狀態有變更且憑證 / 網路可用，預設建立清楚的 commit 並 push 到 `origin main`。
- 若 push 失敗，需在回覆中明確告知原因與目前本地 commit 狀態。

## 品質底線

- 引文必須能追回來源。
- 聊天室引文必須標日期與頁碼。
- 不跨日拼湊引文。
- 不把群友喊價、分析師目標價、玩笑、轉述寫成 KOL 明確觀點。
- 不確定的日期、價位、立場必須標「推估」或「未確認」。
- 文章疑似截斷或內容不清楚時，不做低信心入庫；直接停止紀錄並通知使用者。
