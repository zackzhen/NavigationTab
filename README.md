# NavigationTab
炫酷tab栏  基于第三方开源组件
# 使用方式
setViewPager
setOnPageChangeListener
setTabIndex 跳转指定下标
setTitles 设置标题
getTabIndex 获取下标
setAnimationDuration 设置动画时长

# xx.setTitles(xx.titles[0],"")
动态设置指定下标的标题

# XML布局文件设置方式
    <com.xx.xx.NavigationTabStrip
        android:id="@+id/navi_tab"
        android:layout_width="match_parent"
        android:background="#FFF"
        android:layout_height="40dp"
        android:layout_gravity="center"
        app:nts_Strip="170"
        app:nts_active_color="#3296fa"
        app:nts_animation_duration="50"
        app:nts_color="#3296fa"
        app:nts_corners_radius="3dp"
        app:nts_gravity="bottom"
        app:nts_inactive_color="#ff1a1e23"
        app:nts_size="14sp"
        app:nts_weight="3dp" />
