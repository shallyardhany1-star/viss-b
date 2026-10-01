<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Spektrofotometer UV-Vis 3D · Cr(VI) pada Kulit</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Instrument+Sans:wght@400;600;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="src/style.css">
</head>
<body>
<main class="app">
  <section class="stage" id="stage">
    <canvas id="c" aria-label="Model 3D spektrofotometer UV-Vis"></canvas>
    <div id="labels"></div>
    <p class="hint">Seret untuk memutar · gulir untuk zoom · klik komponen untuk penjelasan</p>
  </section>
  <aside class="panel">
    <h1>Spektrofotometer UV-Vis<br><small>dan penetapan Cr(VI) pada kulit</small></h1>
    <nav class="tabs" role="tablist">
      <button class="tab on" data-t="bagan">Bagan alat</button>
      <button class="tab" data-t="metode">Metode Cr(VI)</button>
      <button class="tab" data-t="hitung">Kurva kalibrasi</button>
    </nav>

    <div class="pane on" id="bagan">
      <div id="info"><h2>Pilih komponen</h2><p>Klik bagian alat di model 3D atau daftar di bawah untuk melihat fungsinya.</p></div>
      <div class="chips" id="chips"></div>
      <label class="ctl"><input type="checkbox" id="ph" checked style="width:auto;margin:0 6px 0 0">Tampilkan foton: warna-warni (polikromatis) sebelum monokromator, satu warna (monokromatis) sesudahnya</label>
      <label class="ctl">Panjang gelombang λ: <b id="wlv">540</b> nm
        <input type="range" id="wl" min="380" max="780" value="540"></label>
      <label class="ctl">Konsentrasi Cr(VI)-DPC: <b id="cv">0.40</b> mg/L
        <input type="range" id="cc" min="0" max="1.2" step="0.05" value="0.4"></label>
      <div class="read"><span>Absorbansi A = <b id="av">0.000</b></span><span>Transmitan T = <b id="tv">100</b>%</span></div>
      <p class="note">Simulasi: kompleks Cr(VI)–difenilkarbazida menyerap maksimum ±540 nm. A = −log T = ε·b·c.</p>
    </div>

    <div class="pane" id="metode">
      <h2>Alur uji Cr(VI) pada kulit</h2>
      <ol class="flow">
        <li><b>Preparasi.</b> Kulit digiling/dipotong halus, ditimbang ±2 g.</li>
        <li><b>Ekstraksi.</b> Dikocok dengan larutan buffer fosfat pH 8,0 (±50 mL) selama ±3 jam; Cr(VI) larut sebagai kromat.</li>
        <li><b>Penyaringan.</b> Ekstrak disaring; aliquot dipindah ke labu ukur.</li>
        <li><b>Pengasaman.</b> Ditambah asam fosfat hingga pH ±1–2.</li>
        <li><b>Pembentukan warna.</b> Ditambah 1,5-difenilkarbazida: Cr(VI) mengoksidasi DPC, terbentuk kompleks Cr(III)–difenilkarbazon berwarna merah-ungu.</li>
        <li><b>Pengukuran.</b> Dibaca pada ±540 nm terhadap blanko reagen.</li>
        <li><b>Perhitungan.</b> Konsentrasi dari kurva kalibrasi, lalu mg/kg kulit.</li>
      </ol>
      <p class="note">Mengacu pada prinsip ISO 17075-1 / SNI setara. Batas umum Cr(VI) pada kulit: 3 mg/kg (REACH, batas deteksi metode). Selalu cek prosedur dan volume resmi laboratorium Anda; ekstrak kulit kadang berwarna sehingga perlu koreksi matriks/spike recovery.</p>
    </div>

    <div class="pane" id="hitung">
      <h2>Kurva kalibrasi &amp; hasil sampel</h2>
      <table id="std"><thead><tr><th>C (mg/L)</th><th>Absorbansi</th></tr></thead><tbody></tbody></table>
      <div class="grid2">
        <label>A sampel<input type="number" id="as" step="0.001" value="0.152"></label>
        <label>Massa sampel (g)<input type="number" id="m" step="0.01" value="2.00"></label>
        <label>Vol. ekstraksi (mL)<input type="number" id="ve" step="1" value="50"></label>
        <label>Faktor pengenceran<input type="number" id="fp" step="0.1" value="1"></label>
      </div>
      <canvas id="cal" width="420" height="240"></canvas>
      <div class="result" id="res"></div>
    </div>
  </aside>
</main>
<script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>
<script src="src/scene.js"></script>
<script src="src/calc.js"></script>
</body>
</html>
