# Prompt Log

## 1. Informasi Dokumen

| Item | Keterangan |
|---|---|
| Nama | Setia Cahya Rani |
| Mata Kuliah | Intelligent Mobile and Web Application Development |
| Proyek | Sistem Monitoring Perubahan Sosial dan Emosional Siswa Sekolah Dasar |
| Judul | Rancang Bangun Sistem Monitoring Perubahan Sosial dan Emosional Siswa Sekolah Dasar Berbasis Web untuk Mendukung Pemantauan Minat Belajar |
| Dokumen | Prompt Log |
| Status | Draft |

---

# 2. Tujuan Prompt Log

Prompt Log digunakan untuk mendokumentasikan proses penggunaan AI dalam membantu penyusunan dokumen kebutuhan sistem.

Dokumen ini mencatat:

1. Konteks yang diberikan kepada AI.
2. Prompt yang digunakan.
3. Tujuan dari setiap prompt.
4. Hasil yang diharapkan.
5. Proses review dan perbaikan.
6. Asumsi yang muncul selama proses penyusunan.
7. Penerapan prinsip Responsible AI.

Prompt Log dibuat agar proses penyusunan PRD dan SRS dapat ditelusuri dan diketahui bagian mana yang berasal dari kebutuhan proyek, asumsi, maupun hasil bantuan AI.

---

# 3. Konteks Awal Proyek

Proyek yang dikembangkan adalah sistem monitoring berbasis web yang digunakan untuk membantu sekolah dalam memantau perubahan sosial dan emosional siswa sekolah dasar serta mendukung pemantauan minat belajar.

Sistem ditujukan terutama untuk membantu guru dalam melakukan pencatatan dan pemantauan perkembangan siswa secara berkala.

Sistem tidak digunakan untuk memberikan diagnosis psikologis atau menentukan kondisi mental siswa.

### Permasalahan Awal

Pemantauan perkembangan sosial dan emosional siswa dapat dilakukan melalui pengamatan guru, tetapi hasil pengamatan dapat sulit ditelusuri apabila masih dilakukan secara manual.

Selain itu, perubahan perilaku siswa dari satu periode ke periode lainnya dapat sulit dibandingkan apabila data tidak tersimpan secara terstruktur.

Oleh karena itu, dibutuhkan sistem berbasis web yang dapat membantu:

- mencatat hasil monitoring siswa;
- menyimpan riwayat monitoring;
- membandingkan perubahan antarperiode;
- mencatat catatan observasi guru;
- memantau indikator sosial;
- memantau indikator emosional;
- memantau indikator minat belajar;
- memberikan informasi perkembangan siswa secara terstruktur.

---

# 4. Prompt 01 — Penyusunan PRD

## Prompt

```text
Saya sedang mengembangkan proyek skripsi dengan judul:

"Rancang Bangun Sistem Monitoring Perubahan Sosial dan Emosional Siswa Sekolah Dasar Berbasis Web untuk Mendukung Pemantauan Minat Belajar"

Buatkan Product Requirements Document (PRD) untuk sistem tersebut.

PRD harus mencakup:
1. Executive Summary
2. Problem Statement
3. Evidence
4. Target Users
5. Stakeholders
6. Persona
7. Value Proposition
8. Goals dan KPI
9. Scope menggunakan MoSCoW
10. Non-goals
11. Assumptions
12. Risks
13. Business Rules
14. Pertimbangan penggunaan AI

Jangan membuat sistem hanya sebagai dashboard. Sistem harus memiliki fungsi untuk menyelesaikan masalah monitoring perkembangan siswa.

Jika terdapat informasi yang belum tersedia, tandai sebagai [ASUMSI-XX] agar dapat diverifikasi kemudian.

Jangan menggunakan metode SAW atau TOPSIS.
