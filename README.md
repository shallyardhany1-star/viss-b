# Spektrofotometer UV-Vis 3D · Penetapan Cr(VI) pada Kulit

Visualisasi 3D interaktif (Three.js) bagan spektrofotometer UV-Vis berkas tunggal dan penerapannya untuk uji
kromium heksavalen [Cr(VI)] pada sampel kulit dengan metode 1,5-difenilkarbazida (±540 nm).

## Fitur
- Model 3D: lampu → monokromator → kuvet → detektor → pembaca data (putar, zoom, klik untuk penjelasan)
- Slider λ dan konsentrasi: warna berkas, absorbansi (A) dan transmitan (T) berubah real-time
- Alur metode uji Cr(VI) pada kulit (ekstraksi buffer fosfat pH 8, pengasaman, DPC, 540 nm)
- Kalkulator kurva kalibrasi (regresi linear, R²) dan hasil mg/kg dari sampel

## Struktur
```
index.html
src/style.css   tampilan
src/scene.js    adegan 3D & interaksi
src/calc.js     regresi & perhitungan mg/kg
```

## Menjalankan lokal
```bash
python3 -m http.server 8000   # lalu buka http://localhost:8000
```

## Hubungkan ke GitHub & publikasi (GitHub Pages)
```bash
git init && git add . && git commit -m "UV-Vis 3D"
git branch -M main
git remote add origin https://github.com/USERNAME/uvvis-3d-cr6.git
git push -u origin main
```
Lalu di GitHub: **Settings → Pages → Deploy from branch → main / (root)**. Situs aktif di
`https://USERNAME.github.io/uvvis-3d-cr6/`.

## Rumus
- A = −log T = ε·b·c
- Cr(VI) (mg/kg) = C(mg/L) × faktor pengenceran × V ekstraksi (mL) / massa sampel (g)

## Catatan
Data kalibrasi dan absorbansi bawaan hanya contoh/simulasi. Gunakan prosedur resmi (ISO 17075-1 / SNI) dan data
laboratorium Anda untuk pelaporan.

Lisensi: MIT
