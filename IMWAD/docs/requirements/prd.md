# PRODUCT REQUIREMENTS DOCUMENT (PRD)

## Rancang Bangun Sistem Monitoring Perubahan Sosial dan Emosional Siswa Sekolah Dasar Berbasis Web untuk Mendukung Pemantauan Minat Belajar

---

## 1. Informasi Dokumen

| Informasi | Keterangan |
|---|---|
| Nama Produk | Sistem Monitoring Perubahan Sosial dan Emosional Siswa SD |
| Platform | Website |
| Penyusun | Setia Cahya Rani |
| Program Studi | Teknik Informatika |
| Mata Kuliah | Intelligent Mobile and Web Application Development |
| Versi Dokumen | 1.0 |
| Status | Draft |

---

# 2. Executive Summary

Sistem Monitoring Perubahan Sosial dan Emosional Siswa Sekolah Dasar Berbasis Web merupakan rancangan sistem informasi yang bertujuan membantu guru melakukan pencatatan dan pemantauan perkembangan sosial, emosional, serta minat belajar siswa secara terstruktur.

Sistem menyediakan fitur untuk mengelola data siswa, melakukan monitoring berdasarkan indikator, menyimpan hasil berdasarkan periode, melihat riwayat perkembangan, membandingkan hasil monitoring, serta menambahkan catatan observasi guru.

Sistem dirancang sebagai alat bantu monitoring dan bukan sebagai alat diagnosis psikologis. Hasil monitoring digunakan sebagai informasi pendukung bagi guru dalam memahami perubahan siswa dan menentukan tindak lanjut pendidikan yang sesuai.

Informasi mengenai kondisi nyata sekolah, jumlah siswa, metode pencatatan yang sedang digunakan, serta tingkat kesulitan guru dalam melakukan monitoring masih perlu diverifikasi melalui observasi dan wawancara.

---

# 3. Problem Statement

## 3.1 Permasalahan

Perkembangan sosial dan emosional siswa merupakan salah satu aspek yang dapat diperhatikan dalam kegiatan pendidikan selain kemampuan akademik.

Guru dapat memperoleh informasi perkembangan siswa melalui pengamatan selama kegiatan belajar dan interaksi di lingkungan sekolah. Namun, apabila hasil pengamatan tidak dicatat secara terstruktur, informasi tersebut dapat menjadi sulit untuk ditelusuri kembali dan dibandingkan antarperiode.

Selain itu, minat belajar siswa juga perlu diperhatikan karena dapat terlihat melalui ketertarikan, keaktifan, keterlibatan, dan ketekunan siswa dalam kegiatan pembelajaran.

Berdasarkan permasalahan tersebut, diperlukan rancangan sistem yang dapat membantu guru:

1. mencatat hasil monitoring siswa;
2. menyimpan data berdasarkan periode;
3. melihat riwayat perkembangan;
4. membandingkan hasil monitoring;
5. mencatat hasil observasi;
6. memantau aspek sosial, emosional, dan minat belajar.

---

# 4. Evidence

Pada tahap penyusunan PRD ini belum tersedia data hasil observasi atau wawancara langsung dari sekolah.

Oleh karena itu, informasi dibedakan menjadi fakta konteks dan asumsi.

| Pernyataan | Status | Cara Verifikasi |
|---|---|---|
| Guru dapat mengamati perilaku siswa dalam kegiatan sekolah | Fakta konteks | Observasi |
| Sistem berbasis web dapat digunakan untuk menyimpan data | Fakta teknis | Implementasi |
| Pencatatan monitoring perlu dilakukan secara terstruktur | Kebutuhan desain | Analisis kebutuhan |
| Guru mengalami kesulitan menggunakan pencatatan yang ada | [ASUMSI-01] | Wawancara |
| Guru membutuhkan perbandingan antarperiode | [ASUMSI-02] | Wawancara |
| Sekolah membutuhkan sistem monitoring berbasis web | [ASUMSI-03] | Observasi dan wawancara |
| Orang tua membutuhkan akses ke sistem | [ASUMSI-04] | Wawancara |

---

# 5. Tujuan Produk

Tujuan produk:

1. Membantu guru melakukan monitoring perkembangan siswa secara terstruktur.
2. Menyediakan penyimpanan data monitoring berdasarkan siswa dan periode.
3. Membantu guru melihat riwayat monitoring siswa.
4. Membantu guru melihat perubahan hasil monitoring antarperiode.
5. Mendukung pemantauan minat belajar.
6. Menyediakan catatan observasi sebagai informasi pendukung.
7. Menyediakan pengelolaan hak akses.
8. Menjaga agar informasi hasil monitoring tidak dianggap sebagai diagnosis.

---

# 6. Target Users

## 6.1 Guru

Guru merupakan pengguna utama sistem.

Kebutuhan guru:

- melihat data siswa;
- melakukan monitoring;
- mengisi indikator;
- menyimpan hasil;
- melihat riwayat;
- membandingkan periode;
- menambahkan catatan.

## 6.2 Admin

