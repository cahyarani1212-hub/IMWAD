# Prompt Log

## 1. Informasi Dokumen

| Item | Keterangan |
|---|---|
| Nama | Setia Cahya Rani |
| Mata Kuliah | Intelligent Mobile and Web Application Development |
| Proyek | Sistem Monitoring Perubahan Sosial dan Emosional Siswa Sekolah Dasar |
| Judul | Rancang Bangun Sistem Monitoring Perubahan Sosial dan Emosional Siswa Sekolah Dasar Berbasis Web untuk Mendukung Pemantauan Minat Belajar |
| Platform | Website |
| Dokumen | Prompt Log |
| Status | Draft |

---

# 2. Tujuan Prompt Log

Prompt Log digunakan untuk mendokumentasikan proses penyusunan dokumen PRD dan SRS dengan bantuan prompt.

Dokumen ini mencatat:

1. Konteks proyek.
2. Prompt yang digunakan.
3. Tujuan setiap prompt.
4. Hasil yang diharapkan.
5. Proses review.
6. Asumsi yang muncul.
7. Perbaikan setelah review.

Penggunaan AI pada tahap ini hanya untuk membantu proses penyusunan dan pemeriksaan dokumen.

AI bukan merupakan fitur dari sistem yang dirancang.

Sistem yang dikembangkan tidak menggunakan AI.

---

# 3. Konteks Awal Proyek

Judul proyek:

"Rancang Bangun Sistem Monitoring Perubahan Sosial dan Emosional Siswa Sekolah Dasar Berbasis Web untuk Mendukung Pemantauan Minat Belajar"

Sistem merupakan website yang membantu guru melakukan monitoring perubahan sosial dan emosional siswa serta mendukung pemantauan minat belajar.

Pengguna sistem:

1. Admin
2. Guru
3. Siswa

Sistem tidak menggunakan AI sebagai bagian dari fitur.

Sistem juga tidak digunakan untuk melakukan diagnosis psikologis siswa.

---

# 4. Prompt 01 — Penyusunan PRD

## Prompt

```text
Kamu adalah requirements analyst yang membantu menyusun Product Requirements Document (PRD).

Susun PRD untuk proyek:

"Rancang Bangun Sistem Monitoring Perubahan Sosial dan Emosional Siswa Sekolah Dasar Berbasis Web untuk Mendukung Pemantauan Minat Belajar"

Sistem berbasis website.

Pengguna:
1. Admin
2. Guru
3. Siswa

Fitur utama:
- login;
- pengelolaan data siswa;
- pengelolaan kelas;
- monitoring sosial;
- monitoring emosional;
- monitoring minat belajar;
- riwayat monitoring;
- catatan observasi;
- perbandingan hasil monitoring antarperiode.

PRD harus mencakup:
- Executive Summary;
- Problem Statement;
- Evidence;
- Target User;
- Stakeholder;
- Persona;
- Value Proposition;
- Goals dan KPI;
- Scope MoSCoW;
- Non-goals;
- Assumptions;
- Risks.

Jangan menambahkan Pakar atau Ahli sebagai pengguna.
Jangan menggunakan SAW atau TOPSIS.
Jangan memasukkan fitur AI.
Jangan membuat diagnosis psikologis.
Jika informasi belum tersedia, tandai sebagai [ASUMSI-XX].
