# Tujuan
Pada materi kali ini Anda akan belajar menerapkan dua mekanisme umum dalam memanfaatkan komponen broadcast receiver yaitu :

* Implementasi broadcast receiver untuk menerima event yang di-broadcast oleh sistem Android. Kali ini kita akan menerima broadcast ketika ada SMS yang masuk.
* Implementasi broadcast receiver untuk komunikasi antar aplikasi.

![MyBroadcastReceiver](https://user-images.githubusercontent.com/68750843/116499867-63c19c80-a8d7-11eb-9f12-aafa4bd9bcd7.gif)

![MyBroadcastReceiver1](https://user-images.githubusercontent.com/68750843/116502422-a71f0980-a8dd-11eb-8726-be94eed7a955.gif)

# Logika Dasar
Melakukan klik ke button permission → untuk check permissionSMS → ada sms masuk → menerima dengan broadcast receiver → menampilkan kelayar Android.

Melakukan klik ke button download → menjalankan background service → proses selesai → menampilkan dalam bentuk toast atau pesan singkat.