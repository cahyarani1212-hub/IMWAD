# SOFTWARE REQUIREMENTS SPECIFICATION (SRS)

## Sistem Monitoring Perubahan Sosial dan Emosional Siswa Sekolah Dasar Berbasis Web

---

# 1. Informasi Dokumen

| Informasi | Keterangan |
|---|---|
| Nama Sistem | Sistem Monitoring Perubahan Sosial dan Emosional Siswa SD |
| Platform | Website |
| Penyusun | Setia Cahya Rani |
| Program Studi | Teknik Informatika |
| Versi | 1.0 |
| Status | Draft |

---

# 2. Purpose

Dokumen Software Requirements Specification (SRS) digunakan untuk menjelaskan kebutuhan perangkat lunak dari sistem monitoring perubahan sosial dan emosional siswa sekolah dasar berbasis web.

SRS menjadi dasar untuk:

- perancangan sistem;
- perancangan database;
- perancangan antarmuka;
- implementasi;
- pengujian;
- evaluasi.

---

# 3. Scope

Sistem mencakup:

- login;
- pengelolaan pengguna;
- pengelolaan siswa;
- pengelolaan kelas;
- pengelolaan indikator;
- monitoring sosial;
- monitoring emosional;
- monitoring minat belajar;
- catatan observasi;
- riwayat monitoring;
- perbandingan antarperiode;
- ringkasan;
- filter;
- validasi indikator;
- hak akses.

Sistem tidak mencakup diagnosis psikologis.

---

# 4. Definitions

| Istilah | Definisi |
|---|---|
| Monitoring | Proses pencatatan dan pemantauan berdasarkan indikator |
| Periode | Waktu pelaksanaan monitoring |
| Indikator | Aspek yang digunakan dalam monitoring |
| Pakar | Pihak yang memvalidasi indikator |
| FR | Functional Requirement |
| NFR | Non-Functional Requirement |
| AI | Artificial Intelligence |
| RBAC | Role-Based Access Control |

---

# 5. User Roles

## 5.1 Admin

Hak akses:

- login;
- mengelola pengguna;
- mengelola kelas;
- mengelola siswa;
- mengelola indikator.

## 5.2 Guru

Hak akses:

- login;
- melihat siswa;
- melakukan monitoring;
- melihat riwayat;
- membandingkan periode;
- membuat catatan observasi.

## 5.3 Pakar

Hak akses:

- melihat indikator;
- melakukan validasi indikator;
- memberikan status validasi.

## 5.4 Siswa

Siswa merupakan objek monitoring dan belum menjadi pengguna langsung pada versi awal.

---

# 6. Environment

Sistem merupakan aplikasi berbasis web.

Lingkungan penggunaan:

- komputer/laptop;
- browser modern;
- server aplikasi;
- database;
- jaringan internet atau jaringan lokal sekolah.

**[ASUMSI-07]** Infrastruktur jaringan sekolah perlu diverifikasi.

---

# 7. Functional Requirements

## FR-01 — Login

**Prioritas:** MUST HAVE

Sistem harus menyediakan halaman login.

### Input

- username/email;
- password.

### Proses

Sistem memvalidasi kredensial pengguna.

### Output

Jika benar:

> Pengguna diarahkan ke dashboard.

Jika salah:

> Sistem menampilkan pesan kesalahan.

### Verifikasi

Black-box testing.

---

# FR-02 — Pengelolaan Pengguna

**Prioritas:** MUST HAVE

Admin dapat:

- menambah pengguna;
- melihat pengguna;
- mengubah pengguna;
- menonaktifkan pengguna;
- menentukan role.

### Verifikasi

Functional testing.

---

# FR-03 — Pengelolaan Data Siswa

**Prioritas:** MUST HAVE

Pengguna berwenang dapat mengelola data siswa.

Data minimal:

- ID siswa;
- nama;
- kelas;
- status.

### Verifikasi

Functional testing.

---

# FR-04 — Monitoring Sosial

**Prioritas:** MUST HAVE

Guru dapat melakukan monitoring aspek sosial siswa berdasarkan indikator yang tersedia.

Guru harus memilih:

- siswa;
- periode;
- indikator;
- nilai/jawaban.

### Verifikasi

Functional testing.

---

# FR-05 — Monitoring Emosional

**Prioritas:** MUST HAVE

Guru dapat melakukan monitoring aspek emosional siswa berdasarkan indikator yang tersedia.

### Verifikasi

Functional testing.

---

# FR-06 — Monitoring Minat Belajar

**Prioritas:** MUST HAVE

Guru dapat melakukan monitoring minat belajar siswa berdasarkan indikator yang tersedia.

### Verifikasi

Functional testing.

---

# FR-07 — Riwayat Monitoring

**Prioritas:** MUST HAVE

Sistem harus menampilkan riwayat monitoring berdasarkan:

- siswa;
- kategori;
- periode.

Riwayat ditampilkan secara kronologis.

### Verifikasi

Black-box testing.

---

# FR-08 — Perbandingan Antarperiode

