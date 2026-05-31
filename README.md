# 🌿 auto-penghijauan

> "Biar kontribusi GitHub keliatan ijo subur tiap hari, padahal aslinya kita lagi rebahan." 😴

![Oasis Status](https://img.shields.io/badge/status-aktif%20turu-success?style=flat-square&color=4caf50)
![Frequency](https://img.shields.io/badge/siraman-tiap%2030%20menit-orange?style=flat-square)

---

## 🤔 Ini Apaan

Ini repo iseng buat otomatisasi **penghijauan** kontribusi GitHub biar keliatan rajin ngoding tiap hari. Daripada grafik kontribusi kosong melompong kayak dompet di akhir bulan, mending kita otomatisasi pake GitHub Actions biar ijonya langsung pekat!

---

## ⚙️ Cara Kerja 

Gak usah ribet, skemanya cuma gini doang:
1. **Bangun:** Tiap 30 menit sekali, GitHub Actions otomatis jalan.
2. **Spam Commit:** Si bot langsung bikin **10 commit** sekaligus biar ijonya pekat kayak matcha latte.
3. **Turu Lagi:** Selesai nge-push perubahan ke GitHub, bot-nya lanjut tidur.

---

## 🚀 Cara Edit 

Buka file [.github/workflows/penghijauan.yml](file:///.github/workflows/penghijauan.yml) terus ganti bagian ini kalau mau eksperimen:

* **Mau atur jeda waktu penyiraman?**
  Ganti bagian `cron`-nya (bawaannya `*/30 * * * *` alias tiap 30 menit).
* **Mau bikin commit-nya lebih banyak?**
  Ganti angka `10` di bagian `for i in {1..10}` sesuai kebutuhan lu.

---

## ⚠️ Disclaimer

> [!IMPORTANT]
> Proyek ini cuma buat seru-seruan & estetika profil GitHub aja ya ges ya. Ingat, ngoding beneran, bikin project riil, dan belajar konsisten tetep yang paling utama. Jangan lupa sesekali jalan-jalan keluar buat hirup udara segar! 

---
Dibuat dengan santai sambil rebahan. 🌱