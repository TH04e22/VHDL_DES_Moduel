# 使用VHDL實現DES加密模組 #
---
![實作結果](demo.jpg)
使用VHDL硬體描述語言撰寫DES(Data Encryption Standard)對稱式加密模組，並使用ModelSim模擬軟體進行模擬後，燒錄至DE2-70開發版，以2x16 LCD模組進行呈現。

| 資料夾名稱 | 說明 |
| ---- | ---- |
| DES | DES加密模組程式碼放置位置 |
| LCD | LCD控制模組程式碼放置位置 |
| Freq_Div | 除頻模組程式碼放置位置 |
| StateMachine | 狀態機負責讀取使用者輸入後使用DES模組進行字串的加密解密，並利用LCD控制模組將結果顯示於LCD模組上。 |
---
[專案報告](https://github.com/TH04e22/VHDL_DES_Moduel/blob/master/%E6%9C%9F%E6%9C%AB%E5%A0%B1%E5%91%8A_0551076_%E9%BB%83%E6%B3%B0%E6%BA%90.docx)