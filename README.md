# NATA Academic Prototype

> **Prototype akademik untuk validasi kebutuhan, analisis proses bisnis, dan pengembangan solusi awal NATA**
>
> Repositori ini digunakan untuk kebutuhan akademik **PKL / Tugas Akhir Program Studi Sistem Informasi — UBSI**.

[![Status](https://img.shields.io/badge/status-discovery-blue)](#-status)
[![Tahap](https://img.shields.io/badge/tahap-validation-orange)](#-status)
[![Lisensi](https://img.shields.io/badge/license-MIT-green)](LICENSE)

---

## 📌 Metadata Akademik

| Field | Isi |
|---|---|
| Nama Mahasiswa | `Fajar Kurnia` |
| NIM | `19231695` |
| Program Studi | Sistem Informasi — UBSI |
| Dosen Pembimbing | `[...]` |
| Periode PKL / TA | `[-]` |
| Versi Dokumen | `v0.1.0` |
| Terakhir Diperbarui | `[-]` |

---

## 🎯 Ringkasan

`nata_academic_prototype` adalah repositori yang menyimpan seluruh artefak akademik untuk PKL dan Tugas Akhir terkait **NATA** — sebuah sistem informasi manajemen operasional untuk UMKM jasa.

Repositori ini dipakai untuk:

- 📑 Dokumentasi analisis kebutuhan sistem
- 🔄 Pemetaan proses bisnis (BPMN / UML / flow)
- 🎨 Desain wireframe & prototype
- 👥 Riset lapangan dan wawancara pengguna
- 📓 Logbook kegiatan PKL
- 📝 Draft laporan PKL / Tugas Akhir

---

## 🎯 Tujuan

1. Menjadi **basis kerja akademik** yang sesuai dengan pedoman PKL UBSI.
2. Menyimpan **artefak riset lapangan dan validasi pengguna** secara terstruktur.
3. Menyusun **prototype yang dapat dipresentasikan** ke dosen pembimbing dan penguji.
4. Menjaga agar **seluruh proses pengembangan terdokumentasi** dengan rapi dan bisa ditelusuri.

---

## 📂 Ruang Lingkup

Repositori ini memuat:

- ✅ Company profile versi akademik
- ✅ Proposal PKL
- ✅ Dokumen kebutuhan sistem (BRD, SRS, user stories)
- ✅ Hasil wawancara lapangan (catatan, transkrip, ringkasan)
- ✅ Assumption board
- ✅ BPMN / UML / flow proses
- ✅ Wireframe / prototype
- ✅ Logbook PKL
- ✅ Draft laporan PKL / TA
- ✅ Daftar referensi

Repositori ini **tidak** memuat:

- ❌ Data pelanggan nyata
- ❌ Kredensial produksi / API key
- ❌ Rahasia dagang / strategi bisnis internal UMKM

---

## 🧭 Prinsip Kerja

- **Fokus pada validasi masalah nyata** — bukan solusi yang diasumsikan.
- **Gunakan bahasa akademik** yang sesuai dengan disiplin Sistem Informasi.
- **Jaga kerahasiaan data responden** — anonimisasi bila diperlukan, simpan data sensitif secara lokal.
- **Setiap artefak harus bisa dipertanggungjawabkan** secara akademik — cantumkan sumber, metode, dan tanggal.

---

## 📁 Struktur Folder

```
nata_academic_prototype/
├── README.md                      # Dokumen ini
├── LICENSE                        # Lisensi MIT
├── CHANGELOG.md                   # Riwayat versi dokumen
├── .gitignore                     # File/folder yang diabaikan Git
│
├── docs/                          # Dokumen utama akademik
│   ├── proposal/                  # Proposal PKL / TA
│   ├── company_profile/           # Profil perusahaan versi akademik
│   ├── requirement_analysis/      # Analisis kebutuhan sistem
│   └── laporan/                   # Draft laporan PKL / TA
│
├── assets/                        # Aset visual & diagram
│   ├── wireframe/                 # Sketsa & mockup UI
│   ├── diagram/                   # BPMN, UML, flow proses
│   └── gambar_lapangan/           # Dokumentasi foto saat riset
│
├── interviews/                    # Riset kualitatif
│   ├── notes/                     # Catatan mentah wawancara
│   ├── transcripts/               # Transkrip verbatim
│   └── summary/                   # Ringkasan & sintesis
│
├── prototype/                     # Prototype aplikasi
├── logbook/                       # Logbook harian/mingguan PKL
└── references/                    # Jurnal, paper, & sumber acuan
```

> 💡 Setiap folder berisi `README.md` lokal yang menjelaskan konvensi penamaan dan template yang tersedia di dalamnya.

---

## 🔄 Alur Kerja

1. **Kumpulkan data lapangan** — wawancara, observasi, dokumentasi.
2. **Dokumentasikan hasil wawancara** — simpan catatan, transkrip, dan ringkasan.
3. **Identifikasi pola masalah** — buat assumption board & affinity diagram.
4. **Susun kebutuhan sistem** — BRD, SRS, user stories.
5. **Buat prototype** — wireframe low-fi → high-fi → interactive.
6. **Uji prototype** — usability test dengan pilot user.
7. **Gunakan hasilnya untuk laporan PKL / TA.**

---

## 🔁 Alur Artefak

```
interviews/summary/tema_agregat.md
            ↓
docs/requirement_analysis/ (BRD, SRS, user stories)
            ↓
assets/diagram/ & assets/wireframe/
            ↓
prototype/ (uji usability)
            ↓
docs/laporan/ (BAB IV Hasil & Pembahasan)
```

---

## 🚀 Cara Menggunakan Repo Ini

1. **Clone** repositori:
   ```bash
   git clone https://github.com/fajarkurnia0388/nata_academic_prototype.git
   ```
2. **Isi setiap folder** menggunakan template yang sudah disediakan (lihat `README.md` di setiap subfolder).
3. **Commit rutin** dengan pesan yang deskriptif, contoh:
   ```
   docs: tambah proposal PKL v0.2
   interview: tambah transkrip wawancara Bu Ani (UMKM A)
   diagram: tambah BPMN proses order berjalan
   ```
4. **Perbarui CHANGELOG.md** setiap ada versi baru artefak.

---

## 📊 Status

| Aspek | Status |
|---|---|
| Tahap | 🔵 Discovery / Validation |
| Fokus | Analisis, riset, prototype |
| Pengguna aktif | ⚪ Belum ada / terbatas pilot |
| Wawancara selesai | `[ ] 0 / [target]` |
| BPMN | `[ ] belum` / `[x] selesai` |
| Wireframe | `[ ] belum` / `[x] selesai` |
| Prototype interaktif | `[ ] belum` / `[x] selesai` |
| Uji usability | `[ ] belum` / `[x] selesai` |
| Laporan PKL/TA | `[ ] draft` / `[x] final` |

---

## ⚠️ Catatan Penting

Repositori ini adalah **ruang kerja akademik**. Setiap fitur yang masih eksperimental, berisiko, atau belum divalidasi cukup disimpan di sini sebagai bahan akademik. Jika sudah stabil dan divalidasi, hasilnya akan dilaporkan di laporan akhir PKL/TA.

---

## 📞 Kontak

- **Penulis:** Fajar Kurnia — [`@fajarkurnia0388`](https://github.com/fajarkurnia0388)
- **Email kampus:** `[Isi email UBSI]`
- **Dosen Pembimbing:** `[Isi nama & kontak]`

---

> "Riset yang baik dimulai dari pertanyaan yang jelas, bukan solusi yang sudah jadi."
