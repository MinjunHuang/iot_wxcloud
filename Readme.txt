***************************************************************
˵����
1. �����汾���԰��ſ� esp_iot_sdk_v1.5.2_wxcloud_beta��
2. ԭʼ�汾�ɽ���΢��LED�Ʊ�׼���ư汾���п��ƣ�
3. �޸����ݣ�
	* ����H5�Զ��������巢���Ŀ������� v161019

***************************************************************
����˵����
    ���ܰ���GPIO4 �̰�ΪLED���أ�������������ģʽ��
 GPIO15 ����airkiss����ָʾLED;
 GPIO12 ����ģ�⿪��LED, GPIO14 ����ģ�ⱨ��LED;

��������˵����
    �޸� airkiss_cloud.h ��  DEVICE_LICENCE ������Ϊ��ʵ��ֵ
    �޸� airkiss_lan.h �� DEVICE_TYPE �� DEVICE_ID ����Ϊ��ʵ��ֵ
    
 ΢��Ӳ����ϸʹ��˵����
    ΢��Ӳ���Ʊ�׼�������̣�http://iot.weixin.qq.com/wiki/new/index.html?page=3-3
    ΢��Ӳ����ֱ�������ĵ���http://iot.weixin.qq.com/wiki/new/index.html?page=4-4-2
    �豸ֱ��΢��Ӳ���ư�����http://iot.weixin.qq.com/wiki/new/index.html?page=5-5

���ر���ѡ�
    BOOT?=new
    APP?=1
    SPI_SPEED?=40
    SPI_MODE?=QIO
    SPI_SIZE_MAP?=2
    
��¼��ַ��
	boot.bin--------------->0x00000
	user1.1024.new.2.bin--->0x01000
	esp_init_data_default-->0xfc000
	blank.bin-------------->0xfe000
	

��־��ӡ��
    ����ʱ��� GLOBAL_DEBUG �궨�壨Makefile ���Ѿ���ӣ����Կ�����ӡ����
    Ĭ�ϴ���0�����־��������Ϊ115200


