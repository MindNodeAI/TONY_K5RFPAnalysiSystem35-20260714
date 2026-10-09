V2.4更新
漏引公式若與原始證據逐字相同且定位唯一，建立候選ID並向AI要求補齊；最多增加一次API請求。只接受候選中的ID，只改evidence_ids，不改正文或原始公式。補齊後重跑驗證。失敗或不確定仍為待覆核草稿。
檢查JSON增加citation_repair，記錄補齊前後問題、嘗試次數、接受／拒絕ID及錯誤。
策略表格中的「客戶要求常駐／全職」也會被標記，不能靠is_assumption略過。
已通過本機單元測試與Edge模擬API整合測試。實際Gemini連線與回覆尚未實測；每次報告仍需內容覆核。
部署index.html及xlsx.full.min.js，重新整理確認頁首V2.4。先跑07及下載檢查JSON。不要上傳RFP至GitHub。
