# AndroidProjectCustomViewsMaven


# 手势解锁控件 #
1、引入方式：  implementation('com.androidProjectCustomViews:androidProjectCustomViews:1.0.0@aar')

2、布局使用：

     <com.androidprojectcustomviews.SudokuSwipeGesturesView
        android:layout_width="375dp"
        android:layout_height="375dp"
        android:background="#ffffff"
        app:circleInnerRingRadius="11dp"
        app:circleEffectiveRadius="33dp"
        app:circleInnerRingUnSelectedColor="#dfdfdf"
        app:circleInnerRingSelectedColor="#4885fc"
        app:circleOuterRingSelectedColor="#4c4885fc"
        app:circleInnerRingErrorColor="#4885fc"
        app:circleOuterRingErrorColor="#4c4885fc"
        app:connectingLineColor="#4885fc"
        app:connectingLineErrorColor="#4885fc"
        app:circleShowType="CIRCLE_SHOW_TYPE_2"/>
3、参数含义：

    circleEffectiveRadius//圆圈的有效半径
    circleInnerRingRadius//圆圈的内圈半径
    circleOuterRingRadius//圆圈的外圈半径
    circleOuterRingBorderWidth//圆圈的外圈的边框宽度
    circleInnerRingSelectedColor//圆圈内圈选中颜色
    circleInnerRingUnSelectedColor//圆圈内圈未选中颜色
    circleInnerRingErrorColor//圆圈内圈错误颜色
    circleOuterRingSelectedColor//圆圈外圈选中颜色
    circleOuterRingUnSelectedColor//圆圈外圈未选中颜色
    circleOuterRingErrorColor//圆圈外圈错误颜色
    circleShowType//圆圈显示模式
    isShowTrack//是否显示绘制轨迹
    connectingLineColor//连接线链接时颜色
    connectingLineErrorColor//连接线错误的时候的颜色
    connectingLineWidth//连接线宽度