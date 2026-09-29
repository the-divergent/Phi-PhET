# Φ Phi-PhET — Simulasi Sains Interaktif

Simulasi sains interaktif ala PhET, ditulis ulang dari nol (HTML5 Canvas + JS murni, tanpa dependency).

Terinspirasi semangat PhET Interactive Simulations (University of Colorado Boulder) — seluruh kode di repo ini orisinal.

## Simulasi (Batch 1)

| Simulasi | Folder | Deskripsi |
|---|---|---|
| Lab Hukum Ohm | `sims/hukum-ohm/` | Slider V/R, animasi aliran elektron, daya |
| Kit Rangkaian DC | `sims/rangkaian-dc/` | Rakit rangkaian di grid; arus dihitung otomatis via Modified Nodal Analysis |
| Lab Kapasitor | `sims/kapasitor/` | Charge/discharge RC, grafik Vc(t) & I(t) live |

## Menambah simulasi baru

1. Buat folder `sims/nama-simulasi/` berisi `index.html` mandiri.
2. Daftarkan di `index.html` (tambah satu card).
3. Push — GitHub Pages update otomatis.

## Menjalankan lokal

Buka `index.html` langsung di browser, atau:

```bash
python3 -m http.server 8000
# buka http://localhost:8000
```

## Hosting

GitHub Pages: Settings → Pages → Deploy from a branch → `main` → `/(root)`.
