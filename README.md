# Server-Settings For Windows
## 1.�����д���
������Ѱ�XShell: https://www.netsarang.com/zh/free-for-home-school/

��װ֮�������Ͻ� **�ļ� -> �½�**

���**����**

<img src="https://github.com/LibertFan/Server-Settings/blob/master/img/XShellHost.png" width='400'/>

��**����**������������

**����**����ӹ���Ա���õ���IP

**�˿ں�**���ر������������֪�ᣩ����22

���**�û������֤**

<img src="https://github.com/LibertFan/Server-Settings/blob/master/img/XShellUserPasswd.png" width='400'/>

**�û���**����ӹ���Ա���õ����û���

**����**����ӹ���Ա���õ�������

## 2.�����Լ��ķ���������

### 2.1.ʹ������
���Լ��ĵ�����ʹ�ñ༭����**FUDAN.py**

<img src="https://github.com/LibertFan/Server-Settings/blob/master/img/Fudan.png" width='400'/>

��18��19�е�**���ѧ��**��**�������**�������Լ��ĸ���ѧ�ź����롣

ʹ��WinSCP��Fudan.py�ļ��ϴ����������Լ����ļ���*/home/����˻�*�¡�

ʹ��XShell���ӵ����������������´���:
```
python2 FUDAN.py
```

����ʮ����֮��ʹ��**Ctrl+C**ֹͣ����

ʹ�����´���������Ƿ����ӵ�����:

```
ping www.baidu.com
```
�����������������˵�����Ѿ��ɹ����ӵ����磨��������ϵ����Ա����ʹ��**Ctrl+C**ֹͣ����

<img src="https://github.com/LibertFan/Server-Settings/blob/master/img/FudanSuccess.png" width='200'/>

### 2.2.����Ananconda
�������°��Anaconda: https://mirrors.tuna.tsinghua.edu.cn/anaconda/archive/

�ҵ��Լ���Ҫ���ص�Anaconda�汾���Ҽ���������

ʹ������Ĵ���ֱ�����ص��������ϣ�
```
wget url
```

### 2.3.��װAnaconda
ʹ�����������������һ�����ص��ļ�
```
bash AnacondaXXXX.sh
```
�ڰ�װ�����һ���Ƿ�Ҫ��anaconda�µ�python��Ϊ�Լ���Ĭ��python��ѡ��yes����һ�������Ὣanaconda�µ�python·����ӵ� ~/.bashrc �¡�

```
vim ~/.bashrc** 
```
ʹ������Ĵ������鿴·���Ƿ���ӳɹ������ļ�ĩβ��������ͼ��ʾ�����û���ҵ��������Լ�������ͼ���� ~/.bashrc ���м��루ע���Լ����ص�anaconda�İ汾�ţ���ʹ��**Esc -> :q**���˳�vim��

<img src="https://github.com/LibertFan/Server-Settings/blob/master/img/BashAnaconda.png" width='200'/>

�����ӳɹ�������**source ~/.bashrc**��ʹ·����Ч��

�������е�������
```
python
```
������Լ���python�汾���������anaconda������������ͼ��ʾ����˵����װ�Ѿ��ɹ���

<img src="https://github.com/LibertFan/Server-Settings/blob/master/img/PythonVersion.png" width='200'/>

### 2.4.��װ�������python��
ʹ������������д������鿴��������**CUDA�汾**��
```
nvcc -V
```

����pytrorch�Ľ̳̻���tensorflow�Ľ̳�����ɰ�װ

## 3.

## 4.