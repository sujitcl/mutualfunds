# mutualfunds
Multi fund Portfolio Analysis Using Clustering Techniques

The code involves the following modules

1. Daily crawling of MF NAVs and Holding patterns from a set of public repositories and saving the data in a SQL db
2. Portfolio Cohorts are analyzed for Diversity Index to avoid overlap of underlying holdings
3. Portfolio performance

<p>  Principal Component Analysis is done to reduce the performance dimensions across multiple timeframes ( Short term to Long Term )
<p> Distance Based algorithms are used to find similarity/dissimilaroty of funds based on holding patterns of underlying stocks </p>

#### Example 1 - Long Term vs Short Term Returns

![image](https://user-images.githubusercontent.com/17408955/215094078-013ceb07-fd9e-4107-be97-8d314c7896bd.png)


#### Example 2 - Risk vs Performance ( A Stability Index is used to represnt risk)

![image](https://user-images.githubusercontent.com/17408955/215094483-304e304f-9a7d-4f0c-991a-c4cc5923e51b.png)

#### Example 3 - Portfolio Diversity Heatmap

![image](https://user-images.githubusercontent.com/17408955/215094933-62b1aa7b-b62f-4990-9ae2-8a7901c5506a.png)


#### Example 4 - Fund Similarity (Top 10 Closest Funds)

![image](https://user-images.githubusercontent.com/17408955/215095639-ec88d150-f2fe-449a-9f3a-d09c53d9fd3e.png)


#### Example 5 - Fund Similarity based on Multi-timeframe Return History

![image](https://user-images.githubusercontent.com/17408955/215095785-2da152f1-f4c1-48ba-a4b5-d65b77a6d6b2.png)

