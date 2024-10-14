#public_transport #票證資料 #culstering #Spatiotemporal_analysis

## 文獻回顧
- 電子票證資料於公共運輸上的分析

| 研究主題                     | 參考文獻                                                                      | 主要發現                                    |
| ------------------------ | ------------------------------------------------------------------------- | --------------------------------------- |
| 電子票證資料應用於使用者穩定性和頻率行為分析   | Bagchi and White (2005)                                                   | 使用者穩定性和頻率行為的分析                          |
| 電子票證資料應用於使用者忠誠度分析        | Blythe (2004); Trépanier and Morency (2010)                               | 使用者忠誠度的分析                               |
| 電子票證資料應用於使用者人口統計分析       | Utsunomiya et al. (2006); El Mahrsi et al. (2014); Langlois et al. (2016) | 各線路使用者的人口統計分析                           |
| 電子票證資料應用於分析外部因素對使用者行為的影響 | Arana et al. (2014); Zhou et al. (2017)                                   | 外部因素（如天氣）對使用者行為的影響                      |
| 電子票證資料應用於提供更好的即時資訊       | Ceapa et al. (2012); Yap et al. (2018)                                    | 提供給公共交通使用者的即時資訊改進                       |
| 目的地識別                    | Trepanier et al. (2007); Chu and Chapleau (2008)                          | 基於轉乘和出行習慣識別旅行目的地                        |
| 單一行程目的地識別                | He and Trépanier (2015)                                                   | 識別單日單次交易使用者的行程目的地                       |
| 行程目的識別                   | Devillaine et al. (2012)                                                  | 識別每次行程的目的                               |
| 多模式出行研究                  | Seaborn et al. (2009)                                                     | 研究多模式出行（如公車和地鐵）                         |
| 電子票證資料與其他資料對比            | Giraud et al. (2016); Kusakabe et al. (2014); Spurr et al. (2014)         | 電子票證資料與APC和GTFS對比，提高目的地估算準確性；評估出行調查的準確性 |
|                          |                                                                           |                                         |
|                          |                                                                           |                                         |
- 電子票證資料分群研究

| 研究主題              | 參考文獻                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | 主要發現                                                    |
| ----------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------- |
| 電子票證使用者行為的時間模式分析  | Asakura et al. (2012); Trépanier (2012)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | 不同時間尺度上使用者行為的時間模式及其演變分析                                 |
| 票價類型對電子票證使用者行為的影響 | Morency et al. (2007); El Mahrsi et al. (2014); [Nishiuchi et al. (2013)](https://link.springer.com/article/10.1007/s13177-012-0051-7)                                                                                                                                                                                                                                                                                                                                                                                                                                                         | 票價類型對使用者行為的影響                                           |
| 電子票證使用者聚類算法及指標研究  | [Morency et al. (2007)](https://www.sciencedirect.com/science/article/pii/S0967070X07000030?via%3Dihub); [Trépanier (2012)](https://link.springer.com/article/10.1007/s13547-011-0019-z); [Zhao et al. (2017)](https://ieeexplore.ieee.org/document/7891954); [Langlois et al. (2016)](https://www.sciencedirect.com/science/article/pii/S0968090X15004283?via%3Dihub); He et al. (2018a, b; 2019); [Faroqi et al. (2019)](https://onlinelibrary.wiley.com/doi/10.1155/2019/5070794); Kieu et al. (2014); [[Mining smart card data for transit riders’ travel patterns.pdf\|Ma et al. (2013)]] | 使用不同的聚類算法（如K-means、層次聚類、DBSCAN）和指標（如漢明距離、歐幾里得距離）進行使用者聚類 |
| 電子票證資料的時間指標測試     | [[A classification of public transit users with smart card data based on time series distance metrics and a hierarchical\|He et al. (2018a)]]; Ghaemi et al. (2017)                                                                                                                                                                                                                                                                                                                                                                                                                            | 使用DTW（動態時間扭曲）和CCD（交叉相關距離）測試電子票證資料的時間指標                  |
| 同時使用時空資料進行聚類      | Ansari et al. (2019); He et al. (2018b); Faroqi et al. (2019)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | 使用時空聚類方法對使用者進行聚類，並比較了不同聚類方法的效果                          |
| 使用DTW指標進行時空聚類     | [[研究進度/文獻回顧/Annotation/Smart Card/Space–time classification of public transit smart card users’ activity locations from smart card data\|He et al. (2018b)]]                                                                                                                                                                                                                                                                                                                                                                                                                                   | 使用DTW指標比較使用者的時空序列，進行時空聚類                                |
| 同時進行空間和時間聚類       | Faroqi et al. (2019)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | 同時進行空間和時間聚類（ST聚類）比先空間再時間（S-T）或先時間再空間（T-S）聚類更為穩健         |

---



- [[研究進度/文獻回顧/Annotation/Modulated spatiotemporal clustering of smart card users#^upqf7o6e7p|運用電子票證資料去進行使用者分群的研究使用了許多不同的分群方法，主要用最多的方法如以下：]]
	- K-means
	- Hierarchical clustering
	- DBSCAN

- [[研究進度/文獻回顧/文獻筆記/Mining smart card data for transit riders’ travel patterns|分類方法的比較]]
	- **K-means 與 Hierarchical clustering**：
	  - K-means方法速度較快。
	  - Hierarchical clustering提供更多彈性和更詳細的分析。
	
	- **評估時間尺度上行為的相似性**：
	  - 常見的度量如Hamming distance 和Euclidean distance 對於時間序列來說不夠充分，因為它們沒有考慮資料的順序。

	- **測試的時間序列度量**：
	  - 動態時間規整(DTW) 和 互相關距離 (CCD) 被應用於電子票證時間資料聚類[[A classification of public transit users with smart card data based on time series distance metrics and a hierarchical|（He et al. 2018a）]]。
	  - 針對電子票證時間資料，設計了新的度量方法[[研究進度/文獻回顧/Annotation/Smart Card/A Visual Segmentation Method for Temporal Smart Card Data|（Ghaemi et al. 2017）]]。

# 要讀清楚！！讀懂！！

## 方法論
- [[動態時間規整(Dynamic Time Warping, DTW)]]
- 