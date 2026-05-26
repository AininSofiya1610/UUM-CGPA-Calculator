# UUM CGPA Calculator

A sleek CGPA calculator built for Universiti Utara Malaysia students, using the UUM grading system.

---

**Live demo:** [uum-cgpa-calculator.vercel.app](https://uum-cgpa-calculator.vercel.app)

## Features

- **Two calculation modes** — Single Semester or full Cumulative CGPA
- **Single Semester mode** — masukkan result sem tertentu sahaja (e.g. Sem 7 je) tanpa perlu input semua sem lepas
- **Previous academic record** — isi CGPA & credit hours lama untuk dapat updated CGPA keseluruhan
- **Cumulative CGPA mode** — track multiple semesters sekaligus dengan collapsible semester cards
- UUM grading scale (A = 4.00, A- = 3.67 ... F = 0.00)
- Live GPA & CGPA calculation
- Honours classification display (First Class, Second Upper, Second Lower, Third Class)
- Clean shadcn-inspired UI

## How to Use

### Single Semester Mode
Sesuai kalau nak check result **satu semester je** tanpa masuk semua rekod lama.

1. Pilih **Single Semester** tab
2. (Optional) Isi **Previous CGPA** dan **Previous Credit Hours** — untuk dapat updated CGPA keseluruhan
3. Tambah subjects, masukkan credit hours dan grade
4. GPA sem + updated CGPA dikira automatik

### Cumulative CGPA Mode
Sesuai kalau nak track **semua semester** dari awal.

1. Pilih **Cumulative CGPA** tab
2. (Optional) Isi previous academic record kalau ada rekod lama
3. Click **Add Semester** untuk tambah semester
4. Masukkan subjects untuk setiap semester
5. CGPA keseluruhan dikira automatik

## UUM Grading Scale

| Grade | Points |
|-------|--------|
| A     | 4.00   |
| A-    | 3.67   |
| B+    | 3.33   |
| B     | 3.00   |
| B-    | 2.67   |
| C+    | 2.33   |
| C     | 2.00   |
| C-    | 1.67   |
| D+    | 1.33   |
| D     | 1.00   |
| E / F | 0.00   |

## Honours Classification

| CGPA        | Classification         |
|-------------|------------------------|
| 3.67 – 4.00 | First Class Honours    |
| 3.00 – 3.66 | Second Class Upper     |
| 2.67 – 2.99 | Second Class Lower     |
| 2.00 – 2.66 | Third Class            |
| Below 2.00  | Below Minimum          |

## Deploy

### Vercel CLI
```bash
npm i -g vercel
cd uum-cgpa-calculator
vercel
```

### GitHub + Vercel (auto-deploy)
1. Push folder ke GitHub repo
2. Pergi [vercel.com](https://vercel.com) → New Project → Import from GitHub
3. Select repo → Deploy
4. Setiap `git push` akan auto-redeploy

---

> Not an official UUM tool. Always verify results with your academic transcript.