Admin bertanggung jawab terhadap pengelolaan sistem.

Kebutuhan admin:

- mengelola pengguna;
- mengelola data siswa;
- mengelola kelas;
- mengatur hak akses;
- mengelola indikator.

## 6.3 Siswa

Siswa merupakan objek yang dimonitor.

Pada rancangan awal siswa belum menjadi pengguna langsung sistem.

**[ASUMSI-05]** Hal ini perlu dikonfirmasi melalui analisis kebutuhan.

## 6.4 Pakar

Pakar digunakan untuk membantu melakukan validasi terhadap indikator monitoring.

---

# 7. Stakeholders

| Stakeholder | Kepentingan | Peran |
|---|---|---|
| Guru | Monitoring siswa | Pengguna utama |
| Siswa | Perkembangan sosial, emosional dan minat belajar | Objek monitoring |
| Sekolah | Pengelolaan informasi siswa | Stakeholder |
| Admin | Pengelolaan sistem | Administrator |
| Pakar | Validasi indikator | Validator |
| Orang tua/wali | Informasi perkembangan siswa | Stakeholder [ASUMSI-04] |
| Pengembang | Pengembangan sistem | Developer |

---

# 8. Persona

## Persona 1 - Guru

**Peran:** Guru kelas

**Tujuan:**
- melakukan monitoring;
- mencatat hasil pengamatan;
- melihat perubahan siswa;
- mengetahui riwayat siswa.

**Kendala:**
- jumlah siswa cukup banyak;
- waktu melakukan pencatatan terbatas;
- membutuhkan informasi yang mudah ditemukan.

**Kebutuhan:**
- form sederhana;
- pencarian siswa;
- riwayat;
- perbandingan periode;
- catatan observasi.

---

## Persona 2 - Siswa

**Peran:** Objek monitoring

Siswa menjadi objek yang diamati pada aspek sosial, emosional, dan minat belajar.

---

## Persona 3 - Pakar

**Peran:** Validator indikator

Pakar memberikan penilaian terhadap kesesuaian indikator yang digunakan dalam sistem.

---

# 9. Value Proposition

Sistem memberikan satu tempat terstruktur bagi guru untuk mencatat dan memantau perkembangan siswa.

Nilai utama:

1. Pencatatan lebih terstruktur.
2. Data dapat disimpan berdasarkan periode.
3. Riwayat monitoring dapat dilihat kembali.
4. Perubahan antarperiode dapat dibandingkan.
5. Catatan observasi dapat disimpan.
6. Akses data dapat dibatasi berdasarkan peran.

---

# 10. Fitur Produk

## Fitur utama

1. Login.
2. Dashboard.
3. Pengelolaan data siswa.
4. Pengelolaan kelas.
5. Pengelolaan indikator.
6. Monitoring sosial.
7. Monitoring emosional.
8. Monitoring minat belajar.
9. Catatan observasi.
10. Riwayat monitoring.
11. Perbandingan antarperiode.
12. Ringkasan hasil monitoring.
13. Filter data.
14. Validasi indikator.
15. Pengaturan hak akses.

---

# 11. Indikator Monitoring Awal

## 11.1 Sosial

Indikator awal:

- interaksi dengan teman;
- kemampuan bekerja sama;
- komunikasi;
- partisipasi dalam kelompok;
- kemampuan membantu atau menerima bantuan.

## 11.2 Emosional

Indikator awal:

- mengenali emosi;
- mengendalikan respons;
- merespons perubahan situasi;
- kemampuan meminta bantuan;
- konsistensi respons.

## 11.3 Minat Belajar

Indikator awal:

- ketertarikan mengikuti pembelajaran;
- keaktifan;
- kemauan menyelesaikan tugas;
- rasa ingin tahu;
- ketekunan.

**Catatan:** indikator tersebut merupakan rancangan awal dan harus divalidasi oleh pakar sebelum digunakan sebagai instrumen final.

---

# 12. Konsep Skala

Contoh rancangan skala:

| Nilai | Keterangan |
|---|---|
| 1 | Belum terlihat |
| 2 | Mulai terlihat |
| 3 | Sering terlihat |
| 4 | Konsisten terlihat |

**[ASUMSI-06]** Skala tersebut harus divalidasi oleh pakar.

---

# 13. Konsep Perubahan

Sistem menyimpan hasil monitoring berdasarkan periode.

Contoh:

| Aspek | Periode 1 | Periode 2 | Perubahan |
|---|---:|---:|---|
| Sosial | 2 | 3 | Meningkat |
| Emosional | 2 | 3 | Meningkat |
| Minat Belajar | 3 | 4 | Meningkat |

Sistem hanya menunjukkan perubahan berdasarkan data yang dimasukkan.

Sistem tidak melakukan diagnosis.

---

# 14. KPI

| KPI | Target Awal | Metode Pengukuran |
|---|---:|---|
| Data monitoring berhasil disimpan | ≥95% | Functional testing |
| Waktu respons halaman utama | ≤3 detik | Performance testing |
| Ketepatan perbandingan | 100% | Dataset pengujian |
| Pengguna berhasil menyelesaikan tugas utama | ≥80% | Usability testing |
| Akses tidak sah | 0 kasus | Security testing |
| Transaksi berhasil | ≥95% | Functional testing |

