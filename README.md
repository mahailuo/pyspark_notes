���ǹ���ѧϰpyspark��һЩ�ʼǣ��ο����ϡ�Python+Spark2.0+hadoop����ѧϰ�������ʵս  �ִ��������������Ȥ�������������������鼮��

˵����
	1������Ŀ�µĴ���Ϊjupter notebook����ȷ���Լ�����ȷ����spark��hadoop
	2��sc��sparkʵ�����Զ�����
	3������������л�������Hadoop 2.7,spark 2.3

����ʾ����
	1��textfile=sc.textFile("file:/c:/f/test.txt")#�����ļ�ע��·����д��ʽfile:
	2��textfile=sc.textFile("hdfs:/hdfsfile/test/test.txt")#hdfs�ļ�ע��·����д��ʽhdfs:
	3��strRDD=sc.parallelize(list(('app','note','oran','app','grap')))