**Prioritas:** MUST HAVE

Sistem harus memungkinkan guru memilih minimal dua periode monitoring untuk dibandingkan.

Output minimal:

- nilai periode pertama;
- nilai periode kedua;
- nilai perubahan;
- status perubahan.

### Verifikasi

Functional testing menggunakan dataset uji.

---

# FR-09 — Catatan Observasi

**Prioritas:** MUST HAVE

Guru dapat menambahkan catatan observasi.

Catatan memiliki:

- siswa;
- isi catatan;
- pengguna pencatat;
- waktu pencatatan.

### Verifikasi

Functional testing.

---

# FR-10 — Filter Monitoring

**Prioritas:** SHOULD HAVE

Sistem menyediakan filter berdasarkan:

- kelas;
- siswa;
- kategori;
- periode.

### Verifikasi

Black-box testing.

---

# FR-11 — Hak Akses

**Prioritas:** MUST HAVE

Sistem harus menerapkan hak akses berdasarkan role.

Contoh:

Admin:

- mengelola pengguna.

Guru:

- melakukan monitoring.

Pakar:

- melakukan validasi indikator.

### Verifikasi

Security testing.

---

# FR-12 — Validasi Indikator

**Prioritas:** SHOULD HAVE

Sistem dapat menyimpan status validasi indikator.

Status:

- Draft;
- Review;
- Disetujui.

### Verifikasi

Functional testing.

---

# FR-13 — Ringkasan Monitoring

**Prioritas:** SHOULD HAVE

Sistem menampilkan ringkasan hasil monitoring berdasarkan data yang tersedia.

Ringkasan tidak boleh memberikan diagnosis.

### Verifikasi

Functional testing.

---

# FR-14 — Pesan Non-Diagnostik

**Prioritas:** MUST HAVE

Sistem harus menampilkan informasi bahwa hasil monitoring bukan diagnosis psikologis.

Contoh:

> "Hasil monitoring merupakan informasi pendukung dan bukan diagnosis psikologis."

### Verifikasi

UI inspection.

---

# 8. Non-Functional Requirements

## NFR-01 — Usability

**Kategori ISO/IEC 25010:** Usability

**Metric:** Persentase pengguna yang berhasil menyelesaikan tugas utama.

**Target:** ≥80%.

**Kondisi pengukuran:** Usability testing.

---

## NFR-02 — Performance

**Kategori ISO/IEC 25010:** Performance Efficiency

**Metric:** Waktu respons halaman.

**Target:** ≤3 detik pada lingkungan pengujian.

**Kondisi pengukuran:** Performance testing.

---

## NFR-03 — Reliability

**Kategori ISO/IEC 25010:** Reliability

**Metric:** Persentase transaksi berhasil.

**Target:** ≥95%.

**Kondisi pengukuran:** Pengujian penyimpanan monitoring.

---

## NFR-04 — Security

**Kategori ISO/IEC 25010:** Security

**Metric:** Jumlah akses tidak sah yang berhasil.

**Target:** 0 kasus.

**Kondisi pengukuran:** Security testing.

---

## NFR-05 — Privacy

**Kategori ISO/IEC 25010:** Security

**Metric:** Kepatuhan akses berdasarkan role.

**Target:** 100% skenario sesuai hak akses.

**Kondisi pengukuran:** Role-based access testing.

---

## NFR-06 — Maintainability

**Kategori ISO/IEC 25010:** Maintainability

**Metric:** Struktur kode dan dokumentasi modul.

**Target:** Modul utama memiliki struktur dan dokumentasi yang jelas.

**Kondisi pengukuran:** Code review.

---

## NFR-07 — Compatibility

**Kategori ISO/IEC 25010:** Compatibility

**Metric:** Browser yang dapat menjalankan sistem.

**Target:** Minimal 2 browser modern.

**Kondisi pengukuran:** Compatibility testing.

---

## NFR-08 — Functional Correctness

**Kategori ISO/IEC 25010:** Functional Suitability

**Metric:** Ketepatan hasil perbandingan.

**Target:** 100% pada dataset pengujian.

**Kondisi pengukuran:** Functional testing.

---

## NFR-09 — AI Accuracy

**Kategori:** AI Performance

**Metric:** Accuracy/Precision/Recall/F1-score sesuai jenis model.

**Target:** Ditentukan setelah AI dan dataset ditetapkan.

**Kondisi:** Evaluasi model.

**Status:** Tidak aktif apabila sistem tidak menggunakan AI.

---

## NFR-10 — AI Latency dan Fallback

**Kategori:** Performance Efficiency/Reliability

**Metric:** Waktu respons AI dan keberhasilan fallback.

**Target:** Ditentukan setelah fitur AI dirancang.

**Kondisi:** AI testing.

**Fallback:**

Jika AI gagal, sistem tetap menyediakan monitoring manual.

**Status:** Tidak aktif apabila sistem tidak menggunakan AI.

---

# 9. Data Requirements

## 9.1 User

```text
user_id
nama
username
email
password_hash
role
status
created_at
updated_at
