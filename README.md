# BottleProgressBar
Ч��
-----------
###1
<br>
![bottleprogress_flash](https://github.com/workdawn/BottleProgressBar/tree/master/raw/bottleprogress_flash.png)

---------
###2
<br>
![bottleprogress_normal](https://github.com/workdawn/BottleProgressBar/tree/master/raw/bottleprogress_normal.png)

------
<br>

˵��
-------
֧�ֵ���������
```
<!-- ƿ���ǿ��ڻ��Ǳտ� -->
<attr name="isOpen" format="boolean"/>
<!-- �Ƿ���ʾ���Ȱٷֱ� -->
<attr name="showPercentText" format="boolean"/>
<!-- ƿ�ڴ�Сһ��-->
<attr name="bottleMouthHalf" format="dimension"/>
<!-- ƿ�ں�ƿ��߶ȱ���-->
<attr name="proportion" format="float"/>
<!-- �սǴ����ȴ�С-->
<attr name="corner" format="float"/>
<!-- ƿ�Ӻ��-->
<attr name="bottleThickness" format="dimension"/>
<!-- ƿ����ɫ-->
<attr name="bottleColor" format="color"/>
<!-- ������ɫ-->
<attr name="waterColor" format="color"/>
<!-- ��Դ��ɫ-->
<attr name="brightColor" format="color"/>
<!-- ���˸���-->
<attr name="waveCount" format="integer"/>
<!-- ���˿��-->
<attr name="waveWidth" format="integer"/>
<!-- ���˵ĸ߶�-->
<attr name="waveHeight" format="integer"/>
<!-- �Ƿ�����������-->
<attr name="openFlash" format="boolean"/>
<!-- �����ٶ� ��λ������-->
<attr name="flashDuration" format="integer"/>

```
ʹ��
------
```
<com.views.bottleprogressbar.widget.BottleProgressBar
        android:id="@+id/progress"
        android:layout_width="100dp"
        android:layout_height="100dp"
        android:progress="50" />
        
```