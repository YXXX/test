# test
两个测试
问题描述1：考察分布式机器学习，当文件过大，不能导入到单机中，如何分布是实现K-means。
思路：需要进行的操作包括，将大文件导入到多台机器，这里用的是hdsf文件系统，利用命令行导入大文件到系统中。在spark中利用hdsf中的数据实现k-means，最后将k-means的代码提交到集群执行。
问题描述2：如何给商家推荐客户。
思路：
