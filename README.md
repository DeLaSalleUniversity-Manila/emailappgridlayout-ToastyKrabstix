# emailappgridlayout-ToastyKrabstix


This assignment illustrates the usage of a Grid layout for an Email app.


## Problem:

Design an Android layout for an email application. (Refer to Chapter 5 of Head First Android Development by Dawn Griffiths and David Griffiths for more details.)    

https://github.com/DeLaSalleUniversity-Manila/HeadFirstAndroid 


## Keypoint:

The xml layout is as follows:
```xml
<?xml version="1.0" encoding="utf-8"?>
<GridLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:paddingLeft="@dimen/activity_horizontal_margin"
    android:paddingRight="@dimen/activity_horizontal_margin"
    android:paddingTop="@dimen/activity_vertical_margin"
    android:paddingBottom="@dimen/activity_vertical_margin"
    android:columnCount="2"
    app:layout_behavior="@string/appbar_scrolling_view_behavior"
    tools:showIn="@layout/activity_main"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_row="0"
        android:layout_column="0"
        android:text="@string/to" />

    <EditText
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_gravity="fill_horizontal"
        android:layout_row="0"
        android:layout_column="1"
        android:hint="@string/hint" />

    <EditText
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_gravity="fill"
        android:gravity="top"
        android:layout_row="1"
        android:layout_column="0"
        android:layout_columnSpan="2"
        android:hint="@string/message" />

    <Button
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_row="2"
        android:layout_column="0"
        android:layout_gravity="center_horizontal"
        android:layout_columnSpan="2"
        android:text="@string/send" />

</GridLayout>
```


## Screenshots:

![alt tag](https://github.com/DeLaSalleUniversity-Manila/emailappgridlayout-ToastyKrabstix/blob/master/device-2015-10-05-202214.png)

![alt tag](https://github.com/DeLaSalleUniversity-Manila/emailappgridlayout-ToastyKrabstix/blob/master/device-2015-10-05-202302.png)
