# 🗓️ Schedule-Maker
[![License: MIT](https://img.shields.io/badge/License-MIT-indigo.svg)](https://opensource.org/licenses/MIT)
[![UI: Tailwind CSS](https://img.shields.io/badge/UI-Tailwind_CSS-38B2AC.svg)](https://tailwindcss.com)
[![Responsive: Mobile-First](https://img.shields.io/badge/Mobile--First-Responsive-brightgreen.svg)]()

**Schedule-Maker** adalah aplikasi web satu file (Single-File Solution) yang dirancang khusus untuk menyusun jadwal secara manual dengan tingkat presisi dan integritas data yang tinggi. Mengusung konsep **Dynamic Principal Architect**, aplikasi ini memberikan kontrol penuh kepada pengguna untuk mengatur slot waktu, guru, dan mata pelajaran tanpa ketergantungan pada server eksternal.

---

## 🇮🇩 Bahasa Indonesia

### 🌟 Pengenalan
Aplikasi ini hadir untuk menjawab tantangan dalam menyusun jadwal yang seringkali membutuhkan fleksibilitas manual namun tetap memerlukan pengawasan logika. Dengan antarmuka **Glassmorphism** yang modern, Schedule-Maker tidak hanya berfungsi sebagai alat input, tetapi juga sebagai sistem cerdas yang menjaga integritas penjadwalan Anda.

### 🚀 Fungsi Utama
* **Hybrid Responsive Grid**: Sistem cerdas yang secara otomatis mengubah tabel matriks (Desktop) menjadi format kartu vertikal (Mobile) untuk kenyamanan jari dan mata.
* **Conflict Detection Engine**: Logika validasi [Real-Time] (a.k.a. pemrosesan seketika) yang mendeteksi jika seorang guru dijadwalkan di dua kelas berbeda pada jam yang sama.
* **Master Data Management**: Manajemen mandiri untuk entitas Guru, Mata Pelajaran dengan kode warna dinamis, dan Daftar Kelas.
* **Local Persistence**: Memanfaatkan `LocalStorage` browser agar data tetap tersimpan secara permanen di perangkat lokal tanpa risiko kebocoran data ke server.
* **Professional Export System**: Modul integrasi untuk mengubah hasil kerja menjadi dokumen fisik digital dalam format **PDF** dan **Excel (XLSX)**.
* **Touch-Optimized UI**: Komponen interaktif yang dirancang dengan ukuran minimal 44x44px untuk memastikan pengalaman navigasi yang lancar di layar sentuh.

### 🛠️ Arsitektur Sistem
Aplikasi ini beroperasi dengan state-driven logic, di mana setiap perubahan data akan memicu sinkronisasi otomatis antara antarmuka dan penyimpanan lokal. Arsitektur kode mengikuti prinsip **SOLID** dan **Atomic Update** untuk memastikan stabilitas sistem saat melakukan modifikasi jadwal.

---

## 🇬🇧 English

### 🌟 Introduction
This application is designed to solve the challenges of manual scheduling that require flexibility without sacrificing logical integrity. Featuring a modern **Glassmorphism** interface, Schedule-Maker acts not just as an input tool, but as an intelligent system that safeguards your scheduling process.

### 🚀 Core Functionalities
* **Hybrid Responsive Grid**: An intelligent system that automatically transforms matrix tables (Desktop) into vertical card formats (Mobile) for optimal viewing and touch accessibility.
* **Conflict Detection Engine**: [Real-Time] (a.k.a. instant processing) validation logic that detects if a teacher is scheduled in two different classes at the same time.
* **Master Data Management**: Independent management for Teacher entities, Subjects with dynamic color-coding, and Class Lists.
* **Local Persistence**: Utilizes browser `LocalStorage` to ensure data remains permanently saved on the local device without data leakage risks to a server.
* **Professional Export System**: Integrated modules to convert your work into digital physical documents in **PDF** and **Excel (XLSX)** formats.
* **Touch-Optimized UI**: Interactive components designed with a minimum size of 44x44px to ensure a smooth navigation experience on touchscreens.

### 🛠️ System Architecture
The application operates on state-driven logic, where every data change triggers an automatic synchronization between the interface and local storage. The code architecture adheres to **SOLID** and **Atomic Update** principles to ensure system stability during schedule modifications.

---

## 📄 Lisensi / License
Distribusi ini berada di bawah lisensi **MIT**. Anda bebas menggunakan, memodifikasi, dan mendistribusikan ulang aplikasi ini baik untuk tujuan personal maupun komersial.

*Distributed under the **MIT License**. Free for personal and commercial use.*

