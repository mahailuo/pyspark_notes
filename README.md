这是关于学习pyspark的一些笔记，参考资料《Python+Spark2.0+hadoop机器学习与大数据实战  林大贵著》，如有兴趣请自行搜索购买正版书籍！

说明：
	1、本项目下的代码为jupter notebook，请确保自己已正确连接spark和hadoop
	2、sc和spark实例已自动生成
	3、本代码的运行环境是下Hadoop 2.7,spark 2.3

代码示例：
	1、textfile=sc.textFile("file:/c:/f/test.txt")#本地文件注意路径书写格式file:
	2、textfile=sc.textFile("hdfs:/hdfsfile/test/test.txt")#hdfs文件注意路径书写格式hdfs:
	3、strRDD=sc.parallelize(list(('app','note','oran','app','grap')))