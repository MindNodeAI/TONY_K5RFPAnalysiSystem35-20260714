V2 使用說明
開啟HTML，使用Excel驗收區或官方RFP上傳入口。
HTML與xlsx.full.min.js放在同一資料夾。
Github Pages：把HTML改名index.html，與xlsx.full.min.js一起上傳；不要上傳RFP或證據JSON。

已實測：官方Excel18筆公式與快取驗收；版本不同、空白填0、公式變更、缺表負向測試；Edge實際上傳；模擬API報告流程、07三項疑點附錄、錯誤ID／日期／單位／結構化主張衝突。

檢查範圍限制：不是完整全文語意驗證。跨報告比較依AI提供的結構化claims key；不同key的語意相同主張未必能辨識。沒有claims的敘述不代表已完成一致性驗證。PDF抽文字不替代圖面／掃描OCR。實際Gemini及Firebase連線未驗證。

有檢查問題時報告可在頁面閱覽，但Word匯出被阻擋。使用下載報告檢查JSON按鈕查看原因。API分析會依既有流程傳送資料，獨立驗收不需API。
