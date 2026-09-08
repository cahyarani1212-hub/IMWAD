# Product Requirements Document (PRD)

## 1. Informasi Dokumen

| Item | Keterangan |
|---|---|
| Nama | Setia Cahya Rani |
| Proyek | Sistem Monitoring Perubahan Sosial dan Emosional Siswa Sekolah Dasar |
| Judul | Rancang Bangun Sistem Monitoring Perubahan Sosial dan Emosional Siswa Sekolah Dasar Berbasis Web untuk Mendukung Pemantauan Minat Belajar |
| Platform | Website |
| Dokumen | Product Requirements Document (PRD) |
| Status | Draft |

---

# 2. Executive Summary

Sistem yang dirancang merupakan sistem monitoring berbasis web yang membantu sekolah dalam melakukan pencatatan dan pemantauan perubahan sosial dan emosional siswa sekolah dasar serta mendukung pemantauan minat belajar.

Sistem membantu guru menyimpan hasil monitoring secara terstruktur sehingga perkembangan siswa dapat dilihat berdasarkan riwayat monitoring dari waktu ke waktu.

Sistem tidak digunakan untuk memberikan diagnosis psikologis kepada siswa.

Fokus utama sistem adalah membantu proses monitoring, pencatatan, penyimpanan riwayat, dan perbandingan perkembangan siswa.

---

# 3. Problem Statement

## Masalah

Pemantauan perkembangan sosial dan emosional siswa dapat dilakukan melalui pengamatan guru. Namun, apabila hasil pengamatan masih dicatat secara manual, data perkembangan siswa dapat sulit disimpan, ditelusuri, dan dibandingkan antarperiode.

Perubahan kondisi sosial, emosional, dan minat belajar siswa juga dapat sulit diketahui secara terstruktur apabila hasil monitoring sebelumnya tidak terdokumentasi dengan baik.

## Dampak Masalah

Masalah tersebut dapat menyebabkan:

- riwayat monitoring siswa sulit ditelusuri;
- guru membutuhkan waktu lebih banyak untuk mencari catatan sebelumnya;
- perubahan perkembangan siswa antarperiode sulit dibandingkan;
- hasil monitoring belum tersimpan secara terstruktur;
- informasi perkembangan siswa sulit digunakan sebagai bahan pemantauan lanjutan.

> Catatan: Pernyataan yang belum didukung hasil observasi, wawancara, atau survei akan ditandai sebagai `[ASUMSI-XX]` dan perlu diverifikasi.

---

# 4. Evidence

## Fakta

Pada tahap awal pengembangan, bukti lapangan berupa hasil observasi, wawancara, atau survei belum sepenuhnya tersedia.

Oleh karena itu, sistem tidak membuat klaim bahwa seluruh sekolah mengalami masalah yang sama.

## Asumsi

| Kode | Pernyataan | Status |
|---|---|---|
| ASUMSI-01 | Guru membutuhkan pencatatan monitoring siswa yang lebih terstruktur | Perlu verifikasi |
| ASUMSI-02 | Riwayat monitoring siswa diperlukan untuk melihat perubahan perkembangan | Perlu verifikasi |
| ASUMSI-03 | Monitoring sosial, emosional, dan minat belajar dapat dilakukan secara berkala | Perlu verifikasi |
| ASUMSI-04 | Guru membutuhkan informasi perubahan hasil monitoring antarperiode | Perlu verifikasi |
| ASUMSI-05 | Website dapat digunakan sebagai media monitoring oleh guru | Perlu verifikasi |
| ASUMSI-06 | Skala monitoring awal menggunakan skala 1–4 | Perlu validasi |

---

# 5. Target User

## Admin

Admin bertugas mengelola data dasar sistem.

Kebutuhan:

- mengelola akun pengguna;
- mengelola data guru;
- mengelola data siswa;
- mengelola data kelas;
- mengatur hak akses pengguna.

## Guru

Guru merupakan pengguna utama sistem dalam proses monitoring.

Kebutuhan:

- melihat data siswa;
- melakukan monitoring sosial;
- melakukan monitoring emosional;
- melakukan monitoring minat belajar;
- menambahkan catatan observasi;
- melihat riwayat monitoring;
- membandingkan perkembangan siswa antarperiode.

## Siswa

Siswa merupakan pengguna yang dapat melihat informasi perkembangan dirinya sesuai hak akses yang diberikan.

Kebutuhan:

- melihat hasil monitoring yang diperbolehkan;
- melihat perkembangan dirinya;
- melihat informasi yang diberikan guru.

---

# 6. Stakeholders

| Stakeholder | Peran | Kebutuhan |
|---|---|---|
| Admin | Pengelola sistem | Pengelolaan pengguna dan data |
| Guru | Pengguna utama | Monitoring dan pemantauan perkembangan siswa |
| Siswa | Pengguna | Melihat informasi perkembangan dirinya |
| Sekolah | Pihak terkait | Mendukung proses monitoring siswa |

---

# 7. Persona

## Persona 1 — Guru

**Nama:** Bu Rina  
**Peran:** Guru Sekolah Dasar

**Kebutuhan:**

