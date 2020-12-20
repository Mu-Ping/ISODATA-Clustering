# ISODATA-Clustering
> 全名：Iterative Self Organizing Data Analysis Techniques Algorithm，迭代自組織數據分析方法

## 簡介
* ISODATA算法和K-Means算法是相似的算法，都是屬於無監督的聚類分析方法

* ISODATA**增加「合併」、「分裂」操作**，進而改進K-Means的一大缺陷：「K值需要預先設定」
  * **合併** -「兩聚簇中心的值小於某閾值」或(且) 「某聚簇內樣本數少於一定閾值」，將最近的2個聚類中心合併。
  
  * **分裂** -「某聚簇的標準差大於一定閾值」 或(且) 「某聚簇內樣本數超過一定閾值」，將該聚簇分裂為2個聚簇。
  
  > **「合併」、「分裂」的操作可以根據不同情境客製化，上述只是其中一種**
* ISODATA以K-Means為基礎，核心概念一樣，故相關知識請參考：[K-Means-Clustering](https://github.com/Mu-Ping/K-Means-Clustering)

## 演算法步驟
