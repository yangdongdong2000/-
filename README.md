# -
在海量的网页预训练数据上进行数据聚类，采用bge获取数据的embedding后用kmeans对embedding进行聚类，再对每个类别用tf-idf统计高频关键词，以关键词质量为衡量该类别质量的评价指标，进行上下采样和类别均衡
