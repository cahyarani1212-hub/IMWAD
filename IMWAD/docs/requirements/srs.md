# Software Requirements Specification (SRS)

## 1. Informasi Dokumen

| Item | Keterangan |
|---|---|
| Nama | Setia Cahya Rani |
| Proyek | Sistem Monitoring Perubahan Sosial dan Emosional Siswa Sekolah Dasar |
| Judul | Rancang Bangun Sistem Monitoring Perubahan Sosial dan Emosional Siswa Sekolah Dasar Berbasis Web untuk Mendukung Pemantauan Minat Belajar |
| Platform | Website |
| Dokumen | Software Requirements Specification (SRS) |
| Status | Draft |

---

# 2. Tujuan

SRS digunakan untuk mendefinisikan kebutuhan perangkat lunak dari sistem monitoring perubahan sosial dan emosional siswa sekolah dasar.

Dokumen ini menjadi dasar dalam proses pengembangan, pengujian, dan evaluasi sistem.

---

# 3. Scope

Sistem mencakup:

- pengelolaan pengguna;
- pengelolaan data siswa;
- pengelolaan kelas;
- monitoring sosial;
- monitoring emosional;
- monitoring minat belajar;
- penyimpanan riwayat monitoring;
- catatan observasi;
- perbandingan hasil monitoring;
- ringkasan perkembangan.

Sistem tidak mencakup diagnosis psikologis.

---

# 4. Definisi

| Istilah | Definisi |
|---|---|
| Monitoring | Proses pencatatan dan pemantauan perkembangan siswa |
| Indikator | Aspek yang digunakan dalam proses monitoring |
| Periode | Waktu pelaksanaan monitoring |
| Riwayat | Kumpulan hasil monitoring dari beberapa periode |
| Guru | Pengguna utama yang melakukan monitoring |
| Admin | Pengguna yang mengelola data dasar sistem |
| Siswa | Pengguna yang dapat melihat informasi perkembangan dirinya |

---

# 5. User dan Stakeholder

## Admin

Admin mengelola:

- pengguna;
- guru;
- siswa;
- kelas;
- hak akses.

## Guru

Guru melakukan:

- monitoring sosial;
- monitoring emosional;
- monitoring minat belajar;
- pencatatan observasi;
- melihat riwayat;
- membandingkan hasil monitoring.

## Siswa

Siswa dapat:

- melihat hasil monitoring yang diperbolehkan;
- melihat informasi perkembangan dirinya.

---

# 6. Lingkungan Operasi

Sistem dirancang sebagai aplikasi berbasis website.

Lingkungan penggunaan:

- komputer atau laptop;
- browser modern;
- jaringan internet atau jaringan lokal sesuai lingkungan implementasi.

Detail teknologi dapat ditentukan pada tahap desain dan implementasi.

---

# 7. Asumsi

| Kode | Asumsi |
|---|---|
| ASUMSI-01 | Guru melakukan monitoring siswa secara berkala |
| ASUMSI-02 | Sekolah membutuhkan penyimpanan monitoring terstruktur |
| ASUMSI-03 | Riwayat monitoring diperlukan |
| ASUMSI-04 | Hasil monitoring dapat dibandingkan antarperiode |
| ASUMSI-05 | Sistem digunakan melalui browser |
| ASUMSI-06 | Skala monitoring awal menggunakan skala 1–4 |

---

# 8. Functional Requirements

## FR-01 — Login

**Requirement:**

Sistem harus dapat melakukan autentikasi pengguna saat pengguna memasukkan username dan password yang valid.

**Output:**

Pengguna diarahkan ke halaman sesuai hak akses.

**Prioritas:** MUST

**Verifikasi:** Functional Testing

---

## FR-02 — Pengelolaan Pengguna

**Requirement:**

Sistem harus memungkinkan Admin menambah, mengubah, dan menghapus data pengguna.

**Output:**

Data pengguna tersimpan atau diperbarui.

**Prioritas:** MUST

**Verifikasi:** Functional Testing

---

## FR-03 — Pengelolaan Data Siswa

**Requirement:**

