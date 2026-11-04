# 明析統計工作台（Stat Workbench）

綜合三位統計專家對各統計軟體（SPSS、R、Python、SAS、Stata、JASP、jamovi、Excel 等）優缺點的整理，取長補短做成的單頁網頁統計工具。打開 `index.html` 即可使用，不需安裝。

- **線上版（claude.ai）**：https://claude.ai/artifact/5HPrXocezRwaF22DES2JJa
- **報告**：`docs/` 內為兩份整理文件（Markdown）

## 主要功能

| 類別 | 內容 |
|---|---|
| 資料 | 上傳 CSV／Excel（.xlsx/.xls）、可直接編輯儲存格、缺失值代碼、反向題、合併多個檔案、長寬資料轉換、範例資料按鈕 |
| 方法顧問 | 依研究問題與變項類型推薦方法並說明理由與前提假設 |
| 分析 | 描述統計、常態性、t 檢定（Welch／Student）、Mann–Whitney、Wilcoxon、ANOVA／Welch ANOVA、Kruskal–Wallis、ANCOVA（Type III）、重複測量 ANOVA（Greenhouse–Geisser）、線性混合模型（REML）、卡方／Fisher、相關、複迴歸（VIF、Breusch–Pagan、Cook's D）、邏輯斯迴歸、Cronbach's α、CFA 與 McDonald's ω |
| 結果 | 自動檢查前提假設、效應量與信賴區間、白話解讀、APA 格式表格、同步產生 R／Python／SPSS 語法 |
| 圖表 | 17 種風格（SPSS、ggplot2、base R、Stata、SAS、Excel、matplotlib、seaborn、APA、Nature、Lancet、Okabe-Ito、Viridis 等）＋自訂風格，可匯出 SVG／PNG |
| 其他 | 檢定力與樣本數計算、統計教學說明、分析紀錄（可重現）、匯出 HTML 報告 |
| 團隊（僅 claude.ai） | 多人即時同步資料、顯示線上成員、共同編輯研究報告 |

## 注意

- AI 協助、下載與團隊協作需要 claude.ai 的執行環境；在一般瀏覽器或 GitHub Pages 開啟時這些功能會自動隱藏，其餘統計功能皆可正常使用。
- 所有計算都在瀏覽器內完成，資料不會上傳。
- 可在 repo 設定開啟 GitHub Pages，網址為 `…/biostat-class/stat-workbench/`。