Target dapat disesuaikan setelah dilakukan pengujian nyata.

---

# 15. MoSCoW Scope

## MUST HAVE

- Login.
- Data siswa.
- Data kelas.
- Monitoring sosial.
- Monitoring emosional.
- Monitoring minat belajar.
- Penyimpanan hasil monitoring.
- Riwayat.
- Perbandingan.
- Catatan observasi.
- Hak akses.
- Informasi non-diagnostik.

## SHOULD HAVE

- Filter.
- Ringkasan hasil.
- Validasi indikator.
- Export laporan.

## COULD HAVE

- Grafik perkembangan.
- Pengingat monitoring.
- Akses orang tua.

## WON'T HAVE

- Diagnosis psikologis.
- Rekomendasi klinis.
- Penentuan hukuman.
- Pemeringkatan siswa.
- Keputusan otomatis terhadap siswa.

---

# 16. Non-Goals

Sistem tidak digunakan untuk:

1. melakukan diagnosis psikologis;
2. menentukan kondisi mental siswa;
3. memberikan label negatif;
4. menentukan hukuman;
5. menggantikan guru;
6. menggantikan pakar;
7. memberikan keputusan klinis;
8. mengumpulkan data pribadi yang tidak diperlukan.

---

# 17. Business Rules Tingkat Produk

1. Setiap hasil monitoring harus berkaitan dengan siswa.
2. Setiap monitoring harus memiliki periode.
3. Monitoring dilakukan berdasarkan indikator yang telah ditentukan.
4. Indikator perlu divalidasi sebelum digunakan sebagai instrumen final.
5. Data siswa hanya dapat diakses pengguna yang memiliki kewenangan.
6. Hasil monitoring bukan diagnosis.
7. Sistem tidak memberikan label negatif.
8. Sistem tidak menentukan hukuman.
9. Keputusan tindak lanjut tetap berada pada guru/pihak berwenang.

---

# 18. Risiko

| Risiko | Dampak | Mitigasi |
|---|---|---|
| Indikator tidak sesuai | Hasil monitoring kurang tepat | Validasi pakar |
| Data siswa bocor | Risiko privasi | Hak akses dan keamanan |
| Guru tidak rutin mengisi | Data tidak lengkap | Form sederhana |
| Hasil disalahartikan | Label negatif | Bahasa non-diagnostik |
| Sistem terlalu kompleks | Sulit digunakan | Batasi fitur utama |
| AI menghasilkan hasil salah | Keputusan tidak tepat | AI opsional dan human review |

---

# 19. Asumsi

| ID | Asumsi | Cara Verifikasi |
|---|---|---|
| ASUMSI-01 | Pencatatan yang ada menjadi kendala | Wawancara |
| ASUMSI-02 | Guru membutuhkan perbandingan | Wawancara |
| ASUMSI-03 | Sekolah membutuhkan sistem web | Observasi |
| ASUMSI-04 | Orang tua membutuhkan akses | Wawancara |
| ASUMSI-05 | Siswa bukan pengguna langsung | Analisis kebutuhan |
| ASUMSI-06 | Skala 1–4 sesuai | Validasi pakar |

---

# 20. Keputusan Penggunaan AI

AI belum menjadi fitur wajib.

Alasannya:

1. Sistem utama dapat berjalan tanpa AI.
2. Dataset siswa belum tersedia.
3. Akurasi AI harus diuji.
4. Data siswa memiliki kebutuhan privasi.
5. Keputusan terhadap siswa tidak boleh sepenuhnya diberikan kepada AI.

Jika AI ditambahkan, diperlukan:

- dataset;
- tujuan AI;
- metrik evaluasi;
- accuracy;
- latency;
- privacy;
- fallback;
- human review.

---

# 21. Success Criteria

Produk dianggap memenuhi tujuan awal apabila:

- guru dapat login;
- guru dapat memilih siswa;
- guru dapat melakukan monitoring;
- hasil dapat disimpan;
- riwayat dapat ditampilkan;
- dua periode dapat dibandingkan;
- catatan dapat disimpan;
- hak akses berjalan;
- sistem memberikan informasi non-diagnostik.

---

# 22. Traceability Awal

| Goal | Requirement |
|---|---|
| GO-01 Pencatatan | FR-03, FR-04, FR-05, FR-06 |
| GO-02 Riwayat | FR-07 |
| GO-03 Perbandingan | FR-08 |
| GO-04 Minat belajar | FR-05 |
| GO-05 Catatan observasi | FR-09 |
| GO-06 Keamanan | FR-11, NFR-04, NFR-05 |

---

# 23. Status PRD

Status dokumen:

**Draft**

Dokumen akan diperbarui setelah:

1. observasi;
2. wawancara;
3. analisis kebutuhan;
4. validasi indikator oleh pakar.
