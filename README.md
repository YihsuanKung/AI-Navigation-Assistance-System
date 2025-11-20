# AI 導覽輔助系統  
智慧校園自主導航車（SLAM × YOLOv4 × 語音控制 × 嵌入式整合）

本專題開發一套能在校園中自動導航的導覽車系統，結合 LiDAR SLAM、YOLOv4 建築物辨識、語音操作與跨平台整合技術，目標是提升校園導覽效率並減少人力依賴。

🎥 Demo 影片：https://www.youtube.com/watch?v=_xXVmry_xc8  
🏆 2024 智慧創新競賽 — *值得注目獎*

---

## 📌 專題介紹
此系統能夠在校園環境中自動完成定位、地圖建構、路徑規劃及避障，並透過影像辨識提供建築物資訊。使用者可透過語音輸入目的地，導覽車會自動規劃路徑並朝指定位置移動。

---

## 🧭 系統架構
- **LiDAR + SLAM**：使用 RPLIDAR A1 搭配 ROS hector_mapping 進行即時建圖與定位  
- **導航與避障**：採用 D\* Lite 進行全局路徑規劃，DWA 做動態避障  
- **影像辨識**：YOLOv4 模型辨識校園建築  
- **語音控制**：透過語音輸入與導覽車互動  
- **跨平台整合**：Raspberry Pi、Arduino、MATLAB GUI、5G/Wi-Fi 傳輸  

---

## 🔧 技術亮點
- LiDAR-based SLAM（hector_mapping）  
- YOLOv4 自建資料集（4500+ 張校園照片）  
- D\* Lite 全局規劃 / DWA 區域避障  
- MATLAB GUI 監控系統  
- Raspberry Pi + Arduino 馬達控制  

---

## 🌟 系統成果 
- 能辨識多座校園建築
- 支援語音輸入目的地
- 即時顯示地圖、路徑、辨識結果與影像串流
