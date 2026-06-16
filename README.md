# Ryan Lee
AIoT 系統工程師 | 邊緣 AI | 嵌入式 Linux | 安全 IoT 整合

---

## 關於我

我專注於在真實硬體限制下設計並部署具備 AI 功能的邊緣系統。

我的重點不僅是單一模型的效能，而是跨越整個系統的**工程決策**，包括：

- 邊緣 AI 推論  
- 嵌入式 Linux 部署  
- 安全的裝置間通訊  
- 可擴展的 IoT 數據管線  
- 考量硬體的權衡分析  

---

# 精選專案
## 🔹 邊緣視覺 AIoT 系統

A modular Edge AI + AIoT integration system designed for Raspberry Pi and Jetson platforms.

This project focuses on:
- Edge AI inference
- Embedded Linux deployment
- AIoT system architecture
- Real-time monitoring

https://github.com/gogohusky-lgtm/EdgeVision-AIoT-System


## 邊緣 AI 視覺推論

基於硬體的 CPU 與 GPU 部署效能比較  
（Raspberry Pi 5 vs Jetson Nano）

- 量化（FP32 / FP16 / INT8 PTQ / QAT）  
- 在 2GB RAM 下的 TensorRT 優化  
- 冷啟動 vs 穩態延遲分析  
- GPIO 硬體回饋驗證  
- 容器化部署  

https://github.com/gogohusky-lgtm/Edge_AI_Vision_Inference  

---

## 安全 RFID 門禁系統  
分散式 IoT 安全架構

- Raspberry Pi 5 + ESP32-CAM 角色分工  
- HMAC-SHA256 UID 驗證  
- 支援 TLS 的 MQTT 通訊  
- RP1 限制下的混合 GPIO 後端  
- SQLite 紀錄與 CSV 匯出  

https://github.com/gogohusky-lgtm/RFID_door_security_system  

---

## 智慧環境監測系統  
分層式 IoT 數據管線

- Arduino 進行確定性 ADC 取樣  
- Raspberry Pi 5 作為 Linux 邊緣節點  
- 基於 MQTT 的訊息架構  
- InfluxDB 時序資料儲存  
- Grafana 歷史分析  
- Flask 即時儀表板  

https://github.com/gogohusky-lgtm/Smart_environment_monitor  

---

# 工程理念

- 部署可行性 > 合成基準測試數字  
- 異質裝置間的明確角色分工  
- 硬體限制決定軟體架構  
- 安全性與可重現性是核心設計因素  

---

# 核心技術

**邊緣 AI**  
TensorFlow Lite、TensorRT、量化、效能測試  

**嵌入式與 IoT**  
Raspberry Pi 5、Jetson Nano、Arduino、ESP32  
GPIO / UART / SPI / I2C  
MQTT (TLS)、Mosquitto  

**資料與後端**  
InfluxDB、Grafana、SQLite、Flask  

---

## 聯絡方式

- GitHub: https://github.com/gogohusky-lgtm  
- LinkedIn: https://www.linkedin.com/in/cheng-chun-ryan-lee-ab8a271/
