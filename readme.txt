1.�� tsb_codegen\properties\generator.properties 
�����dbUrl��jdbcDriver����userName pass, schema ���޸�,��Ϊ�����ӵ��ǲ�ͬ�����ݿ�

dbUserid=tsb
dbPasswd=tsb
dbSchema=tsb
jdbcDriver=com.mysql.jdbc.Driver
dbUrl=jdbc:mysql://10.0.10.21:3306/tsb_ischool_qingguo


2.�޸���Ҫ������ʵ��ı����Ͷ�Ӧ��ʵ�����֣��ÿո����
�޸� tsb_codegen\ssbTables�ļ� ����ı�����ֺͱ��Ӧ��javaʵ��������֣����硣
t_u_basic User
t_u_basic User2


3.�޸İ�ǰ׺��Ϊ�����ɵĴ�����Ҫ���Ӧ����Ŀ·���������Ҫ�������޸�
�� tsb_codegen\properties\generator.properties��������

#�����İ�·��
packageLocation=com/test
#java��ǰ׺
packagePrefix=com.test


4.ִ��
ִ�� com.codegenerator.runner.AppFuseGenerator ��

5.ִ�к󣬴�����tsb_codegen\build ����

6.����ṹ
	src\dao
	src\model
	src\service
	src\webservice












2007-1-31 
���ģ�Ͳ�ӳ���������
����Զ�����ssb-dao.xml��ssb-ds.xml
�Զ�����session-factory�����õ�hbm.xml

