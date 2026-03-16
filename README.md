# 🛠️ SysAdmin - My Tools & Resources

Kumpulan tautan langsung ke *tools*, skrip, dan proyek dokumentasi pengalaman administrasi sistem serta jaringan.

## 📑 Table of Contents

- [Windows (Tools & Skrip)](#windows-tools--skrip)
- [Monitoring (Proyek & Implementasi)](#monitoring-proyek--implementasi)
- [Jaringan (Cisco Switch Command)](#jaringan-cisco-switch-command)
- [Vibe Coding + IT Support](#vibe-coding--it-support)

---

<a id="windows-tools--skrip"></a>
## 🪟 Windows (Tools & Skrip)

Berbagai *tools* dan skrip yang digunakan untuk kebutuhan administrasi, perbaikan (*troubleshooting*), dan manajemen darurat sistem operasi Windows.

- **Windows Utility Kit (Password Resetter, BitLocker Unlocker)**
  Kumpulan *tools* esensial untuk mereset *password* lokal, pemulihan kunci BitLocker, dan utilitas *recovery* lainnya.
  
  [➡️ Akses Google Drive Folder](https://drive.google.com/drive/folders/1-cPvS3D-hIDC7RjQFoZNxASsoIedOoVq?usp=sharing)

[⬆️ Kembali ke Daftar Isi](#table-of-contents)

---

<a id="monitoring-proyek--implementasi"></a>
## 📊 Monitoring (Proyek & Implementasi)

Dokumentasi proyek setup dan konfigurasi sistem *monitoring* untuk memastikan *high availability* layanan dan pengumpulan metrik performa.

### Uptime Kuma Implementation (Ansible)
Implementasi otomatis Uptime Kuma menggunakan Ansible untuk memantau status layanan internal dan eksternal secara *real-time*. Proyek ini mendemonstrasikan kapabilitas otomatisasi dan manajemen konfigurasi server.

[➡️ Lihat Kode di GitHub](https://github.com/victor-point/ansible-chingluh/tree/master/roles/uptime_kuma)

[⬆️ Kembali ke Daftar Isi](#table-of-contents)

---

<a id="jaringan-cisco-switch-command"></a>
## 🌐 Jaringan (Cisco Switch Command)

Kumpulan konfigurasi *best practice* untuk perangkat keras Cisco Switch, mencakup implementasi Layer 2 dan Layer 3 serta pengamanan dasar jaringan (*network security*).

- **Konfigurasi Core dan Access Switch**
  File konfigurasi berbasis CLI yang mendemonstrasikan implementasi jaringan hierarkis. Mencakup konfigurasi Core Switch (Inter-VLAN Routing) dan Access Switch (Layer 2) dengan segregasi VLAN, *trunking*, serta fitur pengamanan seperti `spanning-tree guard root` dan akses SSH.
  
  [➡️ Lihat Kumpulan Konfigurasi di GitHub](https://github.com/victor-point/jaringan-awesome.git)

[⬆️ Kembali ke Daftar Isi](#table-of-contents)

---

<a id="vibe-coding--it-support"></a>
## 👨‍💻 Vibe Coding + IT Support

Proyek eksperimental yang menggabungkan automasi *IT Support* dengan *coding* santai. Fokus pada efisiensi manajemen perangkat keras jaringan.

### Automasi Pemeliharaan UniFi & Switch
Skrip *scheduler* yang didesain untuk mengeksekusi *restart* otomatis secara berkala pada UniFi Controller dan perangkat *switch* (seperti Cisco atau D-Link) di dalam jaringan. Automasi ini berfungsi krusial untuk mencegah terjadinya *memory leak*, membersihkan *cache* sistem yang menumpuk, dan memastikan stabilitas performa perangkat keras agar tetap optimal beroperasi 24/7.

![scheduler wifi](https://github.com/victor-point/My-Awesome-Sysadmin-Stack-2025-Edition-/blob/main/scheduler%20unifi.png)

[⬆️ Kembali ke Daftar Isi](#table-of-contents)

---
