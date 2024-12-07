# -AquaYOLO
「AquaYOLO 魚類監控」系統是一個基於YOLO物體偵測框架的智能監控系統，主要功能包括實時監控水域中的魚類活動力、量測魚類長度，並提供數據分析與可視化報告。該系統適用於水族館、漁業研究機構及其他相關領域。

「AquaYOLO 魚類監控」** 系統是一個基於YOLO物體偵測框架的智能監控系統，主要功能包括實時監控水域中的魚類活動力、量測魚類長度，並提供數據分析與可視化報告。該系統適用於水族館、漁業研究機構及其他相關領域。

**「AquaYOLO 魚類監控」** 系統利用YOLO物體偵測框架，結合目標追踪算法，即時監控水域中的魚類活動力，並在需要時進行魚類長度的精確量測。系統還具備數據存儲、管理、分析與可視化功能，為用戶提供全面的監控與決策支援。

## **功能需求**

### **即時影片處理與魚類偵測**

#### **功能描述**

- **影片輸入**：支援接入多種影片來源，包括即時攝像頭和預錄影片文件。
- **影片預處理**：對影片幀進行提取、尺寸調整、顏色空間轉換等，以適應YOLO模型的輸入要求。
- **魚類偵測**：利用YOLO模型對每幀圖像中的魚類進行物體偵測，標記魚的位置（邊界框）及其置信度。

#### **功能要點**

- **高效處理**：確保影片幀的即時處理，達到預期的幀率（如15-30 FPS）。
- **多目標偵測**：能夠同時偵測多條魚，支援多種類別（如不同魚種）。
- **偵測精度**：高準確率的魚類偵測，降低漏檢和誤檢率。
