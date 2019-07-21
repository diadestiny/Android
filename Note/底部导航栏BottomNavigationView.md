## 底部导航栏的实现(BottomNavigationView)
### 1.导入依赖
>implementation 'com.android.support:design:28.0.0'

### 2.xml代码:
```xml
<android.support.design.widget.BottomNavigationView
        android:id="@+id/navigation"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        app:menu="@menu/navigation"
        android:layout_alignParentBottom="true"
        app:labelVisibilityMode="labeled"/>
		<!--在新api中解决超过3个菜单项显示效果问题-->
```
### 3.menu/navigation.xml代码:
```xml
<menu xmlns:android="http://schemas.android.com/apk/res/android">
    <item
        android:id="@+id/navigation_home"
        android:title="test1" />
    <item
        android:id="@+id/navigation_dashboard"
        android:title="test2" />
    <item
        android:id="@+id/navigation_notifications"
        android:title="test3" />
    <item
        android:id="@+id/test4"
        android:title="test4" />
</menu>
```
### 4.java代码:
>找到BottomNavigationView控件,重写setOnNavigationItemSelectedListener方法




