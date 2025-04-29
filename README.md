# Log-Toast

Main.Activity.xml
'''
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/main"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">



        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:orientation="vertical"
            android:padding="16dp">

            <EditText
                android:id="@+id/website_edit_text"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:hint="@string/edit_website"
                android:inputType="textUri"
                android:autofillHints="username"
                android:paddingVertical="12dp"
                android:layout_marginBottom="8dp"/>

            <Button
                android:id="@+id/open_website_button"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="@string/button_website"
                android:layout_marginBottom="24dp"
                android:paddingVertical="12dp" />

            <EditText
                android:id="@+id/location_edit_text"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:hint="@string/edit_location"
                android:inputType="text"
                android:autofillHints="postalAddress"
                android:paddingVertical="12dp"
                android:layout_marginBottom="8dp"/>

            <Button
                android:id="@+id/location_button"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="@string/button_location"
                android:layout_marginBottom="24dp"
                android:paddingVertical="12dp" />

            <EditText
                android:id="@+id/share_edit_text"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:hint="@string/edit_share"
                android:inputType="text"
                android:autofillHints="username"
                android:paddingVertical="12dp"
                android:layout_marginBottom="8dp"/>

            <Button
                android:id="@+id/share_text_button"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="@string/button_share"
                android:layout_marginBottom="24dp"
                android:paddingVertical="12dp" />
        </LinearLayout>

    </androidx.constraintlayout.widget.ConstraintLayout>

'''