Bu Rina membutuhkan cara yang lebih terstruktur untuk mencatat hasil pengamatan perkembangan siswa dan melihat perubahan hasil monitoring dari waktu ke waktu.

**Tujuan:**

- mencatat hasil monitoring;
- melihat riwayat siswa;
- membandingkan perkembangan;
- memberikan catatan observasi.

---

## Persona 2 — Siswa

**Nama:** Andi  
**Peran:** Siswa Sekolah Dasar

**Kebutuhan:**

Andi membutuhkan informasi sederhana mengenai perkembangan dirinya yang dapat ditampilkan sesuai hak akses.

**Tujuan:**

- melihat perkembangan diri;
- memahami informasi yang diberikan guru;
- mengetahui bagian yang perlu diperhatikan.

---

# 8. Value Proposition

## Pain yang Dikurangi

- pencatatan monitoring yang tidak terstruktur;
- kesulitan mencari riwayat monitoring;
- kesulitan membandingkan hasil monitoring antarperiode.

## Gain yang Diciptakan

- data monitoring tersimpan secara terstruktur;
- riwayat perkembangan lebih mudah ditelusuri;
- guru dapat melihat perubahan hasil monitoring;
- monitoring sosial, emosional, dan minat belajar berada dalam satu sistem.

## Nilai Sistem

Sistem memberikan nilai dengan membantu guru melakukan monitoring perkembangan siswa secara lebih terstruktur dan terdokumentasi.

---

# 9. Indikator Monitoring Awal

## A. Sosial

Indikator awal:

1. Interaksi dengan teman.
2. Kemampuan bekerja sama.
3. Komunikasi.
4. Partisipasi dalam kegiatan.
5. Kemauan membantu.

## B. Emosional

Indikator awal:

1. Kemampuan mengenali emosi.
2. Kemampuan mengendalikan respons.
3. Respons terhadap perubahan.
4. Kemauan meminta bantuan.
5. Konsistensi perilaku.

## C. Minat Belajar

Indikator awal:

1. Ketertarikan terhadap pembelajaran.
2. Keaktifan mengikuti pembelajaran.
3. Penyelesaian tugas.
4. Rasa ingin tahu.
5. Ketekunan.

> Indikator di atas merupakan indikator awal dan perlu divalidasi sebelum digunakan sebagai indikator final sistem.

---

# 10. Skala Monitoring

Skala awal yang direncanakan:

| Nilai | Keterangan |
|---|---|
| 1 | Belum terlihat |
| 2 | Mulai terlihat |
| 3 | Berkembang |
| 4 | Berkembang sangat baik |

**Catatan:** Skala 1–4 merupakan `[ASUMSI-06]` dan harus divalidasi sebelum digunakan pada sistem final.

---

# 11. Goals Produk

## Goal 1

Membantu guru melakukan pencatatan monitoring sosial, emosional, dan minat belajar siswa secara terstruktur.

## Goal 2

Menyediakan riwayat hasil monitoring siswa.

## Goal 3

Membantu guru melihat perubahan hasil monitoring antarperiode.

## Goal 4

Mendukung pemantauan minat belajar siswa berdasarkan hasil monitoring.

---

# 12. KPI

| KPI | Target Awal | Cara Mengukur |
|---|---|---|
| Monitoring siswa berhasil dicatat | ≥ 90% percobaan | Pengujian fungsional |
| Riwayat monitoring dapat ditampilkan | 100% data valid | Pengujian sistem |
| Perbandingan antarperiode dapat ditampilkan | 100% data valid | Pengujian sistem |
| Data siswa hanya dapat diakses sesuai hak akses | 100% skenario pengujian | Security testing |
| Pengguna dapat menyelesaikan proses monitoring | ≥ 80% pengguna uji | Usability testing |

> Target KPI merupakan target awal dan dapat disesuaikan setelah pengujian.

---

# 13. Scope 3 Bulan — MoSCoW

| Prioritas | Fitur |
|---|---|
| MUST | Login pengguna |
| MUST | Pengelolaan data siswa |
| MUST | Pengelolaan data kelas |
| MUST | Monitoring sosial |
| MUST | Monitoring emosional |
| MUST | Monitoring minat belajar |
| MUST | Riwayat monitoring |
| MUST | Catatan observasi guru |
| SHOULD | Perbandingan hasil monitoring antarperiode |
| SHOULD | Filter data siswa |
| SHOULD | Ringkasan perkembangan |
| COULD | Notifikasi monitoring |
| WON'T | Diagnosis psikologis siswa |
| WON'T | Penentuan kondisi mental siswa secara otomatis |

---

# 14. Non-Goals

Sistem tidak ditujukan untuk:

1. Mendiagnosis gangguan psikologis.
2. Menentukan kondisi mental siswa.
3. Menggantikan guru dalam melakukan observasi.
4. Memberikan keputusan otomatis mengenai siswa.
5. Menentukan siswa bermasalah berdasarkan satu hasil monitoring.
6. Menggunakan metode SAW.
7. Menggunakan metode TOPSIS.
8. Menjadi sistem konseling profesional.

---

# 15. Business Rules

1.
