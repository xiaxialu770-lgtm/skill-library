# 我的 Skill 工具庫

22 個個人 skill 的中文用途說明、搜尋分類、完整 ZIP 下載及跨電腦安裝指南。

## 使用網站

直接開啟公開網頁：https://xiaxialu770-lgtm.github.io/skill-library/

下載本儲存庫並解壓縮，使用瀏覽器開啟 `index.html`。頁面與下載包均可離線使用，請保留 `downloads/` 資料夾。

## 安裝 skill

在網站下載單一或全部 ZIP，解壓縮後，將每個完整的 skill 資料夾放入目標電腦的技能目錄。依目標 Codex 版本確認目錄：現行官方文件為 `~/.agents/skills`；本次來源電腦使用 `~/.codex/skills`。

在新的 Codex 對話指定「使用 <skill 名稱>」與你的任務。若技能沒有出現，重新啟動 Codex。

Skill 包保留原始 `SKILL.md`、腳本、參考資料與圖片。外掛、工具、帳號授權及 Python 套件需要在目標電腦另行設定。`soil-teaching-deck` 的部分範例引用外部環境路徑，使用時需依環境調整。

官方說明：https://learn.chatgpt.com/docs/build-skills

## 檔案

- `index.html`：完整網站，含內嵌樣式、資料與互動。
- `catalog.json`：技能目錄、中文說明與各包 SHA-256。
- `downloads/`：22 個單包 ZIP、全部技能 ZIP 與安裝說明。

技能快照日期：2026-10-12。此儲存庫公開，GitHub Pages 從 main 分支根目錄發布。
