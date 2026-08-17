# Push-Dose Norepinephrine for Intraoperative Hypotension in Non-Obstetric Surgery
## Systematic Review Toolkit

**Judul Lengkap:**
*Efficacy and Safety of Push-Dose Norepinephrine for Intraoperative Hypotension Management in Non-Obstetric Surgery: A Systematic Review*

---

## PICO Framework (Revisi)

| Komponen | Deskripsi |
|----------|-----------|
| **P** (Population) | Pasien dewasa yang menjalani operasi non-obstetri dengan hipotensi intraoperatif |
| **I** (Intervention) | Push-dose / bolus norepinephrine (noradrenaline) |
| **C** (Comparison) | Infus kontinu NE / Vasopressor push-dose lain (epinephrine, phenylephrine) / Tanpa kontrol |
| **O** (Outcome) | Reversal hipotensi (pencapaian target MAP), waktu pencapaian target MAP, efek samping (overshoot hipertensi, aritmia, komplikasi akses vaskular) |

---

## Search Strategy

**Database:** PubMed, Scopus, ProQuest

**Keywords:**
```
("Norepinephrine" OR "Noradrenaline") AND ("push dose" OR "bolus" OR "intermittent") AND ("intraoperative hypotension" OR "perioperative hypotension" OR "anesthesia" OR "anaesthesia" OR "surgery" OR "surgical")
```

---

## Struktur File

```
PD-NE/
├── README.md                          ← Panduan lengkap
├── screening/
│   ├── fulltext_screening_form.md     ← Form skrining full-text (per artikel)
│   └── screening_summary.csv          ← Ringkasan keputusan skrining
├── extraction/
│   ├── data_extraction_template.md    ← Template ekstraksi data
│   └── extracted_data_summary.md      ← Ringkasan data semua artikel
├── rob/
│   ├── risk_of_bias_template.md       ← Template RoB (RoB 2 / NOS)
│   └── rob_summary.md                 ← Ringkasan RoB semua artikel
└── synthesis/
    └── results_synthesis.md           ← Sintesis hasil & tabel summary
```

---

## Cara Penggunaan

1. **Full-Text Screening** → Isi `screening/fulltext_screening_form.md` untuk setiap artikel, catat keputusan di `screening/screening_summary.csv`
2. **Ekstraksi Data** → Isi `extraction/data_extraction_template.md` untuk setiap artikel yang lolos skrining
3. **Risk of Bias** → Isi `rob/risk_of_bias_template.md` untuk setiap artikel menggunakan alat yang sesuai:
   - RCT → **RoB 2** (Cochrane Risk of Bias 2.0)
   - Observational → **Newcastle-Ottawa Scale (NOS)**
4. **Sintesis** → Rangkum di `synthesis/results_synthesis.md`

---

## Kriteria Inklusi & Eksklusi

### Inklusi
- Studi pada pasien dewasa (≥18 tahun) menjalani operasi non-obstetri
- Intervensi: push-dose / bolus norepinephrine untuk hipotensi intraoperatif
- Melaporkan setidaknya satu outcome (MAP target, waktu respon, efek samping)
- Full-text tersedia
- Bahasa: Inggris atau Indonesia

### Eksklusi
- Populasi obstetri (seksio sesarea, persalinan)
- Pasien ICU / sepsis (bukan setting intraoperatif)
- Laporan kasus tunggal (n=1) tanpa data komparatif
- Review artikel, editorial, opini
- Data tidak dapat diekstraksi