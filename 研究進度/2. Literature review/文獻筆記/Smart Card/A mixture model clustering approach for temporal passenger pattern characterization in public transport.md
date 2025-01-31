#culstering #票證資料 #two_level_generative_mixture_model 

---
## 文獻
| 研究主題                     | 參考文獻              | 主要發現                                                                                                                          |
| ------------------------ | ----------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| 豐富電子票證資料以推斷缺失的出行目的地和轉乘信息 | [3, 4, 14, 16]    | 豐富電子票證資料以推斷缺失的出行目的地和轉乘信息，從而進一步研究出行數據                                                                                          |
| 資料挖掘在電子票證資料中的應用          | [11, 6, 13, 7, 8] | 通過資料挖掘研究出行行為的不同方面，如出行行為的變異性、乘客忠誠度、社區福祉等                                                                                       |
| 層次聚合聚類在乘客出行行為分析中的應用      | [8]               | 使用層次聚合聚類分析乘客平日出行行為，揭示不同的出行行為模式並強調使用電子票證資料建立使用者定制的交通資訊服務的必要性                                                                   |
| k-means++在乘客出行規律分析中的應用   |                   | 提出了一種有效的數據挖掘方法，用於分析北京市乘客的公共運輸使用者出行模式。通過電子票證數據的時間和空間特徵，識別乘客的行程鏈，並應用DBSCAN和K-Means++算法進行出行模式的聚類和分類。研究結果顯示，粗糙集基算法在準確性和效率上優於其他算法。 |
|                          |                   |                                                                                                                               |

--- 

### 文獻回顧
- 分析方法
	- 根據旅行時間將使用者進行分群(組)，以提取不同模式的使用者(典型通勤行為、零星使用)
	- 提出**基於旅行時間**的使用者聚類方法。
	- [[研究進度/文獻回顧/Annotation/A mixture model clustering approach for temporal passenger pattern characterization in public transport#^bg84k6em689|考慮了時間的連續性]]，而不是大多數現有方法使用的時間段分群(組)，並依賴於從乘客的時間特徵估計高斯混合模型。
- 資料集
	- 資料時間
		- 2014年4月(一個月)
	- 原始資料處理(旅次目的地估計)
		- [用這篇文章](https://www.tandfonline.com/doi/full/10.1080/15472450601122256)
		- [還有這篇](https://journals.sagepub.com/doi/10.3141/1817-24)
	- 資料集特徵
		- **匿名ID資料**：	
			- 每次驗證記錄包含唯一的匿名卡ID。
		- **上車時間**：
		    - 記錄上車的日期和時間（精確到分鐘）。
		- **上車地點**：
		    - 記錄上車的地點。
		- **搭乘路線**：
		    - 記錄所搭乘的巴士或地鐵線路。
		- **票種**：使用者類別
			- 按次付費
			- 免費乘車（基於社會標準，如收入、就業）
			- 短期訂閱者（少於一週）
			- 年輕訂閱者
			- 訂閱者
			- 老年訂閱者
			- Keolis Rennes（KR）代理
	- 資料分佈結構
		- **每週模式**
		    - 平日有三個高峰：早晨、中午、晚上。
		    - 早晨高峰最集中，表示早晨的旅行更規律。
		    - 中午高峰較小，可能因為午休期間乘客較少使用交通網絡。
		- **星期三特別模式**
		    - 星期三中午刷卡次數增加，因為法國中小學生和高中生通常星期三下午沒有課。
		- **最繁忙的一天**
		    - 星期二是活動最繁忙的一天。
		- **夜間活動**
		    - 星期四、星期五和星期天有夜間活動，旅行在服務結束和開始時被記錄。
		- **週末模式**
		    - 週末活動較少，尤其是星期天。
		    - 週末沒有三個高峰的模式，只有下午的一個分散高峰。
- 模型方法
- 結果
	- 