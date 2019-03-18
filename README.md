# TableLayout
线性布局：
==
tablelayout.xml
--
    <?xml version="1.0" encoding="utf-8"?>
    <TableLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:stretchColumns="2"
    android:background="#000000">

    <TableRow>

        <TextView
            android:id="@+id/t1"
            android:layout_height="wrap_content"
            android:layout_column="0"
            android:textColor="@drawable/text"
            android:gravity="center"
            android:text="@string/open" />

        <TextView
            android:id="@+id/t2"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_column="3"
            android:text="@string/ctrl_o"
            android:gravity="end"
            android:textColor="@drawable/text" />
    </TableRow>
    <TableRow>

        <TextView
            android:id="@+id/t3"
            android:layout_height="wrap_content"
            android:layout_column="0"
            android:text="@string/save"
            android:gravity="center"
            android:textColor="@drawable/text" />

        <TextView
            android:id="@+id/t4"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_column="3"
            android:text="@string/ctrl_s"
            android:gravity="end"
            android:textColor="@drawable/text" />
    </TableRow>
    <TableRow>

        <TextView
            android:id="@+id/t5"
            android:layout_height="wrap_content"
            android:layout_column="0"
            android:text="@string/save_as"
            android:gravity="center"
            android:textColor="@drawable/text" />

        <TextView
            android:id="@+id/t6"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_column="3"
            android:text="@string/ctrl_shift_s"
            android:textColor="@drawable/text" />
    </TableRow>
    <View
        android:layout_width="fill_parent"
        android:layout_height="1dip"
        android:background="#c2b9b9" />
    <TableRow>

        <TextView
            android:id="@+id/t7"
            android:layout_width="72dp"
            android:layout_height="wrap_content"
            android:layout_column="0"
            android:text="@string/x_import"
            android:textColor="@drawable/text" />


    </TableRow>
    <TableRow>

        <TextView
            android:id="@+id/t8"
            android:layout_height="wrap_content"
            android:layout_column="0"
            android:text="@string/x_expot"
            android:textColor="@drawable/text" />

        <TextView
            android:id="@+id/t9"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_column="3"
            android:text="@string/ctrl_shift_s"
            android:textColor="@drawable/text" />
    </TableRow>
    <View
        android:layout_width="fill_parent"
        android:layout_height="1dip"
        android:background="#c2b9b9" />
    <TableRow>

    <TextView
        android:id="@+id/t10"
        android:layout_height="wrap_content"
        android:layout_column="0"
        android:text="@string/quit"
        android:gravity="center"
        android:textColor="@drawable/text"/>
    </TableRow>
    </TableRow>
    
colors.xml
--
    <?xml version="1.0" encoding="utf-8"?>
    <resources>
    <color name="colorPrimary">#008577</color>
    <color name="colorPrimaryDark">#00574B</color>
    <color name="colorAccent">#D81B60</color>
    </resources>
    
strings.xml
--
    <resources>
    <string name="app_name">TableLayout</string>
    <string name="quit">     Quit...</string>
    <string name="ctrl_shift_s">Ctrl-Shift-S</string>
    <string name="x_expot">X Expot...</string>
    <string name="x_import">X Import...</string>
    <string name="ctrl_shift_s">Ctrl-Shift-S</string>
    <string name="save_as">Save As...</string>
    <string name="ctrl_s">Ctrl-S</string>
    <string name="save">Save...</string>
    <string name="open">Open...</string>
    <string name="ctrl_o">Ctrl-O</string>
    </resources>
    
styles.xml
--
    <resources>

    <!-- Base application theme. -->
    <style name="AppTheme" parent="Theme.AppCompat.Light.DarkActionBar">
        <!-- Customize your theme here. -->
        <item name="colorPrimary">@color/colorPrimary</item>
        <item name="colorPrimaryDark">@color/colorPrimaryDark</item>
        <item name="colorAccent">@color/colorAccent</item>
    </style>

    </resources>
    
text.xml
--
    <?xml version="1.0" encoding="utf-8"?>
    <selector xmlns:android="http://schemas.android.com/apk/res/android">
    <!-- 字体颜色 -->
    <item android:color="#c2b9b9"/>
    </selector>


运行结果：
--





