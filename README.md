# Tutorial Install Flutter
NAMA : Calvin Shandika <br>
NIM : 20175520016 <br>
Prodi : Teknik Informatika <br>
Kode Mata Kuliah : (COE-5109) <br> <img src="logo.png">

LANGKAH-LANGKAH INSTALL FLUTTER: <br>
1.Siapkan Software FLUTTER beserta SDK <br>
2.Kemudian,download Command Line Tools Only pada  web Android Developer: <br>
https://developer.android.com/studio/#command-tools
<img src="develop.PNG">
3.Setelah filenya di download letakkan dalam satu folder yaitu Local Disk (C:\Android) dan setelah itu kita extract.Maka hasilnya akan ada 2 folder yaitu folder flutter dan tools.<br> <br>
4.Selanjutnya silahkan download OpenJDK di halaman ini, dan pilih yang berekstensi zip. sesuaikan dengan sistem operasi yang digunakan, setelah di download jangan lupa untuk mengekstrak ke folder Android yang sudah kita punya sebelumnya dan rename nama folder dari jdk8u212-b03 menjadi openjdk. totalnya sekarang kita punya 3 folder yaitu flutter, tools dan openjdk.<br> <br>
5.Setelah itu, kita harus menge-set Environment Variable dan Path, untuk windows silahkan buka command prompt dan ketikan command perbaris:<br>
•	setx JAVA_HOME “C:\Android\openjdk” <br>
•	setx ANDROID_HOME “C:\Android” <br>
•	setx ANDROID_SDK_ROOT “C:\Android\tools” <br> 
•	setx path “%path%;”C:\Android\sdk;C:\Android\tools\bin;C:\Android\flutter\bin” <br>
<br>
6.Langkah selanjutnya adalah buka Command Prompt di C:/Android/tools/bin lalu jalankan beberapa perintah berikut: <br>
•	sdkmanager “system-images;android-28;default;x86_64” <img src="flutter 4.PNG"> <br>
•	sdkmanager “platform-tools” <img src="flutter 6.PNG"> <br>
•	sdkmanager “build-tools;28.0.3” <img src="flutter 5.PNG"> <br>
•	sdkmanager “platforms;android-28”  <img src="flutter 3.PNG"> <br>
<br>
7.Setelah itu update sdk dengan command : sdkmanager —-update Jangan lupa untuk menjalankan syntax accept licenses nya flutter doctor --android-licenses <img src="flutter 7.PNG"> <br>
8.Selanjutnya install Visual Studio Code dan ekstension flutter serta dart nya. <img src="flutter 1.PNG"> <br>
9.Jika semuanya sudah selesai silahkan buka terminal (Command Prompt) di Android/flutter atau untuk pengguna windows bisa double klik di C:\Android\Flutter\flutter_console.bat dan jalankan perintah flutter doctor, maka hasilnya seperti gambar berikut.
<img src="flutter 2.PNG"> <img src="sdklisence.PNG"> <br>
10.Step terakhir adalah buat project di VsCode dengan klik F1 dan mengetikan Flutter: New Project setelah project selesai di load, klik F5 untuk mendeploy ke android device teman-teman.








