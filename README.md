# MDProgress
类似md风格的圆形进度条：


![](http://opbgt9bbj.bkt.clouddn.com/sadf.gif)


使用方法：

    compile 'com.jaywei:mdprogress:1.0.0'

布局代码：

    <com.jaywei.mdprogress.CircularProgressBar
            android:layout_width="38dp"
            android:layout_height="38dp"
            android:layout_marginBottom="14.0dip"
            android:indeterminate="true"
            app:cpb_color="#ff0000"
            app:cpb_max_sweep_angle="300"
            app:cpb_min_sweep_angle="10"
            app:cpb_rotation_speed="1.0"
            app:cpb_stroke_width="1.7dp"
            app:cpb_sweep_speed="1.0"/>
