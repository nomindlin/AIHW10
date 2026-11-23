# 高齡運動健康 LLM Wiki

這是研究高齡運動健康（預防肌少症與失智症）的個人知識庫和 HTML 簡報系統，採用 Andrej Karpathy 的 LLM Wiki 架構。

- AI 的工作規則全部寫在 [AGENTS.md](AGENTS.md)。
- 總入口是 [wiki/index.md](wiki/index.md)。

## 怎麼用
1. 把論文 PDF、網頁文章、指引或筆記放進 `raw/` 底下對應的資料夾。
2. 對 AI 說：「匯入 raw/論文/xxx.pdf」。AI 會先列出執行計畫，你確認後才會動手。
3. 要提問、做健康檢查或生成簡報，直接說「查詢：…」「執行 Lint」「做一份衛教簡報：…」。

建議用 Obsidian 開這個資料夾，可以直接使用 `[[連結]]` 和關聯圖。
