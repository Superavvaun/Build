# 🥝 Kiwi Browser - Custom Build (Public Archive)

![build apk](https://img.shields.io/badge/build-optimized-brightgreen)
![platform](https://img.shields.io/badge/platform-Android_arm64--v8a-orange)

Selamat datang! Repositori ini adalah hasil modifikasi dan otomatisasi alur kerja (*workflow*) untuk membangun **Kiwi Browser** secara mandiri menggunakan GitHub Actions. Proyek ini difokuskan pada stabilitas build untuk arsitektur modern 64-bit.

---

## 🛠️ Informasi Proyek (Public Archive)
Repositori ini bersifat **Public Archive**. Silakan gunakan repositori ini sebagai referensi atau fondasi untuk proyek kamu sendiri:
* **Bebas Dikembangkan:** Kamu sangat dipersilakan untuk melakukan *Fork*, memodifikasi tampilan (*UI/UX*), menambahkan fitur, atau mengoptimalkan kode lebih lanjut.
* **Open for All:** Jika kamu berhasil meningkatkan kecepatan build atau memperbaiki bug pada script `.yml`, jangan ragu untuk berbagi melalui *Pull Request*.
* **Status:** Build ini disediakan "apa adanya" (*as-is*) untuk tujuan edukasi dan pengembangan hobi.

---

## 🚀 Fitur Build Ini
* **High Performance:** Dioptimalkan khusus untuk perangkat Android **arm64-v8a**.
* **Smart Automation:** Menggunakan filter kustom `vpython` untuk mengakali keterbatasan *Depot Tools* Google di lingkungan GitHub Runner.
* **Dual Python Setup:** Perpindahan otomatis antara Python 2 (untuk setup) dan Python 3.11 (untuk kompilasi Ninja).
* **Disk Management:** Pembersihan otomatis dependensi yang tidak digunakan untuk mencegah error *Out of Disk Space* pada server GitHub.

---

## 📦 Cara Build Sendiri
1.  **Fork** repositori ini ke akun GitHub kamu.
2.  Buka tab **Actions** di bagian atas halaman repositori.
3.  Pilih workflow **build apk** di bilah sisi kiri.
4.  Klik tombol **Run workflow**.
5.  Setelah proses selesai (sekitar 2-4 jam), hasil APK bisa kamu unduh di bagian **Releases** atau **Artifacts**.

---

## ⚠️ Disclaimer
* **Bukan Rilis Resmi:** Ini adalah build independen, bukan rilis resmi dari Geometry OU.
* **Risiko Pengguna:** Segala risiko terkait performa dan data ditanggung oleh pengguna.
* **Sync & API:** Fitur sinkronisasi Google mungkin tidak berfungsi karena pembatasan API Key pada build pihak ketiga.

---

## 🎖️ Credits & Acknowledgments
Proyek ini tidak akan mungkin ada tanpa kerja keras dari para pengembang berikut:

* **[Kiwi Browser Team (Geometry OU)](https://github.com/kiwibrowser/src.next):** Sebagai pengembang utama yang membawa ekstensi Chrome ke perangkat seluler.
* **[The Chromium Project](https://www.chromium.org/):** Fondasi utama dari hampir semua browser modern di dunia.
* **GitHub Actions:** Sebagai penyedia infrastruktur build yang luar biasa.
* **Community Modders:** Terima kasih kepada semua pihak yang terus berbagi ilmu mengenai modifikasi Chromium engine.

---
*Dibuat dengan ❤️ untuk komunitas open-source.*
