# 當「做一顆按鈕」不再是問題：Spec-Driven Development 深度導讀

DeepLearning.AI × JetBrains《Spec-Driven Development with Coding Agents》課程的深度導讀文章。從 vibe coding 的失控案例出發，拆解「憲法（constitution）」、功能開發迴圈、人機審查分工、agent skills 自動化，到 GitHub Spec Kit／OpenSpec 等開源框架比較。

線上閱讀：https://lushinshang.github.io/spec-driven-development-coding-agents/

## 200 字介紹

一顆按鈕可以靠對話反覆修改，一個要跑好幾個月的專案不行——每次對話從頭來過，決定只活在聊天紀錄裡，程式碼一直堆但「為什麼」一直流失。JetBrains 開發者關係工程師 Paul Everitt 在這堂與 DeepLearning.AI 合作的課程裡，示範如何用一份可以讀、可以審、可以跨 agent 攜帶的規格文件，取代「靠聊天調整」的開發方式：專案層級的憲法定義願景與技術棧，功能層級的迴圈跑完規劃、實作、驗證，人類的角色從打字變成判斷與審查。文章也整理了課程提到的 MCP、agents.md、Agent Skills、ACP 標準堆疊，以及 GitHub Spec Kit 與 OpenSpec 兩套開源框架的對應關係。

## 檔案說明

| 檔案 | 說明 |
|---|---|
| `index.html` | 發布網頁本體 |
| `images/` | 5 組資訊圖表（各含 16:9 桌機版與 9:16 手機版） |
| `spec-driven-development-coding-agents.md` | 深度導讀 Markdown 原稿 |
| `share_post.md` | 社群分享文 |

## 原始素材

- 課程：[Spec-Driven Development with Coding Agents](https://www.deeplearning.ai/courses/spec-driven-development-with-coding-agents)（DeepLearning.AI，與 JetBrains 合作）
- 影片：[Full Course: Spec-Driven Development with Coding Agents](https://www.youtube.com/watch?v=hy8UstR2NEg)（YouTube）
- 逐字稿來源：上述影片的 YouTube 官方自動字幕，本地去重後整理

## 查證來源

- 課程頁面：https://www.deeplearning.ai/courses/spec-driven-development-with-coding-agents
- Andrew Ng 公告：https://x.com/AndrewYNg/status/2044449830605582629
- 課程素材 GitHub repo：https://github.com/https-deeplearning-ai/sc-spec-driven-development-files
- 講師與貢獻者姓名（Paul Everitt、Konstantin Chaika、Zina Smirnova、Isabel Zaro）已透過上述來源查證拼法，逐字稿自動字幕原始拼法有誤，本文已修正
