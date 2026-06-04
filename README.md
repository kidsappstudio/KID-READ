Here are the brief introductions in both Chinese and English for your calendar web application and its exported file:

---

### 中文簡介 (Chinese Introduction)

**1. 網頁系統簡介**
本專案為一個專為家庭設計的「親子學習週曆」互動網頁。系統整合了直觀的週看板（Kanban）與動態月曆視圖，方便家長與孩子追蹤每日的學習進度（如數學講義、英文套書等）。系統具備貼心的雙向歷史紀錄功能（支援「恢復上一動」與「取消復原」），並特別針對手機版進行了觸控與畫面精簡優化，讓親子在跨裝置操作時皆能流暢體驗。

**2. 匯出檔案簡介**
當家長從後台點選「CSV報表匯出」時，系統會自動生成一個名為 **"learning-history.csv"** 的檔案。此檔案完整記錄了所有「已完成」的學習任務，包含小孩姓名、日期、科目及備註等欄位。為了防止 Windows 電腦的 Excel 開啟時出現亂碼，檔案已特別加入微軟認證的記號（BOM），確保您在手機與電腦上雙擊打開時，都能直接看到一清二楚的漂亮中文報表。

---

### English Introduction

**1. Web Application Overview**
This project is an interactive **"Parent-Child Learning Calendar"** web application tailored for families. It features an intuitive weekly Kanban board and a dynamic monthly calendar layout, allowing parents and children to easily track daily learning tasks (e.g., math worksheets, English reading). The system includes user-friendly history tracking (supporting both Undo and Redo functions) and is fully optimized for mobile devices with streamlined views and touch gestures, ensuring a seamless experience across all platforms.

**2. Exported File Overview**
When parents click "Export CSV Report" in the admin section, the system automatically generates a file named **"learning-history.csv"**. This file archives all "Completed" learning tasks, displaying columns such as Child's Name, Date, Subject, and Memos. To prevent Chinese character corruption (mojibake) when opened in Microsoft Excel on Windows, the file is embedded with a Byte Order Mark (BOM), ensuring that it displays perfectly clear text whether you double-click to open it on a PC or a mobile phone.