Sistem harus memungkinkan Admin mengelola data siswa.

**Output:**

Data siswa dapat ditambahkan, diubah, dan ditampilkan.

**Prioritas:** MUST

**Verifikasi:** Functional Testing

---

## FR-04 — Pengelolaan Kelas

**Requirement:**

Sistem harus memungkinkan Admin mengelola data kelas dan hubungan siswa dengan kelas.

**Output:**

Data kelas dan siswa tersimpan sesuai kelas.

**Prioritas:** MUST

**Verifikasi:** Functional Testing

---

## FR-05 — Monitoring Sosial

**Requirement:**

Sistem harus memungkinkan Guru mencatat hasil monitoring indikator sosial siswa pada periode tertentu.

**Output:**

Hasil monitoring sosial tersimpan berdasarkan siswa dan periode.

**Prioritas:** MUST

**Verifikasi:** Functional Testing

---

## FR-06 — Monitoring Emosional

**Requirement:**

Sistem harus memungkinkan Guru mencatat hasil monitoring indikator emosional siswa pada periode tertentu.

**Output:**

Hasil monitoring emosional tersimpan berdasarkan siswa dan periode.

**Prioritas:** MUST

**Verifikasi:** Functional Testing

---

## FR-07 — Monitoring Minat Belajar

**Requirement:**

Sistem harus memungkinkan Guru mencatat hasil monitoring indikator minat belajar siswa pada periode tertentu.

**Output:**

Hasil monitoring minat belajar tersimpan berdasarkan siswa dan periode.

**Prioritas:** MUST

**Verifikasi:** Functional Testing

---

## FR-08 — Catatan Observasi

**Requirement:**

Sistem harus memungkinkan Guru menambahkan catatan observasi pada hasil monitoring siswa.

**Output:**

Catatan observasi tersimpan dan dapat ditampilkan kembali.

**Prioritas:** MUST

**Verifikasi:** Functional Testing

---

## FR-09 — Riwayat Monitoring

**Requirement:**

Sistem harus menampilkan riwayat monitoring siswa berdasarkan periode.

**Output:**

Data monitoring dari periode sebelumnya dapat ditampilkan.

**Prioritas:** MUST

**Verifikasi:** Functional Testing

---

## FR-10 — Perbandingan Monitoring

**Requirement:**

Sistem harus dapat membandingkan hasil monitoring siswa dari minimal dua periode yang tersedia.

**Output:**

Perubahan hasil monitoring antarperiode dapat ditampilkan.

**Prioritas:** SHOULD

**Verifikasi:** Functional Testing

---

## FR-11 — Filter Data

**Requirement:**

Sistem harus memungkinkan Guru memfilter data monitoring berdasarkan kelas, siswa, dan periode.

**Output:**

Sistem menampilkan data sesuai filter yang dipilih.

**Prioritas:** SHOULD

**Verifikasi:** Functional Testing

---

## FR-12 — Informasi Perkembangan Siswa

**Requirement:**

Sistem harus menampilkan informasi perkembangan siswa berdasarkan hasil monitoring yang tersimpan.

**Output:**

Informasi perkembangan ditampilkan kepada pengguna yang memiliki hak akses.

**Prioritas:** SHOULD

**Verifikasi:** Functional Testing

---

## FR-13 — Akses Siswa

**Requirement:**

Sistem harus memungkinkan siswa melihat informasi perkembangan dirinya sesuai hak akses.

**Output:**

Siswa hanya dapat melihat data dirinya sendiri.

**Prioritas:** SHOULD

**Verifikasi:** Security Testing

---

## FR-14 — Pembatasan Diagnosis

**Requirement:**

Sistem harus menampilkan informasi bahwa hasil monitoring bukan merupakan diagnosis psikologis.

**Output:**

Pesan pembatasan ditampilkan pada bagian yang relevan.

**Prioritas:** MUST

**Verifikasi:** Inspection

---

# 9. Non-Functional Requirements

## NFR-01 — Usability

**Kategori ISO/IEC 25010:** Usability

**Requirement:**

