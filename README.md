    <RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <ImageView
        android:src="@drawable/marvin_the_paranoid"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:scaleType="centerCrop"
        />

    <TextView
        android:text="Wearily I sit here,"
        android:id="@+id/hp_malvin"
        android:textColor="#1B5E20"
        android:fontFamily="sans-serif-light"
        android:textStyle="bold"
        android:padding="12dp"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignParentRight="true"
        android:textSize="32sp" />

    <TextView
        android:text="pain and"
        android:layout_above="@id/companions"
        android:id="@+id/pain"
        android:textColor="#1B5E20"
        android:fontFamily="sans-serif-light"
        android:textStyle="bold"
        android:paddingLeft="20dp"
        android:paddingRight="15dp"
        android:paddingTop="15dp"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignParentLeft="true"
        android:textSize="28sp"/>

    <TextView
        android:text="error messages"
        android:layout_above="@id/companions"
        android:layout_toRightOf="@id/pain"
        android:id="@+id/error_messages"
        android:textColor="#F44336"
        android:fontFamily="sans-serif-light"
        android:textStyle="bold"
        android:paddingRight="15dp"
        android:paddingTop="15dp"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:textSize="28sp"/>

    <TextView
        android:text="my only companions."
        android:id="@+id/companions"
        android:textColor="#1B5E20"
        android:fontFamily="sans-serif-light"
        android:textStyle="bold"
        android:paddingLeft="20dp"
        android:paddingRight="15dp"
        android:paddingBottom="20dp"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_alignParentBottom="true"
        android:layout_alignParentLeft="true"
        android:textSize="28sp"/>

    <ImageView
        android:src="@drawable/smiley"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:scaleType="centerCrop"
        android:layout_centerHorizontal="true"
        android:layout_centerVertical="true"
        android:paddingBottom="16dp"
        android:paddingRight="16dp"
        />
    
</RelativeLayout>
