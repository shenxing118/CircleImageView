# CircleImageView
在https://github.com/hdodenhof/CircleImageView的基础上添加圆角矩形
通过type属性定义类型，默认为圆形图片（circle,roundRect两种类型）
圆角矩形通过round_rect_corner属性设置圆角大小，圆角矩形暂不支持border_overlay属性（边框是否覆盖在图片上）

 <com.widget.shen.circleimageview.CircleImageView
      android:layout_width="100dp"
      ndroid:layout_height="100dp"
      android:layout_marginTop="10dp"
      android:src="@mipmap/avator3"
      app:border_color="@color/colorPrimary"
      app:border_width="5dp" />


  <com.widget.shen.circleimageview.CircleImageView
      android:layout_width="100dp"
      android:layout_height="100dp"
      android:layout_marginTop="10dp"
      android:src="@mipmap/avator3"
      app:border_color="@color/colorPrimary"
      app:border_width="5dp"
      app:round_rect_corner="10dp"
      app:type="roundRect" />
