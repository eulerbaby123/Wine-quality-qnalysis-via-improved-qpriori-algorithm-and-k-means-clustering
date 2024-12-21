the zip is the code for Wine quality qnalysis via improved qpriori algorithm and k-means++ clustering

if you want to apply the code to your research. read readour.txt in the zip file for more imformations.
due the limited time , i have too many exam , i don't have the time to write a detailed readme.md , I will come back during the Winter vacation!!!!!

/////////////////////////////////////////////////////////////////////////////////////////
Wine quality qnalysis via improved qpriori algorithm and k-means++ clustering
Weijian Xie¹
¹Jiangnan University, School of Artificial Intelligence and Computer Science, Wuxi 214122, China;
Abstract
Abstract: Objective The evaluation of wine quality is a complex problem involving multiple chemical components and sensory characteristics. 
Traditional association rule mining methods struggle with efficiency when processing continuous variables, while clustering methods are effective for feature discretization but lack capabilities for uncovering deeper associations. 
To address these limitations, we propose a comprehensive data mining framework that integrates the improved Apriori algorithm, K-means++ clustering, 
and feature subset selection to uncover the underlying associations between wine quality and its attributes. 
Method The study begins with extensive data preprocessing, including cleaning and standardization. Outliers are removed using the Interquartile Range (IQR) and Z-score methods to enhance data quality. 
Next, continuous variables are discretized using the K-means++ clustering algorithm, with the optimal number of clusters determined by the silhouette coefficient method, achieving both dimensionality reduction and feature discretization. 
The discretized data are then analyzed using an improved Apriori algorithm, which dynamically adjusts the support threshold and incorporates feature subset selection to optimize efficiency and improve rule interpretability. 
Result Experimental results demonstrate that the proposed method effectively identifies significant relationships between wine quality and its attributes. For instance, lower density samples are more likely to have higher quality ratings, 
and moderate alcohol levels are strongly correlated with superior wine quality. 
The improved Apriori algorithm, enhanced with dynamic support thresholding and feature subset selection, reduces redundant computations while improving rule quality. 
The discovered associations provide actionable insights into key factors influencing wine quality, such as alcohol content and density. 
Conclusion This study presents a novel data mining approach that combines K-means++ clustering, feature subset selection, and an improved Apriori algorithm to address challenges in mining associations within continuous variable datasets. 
The framework demonstrates significant improvements in efficiency and accuracy, not only in wine quality analysis but also as a reference for mining continuous data in other domains.
Key words:
data mining; K-means++ clustering; Apriori algorithm; association rule mining; wine quality analysis; dynamic support threshold; feature discretization; feature subset selection

