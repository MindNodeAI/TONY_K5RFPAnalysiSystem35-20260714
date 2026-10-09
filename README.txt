V2.1 來源接入修正
兩個Excel上傳入口均會將證據加入正式RFP來源。主入口同名檔案重新上傳會替換舊紀錄。
來源狀態顯示已接入份數。舊專案缺少evidenceRecord時，在AI呼叫前阻擋並提示重新上傳原始檔；不從舊文字猜造證據。
重新上傳兩份PDF與原始Excel後，確認來源接入3份及Excel18/18。先生成07，再下載report_validation.json。
AI若仍未提供證據ID，報告仍列待覆核，不自動配上猜測來源。
本機Edge測試通過：兩個上傳入口、舊專案阻擋、新專案保存／還原、非空source_hashes及模擬API報告檢查。
實際Gemini/Firebase線上連線未測試；mock API測試不代表模型每次都遵守引用要求。
GitHub Pages上傳index.html與xlsx.full.min.js，不上傳RFP或測試資料。
