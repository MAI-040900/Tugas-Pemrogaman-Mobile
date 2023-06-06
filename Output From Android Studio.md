# Tugas-Pemrogaman-Mobile
![Output activity_main](https://github.com/MAI-040900/Tugas-Pemrogaman-Mobile/assets/134959168/956d19af-5f81-4a2f-8bc4-bdcdbe7d74e8)

<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity"
    android:background="@color/background">


    <ImageView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:src="@drawable/gambar0"
        android:layout_marginTop="10dp"
        android:layout_alignParentTop="true"
        android:layout_alignParentLeft="true"
        android:id="@+id/img_1"
        />
    <ImageView
        android:layout_width="350dp"
        android:layout_height="350dp"
        android:src="@drawable/gambar001"
        android:layout_below="@id/img_1"
        android:layout_centerHorizontal="true"
        android:id="@+id/img_2"
        />
    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@id/img_2"
        android:text="WELCOME"
        android:layout_centerHorizontal="true"
        android:fontFamily="@font/poppinssemibold"
        android:textSize="30sp"
        android:textColor="@color/black"
        android:id="@+id/txt_1"
        />

    <TextView
        android:id="@+id/txt_2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@id/txt_1"
        android:layout_marginTop="0dp"
        android:fontFamily="@font/poppinsregular"
        android:gravity="center"
        android:textSize="20sp"
        android:padding="22dp"
        android:text="Solve your complaints with the KLINIK ATLANTIC "
        android:textColor="@color/black" />

    <Button
        android:id="@+id/btn_1"
        android:layout_width="wrap_content"
        android:layout_height="50dp"
        android:layout_below="@id/txt_2"
        android:layout_centerHorizontal="true"
        android:layout_marginStart="12dp"
        android:layout_marginTop="12dp"
        android:layout_marginEnd="12dp"
        android:layout_marginBottom="12dp"
        android:width="300dp"
        android:background="@drawable/button_shape"
        android:fontFamily="@font/poppinssemibold"
        android:text="Login"
        android:gravity="center"
        android:textColor="@color/white"
        android:textSize="20dp"
        />

    <Button
        android:id="@+id/btn_2"
        android:layout_width="wrap_content"
        android:layout_height="50dp"
        android:layout_below="@id/btn_1"
        android:layout_centerHorizontal="true"
        android:layout_marginStart="12dp"
        android:layout_marginEnd="12dp"
        android:layout_marginBottom="12dp"
        android:width="300dp"
        android:background="@drawable/button_shape"
        android:fontFamily="@font/poppinssemibold"
        android:text="Regrister"
        android:gravity="center"
        android:textColor="@color/white"
        android:textSize="20dp"
        />
</RelativeLayout>

![Output activity_login](https://github.com/MAI-040900/Tugas-Pemrogaman-Mobile/assets/134959168/e09e7ad1-b697-4124-912e-9ff4f680c749)

<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".RegisterActivity"
    android:background="@color/background">

    <ImageView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:src="@drawable/gambar0"
        android:layout_marginTop="10dp"
        android:layout_alignParentTop="true"
        android:layout_alignParentRight="true"
        android:id="@+id/L_img_1"
        />
    <ImageView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:src="@drawable/ic_back"
        android:layout_marginLeft="16dp"
        android:layout_marginTop="16dp"
        />
    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@id/L_img_1"
        android:text="Welcome Back!"
        android:layout_marginTop="20dp"
        android:layout_centerHorizontal="true"
        android:fontFamily="@font/poppinssemibold"
        android:textSize="30sp"
        android:textColor="@color/black"
        android:id="@+id/L_txt_1"
        />
    <ImageView
        android:layout_width="350dp"
        android:layout_height="300dp"
        android:layout_below="@id/L_txt_1"
        android:src="@drawable/gambar003"
        android:id="@+id/L_img_2"
        android:layout_centerHorizontal="true"
        />
    <LinearLayout
        android:id="@+id/ly_1"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="vertical"
        android:layout_below="@+id/L_img_2"
        android:padding="30dp"
        >

        <EditText
            android:layout_width="match_parent"
            android:layout_height="57dp"
            android:background="@drawable/button_shape1"
            android:layout_marginTop="10dp"
            android:gravity="center"
            android:text="Enter Your Email"
            android:paddingLeft="10dp"
            android:textSize="20dp"
            android:textColor="@color/black"
            android:fontFamily="@font/poppinsregular"
            android:id="@+id/edt_email"
            />

        <EditText
            android:layout_width="match_parent"
            android:layout_height="57dp"
            android:background="@drawable/button_shape1"
            android:layout_marginTop="10dp"
            android:gravity="center"
            android:textSize="20dp"
            android:hint="Confirm Password"
            android:paddingLeft="10dp"
            android:textColor="@color/black"
            android:fontFamily="@font/poppinsregular"
            android:id="@+id/edt_conf_password"
            />

    </LinearLayout>
    <Button
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:gravity="center"
        android:text="Login"
        android:layout_below="@id/ly_1"
        android:layout_centerHorizontal="true"
        android:background="@drawable/button_shape"
        android:width="300dp"
        android:textColor="@color/white"
        android:textSize="18sp"
        android:id="@+id/L_btn_1"
        android:fontFamily="@font/poppinsbold"
        />
    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal"
        android:layout_below="@+id/L_btn_1"
        android:gravity="center"
        android:layout_marginTop="20dp">
        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Not have an account?"
            android:textColor="@color/black"
            android:fontFamily="@font/poppinsregular"
            android:textSize="12sp"
            />
        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Register"
            android:fontFamily="@font/poppinssemibold"
            android:id="@+id/txt_register"
            android:textSize="12sp"
            android:textColor="@color/primaryColor"
            />

    </LinearLayout>

</RelativeLayout>

![Output activity_regrister](https://github.com/MAI-040900/Tugas-Pemrogaman-Mobile/assets/134959168/0a1a8376-92a8-4a22-b4b5-ec9bed5e8207)