Sistem harus dapat digunakan oleh pengguna uji untuk menyelesaikan proses monitoring tanpa bantuan teknis khusus.

**Target:**

Minimal 80% pengguna uji dapat menyelesaikan tugas utama.

**Kondisi ukur:**

Usability testing.

**Verifikasi:** Usability Testing

---

## NFR-02 — Performance

**Kategori ISO/IEC 25010:** Performance Efficiency

**Requirement:**

Halaman utama dan halaman monitoring harus memberikan respons dalam waktu maksimal 3 detik pada kondisi pengujian yang ditentukan.

**Target:** ≤ 3 detik

**Verifikasi:** Performance Testing

---

## NFR-03 — Reliability

**Kategori ISO/IEC 25010:** Reliability

**Requirement:**

Data monitoring yang berhasil disimpan harus dapat ditampilkan kembali.

**Target:** 100% data valid dapat ditemukan kembali.

**Verifikasi:** Functional Testing

---

## NFR-04 — Security

**Kategori ISO/IEC 25010:** Security

**Requirement:**

Sistem harus membatasi akses data berdasarkan role pengguna.

**Target:** 100% skenario pengujian akses tidak sah ditolak.

**Verifikasi:** Security Testing

---

## NFR-05 — Privacy

**Kategori ISO/IEC 25010:** Security

**Requirement:**

Data siswa hanya dapat diakses oleh pengguna yang memiliki hak akses.

**Target:** Tidak terdapat akses data siswa tanpa hak.

**Verifikasi:** Security Testing

---

## NFR-06 — Maintainability

**Kategori ISO/IEC 25010:** Maintainability

**Requirement:**

Kode sistem harus disusun secara terstruktur sehingga perubahan pada satu fungsi tidak mengharuskan perubahan pada seluruh sistem.

**Target:** Modul utama dapat diperbarui secara terpisah.

**Verifikasi:** Code Inspection

---

## NFR-07 — Compatibility

**Kategori ISO/IEC 25010:** Compatibility

**Requirement:**

Sistem harus dapat digunakan pada browser modern yang umum digunakan.

**Target:** Berhasil diuji pada minimal dua browser.

**Verifikasi:** Compatibility Testing

---

## NFR-08 — Functional Correctness

**Kategori ISO/IEC 25010:** Functional Suitability

**Requirement:**

Sistem harus menyimpan hasil monitoring sesuai nilai yang dimasukkan oleh Guru.

**Target:** 100% data pengujian tersimpan sesuai input.

**Verifikasi:** Functional Testing

---

# 10. Kebutuhan Data

## Data User

Data minimal:

- user_id;
- nama;
- username;
- password;
- role.

## Data Siswa

Data minimal:

- student_id;
- nama siswa;
- kelas;
- informasi identitas yang diperlukan.

## Data Kelas

Data minimal:

- class_id;
- nama kelas;
- wali/guru terkait.

## Data Indikator

Data minimal:

- indicator_id;
- kategori;
- nama indikator;
- deskripsi indikator;
- status aktif.

Kategori indikator:

- sosial;
- emosional;
- minat belajar.

## Data Monitoring

Data minimal:

- monitoring_id;
- student_id;
- teacher_id;
- periode;
- indicator_id;
- nilai;
- tanggal monitoring.

## Data Observasi

Data minimal:

- observation_id;
- monitoring_id;
- teacher_id;
- catatan;
- tanggal.

---

# 11. Aturan Bisnis

1. Pengguna harus login sebelum mengakses sistem.
2. Setiap pengguna memiliki role.
3. Admin mengelola data dasar sistem.
4. Guru melakukan monitoring siswa.
5. Siswa hanya dapat melihat informasi dirinya sendiri.
6. Guru hanya dapat mengakses siswa sesuai kewenangannya.
7. Hasil monitoring memiliki periode.
8. Nilai monitoring harus berada pada rentang skala yang ditentukan.
9. Catatan observasi dapat ditambahkan oleh Guru.
10. Data monitoring tidak boleh dihapus tanpa hak akses.
11. Hasil monitoring tidak digunakan sebagai diagnosis psikologis.
12. Sistem tidak menentukan keputusan akhir terhadap siswa.

