**Introduction**
In the dynamic landscape of garment manufacturing, optimising workforce productivity is pivotal for sustained success.  This project endeavours to unlock patterns and relationships within a comprehensive dataset using advanced clustering techniques.
By employing K-means and hierarchical clustering, the objective is to discern distinct productivity segments which will empower the formulation of more targeted and effective workforce management strategies, contributing to enhanced operational efficiency in the garment industry.

**Dataset**

The dataset sourced from www.kaggle.com/datasets/ comprises key operational metrics essential for optimising workforce output such as day of the week, quarter of the month, department and team numbers, team size, style changes, targeted and actual productivity, Standard Minute Value (SMV), work in progress (WIP), overtime, incentives, idle time, and the count of idle workers, the dataset provides a multifaceted view of productivity dynamics. Temporal factors such as the day and quarter offer contextual insights, unveiling patterns in productivity.
Department and team details bring attention to variations across different production lines or segments, while workforce size and style changes impact overall line efficiency. SMV and targeted productivity serve as benchmarks for core performance evaluation. Variables including WIP and overtime shed light on operational hurdles and the extended working hours required for goal to be achieved. Incentives is a crucial motivator, influencing overall productivity.

The dataset further incorporates idle time and the count of idle workers which are crucial for identifying process bottlenecks and inefficiencies. Finally, the actual productivity percentage stands as a critical outcome measure, reflecting the tangible efficiency of the workforce. 
This dataset forms the cornerstone for a comprehensive analysis of productivity dynamics in the garment manufacturing sector.

#### Clustering Analysis Results

#### K-means Clustering

1. **Optimal Number of Clusters:** 3

2. **Cluster Distribution:**
   - Cluster 0: 598 instances
   - Cluster 1: 586 instances
   - Cluster 2: 13 instances

3. **Cluster Characteristics:**

#### Cluster 0:

- **Moderate Targeted Productivity:** 0.74
- **Low SMV:** 5.30
- **Moderate WIP:** 129.50
- **Moderate Over-time:** 2125.30
- **Moderate Incentives:** 32.47
- **Minimal Idle Time and Men**
- **Low Style Changes:** 0.00
- **Low Number of Workers:** 13.62
- **Moderate Actual Productivity:** 0.76

#### Cluster 1:

- **Lower Targeted Productivity:** 0.72
- **Higher SMV:** 24.39
- **Higher WIP:** 1236.27
- **Higher Over-time:** 6967.70
- **Higher Incentives:** 44.59
- **Minimal Idle Time and Men**
- **Moderate Style Changes:** 0.29
- **Higher Number of Workers:** 54.73
- **Lower Actual Productivity:** 0.72

**Cluster 2:**

- **Low Targeted Productivity:** 0.65
- **High SMV:** 26.24
- **Low WIP:** 572.00
- **High Over-time:** 4241.54
- **Low Incentives:** 3.54
- **High Idle Time and Men**
- **High Style Changes:** 0.69
- **High Number of Workers:** 55.46
- **Lowest Actual Productivity:** 0.42

4. **Visualization:** Scatter plot illustrating data points in reduced dimensions.

**Hierarchical Clustering**

1. **Cluster Distribution:**
   - Cluster 0: 691 instances
   - Cluster 1: 497 instances
   - Cluster 2: 9 instances

**Evaluation Metrics**

Silhouette scores were computed for both K-means and Hierarchical clustering, resulting in values of 0.586 and 0.579, respectively, indicating above-average cohesion and separation.
Calinski-Harabasz scores were also calculated, with K-means achieving a score of 1380.19 and Hierarchical clustering scoring 1292.19, confirming the effectiveness of both methods in separating the data into distinct clusters.

**Conclusion**

Both K-means and Hierarchical clustering methods successfully segmented the dataset into meaningful clusters based on underlying patterns.
The identified clusters offer valuable insights for further analysis and decision-making processes, such as targeted interventions or resource allocation strategies, aimed at enhancing productivity and operational efficiency.

While the current results are promising, it is important to acknowledge that the choice of clustering algorithm and its hyperparameters can significantly impact performance metrics. To ensure robustness and explore alternative methods, further studies should involve the exploration of other clustering algorithms, such as DBSCAN, Gaussian Mixture Models, Mean shift clustering, etc and fine-tuning hyperparameters to optimize cluster quality. This iterative approach will contribute to a comprehensive understanding of the data and may lead to more refined and accurate cluster assignments. The continuous refinement of clustering techniques aligns with the dynamic nature of data analysis, providing an avenue for uncovering deeper insights and improving the overall efficiency of clustering methodologies.

**Acknowledgements**
- Relevant papers

1. Clark, R., & Zhao, L. (2020). Application of Clustering Algorithms in Performance Management. Journal of Data Science.
2. Kapoor, A., & Lee, D. (2022). Predictive Models in Human Resource Management. Journal of Business Analytics.
3. Nguyen, H., et al. (2021). Data-Driven Approaches in Textile Manufacturing. International Journal of Clothing Science and
Technology.
4. Williams, S. (2018). Ergonomics in Apparel Industry: A Study on Worker Efficiency. Journal of Industrial Engineering and
Management.
