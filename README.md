# AGV Energy Optimization

本專案致力於 **自動導引車（AGV）** 於倉儲/物流場域下的能源消耗最佳化與路徑規劃。  
我們結合了路徑規劃（如 Dijkstra、ACO）及能源模型，並支援多台 AGV 排程與能耗計算。

## 特色功能

- 批次訂單分配與多車協作
- 能源消耗評估與最佳化
- 支援多種路徑規劃與調度演算法（Dijkstra、ACO 等）
- 易於擴充、模組化設計
- Colab/Jupyter Notebook 展示與可視化
## 專案結構
```
warehouse-agv-optimizer/
├── README.md
├── main.py
└── energy.py
```
## 使用方法

1. 下載或 clone 此 repo
2. 安裝依賴套件（見 `requirements.txt`）
3. 執行 `main.py` 或於 notebook/ 下開啟 `demo.ipynb` 進行測試

```bash
git clone https://github.com/yourgroup/agv-energy-opt.git
cd agv-energy-opt
pip install -r requirements.txt
python main.py
