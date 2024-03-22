## Mobile Program JSON

**Nama :** Anggita Risqi Nur Clarita

**NIM :** 312210450

**Kelas :** TI.22.A.4

**Mata Kuliah :** Pemrograman Mobile

**Dosen Pengampu :** Donny Maulana, S.Kom., M.M.S.I

### Android Studio, JSON (reqres.in), dan Kotlin

**Prerequisites:**

- Instal Android Studio ([https://developer.android.com/studio](https://developer.android.com/studio))
- Pahami dasar Kotlin dan pengembangan Android

**Steps:**

1. **Buat Project Baru:**

   - Buka Android Studio dan pilih "Start a new project".
   - Masukkan nama, language yang ingin dipakai dan target API level.

2. **Tambahkan Dependensi:**

   - Di file `build.gradle` level aplikasi, tambahkan dependensi di bawah `dependencies`:

     ```java
     implementation("androidx.recyclerview:recyclerview:1.1.0")
     implementation("com.github.bumptech.glide:glide:4.11.0")
     implementation("com.loopj.android:android-async-http:1.4.9")

     implementation("com.google.code.gson:gson:2.8.6")

     implementation("com.squareup.retrofit2:retrofit:2.6.4")
     implementation("com.squareup.retrofit2:converter-gson:2.6.4")

     implementation("com.squareup.okhttp3:logging-interceptor:3.8.0")
     debugImplementation("com.github.chuckerteam.chucker:library:3.3.0")
     ```

3. **Model Data (POJO):**

   - Buat file Kotlin baru untuk model data.
   - Gunakan tipe data sesuai struktur JSON dari reqres.in.

4. **Interface Retrofit:**

   - Buat file Kotlin baru (misalnya `ApiService.kt`).
   - Buat interface dengan metode untuk endpoint reqres.in API.

5. **Implementasi Panggilan Jaringan:**

   - Buat file Kotlin (misalnya `ApiConfig.kt`) untuk menangani permintaan jaringan.

6. **Gunakan Data di Activity:**

   - Di file Kotlin activity utama (misalnya `MainActivity.kt`), lakukan panggilan jaringan.

7. **Layout XML:**

   - Buat file layout baru (misalnya `activity_main.xml`) untuk menampilkan data pengguna.

   - Gunakan TextView dll. sesuai kebutuhan.

**Link Video:**

- Youtube : [Click Here](https://youtu.be/z1nB92n-BKc)

**Sumber:**

- Dokumentasi Retrofit: [https://square.github.io/retrofit/](https://square.github.io/retrofit/)
- Dokumentasi Kotlin: [https://kotlinlang.org/docs/](https://kotlinlang.org/docs/)
- Tutorial reqres.in: [https://reqres.in/](https://reqres.in/)
