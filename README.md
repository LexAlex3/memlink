����
֧����ͨList/����List/˫���������List���͡�
List�е������Item��֧��һ�����ֶΣ����͡������ƣ�+���ɸ��������ԣ�bit��,��������֧�ָ��ֹ��˲���
ǿһ���ԣ��κ�д����ʵʱˢ��bin-log����֤���ݲ���ʧ
���ÿ������������ڴ�ʹ�ã���������Ч��
֧�ֶ����(Ver0.5)����ͬ��洢Ϊ��ͬ�����ļ�����Ǩ��
֧������ͬ��
֧�ֿͻ���
֧�ֵĿͻ���SDK������swig����

C/C++
PHP
Python
Java
����ָ��
�����Դ�perf��memlink/performance/perf��������4�� 32G�ڴ�������Ͻ��еĲ���,�ò�����һ�����صĵ��ͻ���ѹ�����ԣ����Խ��ֻ�����ǹ��п�����

Create 28386.82reqs/s

./perf -h 127.0.0.1 -t 100 -n 10000 -d create -k xyz -s 4

Insert 29033.73reqs/s

./perf -h 127.0.0.1 -t 90 -n 10000 -d insert -k xyz0 -s 4

Range 31384.88reqs/s

./perf -h 127.0.0.1 -t 90 -n 10000 -d range -k xyz0 -f 50 -l 100

Lpop 30930.09reqs/s

./perf -h 127.0.0.1 -t 50 -n 10000 -d lpop -k xyz4 -l 10

Sharding
It supports client-side sharding.

Who is using
���� ����

Road map
Sponsor
sponsored by tianya.inc