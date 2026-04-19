# 🥝 Kiwi Browser - Custom Build

| [🇮🇩 Bahasa Indonesia](#bahasa-indonesia) | [🇺🇸 English](#english) |
|-------------------------------------------|------------------------|

---

## 🇮🇩 Bahasa Indonesia <a name="bahasa-indonesia"></a>

### 🛠️ Informasi Proyek (Arsip Publik)
Repositori ini adalah hasil modifikasi alur kerja (*workflow*) untuk membangun **Kiwi Browser** secara mandiri...

*# 🥝 Kiwi Browser - Custom Build (Public Archive)

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
*Dibuat dengan ❤️ untuk komunitas open-source.**

---

## 🇺🇸 English <a name="english"></a>

### 🛠️ Project Information (Public Archive)
This repository is a modified workflow to build **Kiwi Browser** independently...

*# ðŸ¥ Kiwi Browser - Custom Build (Public Archive)

Welcome! This repository is the result of modifications and workflow automation to build Kiwi Browser independently using GitHub Actions. This project focuses on build stability for modern 64-bit architecture.

--------------------------------------------------------------------------------
ðŸ› ï¸ PROJECT INFORMATION (PUBLIC ARCHIVE)
--------------------------------------------------------------------------------
This repository is a Public Archive. Please use this repository as a reference or a foundation for your own projects:

* Free to Develop: You are highly encouraged to Fork, modify the UI/UX, add features, or further optimize the code.
* Open for All: If you succeed in increasing build speeds or fixing bugs in the .yml scripts, feel free to share them via Pull Request.
* Status: This build is provided "as-is" for educational purposes and hobbyist development.

--------------------------------------------------------------------------------
ðŸš€ FEATURES OF THIS BUILD
--------------------------------------------------------------------------------
* High Performance: Specifically optimized for arm64-v8a Android devices.
* Smart Automation: Uses custom vpython filters to bypass Google Depot Tools limitations within the GitHub Runner environment.
* Dual Python Setup: Automatic switching between Python 2 (for setup) and Python 3.11 (for Ninja compilation).
* Disk Management: Automatic cleanup of unused dependencies to prevent Out of Disk Space errors on GitHub servers.

--------------------------------------------------------------------------------
ðŸ“¦ HOW TO BUILD IT YOURSELF
--------------------------------------------------------------------------------
1. Fork this repository to your GitHub account.
2. Open the Actions tab at the top of the repository page.
3. Select the "build apk" workflow in the left sidebar.
4. Click the Run workflow button.
5. Once the process is complete (approx. 2-4 hours), you can download the APK from the Releases or Artifacts section.

--------------------------------------------------------------------------------
âš ï¸ DISCLAIMER
--------------------------------------------------------------------------------
* Not an Official Release: This is an independent build, not an official release from Geometry OU.
* User Risk: All risks regarding performance and data are borne by the user.
* Sync & API: Google synchronization features may not work due to API Key restrictions on third-party builds.

--------------------------------------------------------------------------------
ðŸŽ–ï¸ CREDITS & ACKNOWLEDGMENTS
--------------------------------------------------------------------------------
This project would not be possible without the hard work of the following developers:

* Kiwi Browser Team (Geometry OU) [https://github.com/kiwibrowser/src.next]: The lead developers who brought Chrome extensions to mobile devices.
* The Chromium Project [https://www.chromium.org/]: The core foundation of almost every modern browser in the world.
* GitHub Actions: For providing incredible build infrastructure.
* Community Modders: Thanks to everyone who continues to share knowledge regarding Chromium engine modification.

--------------------------------------------------------------------------------
Created with â¤ï¸ for the open-source community.*
