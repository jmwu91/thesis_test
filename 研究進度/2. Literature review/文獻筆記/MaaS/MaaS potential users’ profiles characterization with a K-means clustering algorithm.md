#MaaS #問卷調查 #K-means #潛在使用者 #culstering 

--- 

## 文獻回顧


| 文獻                                                                                                                                            | 研究內容                      | 方法論                                         | 發現                                |
| :-------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------ | :------------------------------------------ | :-------------------------------- |
| [Alonso-González et al. (2020)](https://www.sciencedirect.com/science/article/pii/S0965856419302575)                                          | 檢測人們採用MaaS的相關因素           | Latent Class Cluster Analysis               | 獲得五種不同的使用者群體                      |
| López Carreiro et al. (2021)                                                                                                                  | 檢測人們採用MaaS的相關因素           | Agglomerative Hierarchical Clustering       | 獲得四種不同的使用者群體，均包含「MaaS愛好者」群體       |
| Sumardi et al. (2017); Alkhereibi et al. (2021); Lu et al. (2023)                                                                             | 應用機器學習於交通研究，尤其是聚類目的       | Machine learning algorithms                 | 探索數據間的關係，學習模式並做出預測                |
| Zijlstra et al. (2020)                                                                                                                        | 確定MaaS早期採用者的五個指標          | Lasso regression analysis(LASSO)            | 獲得稀疏模型，準確預測和增強解釋力                 |
| [Duan et al. (2022)](https://www.sciencedirect.com/science/article/pii/S0965856422002725#s0015)                                               | 預測MaaS採用率                 | Artificial Neural Network (ANN)             | 使用33個輸入變量估計不同的旅行類別模型              |
| [[Application of crowdsourced data to infer user satisfaction with Mobility as a Service (MaaS) 1\|Aman and Smith-Colin (2022)]] | 研究性別對MaaS滿意度的影響因素         | Text mining and ordinal logit regression    | 確認影響MaaS滿意度的因素                    |
| Watters & Andrew (2008)                                                                                                                       | 描述聚類分析技術，根據一個或多個變量對案例進行分組 | Theoretical explanation of cluster analysis | 聚類分析根據相似性進行元素聚合，並可根據預期群組數目生成相應的聚類 |
| McCormack et al. (2012), Gomari et al. (2021), Niu et al. (2021), Zhang et al. (2022)                                                         | 應用聚類分析於交通研究               | Cluster analysis in transport studies       | 探索變量組中的模式                         |

--- 
## 方法論

本研究將線上問卷的分成四個部分
>[[研究進度/文獻回顧/Annotation/MaaS potential users’ profiles characterization with a K-means clustering algorithm#^tq4vart6xg|To achieve our research purposes, we first design an online survey divided into four main blocks of questio]]
- 問卷設計形式
	- Block 1. Use of technological tool
	- Block 2. Personal attitudes and lifestyle preferences.
	- Block 3. Mobility patterns and travel-related characterist
	- Block 4. Socioeconomic and demographic informati
- 共得到9,095份有效問卷 (蛤屁啦怎麼那麼多)
	- [[研究進度/文獻回顧/Annotation/MaaS potential users’ profiles characterization with a K-means clustering algorithm#^rkadwxlm54b|問卷結果結構]]
	- [[研究進度/文獻回顧/Annotation/MaaS potential users’ profiles characterization with a K-means clustering algorithm#^d4wtlvm4y5|問卷結果]] -> 得到了三種分類的MaaS潛在使用者
		- First culster: [[研究進度/文獻回顧/Annotation/MaaS potential users’ profiles characterization with a K-means clustering algorithm#^9pzvjpbc68s|MaaS-enthusiasts]]
		- Second culster: [[研究進度/文獻回顧/Annotation/MaaS potential users’ profiles characterization with a K-means clustering algorithm#^xtw7pnknyy|Innovation doubtful users]]
		- Third culster: [[研究進度/文獻回顧/Annotation/MaaS potential users’ profiles characterization with a K-means clustering algorithm#^k7i929l7ia|Anti-new technologies]]

--- 

## 結論與建議

- **研究目標**：識別馬德里大都市區的潛在MaaS使用者群體，制定鼓勵可持續出行行為的個性化建議
- **方法**：
  - 評估影響MaaS接受意願的態度因素
  - 使用[[k-means]]聚類算法根據相似性將個體分組
- **結果**：
  - **MaaS愛好者**：對MaaS高度開放，環保價值高，經常使用公共交通和自行車
  - **創新懷疑者**：對MaaS的使用意願中立到適中
  - **反新技術者**：反對MaaS
- **發現**：
  - 願意採用MaaS的個體環保意識高，對新技術和新出行選項開放
- **注意事項**：研究基於調查描述的虛擬應用，未來研究應考慮實際偏好的調查，以獲取部署MaaS應用的相關信息