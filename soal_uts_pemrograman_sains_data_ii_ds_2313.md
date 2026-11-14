# SOAL UJIAN TENGAH SEMESTER (UTS)

## PEMROGRAMAN SAINS DATA II (DS-2313)

**Institut Teknologi Sains Bandung (ITSB)**

**Fakultas Digital, Desain dan Bisnis | Program Studi Sains Data**

* **Bagian A:** Konsep

* **Bagian B:** Praktikum Pemrograman

* *Dikerjakan menggunakan Python pada Jupyter Notebook (`.ipynb`)*

### Informasi Ujian

| Atribut | Keterangan | 
| ----- | ----- | 
| **Mata Kuliah / Kode** | Pemrograman Sains Data II / DS-2313 (3 SKS: T = 2, P = 1) | 
| **Dosen Pengampu** | Bakti Siregar, S.Si., M.Sc | 
| **Semester / Tahun Akademik** | Semester 4 / TA Ganjil 2026/2027 | 
| **Hari / Tanggal** | Rabu, 11 November 2026 | 
| **Waktu** | $150 \text{ menit } (1 \times 3 \times 50')$ | 
| **Sifat Ujian** | Kerjakan Mandiri dan Presentasikan di Video YouTube (Maksimum 10 Menit) | 
| **Nama / NIM** |  | 
| **Kelas** |  | 

## A. Informasi Ujian dan Keterkaitan dengan RPS

Ujian ini merupakan Ujian Tengah Semester (UTS) pada Pertemuan 8 dengan bobot 20% terhadap nilai akhir mata kuliah (RPS OBE DS-2313). Sesuai Rancangan Penilaian RPS, UTS menekankan studi kasus teknis pemrosesan dan pembersihan data menggunakan library modern (CPMK-1), yang dikerjakan sebagai masalah pemrograman: menulis fungsi dan kelas yang mendeteksi, memperbaiki, dan memverifikasi data secara otomatis. Cakupan materi adalah Pertemuan 1–7. Ujian terdiri atas Bagian A - Konsep (20 poin) dan Bagian B - Praktikum (80 poin) dalam satu notebook.

### CPL Prodi yang dibebankan dan bobotnya pada UTS

| Kode | Deskripsi CPL (RPS DS-2313) | Diukur pada | Bobot | 
| ----- | ----- | ----- | ----- | 
| **CPL-1** | Menguasai konsep teoretis sains data, statistik, dan komputasi untuk menyelesaikan permasalahan berbasis data secara sistematis. | A1–A9, B3, B5 | 50% | 
| **CPL-2** | Mampu merancang dan mengimplementasikan algoritma pemodelan data tingkat lanjut menggunakan perangkat lunak dan bahasa pemrograman terkini. | B1, B2, B4, B6 | 50% | 
| **TOTAL** |  |  | **100%** | 

> *Catatan:* Proporsi 50% : 50% mengikuti tabel Korelasi CPL terhadap CPMK pada RPS. B3 dan B5 dipetakan ke CPL-1 karena menuntut keputusan statistik (pemilihan imputasi, Z-score vs IQR, kuadrat terkecil dan metrik regresi); B1, B2, B4, dan B6 dipetakan ke CPL-2 karena menuntut perancangan dan implementasi algoritma.

### CPMK yang diukur dan bobotnya pada UTS

| CPMK | Deskripsi CPMK (RPS DS-2313) | Sub-CPMK | Diukur pada | Bobot | 
| ----- | ----- | ----- | ----- | ----- | 
| **CPMK-1** | Mahasiswa mampu menguasai teknik pemrosesan data tingkat lanjut dan pembersihan data menggunakan library modern. | Sub-CPMK-1, 2 | A1–A5, A9, B1–B4 | 69% | 
| **CPMK-2** | Mahasiswa mampu membangun model prediksi menggunakan algoritma machine learning supervised dan unsupervised dengan akurasi yang terukur. | Sub-CPMK-3, 4 | A6–A8, B5, B6 | 31% | 
| **TOTAL** |  |  |  | **100%** | 

> *Catatan:* Porsi CPMK-1 lebih besar sesuai Rancangan Penilaian RPS yang menetapkan UTS untuk CPMK-1. CPMK-2 diukur sebagai pendukung melalui materi Pertemuan 5–7.

### Sub-CPMK yang diukur

| Sub-CPMK | Pertemuan | Kemampuan Akhir (RPS DS-2313) | Diukur pada | 
| ----- | ----- | ----- | ----- | 
| **Sub-CPMK-1** | 1–2 | C3 - Melakukan teknik manipulasi data kompleks dan pembersihan data menggunakan pustaka Pandas dan NumPy. | A1, A2, A9, B2 | 
| **Sub-CPMK-2** | 3–4 | C4 - Mendeteksi dan menangani anomali data serta menangani missing values dengan metode statistik. | A3, A4, A5, B1, B3, B4 | 
| **Sub-CPMK-3** | 5–6 | C3 - Mengimplementasikan algoritma regresi dan klasifikasi dasar dalam membangun model prediktif. | A6, A7, B5, B6(b) | 
| **Sub-CPMK-4** | 7 | C4 - Mengevaluasi kinerja model menggunakan metrik akurasi, presisi, recall, dan F1-score. | A8, B6(a, c, d) | 

### Struktur Soal

| Bagian | Isi | CPMK | CPL | Poin | 
| ----- | ----- | ----- | ----- | ----- | 
| **A** | Konsep: 9 soal uraian (A1–A8 @ 2 poin, A9 @ 4 poin) | CPMK-1, CPMK-2 | CPL-1 | 20 | 
| **B** | Praktikum: 6 soal pemrograman dengan uji publik dan uji tersembunyi | CPMK-1, CPMK-2 | CPL-1, CPL-2 | 80 | 
| **TOTAL** |  |  |  | **100** | 

## B. Petunjuk Ujian

1. Kerjakan mandiri dan presentasikan di video YouTube (maksimum 10 menit).

2. Ganti nama berkas notebook menjadi `UTS_DS2313_<NIM>.ipynb` dan isi identitas.

3. Jalankan sel **Persiapan** tanpa mengubahnya. Sel tersebut juga menyediakan fungsi `uji()` dan `jalankan_uji()`.

4. Gunakan `random_state=42` atau `seed=42` pada setiap pembagian data dan model.

5. Nama dan *signature* fungsi atau kelas yang diminta tidak boleh diubah, karena uji tersembunyi memanggilnya persis seperti itu.

6. Setiap soal Bagian B memiliki sel uji publik. Lulus semua uji publik belum menjamin nilai penuh: uji tersembunyi memeriksa kasus tepi (data kosong, kolom hilang, nilai ekstrem, dan masukan yang tidak boleh diubah).

7. Setiap hasil wajib disertai interpretasi singkat. Jalankan **Restart & Run All** sebelum mengumpulkan, lalu unggah notebook ke LMS sebelum waktu ujian berakhir.

## Dataset dan Persiapan Data

Dataset adalah **Heart Disease (UCI Cleveland)** berisi 303 pasien, ditambah tabel referensi klinik. Versi ujian sengaja dikotori oleh sel Persiapan berikut (**jangan diubah**):

```python
URL = 'https://raw.githubusercontent.com/kb22/Heart-Disease-Prediction/master/dataset.csv'
asli = pd.read_csv(URL)

# Pembuatan data ujian (JANGAN DIUBAH)
rng = np.random.default_rng(2026)
hd = asli.copy()
hd.insert(0, 'id_pasien', [f'P{i:04d}' for i in range(1, len(hd) + 1)])
hd['kode_klinik'] = rng.choice(['KL01', 'KL02', 'KL03', 'KL04', 'KL05'], len(hd))
hd['sex'] = hd['sex'].map({1: 'Laki-laki', 0: 'Perempuan'})
hd.loc[rng.choice(len(hd), 12, replace=False), 'sex'] = 'L'          # penulisan tidak konsisten
hd.loc[rng.choice(len(hd), 6, replace=False), 'sex'] = ' perempuan ' # huruf & spasi tidak konsisten
hd.loc[rng.choice(len(hd), 18, replace=False), 'chol'] = 0           # nilai mustahil (kode hilang)
hd.loc[rng.choice(len(hd), 15, replace=False), 'trestbps'] = np.nan  # nilai hilang
hd.loc[rng.choice(len(hd), 2, replace=False), 'chol'] = 5640         # galat input
hd['age'] = hd['age'].astype(str) + 'th'                             # angka sebagai teks
hd = pd.concat([hd, hd.sample(6, random_state=3)], ignore_index=True) # duplikat

klinik = pd.DataFrame({
    'kode_klinik': ['KL01', 'KL02', 'KL03', 'KL04', 'KL06'],
    'kota': ['Bekasi', 'Bandung', 'Jakarta', 'Bogor', 'Depok'],
    'tipe': ['RS Swasta', 'RSUD', 'RS Swasta', 'Klinik Utama', 'RSUD']
})

HD_ASLI = hd.copy()  # untuk memeriksa bahwa fungsi tidak mengubah masukan
print('hd:', hd.shape, '| klinik:', klinik.shape)  # hd: (309, 16) | klinik: (5, 3)
```

### Kamus Data

| Kolom | Keterangan | 
| ----- | ----- | 
| `id_pasien`, `kode_klinik` | Pengenal pasien dan kode klinik (referensi ke tabel `klinik`) | 
| `age`, `sex` | Usia (tersimpan sebagai teks) dan jenis kelamin (penulisan tidak konsisten) | 
| `cp` | Tipe nyeri dada (0–3) | 
| `trestbps`, `chol` | Tekanan darah istirahat ($\text{mmHg}$) dan kolesterol ($\text{mg/dL}$) | 
| `fbs`, `restecg` | Gula darah puasa $> 120$ dan hasil EKG istirahat | 
| `thalach`, `exang`, `oldpeak` | Denyut jantung maksimum, angina akibat olahraga, dan depresi ST | 
| `slope`, `ca`, `thal` | Hasil pemeriksaan lanjutan | 
| `target` | $1 =$ penyakit jantung, $0 =$ tidak | 

## BAGIAN A — KONSEP

**20 poin | A1–A8 @ 2 poin, A9 @ 4 poin | CPL-1 | CPMK-1, CPMK-2 | Dikerjakan tanpa bantuan**

* **A1.** Tuliskan aturan *broadcasting* NumPy sebagai algoritma (pseudocode) yang menerima dua *shape* dan mengembalikan *shape* hasil atau galat. Apa hasil `(4, 3)` dengan `(3,)` dan `(4, 3)` dengan `(4,)`? Bagaimana program dapat mendeteksi bahwa sebuah potongan array adalah *view*?

  *(2 poin | CPL-1 | CPMK-1 | Sub-CPMK-1)*

* **A2.** Jelaskan algoritma *hash join* di balik `merge` beserta kompleksitasnya, dibandingkan *nested loop join*. Mengapa *join* dengan kunci ganda di tabel kanan berbahaya, dan bagaimana program mendeteksinya sebelum *join* dijalankan?

  *(2 poin | CPL-1 | CPMK-1 | Sub-CPMK-1)*

* **A3.** Jelaskan MCAR, MAR, dan MNAR dengan contoh rekam medis. Tuliskan algoritma sederhana untuk menguji secara otomatis apakah nilai hilang suatu kolom konsisten dengan MCAR. Mengapa MNAR tidak dapat diuji dari data?

  *(2 poin | CPL-1 | CPMK-1 | Sub-CPMK-2)*

* **A4.** Pada Pertemuan 3, aturan *"lonjakan frekuensi di ujung distribusi"* dipakai untuk mendeteksi kode hilang. Jelaskan logikanya. Mengapa `Pregnancies = 0` tidak ditandai, sedangkan `Insulin = 0` ditandai? Mengapa pembersih otomatis memakai kebijakan konsensus ($\ge 2$ aturan) sebelum mengubah data?

  *(2 poin | CPL-1 | CPMK-1 | Sub-CPMK-2)*

* **A5.** Jelaskan kontrak `fit/transform`. Mengapa transformasi yang mempelajari statistik harus berupa kelas, bukan fungsi? Apa arti konvensi atribut berakhiran `_` dan mengapa `fit` mengembalikan `self`? Apa yang harus terjadi bila `transform` dipanggil sebelum `fit`?

  *(2 poin | CPL-1 | CPMK-1 | Sub-CPMK-2)*

* **A6.** Tuliskan pseudocode *gradient descent* untuk regresi linear yang (a) memiliki kriteria henti dan (b) mendeteksi divergensi serta memperbaikinya sendiri. Tuliskan rumus $R^2$, MAE, RMSE dan jelaskan mengapa $\text{RMSE} \ge \text{MAE}$.

  *(2 poin | CPL-1 | CPMK-2 | Sub-CPMK-3)*

* **A7.** Mengapa `1/(1+np.exp(-z))` dan `np.log(p)` dapat gagal secara numerik? Tuliskan versi stabil *sigmoid* dan *log-loss*. Apa arti $\exp(\beta_j)$ pada regresi logistik?

  *(2 poin | CPL-1 | CPMK-2 | Sub-CPMK-3)*

* **A8.** Dari *confusion matrix* $TN=90$, $FP=10$, $FN=30$, $TP=70$ hitung akurasi, presisi, recall, dan F1. Jelaskan cara menghitung ROC-AUC tanpa menggambar kurva beserta kompleksitasnya.

  *(2 poin | CPL-1 | CPMK-2 | Sub-CPMK-4)*

* **A9.** Konsep pemrograman:

  *(4 poin (1 poin per bagian) | CPL-1 | CPMK-1 | Sub-CPMK-1, Sub-CPMK-2)*

  **(a)** Apa itu fungsi murni dan idempoten, dan mengapa keduanya penting untuk fungsi pembersihan data?

  **(b)** Kapan memakai `raise` dan kapan memakai `assert`?

  **(c)** Tuliskan kerangka *custom exception* `DataTidakValid` beserta cara menangkapnya.

  **(d)** Apa itu *closure*? Berikan contoh dari evaluasi model.

## BAGIAN B — PRAKTIKUM PEMROGRAMAN

**80 poin | B1–B6 | CPL-1 (30 poin), CPL-2 (50 poin) | CPMK-1, CPMK-2 | Boleh membuka dokumentasi resmi**

> *Catatan:* Untuk setiap soal: tulis fungsi atau kelas yang diminta pada sel kode, jalankan sel uji publik, lalu tulis interpretasi. Semua fungsi harus murni (tidak mengubah DataFrame masukan) dan diberi *docstring*.

### B1 — Detektor Masalah Kualitas Data Otomatis

**10 poin | CPL-2 | CPMK-1 | Sub-CPMK-2 | 9 uji publik**

```python
def deteksi_masalah(df, ref_klinik):  # -> DataFrame ['jenis', 'kolom', 'jumlah', 'contoh']
```

Fungsi harus menemukan sendiri masalah berikut tanpa menuliskan nama kolom tertentu di dalam logika (kecuali `kode_klinik` untuk referensi), dan tidak boleh mengubah `df`:

| Jenis | Kriteria | 
| ----- | ----- | 
| `ANGKA_SEBAGAI_TEKS` | Kolom bertipe teks yang isinya angka beserta satuan | 
| `KATEGORI_TIDAK_KONSISTEN` | Penulisan kategori berbeda huruf, spasi, atau singkatan | 
| `NOL_MUSTAHIL` | Nilai $0$ di ujung bawah kolom numerik kontinu yang frekuensinya melonjak dibanding nilai tetangganya dan terpisah lebih dari $1/2 \text{ IQR}$ dari nilai terkecil berikutnya. Nol yang menyatu dengan sebaran (misalnya `oldpeak`) adalah nilai sah. | 
| `HILANG` | Nilai `NaN` pada suatu kolom | 
| `NILAI_EKSTREM` | Nilai $> Q_3 + 10 \cdot \text{IQR}$ | 
| `DUPLIKAT` | Baris ganda dengan mengabaikan kolom ID | 
| `KUNCI_YATIM` | Kode klinik yang tidak memiliki referensi di `ref_klinik` | 

### B2 — Wrangling yang Dapat Diuji

**15 poin | CPL-2 | CPMK-1 | Sub-CPMK-1 | 6 uji publik**

```python
def seragamkan(df):
def gabung_aman(kiri, kanan, kunci):
```

**(a)** Tulis `seragamkan(df)` (fungsi murni) yang mengubah `age` menjadi numerik dengan membuang satuan teks apa pun menggunakan *regex*, serta menyeragamkan `sex` menjadi tepat `{'Laki-laki', 'Perempuan'}` memakai peta yang dibangun otomatis dari kunci kanonik dan aturan huruf awal (bukan daftar ganti manual).

**(b)** Tulis `gabung_aman(kiri, kanan, kunci)` yang memvalidasi *join many-to-one* sebelum menjalankannya (lempar `ValueError` bila kunci kanan ganda), melakukan *left join*, menjamin jumlah baris tetap, dan mencetak kunci yatim.

**(c)** Dengan satu rantai *method*, tampilkan rata-rata `chol` valid ($100\text{–}700$) dan persentase `target == 1` per `kota` $\times$ `sex`.

### B3 — Pembersih Otomatis yang Teruji

**20 poin | CPL-1 | CPMK-1 | Sub-CPMK-2 | 6 uji publik**

```python
def pilih_imputasi(df, kolom, kelompok='sex', proporsi=0.2, ulang=5, seed=42):  # -> 'median' | 'median_kelompok'
def bersihkan(df):
```

Tulis `bersihkan(df)`, fungsi yang murni dan idempoten, yang:
**(a)** memanggil `seragamkan`;

**(b)** membuang duplikat dengan mengabaikan `id_pasien`;

**(c)** mengodekan nol mustahil sebagai `NaN` memakai hasil `deteksi_masalah` (bukan menulis `'chol'` secara langsung);

**(d)** memperlakukan nilai ekstrem (galat input) sebagai nilai hilang;

**(e)** mengimputasi kolom numerik yang hilang dengan metode yang dipilih program melalui eksperimen penyamaran kecil antara median global dan median per `sex` (fungsi `pilih_imputasi`);

**(f)** diakhiri dengan `assert` validasi.

Setelah itu, bandingkan deteksi *outlier* Z-score dan IQR pada `chol` dan `trestbps` hasil pembersihan.

### B4 — Transformer Sendiri dengan Kontrak `fit/transform`

**10 poin | CPL-2 | CPMK-1 | Sub-CPMK-2 | 6 uji publik**

```python
class SkalaRobustku:  # __init__(self, kolom), fit(X) -> self, transform(X) -> DataFrame
class OneHotKu:       # __init__(self, kolom), fit(X) -> self, transform(X) -> DataFrame
```

1. Bagi data bersih $75/25$ dengan `stratify` `target` dan `random_state=42`.

2. Tulis kelas `SkalaRobustku` dan `OneHotKu` dengan antarmuka `fit(X) -> self` dan `transform(X) -> DataFrame` baru (tidak mengubah `X`).

3. Lempar `RuntimeError` bila `transform` dipanggil sebelum `fit`, dan beri akhiran `_` pada atribut hasil belajar.

4. `OneHotKu` harus menghasilkan kolom yang sama untuk data latih dan uji, termasuk saat data uji memuat kategori baru.

5. Gunakan kedua kelas untuk membangun matriks fitur latih dan uji (numerik: `age`, `trestbps`, `chol`, `thalach`, `oldpeak`; kategorikal: `cp`, `thal`, `sex`).

### B5 — Regresi Linear dari Nol

**10 poin | CPL-1 | CPMK-2 | Sub-CPMK-3 | 4 uji publik**

```python
def ols(X, y):             # -> (intersep, koef), memakai np.linalg.lstsq
def metrik_regresi(y, yhat):  # -> dict {'R2', 'MAE', 'RMSE'}
```

1. Tulis `ols(X, y)` yang mengembalikan `(intersep, koef)` memakai `np.linalg.lstsq`, tanpa *scikit-learn*.

2. Tulis `metrik_regresi(y, yhat)` yang mengembalikan `dict` $R^2$, MAE, dan RMSE, serta melempar `ValueError` bila panjang `y` dan `yhat` berbeda.

3. Prediksi `thalach` dari `age`, `trestbps`, `chol`, `exang`, dan `sex` (*dummy*, *drop first*) pada *split* B4 menggunakan data sebelum *scaling*.

4. Bandingkan dengan tolok ukur rata-rata dan tafsirkan koefisien `age`.

### B6 — Regresi Logistik, AUC, dan Pemilihan Ambang

**15 poin | CPL-2 | CPMK-2 | Sub-CPMK-3, Sub-CPMK-4 | 5 uji publik**

```python
def auc_peringkat(y, skor):
def lipatan_berstrata(y, k=5, seed=42):  # generator (indeks_latih, indeks_val)
def ambang_untuk_recall(y, prob, target):
```

**(a)** Tulis `auc_peringkat(y, skor)` berbasis Mann-Whitney yang menangani skor kembar, dan `lipatan_berstrata(y, k, seed)` sebagai *generator*.

**(b)** Pilih $C \in \{0.01, 0.03, 0.1, 0.3, 1, 3, 10\}$ untuk `LogisticRegression` dengan validasi silang buatan sendiri (5 lipatan, skor AUC) pada matriks fitur latih.

**(c)** Pada data latih (prediksi *out-of-fold*), tulis `ambang_untuk_recall(y, prob, target)` yang memilih ambang tertinggi dengan $\text{recall} \ge \text{target}$; gunakan target $0.90$.

**(d)** Laporkan *confusion matrix*, presisi, recall, F1, dan AUC pada data uji satu kali saja. Dalam konteks skrining penyakit jantung, metrik mana yang paling penting dan mengapa?

## C. Ketentuan Pengerjaan

* Seluruh jawaban Bagian A dan Bagian B dikerjakan dalam satu notebook Jupyter (`.ipynb`) menggunakan Python.

* Jawaban Bagian A ditulis pada sel Jawaban (markdown) di bawah setiap soal.

* Kode Bagian B ditulis pada sel Jawaban Anda, diberi komentar pada setiap langkah, dan diikuti sel Interpretasi.

* Fungsi harus murni, diberi *docstring*, memakai nama yang bermakna, dan tanpa duplikasi kode.

* Data uji tidak boleh digunakan untuk pelatihan, pemilihan hiperparameter, atau pemilihan ambang.

* Interpretasi harus merujuk pada hasil aktual dari notebook, bukan asumsi.

* Ujian dikerjakan secara individu. Bekerja sama, menyalin pekerjaan orang lain, plagiarisme, atau menggunakan joki dikenai sanksi sesuai kontrak perkuliahan.

## D. Jawaban yang Dikumpulkan

| Soal | Komponen | Bentuk Jawaban | 
| ----- | ----- | ----- | 
| **A1–A9** | Konsep pemrosesan data, pemodelan, dan pemrograman | Uraian singkat, pseudocode, rumus, dan perhitungan (A8) | 
| **B1** | Detektor masalah kualitas data | Fungsi `deteksi_masalah`, uji publik, interpretasi | 
| **B2** | Wrangling yang dapat diuji | Fungsi `seragamkan` dan `gabung_aman`, rantai method, interpretasi | 
| **B3** | Pembersih otomatis | Fungsi `pilih_imputasi` dan `bersihkan`, perbandingan Z-score vs IQR | 
| **B4** | Transformer `fit/transform` | Kelas `SkalaRobustku` dan `OneHotKu`, matriks fitur latih dan uji | 
| **B5** | Regresi linear dari nol | Fungsi `ols` dan `metrik_regresi`, perbandingan tolok ukur, tafsiran koefisien | 
| **B6** | Regresi logistik dan ambang | Fungsi AUC, lipatan, ambang; pemilihan $C$; metrik data uji | 

* **File yang dikumpulkan:** `UTS_DS2313_<NIM>.ipynb`

* Pastikan notebook telah dijalankan dengan **Restart & Run All** tanpa galat sehingga seluruh output, hasil uji, dan interpretasi tampil.

## E. Rubrik Penilaian dan Bobot CPL

| Soal | Aspek yang Dinilai | CPL | CPMK | Sub-CPMK | Uji Publik | Poin | 
| ----- | ----- | ----- | ----- | ----- | ----- | ----- | 
| **A1–A2** | Broadcasting, view, dan hash join | CPL-1 | CPMK-1 | 1 | — | 4 | 
| **A3–A5** | Mekanisme data hilang, kode hilang, kontrak fit/transform | CPL-1 | CPMK-1 | 2 | — | 6 | 
| **A6–A7** | Gradient descent, metrik regresi, stabilitas numerik | CPL-1 | CPMK-2 | 3 | — | 4 | 
| **A8** | Metrik klasifikasi dan ROC-AUC | CPL-1 | CPMK-2 | 4 | — | 2 | 
| **A9** | Konsep pemrograman | CPL-1 | CPMK-1 | 1, 2 | — | 4 | 
|  | **Subtotal Bagian A** |  |  |  |  | **20** | 
| **B1** | Detektor masalah kualitas data | CPL-2 | CPMK-1 | 2 | 9 | 10 | 
| **B2** | Wrangling dan join aman | CPL-2 | CPMK-1 | 1 | 6 | 15 | 
| **B3** | Pembersih otomatis murni dan idempoten | CPL-1 | CPMK-1 | 2 | 6 | 20 | 
| **B4** | Transformer fit/transform | CPL-2 | CPMK-1 | 2 | 6 | 10 | 
| **B5** | Regresi linear dari nol | CPL-1 | CPMK-2 | 3 | 4 | 10 | 
| **B6** | Regresi logistik, AUC, dan ambang | CPL-2 | CPMK-2 | 3, 4 | 5 | 15 | 
|  | **Subtotal Bagian B** |  |  |  |  | **80** | 
| **TOTAL** |  |  |  |  |  | **100** | 

### Rekapitulasi Bobot CPL dan CPMK

| CPL | CPMK-1 | CPMK-2 | Total | 
| ----- | ----- | ----- | ----- | 
| **CPL-1** | 34% | 16% | 50% | 
| **CPL-2** | 35% | 15% | 50% | 
| **TOTAL** | **69%** | **31%** | **100%** | 

### Aspek Penilaian Setiap Soal (RPS - Rubrik UTS/UAS)

| Aspek | Bobot | Kriteria Sangat Baik (85–100) | Cara Dinilai pada UTS Ini | 
| ----- | ----- | ----- | ----- | 
| **Kebenaran solusi dan logika pemrograman** | 35% | Solusi akurat, logika efisien, tanpa galat sintaksis | Uji publik (terlihat) dan uji tersembunyi (dijalankan dosen) pada fungsi Anda | 
| **Analisis kritis dan interpretasi data** | 35% | Interpretasi mendalam dengan argumen statistik yang logis | Sel Interpretasi setiap soal | 
| **Kerapian dan dokumentasi jawaban** | 30% | Struktur sistematis, komentar kode lengkap | Docstring, nama bermakna, fungsi murni, tanpa duplikasi | 
| **TOTAL** | **100%** |  |  | 

> $\text{Skor setiap soal} = \text{poin soal} \times (\text{skor aspek tertimbang} / 100)$. Nilai UTS = jumlah skor seluruh soal (maksimum 100) dan menjadi komponen UTS (20%) pada penilaian akhir mata kuliah.

---

## F. Panduan Prompt Pengerjaan (Workflow Terstruktur)

Bagian ini berisi kumpulan *prompt* siap pakai untuk membantu membedah, merancang, dan memverifikasi solusi setiap bagian UTS secara bertahap agar memenuhi seluruh kriteria rubrik (fungsi murni, tanpa *hardcoding*, aman dari *data leakage*, dan tahan terhadap uji tersembunyi).

### 1. System Prompt (Gunakan di Awal Sesi)

Salin dan tempel *prompt* ini terlebih dahulu sebagai konteks dasar sebelum menanyakan soal spesifik:

```text
Bertindaklah sebagai Senior Data Scientist & Python Software Engineer yang membimbing saya mengerjakan UTS Pemrograman Sains Data II (DS-2313).

Aturan ketat yang WAJIB dipatuhi dalam setiap kode yang Anda hasilkan:
1. PURE FUNCTIONS & IMMUTABILITY: Semua fungsi/kelas tidak boleh memodifikasi DataFrame/array input secara in-place (selalu gunakan .copy()).
2. NO HARDCODING: Jangan menuliskan nama kolom spesifik secara eksplisit dalam logika deteksi (kecuali 'kode_klinik' atau parameter yang memang diminta pada signature).
3. EXACT SIGNATURES: Pertahankan nama fungsi, kelas, parameter, tipe kembalian, dan konvensi atribut berakhiran '_' (fitted attributes) persis seperti yang diminta soal.
4. EDGE-CASE RESILIENT: Pastikan kode tahan terhadap uji tersembunyi seperti DataFrame kosong, kolom yang hilang, pembagian dengan nol (IQR=0 atau std=0), dan kategori baru pada data uji.
5. DOCUMENTATION: Sertakan docstring berstandar NumPy/Google dan komentar singkat pada langkah-langkah logika penting.
6. DATA LEAKAGE PREVENTION: Jangan pernah menyentuh data uji (test set) selama proses fit, pemilihan hiperparameter, maupun penentuan ambang batas (threshold).
```

### 2. Prompt Bagian A — Konsep (A1–A9)

```text
Bantu saya menyusun kerangka jawaban untuk soal Bagian A (A1 sampai A9) UTS DS-2313 berikut:
[Tempel teks soal A1–A9 di sini]

Ketentuan format jawaban:
- Gunakan bahasa Indonesia akademis yang ringkas, padat, dan langsung menjawab inti pertanyaan.
- Tuliskan pseudocode yang terstruktur dan mudah dibaca untuk soal A1, A3, dan A6.
- Untuk A7, tampilkan derivasi matematis singkat untuk versi stabil sigmoid (menggunakan np.where untuk z >= 0 dan z < 0) dan log-loss (menggunakan np.clip atau log-sum-exp).
- Untuk A8, tampilkan langkah perhitungan manual yang jelas dari nilai TN=90, FP=10, FN=30, TP=70 beserta penjelasan kompleksitas O(n log n) pada perhitungan ROC-AUC berbasis pengurutan peringkat.
- Untuk A9, berikan contoh kode Python singkat dan idiomatik untuk custom exception DataTidakValid dan closure evaluasi model.
```

### 3. Prompt Bagian B — Praktikum Pemrograman (Per Soal)

#### Prompt B1: Detektor Masalah Kualitas Data (`deteksi_masalah`)
```text
Kerjakan soal B1: tulis fungsi `deteksi_masalah(df, ref_klinik)` yang mengembalikan DataFrame dengan kolom `['jenis', 'kolom', 'jumlah', 'contoh']`.

Pastikan logika deteksi bersifat generik (tanpa hardcode nama kolom, kecuali 'kode_klinik') untuk mendeteksi 7 jenis anomali berikut:
1. `ANGKA_SEBAGAI_TEKS`: kolom object/string yang mayoritas/sebagian nilainya mengandung pola angka diikuti satuan teks (contoh: '63th').
2. `KATEGORI_TIDAK_KONSISTEN`: kolom kategorikal/teks ber-kardinalitas rendah yang memiliki variasi penulisan karena huruf kapital, spasi berlebih, atau singkatan huruf awal (misal 'L' vs 'Laki-laki', ' perempuan ' vs 'Perempuan').
3. `NOL_MUSTAHIL`: kolom numerik kontinu (bukan biner/diskrit kecil) yang memiliki nilai 0 di ujung bawah dengan lonjakan frekuensi signifikan dibanding tetangganya, serta jarak antara 0 dan nilai terkecil positif berikutnya > 0.5 * IQR (sehingga 'chol' terdeteksi, namun 'oldpeak' yang nol-nya menyatu dengan sebaran tidak terdeteksi).
4. `HILANG`: jumlah nilai NaN per kolom.
5. `NILAI_EKSTREM`: nilai numerik di atas Q3 + 10 * IQR.
6. `DUPLIKAT`: baris duplikat ketika kolom pengenal (ID unik per baris) diabaikan.
7. `KUNCI_YATIM`: nilai 'kode_klinik' pada `df` yang tidak ada di `ref_klinik['kode_klinik']`.

Sertakan juga pengujian kasus tepi (df kosong, tidak ada anomali) dan draf sel Interpretasi berdasarkan output aktual dataset `hd`.
```

#### Prompt B2: Wrangling yang Dapat Diuji (`seragamkan` & `gabung_aman`)
```text
Kerjakan soal B2 secara lengkap dan terpisah menjadi 3 bagian:
1. `seragamkan(df)`: Fungsi murni yang mengubah kolom `age` menjadi numerik (float/int) dengan menghapus satuan teks menggunakan regex, serta menyeragamkan kolom `sex` menjadi tepat `{'Laki-laki', 'Perempuan'}` dengan membangun peta otomatis dari daftar nilai kanonik `['Laki-laki', 'Perempuan']` berdasarkan pencocokan huruf awal (case-insensitive setelah strip), bukan kamus ganti manual.
2. `gabung_aman(kiri, kanan, kunci)`: Fungsi murni yang memvalidasi relasi many-to-one (melempar `ValueError` jika `kanan[kunci]` memiliki duplikat), mencetak daftar kunci yatim yang tidak ditemukan di tabel kanan, melakukan left join, dan memverifikasi dengan `assert` bahwa jumlah baris hasil sama persis dengan `len(kiri)`.
3. Rantai Method (Method Chaining): Tuliskan satu rantai method Pandas yang menggabungkan `hd` yang sudah diseragamkan dengan `klinik`, memfilter `chol` valid pada rentang 100-700, lalu menampilkan rata-rata `chol` dan persentase `target == 1` yang dikelompokkan berdasarkan `kota` dan `sex`.
4. Buat template sel Interpretasi untuk menjelaskan temuan dari tabel agregasi tersebut.
```

#### Prompt B3: Pembersih Otomatis (`pilih_imputasi` & `bersihkan`)
```text
Kerjakan soal B3:
1. `pilih_imputasi(df, kolom, kelompok='sex', proporsi=0.2, ulang=5, seed=42)`: Lakukan eksperimen masking (penyamaran) berulang sebanyak `ulang` kali pada nilai valid `df[kolom]` dengan menutupi `proporsi` data secara acak (gunakan `np.random.default_rng(seed)`). Bandingkan galat (MAE atau RMSE) antara imputasi `'median'` global vs `'median_kelompok'` berdasarkan `kelompok`, lalu kembalikan string metode dengan galat rata-rata terkecil. Tangani juga kasus tepi jika seluruh kelompok bernilai NaN.
2. `bersihkan(df)`: Fungsi murni dan idempoten (memanggil `bersihkan(bersihkan(df))` menghasilkan output identik) yang menjalankan pipeline:
   (a) memanggil `seragamkan(df)`,
   (b) menghapus duplikat dengan mengabaikan `id_pasien`,
   (c) memanggil `deteksi_masalah` untuk menemukan kolom dengan `NOL_MUSTAHIL` secara dinamis dan mengubah nilai 0 tersebut menjadi `np.nan`,
   (d) mengubah `NILAI_EKSTREM` (> Q3 + 10 * IQR) menjadi `np.nan`,
   (e) mengimputasi seluruh kolom numerik yang memiliki NaN menggunakan metode terpilih dari `pilih_imputasi`,
   (f) menutup fungsi dengan `assert` validasi (tidak ada lagi NaN pada fitur numerik, tidak ada duplikat, kategori `sex` valid).
3. Tuliskan kode pembanding deteksi outlier menggunakan metode Z-score (|z| > 3) dan IQR (1.5 * IQR) pada kolom `chol` dan `trestbps` setelah dibersihkan, serta jelaskan perbedaannya pada sel Interpretasi.
```

#### Prompt B4: Transformer Kustom (`SkalaRobustku` & `OneHotKu`)
```text
Kerjakan soal B4:
1. Bagi data bersih dari B3 menjadi data latih (75%) dan data uji (25%) menggunakan `train_test_split` dengan `stratify=y` dan `random_state=42`.
2. Implementasikan kelas `SkalaRobustku(kolom)`:
   - `fit(self, X, y=None)`: menghitung median (`median_`) dan rentang interkuartil (`iqr_`) untuk setiap kolom pada `kolom`, tangani kasus jika `iqr_ == 0` agar tidak terjadi pembagian dengan nol, lalu kembalikan `self`.
   - `transform(self, X)`: lempar `RuntimeError` jika atribut `median_` / `iqr_` belum ada; kembalikan salinan DataFrame baru dengan kolom numerik yang telah diskalakan `(x - median) / iqr`.
3. Implementasikan kelas `OneHotKu(kolom)`:
   - `fit(self, X, y=None)`: menyimpan daftar kategori unik terurut per kolom pada atribut `kategori_`, lalu kembalikan `self`.
   - `transform(self, X)`: lempar `RuntimeError` jika belum di-fit; hasilkan DataFrame baru dengan kolom biner (0/1) yang urutan dan namanya identik dengan hasil `fit` (abaikan kategori baru yang muncul di data uji tanpa error).
4. Terapkan kedua transformer pada fitur numerik `['age', 'trestbps', 'chol', 'thalach', 'oldpeak']` dan fitur kategorikal `['cp', 'thal', 'sex']` untuk membentuk `X_train_proc` dan `X_test_proc`.
```

#### Prompt B5: Regresi Linear dari Nol (`ols` & `metrik_regresi`)
```text
Kerjakan soal B5 tanpa menggunakan scikit-learn untuk model maupun metriknya:
1. `ols(X, y)`: Tambahkan kolom konstanta (angka 1) untuk intersep pada matriks fitur `X`, hitung parameter menggunakan `np.linalg.lstsq(X_aug, y, rcond=None)`, dan kembalikan tuple `(intersep, koef)`.
2. `metrik_regresi(y, yhat)`: Validasi panjang array (lempar `ValueError` jika `len(y) != len(yhat)` atau kosong), hitung R2, MAE, dan RMSE dari nol menggunakan NumPy, lalu kembalikan dictionary `{'R2': ..., 'MAE': ..., 'RMSE': ...}`.
3. Gunakan data latih dan uji dari split B4 (sebelum scaling) untuk memprediksi `thalach` dari fitur `['age', 'trestbps', 'chol', 'exang']` ditambah variabel dummy `sex` (drop_first=True).
4. Bandingkan metrik prediksi model pada data uji terhadap baseline prediksi rata-rata `y_train`, serta berikan interpretasi nilai dan arah koefisien `age` dalam konteks fisiologis.
```

#### Prompt B6: Regresi Logistik, AUC, dan Pemilihan Ambang
```text
Kerjakan soal B6:
1. `auc_peringkat(y, skor)`: Implementasikan perhitungan ROC-AUC berbasis statistik uji Mann-Whitney U menggunakan peringkat rata-rata (`scipy.stats.rankdata` atau implementasi manual tie-handling) untuk menangani skor kembar secara akurat tanpa kurva ROC.
2. `lipatan_berstrata(y, k=5, seed=42)`: Buat fungsi generator yang menghasilkan pasangan `(indeks_latih, indeks_val)` sebanyak `k` lipatan dengan menjaga proporsi kelas `y` tetap seimbang di setiap lipatan (gunakan `np.random.default_rng(seed)`).
3. Lakukan validasi silang 5-lipatan buatan sendiri pada data latih B4 untuk memilih nilai `C` terbaik dari `{0.01, 0.03, 0.1, 0.3, 1, 3, 10}` pada `LogisticRegression(max_iter=1000, random_state=42)` berdasarkan skor rata-rata `auc_peringkat`, sekaligus kumpulkan prediksi probabilitas out-of-fold (OOF) untuk `C` terbaik.
4. `ambang_untuk_recall(y, prob, target)`: Dari probabilitas OOF data latih, cari nilai ambang batas (threshold) tertinggi yang menghasilkan `recall >= target` (gunakan `target=0.90`).
5. Latih ulang model final menggunakan seluruh data latih dengan `C` terbaik, lalu evaluasi SATU KALI SAJA pada data uji menggunakan ambang terpilih dari langkah 4. Tampilkan confusion matrix, presisi, recall, F1, dan AUC, lalu tulis interpretasi mendalam mengenai metrik terpenting dalam kasus skrining penyakit jantung.
```

### 4. Prompt Audit Akhir Sebelum Pengumpulan (Checklist)

Gunakan *prompt* ini untuk memeriksa kembali seluruh notebook sebelum menekan **Restart & Run All**:

```text
Tinjau seluruh kode saya dari B1 hingga B6 terhadap daftar pemeriksaan berikut:
1. Apakah ada fungsi yang mengubah DataFrame input `HD_ASLI` atau `X_train` secara tidak sengaja?
2. Apakah semua fungsi/kelas memiliki docstring dan penamaan parameter yang persis sama dengan soal?
3. Apakah ada kebocoran data (data leakage) dari `X_test` atau `y_test` ke proses imputasi, scaling, one-hot encoding, pemilihan C, atau pemilihan threshold?
4. Apakah semua kasus tepi (DataFrame kosong, IQR = 0, kategori asing di data uji, panjang array berbeda) sudah ditangani dengan exception yang sesuai (`ValueError`, `RuntimeError`)?
5. Buatkan poin-poin skrip presentasi 10 menit (maksimal 8-10 slide/bagian) yang merangkum alur kerja, temuan anomali data, eksperimen imputasi, dan hasil evaluasi model untuk video YouTube.
```