# Auto-Sanitize 🧹

一個免後端、完全在瀏覽器運行的設定檔敏感資訊遮蔽工具。

---

## 🌟 為什麼選擇 Auto-Sanitize？

* **🔒 100% 隱私安全（Zero Backend）**：所有資料處理與遮蔽（Redact）皆在本地瀏覽器完成，絕不上傳任何設定檔至後端伺服器。
* **⚡ 自動偵測秘密**：貼上設定檔（`.env`、`config.yaml`、`.json`），自動偵測並遮蔽 API Keys、密碼、Token 與敏感金鑰。
* **🤖 LLM 語意驗證**：可選擇性串接 LLM（Claude / GPT / Gemini），進行更深度的語意安全驗證與漏網之魚檢查。
* **🌐 雙語支援**：提供中英文（ZH/EN）一鍵切換介面。

## 🛠️ 如何使用？

1. 直接開啟專案中的 [sanitize.html](sanitize.html)（亦可透過 GitHub Pages 線上使用）。
2. 將含有敏感資訊的設定檔內容貼入輸入框。
3. 預覽自動遮蔽後的結果，確認無誤後即可安全複製或匯出！
