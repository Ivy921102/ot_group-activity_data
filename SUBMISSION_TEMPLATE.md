# 作業繳交草稿範本（請複製以下內容至作業繳交區）

**繳交標題格式**：
`[請填寫學校簡稱] [請填寫學號] [請填寫系級簡稱] [請填寫姓名] 職能治療團體活動資料庫`
*(範例：高醫 111018000 職治三 王小明 職能治療團體活動資料庫)*

---

### 一、專案簡介
本專案為**「職能治療團體活動資料庫」（OT Group Activity Wiki）**。
不同於傳統單次網頁製作（Vibe Coding），本專案借鑑電腦科學家 Andrej Karpathy 的 **LLM Wiki 持久型知識庫架構**，旨在解決臨床職能治療師在活動教案設計上零散、缺乏結構與難以複利累積的痛點。

- **完整收錄 26 篇臨床活動教案**：將存放在 `sources/` 資料夾中的 **22 份真實臨床教學 PDF 計畫書** 完整 Ingest 收錄，涵蓋高雄長庚醫院精神科病房（10K/11K/12K）、呈泰日間型精神復健機構、兒童早期療育與長照社區據點。
- **限定四大臨床族群**：兒童職能（6篇）、精神科病房（8篇）、社區精神復健（7篇）、高齡長照（5篇）。
- **強化活動分析核心**：每個活動均規範「分級與調適（Grading Down 簡化 / Grading Up 加難）」與嚴謹的「安全注意事項與禁忌症」。
- **設計風格**：融入《戀與深空》角色沈星回官方代表色「星河紫（#9E86C8）」與星光暖金暖色系，兼具臨床專業與溫暖陪伴感。

---

### 二、GitHub Repository 連結
`[請貼上您的 GitHub 專案網址，例如：https://github.com/your-username/ot-group-activity-wiki]`

---

### 三、網頁瀏覽連結 (GitHub Pages)
`[請貼上您的 GitHub Pages 網址，例如：https://your-username.github.io/ot-group-activity-wiki/]`

---

### 四、AGENTS.md 完整內容
*(請直接複製專案根目錄下的 `AGENTS.md` 內容貼於此處，或參見專案內之 AGENTS.md 檔案)*

---

### 五、簡短說明：如果之後要新增一個新的頁面或內容，你設計的規則可以如何幫助 AI 繼續完成？

本專案在 `AGENTS.md` 中建立了完整的三層結構（Raw Sources → Markdown Wiki → Web UI）與自動化維護規則，能確保任何接手的 AI 代理人皆能依循 SOP 實現知識的「持久累積」：

1. **嚴格的 Schema 規範讓輸出零偏差**：
   `AGENTS.md` 第 4 節規範了每個活動必須具備的 YAML Frontmatter 與 5 大模組（設計理念、道具與場地佈置、團體流程步驟、分級調適 Grading Down/Up、安全注意事項）。AI 只要讀取原始素材（無論是 Word 或是 PDF），就能精準提取並填入標準欄位，絕不缺漏臨床關鍵資訊。

2. **雙向連結與知識網絡自動交織（Cross-referencing）**：
   AI 在 Ingest（收錄）新活動時，被強制要求檢查 `wiki/populations/` 與 `wiki/skills/`，自動將新活動掛載進對應能力與族群頁面的推薦清單，避免產生「孤兒活動」，使知識庫越用越豐富。

3. **雙重索引與歷程追蹤機制（Indexing & Logging）**：
   每次新增活動，AI 必須同步更新 `wiki/index.md` 矩陣目錄並在 `wiki/log.md` 以標準時間標籤（`## [YYYY-MM-DD] ingest | ...`）追加日誌，讓後續 AI 能秒級檢索全站結構與演進脈絡。

4. **資料層與前端自動同動（Front-end Sync）**：
   `AGENTS.md` 規範 AI 在產出 Markdown 的同時，將結構化數據同步寫入 `data/activities.json`，靜態網頁端（GitHub Pages）無需重新編譯，即可自動渲染出具備卡片篩選、搜尋與彈窗詳情的新活動。
