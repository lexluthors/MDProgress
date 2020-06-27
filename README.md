# MDProgress
Material Design风格的圆形进度条：

***特性：**

#可以调节进度条的粗细

#可以调节进度条的转速

#可以设置是否带有圆角（线冒）

#可以调节进度条的最大和最小角度范围

#支持颜色队列


![](https://ss1.bdstatic.com/70cFvXSh_Q1YnxGkpoWK1HF6hhy/it/u=1995875337,1872320794&fm=26&gp=0.jpg)


使用方法：

    compile 'com.jaywei:mdprogress:1.0.2'


属性：

    cpb_max_sweep_angle：最大角度属性,默认310
    cpb_min_sweep_angle：最小角度属性，默认最小20
    cpb_cap_round：是否显示线冒（圆角），默认直角false
    cpb_stroke_width：进度条粗细
    cpb_rotation_speed：进度条的整体转速，默认1
    cpb_sweep_speed：进度条颜色部分动画收缩速度，默认1


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
            app:cpb_cap_round="true"
            app:cpb_sweep_speed="1.0"/>