---

# 12. Security Requirements

Sistem harus:

1. Melakukan autentikasi pengguna.
2. Menggunakan role-based access control.
3. Membatasi akses data berdasarkan role.
4. Mencegah siswa mengakses data siswa lain.
5. Membatasi Admin dan Guru sesuai hak akses.
6. Melindungi data login pengguna.
7. Tidak menampilkan data siswa kepada pengguna yang tidak memiliki hak.

---

# 13. Privacy Requirements

Data siswa harus diperlakukan sebagai data yang membutuhkan perlindungan.

Sistem harus:

- membatasi akses data;
- menyimpan hanya data yang diperlukan;
- tidak menampilkan data siswa secara terbuka;
- menggunakan data sesuai kebutuhan sistem;
- tidak menggunakan hasil monitoring untuk diagnosis;
- mempertimbangkan izin dan ketentuan sekolah dalam penggunaan data penelitian.

---

# 14. Acceptance Criteria

Sistem dapat dianggap memenuhi kebutuhan apabila:

- [ ] Admin dapat login.
- [ ] Guru dapat login.
- [ ] Siswa dapat login.
- [ ] Admin dapat mengelola data siswa.
- [ ] Guru dapat melakukan monitoring sosial.
- [ ] Guru dapat melakukan monitoring emosional.
- [ ] Guru dapat melakukan monitoring minat belajar.
- [ ] Guru dapat menambahkan catatan observasi.
- [ ] Riwayat monitoring dapat ditampilkan.
- [ ] Data antarperiode dapat dibandingkan.
- [ ] Siswa hanya dapat melihat data dirinya.
- [ ] Data tidak dapat diakses oleh pengguna tanpa hak.
- [ ] Sistem menampilkan batasan bahwa monitoring bukan diagnosis.

---

# 15. Traceability Matrix

| PRD | SRS | Verification |
|---|---|---|
| Monitoring sosial | FR-05 | Functional Testing |
| Monitoring emosional | FR-06 | Functional Testing |
| Monitoring minat belajar | FR-07 | Functional Testing |
| Catatan observasi | FR-08 | Functional Testing |
| Riwayat monitoring | FR-09 | Functional Testing |
| Perbandingan antarperiode | FR-10 | Functional Testing |
| Filter data | FR-11 | Functional Testing |
| Informasi perkembangan | FR-12 | Functional Testing |
| Akses siswa | FR-13 | Security Testing |
| Batasan diagnosis | FR-14 | Inspection |
| Usability | NFR-01 | Usability Testing |
| Performance | NFR-02 | Performance Testing |
| Reliability | NFR-03 | Functional Testing |
| Security | NFR-04 | Security Testing |
| Privacy | NFR-05 | Security Testing |
| Maintainability | NFR-06 | Code Inspection |
| Compatibility | NFR-07 | Compatibility Testing |
| Functional Correctness | NFR-08 | Functional Testing |

---

# 16. Metode Verifikasi

| Requirement | Metode |
|---|---|
| FR-01 | Functional Testing |
| FR-02 | Functional Testing |
| FR-03 | Functional Testing |
| FR-04 | Functional Testing |
| FR-05 | Functional Testing |
| FR-06 | Functional Testing |
| FR-07 | Functional Testing |
| FR-08 | Functional Testing |
| FR-09 | Functional Testing |
| FR-10 | Functional Testing |
| FR-11 | Functional Testing |
| FR-12 | Functional Testing |
| FR-13 | Security Testing |
| FR-14 | Inspection |
| NFR-01 | Usability Testing |
| NFR-02 | Performance Testing |
| NFR-03 | Functional Testing |
| NFR-04 | Security Testing |
| NFR-05 | Security Testing |
| NFR-06 | Code Inspection |
| NFR-07 | Compatibility Testing |
| NFR-08 | Functional Testing |

---

# 17. Status Dokumen

**Status:** Draft

SRS akan diperbarui berdasarkan hasil:

- observasi;
- wawancara;
- survei;
- validasi indikator;
- review dosen;
- pengujian sistem.
