# splash-screen
splash screen xml code for front end
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/splash"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
android:orientation="vertical"
    tools:context="eighteen.cmp.mani.friendlyvission.Splash">
    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_gravity="center"
        android:gravity="center"
        android:orientation="vertical">
<ImageView
    android:layout_width="150dp"
    android:layout_height="150dp"
    android:foregroundGravity="center"
    android:src="@drawable/blind"/>
        <TextView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:padding="10dp"
            android:text="Visulaly Impaird"
            android:textStyle="bold"
            android:layout_gravity="bottom"
            android:textSize="18dp"
            android:textColor="@color/colorAccent"
            android:gravity="bottom|center"
            android:fontFamily="cursive"/>
    </LinearLayout>
</LinearLayout>
