# 1142_CE5033_Group_Final_Project
統計方法與資料採礦期末分組專題

## 專題簡介
本專題以「探討 AI 使用習慣與付費行為對學生 GPA、學習能力及時間分配的影響」為主題，使用 Kaggle 資料集進行資料前處理、探索性資料分析、統計檢定與資料探勘分析，進一步比較付費與非付費 AI 使用者在學習成效、技能保留與使用行為上的差異。

## 資料來源
- Kaggle Dataset：`Impact of Ai on Students`
- 來源連結：<https://www.kaggle.com/datasets/laveshjadon/ai-impact-on-students>

## 分析內容
### 1. 資料前處理
- 檢查缺失值、重複值與資料型態
- 轉換與整理可分析的乾淨資料集
- 輸出處理後資料供後續分析使用

### 2. 探索性資料分析（EDA）
- 敘述統計與類別變數分布
- 數值變數直方圖與箱型圖
- 相關係數矩陣與熱圖
- 主要變數與 `GPA_Change` 的關聯視覺化

### 3. 統計分析
- 以獨立樣本 t 檢定比較付費 / 非付費使用者差異
- 以 ANOVA 與 Tukey 事後檢定分析提示詞技巧與學習成效的關聯
- 搭配效應量（Cohen's d）輔助解讀結果

### 4. 資料探勘
- Association Rules：找出學生特徵與學習表現之關聯規則
- Random Forest：分析影響學生倦怠風險的特徵重要性
- K-Means：進行學生族群分群與輪廓分析

## 執行環境
**R語言** ，使用套件：
`tidyverse`, `dplyr`, `ggplot2`, `skimr`, `janitor`, `GGally`, `corrplot`, `effsize`, `arules`, `randomForest`, `cluster`, `patchwork`, `showtext`

## 專案結構
```text
Group_Final_Project/
├─ main.ipynb   --主要程式碼
├─ ai_student_impact_dataset.csv   --原始資料
└─ visualizations/   --可視化圖表(包含EDA、kmeans、association_rules的輸出圖表)
```
