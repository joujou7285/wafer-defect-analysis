# Wafer Defect Analysis  

## 目的  
利用深度學習中的卷積神經網路（CNN）對半導體晶圓的圖像進行自動化缺陷分類，提升生產效率並降低人工檢測的成本與錯誤率。

## 技術工具  
- Python  
- TensorFlow  
- Keras  
- Scikit-learn  
- Pandas  
- Numpy  

## 成果亮點  
1. 使用卷積神經網絡（CNN）進行晶圓缺陷分類，成功將缺陷分類為 9 類，並在測試集上達到 **95.5%** 的準確率。  
2. 測試損失為 **0.206**，顯示出模型在分類任務中的高效表現。  
3. 透過 **批標準化（Batch Normalization）**、**最大池化（Max Pooling）** 和 **Dropout** 技術提升了模型的穩定性，並有效防止過擬合。  
4. 進行了資料預處理和特徵工程，包括處理遺失值、標籤轉換以及數據格式化，為模型提供了高質量的訓練資料。

## 使用方式  
1. 點選 [半導體製程晶圓缺陷分析.ipynb](./) 可查看程式碼與結果展示。  
