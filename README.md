# MODUL-EKONOMETRIKA-DAN-APLIKASI-DALAM-R-STUDIO


# Bab 1: Pendahuluan

------------------------------------------------------------------------

## DEFINISI DAN RUANG LINGKUP EKONOMETRIKA

Ekonometrika pada dasarnya adalah cabang ilmu ekonomi yang memiliki
keterkaitan dengan ilmu matematika dan statistika yang digunakan sebagai tolak ukur parameter hubungan ekonomi yang selaras dengan teori ekonomi
itu sendiri.Dalam konseptualnya, ekonometrika juga dapat digunakan
sebagai estimasi dari suatu fenomena ekonomi yang didasarkan pada
parameter-parameter statistik untuk kemudian diprediksi pada periode
selanjutnya. Reza Mubarak dalam bukunya yang berjudul "Pengantar
Ekonometrika" juga menjelaskan beberapa definisi ekonometrika yang
dikemukakan oleh apra ahli, yakni antara lain sebagai berikut. - Menurut
Damodar N. Gujarati ekonometrika adalah penerapan ilmu yang didasarkan
pada teori ekonomi, matematika, dan statistika guna memberikan dukungan
empiris pada model yang telah dibangun serta memberikan hasil pada suatu
angka. - Menurut Hill, Griffith dan Judge, 2001 ekonometrika adalah cara
dari setiap individu untuk menggunakan data dan teori dari ilmu ekonomi,
bisnis dan ilmu ilmu sosial, bersama-sama dengan alat statistika untuk
menjawab pertanyaan "seberapa besar". Kata ini merujuk pada kemampuan
individu untuk dapat memprediksi dan menyimpulkan variabel mana yang
sekiranya dapat memberikan pengaruh terhadap variabel lain.

Ekonometrika berdasarkan suku katanya terbagi menjadi dua, yakni
ekonomi(economics) dan pengukuran(metric). Untuk itu, apabila kedua suku
kata ini digabungkan maka akan menghasilkan suatu makna yang
menginterpretasikan bahwa ilmu ekonometrika adalah disiplin ilmu yang
yang juga digunakan dalam alat ukur ekonomi. Terdapat satu teori ekonomi
yang cukup dikenal yakni mengenai teori hukum permintaan, yang
menjelaskan bahwa terdapat hubungan yang negatif antara harga dan
kuantitas yang diminta, faktor-faktor lain tetap (ceteris paribus). Jika
harga naik maka jumlah barang yang diminta akan turun dan sebaliknya
jika harga turun jumlah barang yang diminta akan naik. Dari teori
inilah, cabang ilmu ekonometrika akan memvisualisasikannya ke dalam
suatu model persamaan yang kemudian diuji dan dihasilkan kesimpulan atau
interpretasinya berdasarkan statistik uji.

Sejalan dengan landasan konseptualnya, ekonometrika merupakan bagian
dari ilmu multidisiplin yang menggabungkan teori ekonomi, matematika,
dan statistika di dalamnya. Untuk itu, berikut beberapa peranan dari
ketiga teori tersebut, yakni sebagai berikut. 1. Teori Ekonomi : Ekonomi
sendiri berperan dalam pembuatan hipotesis berupa pernyataan yang secara
umum sifatnya kualitatif dalam relasi antar variabel ekonominya. Sebagai
gambaran yakni pada tingkat inflasi dengan suku bunga yang menyatakan
bahwa ketika suku bunga suatu bank sentral mengalami peningkatan, maka
tingkat inflasi akan cenderung menurun. Hal tersebut dapat terjadi
karena kenaikan suku bunga secara tidak langsung akan membuat biaya
pinjaman semakin mahal atau naik, sehingga dapat mengurangi belanja
konsumen ataupun investasi bisnis yang pada akhirnya membuat
individu/perusahaan tidak melakukan inflasi secara besar-besaran. 2.
Teori Matematika : Dalam hal ini, teori matematika diaplikasikan dalam
suatu pembentukan persamaan model matematis tanpa verifikasi teori
secara empiris. Misalnya pada fungsi produksi yang dimodelkan sebagai
berikut. 
$
Y = \beta_0 + \beta_1 X_1 + \beta_2 X_2
$

Di mana: - $Y$ adalah output suatu proses produksi, - $X_1$ adalah input
modal, - $X_2$ adalah input tenaga kerja, - $\beta_0$ adalah
intercept, - $\beta_1$ dan $\beta_2$ adalah koefisien untuk
masing-masing input $X_1$ dan $X_2$. 3. Teori Statistika : statistika
memiliki peranan yang cukup luas dalam tahap pengumpulan data empiris,
transformasi model matematika menjadi model ekonometrika, pengolahan
data, ataupun estimasi parameter regresi dengan melakukan uji hipotesis
dan ketepatan pembuatan model. ---

## MODEL EKONOMETRIKA

Abdul Aziz dalam bukunya yang berjudul "Ekonometrika" menjelaskan bahwa
model ekonomi matematis yang tidak mengindahkan kehadiran variabel
disturbansi bersifat deterministis, sedangkan model ekonometrika yang
memasukkan variabel disturbansi kedalamnya bersifat stokastis.Terdapat
pula 4 bentuk hubungan yang berkaitan dengan pembuatan model dalam
ekonometrika, yakni sebagai berikut. 1. Hubungan berbentuk definisi atau
identitas yang tidak memerlukan pembuktian lebih lanjut atas
kehadirannya, misalnya R = P Q atau pendapatan penjualan (R) sama dengan
jumlah barang yang dijual (Q) dikal;ikan dengan harga penjualan perunit
(P ). Dengan kata lain, hubungan ini dianggap sebagai fakta yang sudah
jelas dan tidak lagi dipertanyakan. Misalnya, dalam ekonomi, kita
mengenal rumus untuk pendapatan (Revenue), yang dihitung dengan
mengalikan jumlah barang yang dijual (Q) dengan harga per unit barang
(P). Jadi, R (pendapatan) didefinisikan sebagai hasil perkalian P (harga
per unit) dan Q (jumlah barang yang dijual). Hubungan ini sangat
sederhana dan langsung karena hanya menunjukkan hubungan yang mendasar
antara dua variabel tanpa melibatkan variabel lain yang lebih kompleks.
2. Hubungan yang berkaitan dengan teknologi seperti Q = f (K, L) atau
keluaran yang dihasilkaan (Q) sebagai fungsi dari Kapital (K) dan tenaga
kerja (L). Dengan kata lain, hubungan ini berkaitan dengan konsep fungsi
produksi yang menggambarkan bagaimana suatu output dihasilkan dari
kombinasi faktor-faktor produksi (misalnya modal dan tenaga kerja).
Hubungan ini sering kali merupakan sebuah fungsi teknis yang menjelaskan
bagaimana input (seperti modal dan tenaga kerja) berinteraksi untuk
menghasilkan output. Misalnya, fungsi produksi dalam ekonomi dapat
digambarkan sebagai Q = f(K, L), yang menunjukkan bahwa output (Q)
dihasilkan dari kombinasi kapital (K) dan tenaga kerja (L). Fungsi ini
menunjukkan hubungan antara faktor-faktor input yang digunakan dalam
proses produksi untuk menghasilkan suatu barang atau jasa. Sebagai
contoh, dalam pabrik pembuatan mobil, K bisa mewakili jumlah mesin dan
peralatan produksi, sementara L mewakili jumlah pekerja yang terlibat.
Kombinasi kedua input ini menghasilkan Q, yaitu jumlah mobil yang dapat
diproduksi. Semakin baik teknologi atau semakin efisien penggunaan modal
dan tenaga kerja, maka Q bisa meningkat. 3. Hubungan kelembagaan seperti
jumlah penerimaan pajak penjualan sama dengan volume penjualan dikalikan
tarif pajak penjualan per unit yang ditetapkan oleh lembaga pemerintah.
4. Hubungan perilaku yang memperlihatkan respon sebuah variabel terhadap
perubahan variabel ekonomi lainnya, misalnya C = f (Y ) atau pengeluaran
konsumsi sebagai fungsi dari pendapatan disposebel. Fungsi C = f(Y)
berarti bahwa pengeluaran konsumsi (C) adalah fungsi dari pendapatan
disposebel (Y). Pendapatan disposebel adalah pendapatan setelah
dikurangi pajak dan potongan lainnya yang bisa digunakan oleh individu
atau rumah tangga untuk membeli barang dan jasa. C (pengeluaran
konsumsi): Merupakan jumlah uang yang dikeluarkan oleh rumah tangga
untuk membeli barang dan jasa. Y (pendapatan disposebel): Merupakan
jumlah pendapatan yang dapat digunakan oleh rumah tangga setelah
dikurangi pajak dan kewajiban lainnya. Fungsi ini menunjukkan bagaimana
pengeluaran konsumsi dipengaruhi oleh besarnya pendapatan yang tersedia
untuk dibelanjakan. Semakin besar pendapatan disposebel, biasanya
semakin tinggi pengeluaran konsumsi. ---

## METODOLOGI EKONOMETRIKA

Pada dasarnya, aliran utama metodologi ekonometrika dipelopori oleh
Hendry dan Richard yang sifatnya adalah top down atau general to
specific. Sejalan dengan teorinya, metodologi ekonometrika sendiri
diawali dengan pernyataan teori atau hipotesis.Langkah berikutnya adalah
dengan membuat spesifikasi model dan melakukan estimasi model yang kita
bangun.Sebaiknya, setelah estimasi model diperlukan langkah lebih lanjut
yang meliputi uji spesifikasi model dan diagnosis (modeling) terlebih
dahulu. Langkah ini diperlukan untuk membuktikan apakah model yang kita
bangun sudah tepat atau tidak bias lagi. Jika model sudah tepat maka
kita bisa membuat generalisasi melalui uji statistik. Selanjutnya hasil
estimasi tersebut dapat digunakan untuk melakukan prediksi atau
peramalan. Tetapi, apabila model yang ada belum tepat maka kita harus
meninjau kembali spesifikasi model yang kita bangun. Pembentukan model
harus kita lakukan kembali pada langkah kedua. Adapun gambaran alur dari
metodologinya yakni sebagai berikut.

```{r, echo=TRUE}
library(DiagrammeR)

grViz("
digraph metodologi_ekonometrika {
  graph [layout = dot, rankdir = TB]
  
  node [shape = rectangle, style = filled, fillcolor = white, color = black]
  A [label = 'Pernyataan Teori/Hipotesis']
  B [label = 'Spesifikasi model']
  C [label = 'Data']
  D [label = 'Estimasi model dan Uji Hipotesis']
  E [label = 'Prediksi']
  F [label = 'Tidak']
  G [label = 'Ya']

  edge [color = black, arrowhead = normal]
  A -> B
  B -> D
  C -> B
  D -> E [label = 'Ya']
  D -> F [label = 'Tidak']
}
")

```

------------------------------------------------------------------------

# Bab 2 : MODEL STATISTIK PADA EKONOMETRIKA

------------------------------------------------------------------------

## ESTIMASI MODEL EKONOMETRIKA

### Ordinary Least Squares (OLS)

Metode Ordinary Least Squares ini merupakan model estimasi yang
ditujukan untuk mendapatkan estimator regresi (koefisien regresi) yang
tidak bias (unbiased) dan efisien (efficient). Dalam suatu model
statistik linier yakni
$
y = \beta_1 X_1 + \beta_2 X_2 + \dots + \beta_k X_k + \epsilon
$ 
Variabel e sangat memegang peran dalam model ekonometrika, tetapi
variabel ini tidak dapat diteliti dan tidak pula tersedia informasi
tentang bentuk distribusi kemungkinannya. Disamping asumsi mengenai
distribusi probabilitasnya, beberapa asumsi lainnya khususnya tentang
sifat statistiknya perlu dibuat dalam menerapkan metode OLS. Beberapa
asumsi mengenai variabel $e$ yang dikemukakan oleh Gauss, yakni sebagai
berikut. 1. Nilai rata-rata atau harapan variabel e adalah sama dengan
nol. Atau dalam bentuk suatu persamaan yakni $E(e) = 0$. Hal ini
mengartikan bahwa error memiliki harapan nol berarti bahwa kesalahan
rata-rata antara model dan data yang diamati adalah nol.Jika eror
memiliki rata-rata sama dengan nol, maka rata-rata nilai yang diestimasi
oleh model akan sesuai dengan nilai sebenarnya.Dengan syarat ini juga
menjadikan hubungan antara variabel independen (X) dan variabel dependen
(Y) yang diprediksi oleh model adalah benar dan tidak dipengaruhi oleh
bias. 2. Tidak terdapat autokorelasi antar variabel untuk setiap
observasi. Dengan kata lain dapat dituliskan dalam persamaan yakni
sebagai berikut. Persamaan berikut menunjukkan varians:

$
Var(e_i, e_j) = 
\begin{cases} 
\sigma^2, & \text{jika } i = j \\
0, & \text{jika } i \neq j
\end{cases}
$

Hal ini mengartikan bahwa kesalahan pada pengamatan satu tidak boleh
dipengaruhi oleh kesalahan pada pengamatan sebelumnya atau
sesudahnya.Jika autokorelasi terjadi, maka estimasi koefisien regresi
akan menjadi tidak akurat, sehingga model regresi linier tidak dapat
menghasilkan prediksi yang tepat dan dapat mempengaruhi kesimpulan yang
ditarik dari model tersebut. 3. Variabel x dan variabel e adalah saling
tidak tergantung untuk setiap observasi sehingga 
$Cov(x_i, e_i) = E\left[(x_i - E(x_i))(e_i - E(e_i))\right]$
$= E\left[(x_i - \bar{x})(e_i - 0)\right]$
$= E\left[(x_i - \bar{x}) e_i\right]$
$= (x_i - \bar{x}) E(e_i)$
$= 0$ 
Dimisalkan bahwa sampel untuk y diberikan, maka untuk mendapatkan
taksiran $\beta$ dapat dibuat dengan persamaan $e = y − Xβ$. Hasil yang
diharapkan adalah akan menghasilkan komponen sistematik yang lebih
berperan dari pada komponen stokastiknya. Karena bila komponen stokastik
yang lebih berperan artinya hanya diperoleh sedikit informasi tentang y.
Dengan kata lain, X tidak mampu menjelaskan y.Pada akhirnya mendapatkan
persamaan yakni 
$
\hat{\beta} = (X^T X)^{-1} X^T y
$ 
yang dinamakan sebagai penaksir (estimator) parameter β secara
kuadrat terkecil (Ordinary Least Square, OLS).

------------------------------------------------------------------------

## KORELASI DAN REGRESI

### Analisis Korelasi

Pada dasarnya analisis korelasi bertujuan untuk mengukur tingkat
keeratan hubungan linier yang terjadi antar dua variabel. Tingkat
keeratan tersebut dapat diukur oleh koefisien korelasi yang rumusnya
adalah sebagai berikut. 
$
r_{xy} = \frac{\sum_{i=1}^n (x_i - \bar{x})(y_i - \bar{y})}
{\sqrt{\sum_{i=1}^n (x_i - \bar{x})^2} \sqrt{\sum_{i=1}^n (y_i - \bar{y})^2}} 
\quad ; \quad -1 \leq r_{xy} \leq 1
$

Bentuk lain dari rumus:

$
r_{xy} = \frac{\sum_{i=1}^n x_i y_i - n\bar{x}\bar{y}}
{\sqrt{\sum_{i=1}^n x_i^2 - n\bar{x}^2} \sqrt{\sum_{i=1}^n y_i^2 - n\bar{y}^2}}
$ 
Adapun klasifikasi dari nilai koefisien korelasi yakni sebagai
berikut. 1. Jika nilai r semakin mendekati -- 1, maka kedua variabel
cenderung semakin berhubungan negatif. Hal ini berarti jika nilai X
semakin naik, maka nilai Y semakin turun. Begitu juga sebaliknya, jika
nilai X semakin turun, maka nilai Y semakin naik. 2. Jika nilai r
semakin mendekati 1, maka kedua variabel cenderung semakin berhubungan
positif. Hal ini berarti jika nilai X semakin naik, maka nilai Y juga
semakin naik. Begitu juga sebaliknya, jika nilai X semakin turun, maka
nilai Y juga semakin turun. 3. Jika nilai r semakin mendekati 0, maka
kedua variabel cenderung semakin tidak memiliki hubungan. Dengan kata
lain, dapat diartikan juga bahwa tanda positif (+) pada koefisien
korelasi mengartikan adanya hubungan yang searah yang positif sehingga
ketika nilai x naik, maka nilai y pun juga ikut naik. Dan sebaliknya
tanda (-) pada koefisien korelasi mengartikan bahwa adanya hubungan
negatif terbalik yang membuat ketika nilai x mengalami kenaikan maka
nilai y mengalami penurunan.

### Regresi 

Pada dasarnya Analisis regresi merupakan suatu bentuk hubungan dari suatu pengaruh variabel independen terhadap variabel dependennya.Berdasarkan jenisnya, analisis regresi dibedakan menjadi 2 yakni regresi sederhana yang hanya melibatkan 1 variabel independen dan regresi berganda yang melibatkan dua atau lebih variabel independen. Berikut penjabaran dari masing-masing jenis regresinya.

#### Regresi Sederhana

Regresi sederhana merupakan analisis statistik yang menggambarkan
hubungan antara satu variabel dependen (atau terikat) dengan satu
variabel independen (atau bebas) menggunakan persamaan linier.Adapun
model persamaan dari regresi sederhana ini adalah sebagai berikut. 
$
Y = \beta_0 + \beta_1 X + \epsilon
$ 
Di mana: - 
$Y$ adalah variabel dependen (yang ingin diprediksi), -
$X$ adalah variabel independen (yang digunakan untuk memprediksi $Y$), -
$\beta_0$ adalah **intercept** atau konstanta (nilai $Y$ ketika
$X = 0$), - 
$\beta_1$ adalah **koefisien regresi** atau slope (mengukur
perubahan pada $Y$ untuk setiap perubahan satu unit pada $X$), -
$\epsilon$ adalah **error term** atau gangguan (perbedaan antara nilai
yang diamati dan yang diprediksi oleh model).

$\beta_0$ dan $\beta_1$ berperan sebagai parameter populasi. Selain itu,
persamaan regresi yang dihitung dengan menggunakan metode kuadrat
terkecil dapat memenuhi sifat sebagai berikut. 
1. Jumlah residual sama
dengan nol. Apabila dituliskan dalam persamaan matematis yakni sebagai
berikut. 
$\sum_{i=1}^n e_i =0$
dengan pembuktian, yakni $\sum_{i=1}^n e_i = \sum_{i=1}^n \left( Y_i - b_0 - b_1 X_i \right)
= \sum_{i=1}^n Y_i - n b_0 - b_1 \sum_{i=1}^n X_i = 0 \quad \text{(dari persamaan normal)}$ 
3. Jumlah kuadrat residual adalah minimum. 
4. Jumlah nilai observasi
---

#### Regresi Berganda

Regresi linier berganda adalah analisis statistik yang mengukur hubungan
antar dua atau lebih variabel independen terhadap variabel
dependennya.Menurut Sugiyono (2012: 275), analisis regresi berganda
digunakan oleh peneliti, bila peneliti bermaksud meramalkan keadaan
(naik turunnya) variabel dependen (kriterium), bila dua atau lebih
variabel independen sebagai faktor prediktor dimanipulasi (naik
turunnya). Dalam hal ini, ada tiga variable bebas dan satu variable
terikat. Persamaan model regresi bergandanya yakni sebagai berikut.
$𝑌=𝑎+𝑏1𝑋1+𝑏2𝑋2+⋯+𝑏𝑛𝑋𝑛$ ---

## Koefisien Determinasi

Koefisien determinasi dalam konsep regresi diartikan sebagai ukuran
kebaikan model untuk mengetahui sejauh mana variabel independen mampu
menjelaskan variasi pada variabel dependennya. Semakin besar nilai $R^2$
(mendekati 1), maka model dikatakan semain baik. Adapun rumus dari
koefisien determinasi yakni sebagai berikut. 
$R^2 = 1 - \frac{\text{SSE}}{\text{SST}}$ 
Di mana: - $\text{SSE} = \sum (Y_i - \hat{Y}_i)^2$: **Sum of Squared
Errors** (selisih kuadrat antara nilai aktual dan prediksi), -
$\text{SST} = \sum (Y_i - \bar{Y})^2$: **Total Sum of Squares** (variasi
total dalam $Y$). Nilai apda koefisien determinasi sendiri berkisar dari
0 hingga 1. Jika koefisien determinasi berada tepat pada angka 0
menunjukkan bahwa tidak ada pengaruh dari variabel independen terhadap
variasi variabel dependennya yang mengartikan model tidak cukup baik
untuk menggambarkan hubungan antar variabel. Sementara jika koefisien
berada tepat angka 1 maka variabel independen dinyatakan baik dalam
memengaruhi variasi variabel dependennya.

---

## Uji Hipotesis 

### Uji F (Serentak)
Uji F merupakan uji hipotesis serentak yang ditujukan untuk melihat pengaruh variabel bebas (independen) secara bersama-sama terhadap variabel terikatnya. Tingakatan yang digunakan adalah sebesar 0.5 atau 5%, jika nilai signifikan F < 0.05 maka dapat diartikan bahwa variabel independent secara simultan mempengaruhi variabel dependen ataupun sebaliknya (Ghozali, 2016). Uji simultan F (Uji Simultan) digunakan untuk mengetahui ada atau tidaknya pengaruh secara bersama – sama atau simultan antara variabel independen terhadap variabel dependen. Adapun pengambilan kesimpulan dalam uji F ini yakni sebagai berikut. 
1. Jika nilai signifikan F < 0,05 maka H0 ditolak dan H1 diterima. Artinya semua variabel independent/bebas memiliki pengaruh secara signifikan terhadap variabel dependen/terikat.
2. Jika nilai signifikan F > 0,05 maka H0 diterima dan H1 Artinya, semua variabel independent/bebas tidak memiliki pengaruh secara signifikan terhadap variabel dependen/terikat.
Dan hipotesis dalam uji ini yakni sebagai berikut. 
$H0: β1=β2=…=βp = 0$
$H1: minimal terdapat satu βj ≠ 0, j= 1,2,3,…,p$
p merupakan jumlah parameter yang terdapat di dalam model regresi. Jika dalam tabel ANOVA, maka terdapat beberapa rumus yang diperlukan untuk melengkapi ANOVA yakni sebagai berikut. 
1. Derajat bebas Regresi : p
2. Derajat Bebas Residual : $n-(p+1)$
3. Derajat Bebas Total : $n-1$
4. Jumlah Kuadrat Regresi : $\text{SSR} = \sum (\hat{Y}_i - \bar{Y})^2$
5. Jumlah Kuadrat Residual : $\text{SSE} = \sum (Y_i - \hat{Y}_i)^2$
6. Jumlah Kuadrat Total : $\text{SST} = \sum (Y_i - \bar{Y})^2$
7. Kuadrat Tengah Regresi : \( \text{MSR} = \frac{\text{SSR}}{p} \)
8. Kuadrat Tengah Residual : \( \text{MSE} = \frac{\text{SSE}}{n - p - 1} \)
9. F hitung : \( \text{Fhitung} = \frac{\text{MSR}}{MSE} \)

---

### Uji T
Uji T pada regresi bertujuan untuk menguji apakah nilai koefisien regresi mempunyaipengaruh yang signifikan. Uji t dilakukan untuk menguji hipotesis penelitian mengenai pengaruh dari masing-masing variabel bebas secara parsial terhadap variabel terikat. Pengambilan keputusan dilakukan dengan melihat nilai signifikansi pada tabel Coefficients. Biasanya dasar pengujian hasil regresi dilakukan dengan tingkat kepercayaan sebesar 95% atau dengan taraf signifikannya sebesar 5% (α = 0,05). Adapun kriteria dari uji statistik t (Ghozali, 2016) yakni sebagai berikut. 
1. Jika nilai signifikansi uji t > 0,05 maka H₀ diterima dan Ha ditolak. Artinya tidak ada pengaruh antara variabel independen terhadap variaben dependen.
2. Jika nilai signifikansi uji t < 0,05 maka H₀ ditolak dan Ha diterima. Artinya terdapat pengaruh antara variabel independen terhadap variabel dependen.
Adapun hipotesis pengujiannya yakni sebagai berikut. 
$ H0 : βi = 0$
$H1 : βi ≠ 0, i = 1, 2, …, p$
Adapun statistik uji yang digunakan yakni sebagai berikut. 
$t_{hit} = \frac{r \cdot \sqrt{n - 2}}{\sqrt{1 - r^2}}$
dengan keterangan , 
- \( r \): Koefisien korelasi.
- \( n \): Ukuran sampel.
- \( t_{hit} \): Nilai statistik \( t \).
---

# Bab 3 : ASUMSI MODEL KLASIK

## HETEROSKEDASTISITAS 

### PENGERTIAN HETEROSKEDASTISITAS 

Didalam Uji  heteroskedastisitas bermanfaat untuk  melihat  apakah  terdapat ketidaksamaan varians dari residual  satu  ke  pengamatan ke pengamatan  yang  lain.  Model  regresi  yang  memenuhi persyaratan  adalah  di  mana  terdapat  kesamaan  varians  dari  residual  satu  pengamatan  kepengamatan yang lain tetap atau bisa disebut homoskedastisitas. Deteksi heteroskedastisitas dapat dilakukan dengan metode scatter plot dengan memplotkan nilai ZPRED  (nilai  prediksi)  dengan  SRESID  (nilai  residualnya).  Model  yang  baik  didapatkan  jika tidak  terdapat  pola  tertentu  pada  grafik,  seperti  mengumpul di  tengah,  menyempit  kemudian melebar  atau  sebaliknya  melebar  kemudian  menyempit.  

  Homoskedastisitas sendiri memiliki arti bahwa terdapat varians variabel pada model regresi yang sama. Apabila terjadi sebaliknya varian variabel pada model regresi miliki nilai yang tidak sama maka disebut heteroskedastisitas. Dan jika terjadi heteroskedastisitas, maka hal itu akan mempengaruhi hasil dari analisis data tersebut dikarenakan terdapat perbedaan varian yang menunjukkan data tersebut masih homogen. Pada kondisi homoskedastisitas:

$\text{Var}(Y_i) = \text{Var}(\varepsilon_i) = \sigma^2, \; i = 1, 2, \ldots, n$

Sedangkan pada kondisi heteroskedastisitas:

$\text{Var}(Y_i) = \text{Var}(\varepsilon_i) = \sigma_i^2, \; i = 1, 2, \ldots, n$

dengan n menunjukkan jumlah observasi.

### PENDEKATAN METODE FORMAL

Pada metode formal, pendeteksian dilakukan dengan menggunakan pengujian secara
statistika. Beberapa statistik uji yang digunakan anatara lain:

#### Uji Korelasi Rank Spearman

Korelasi Spearman menghitung asosiasi antara dua variabel berdasarkan peringkat (rank) daripada nilai aslinya. Langkah-langkahnya adalah sebagai berikut:

1. Meregresikan $( Y )$ pada $( X $), $( Y_i = \beta_0 + \beta_1 X_i + \varepsilon_i $).

   Dari hasil pendugaan menggunakan metode OLS, diperoleh error ($( \varepsilon_i $)).

2. Tanpa memperhatikan tanda dari $( \varepsilon_i \)$ (diambil $( |\varepsilon_i| \)$, berikan rank dari pasangan variabel $( \varepsilon_i \)$ dengan $( X_i \)$. Selanjutnya, hitung besarnya koefisien korelasi rank Spearman antara kedua variabel tersebut dengan menggunakan persamaan:

   $r = 1 - 6 \left[ \frac{\sum d_i^2}{n(n^2 - 1)} \right]$

   dengan:
   - $( d_i \)$: selisih rank pasangan variabel $( \varepsilon_i \)$ dengan $( X_i \)$ individu ke-$( i \)$,
   - $( n \)$: banyaknya individu yang diamati.

3. Gunakan statistik uji $( t \)$ dengan rumusan sebagai berikut:

   $t = \frac{r \sqrt{n - 2}}{\sqrt{1 - r^2}} \sim t$

   dengan derajat bebas \( n - 2 \).
   
#### Uji Glejser

Uji Glejser merupakan salah satu metode statistik yang digunakan untuk mendeteksi adanya heteroskedastisitas dalam sebuah model. Pada uji Glejser, tahap pertama adalah meregresikan \( Y \) terhadap \( X \) dan diperoleh \( \varepsilon_i \). Selanjutnya, pada tahap kedua dilakukan regresi \( |\varepsilon_i| \) terhadap \( X \). Beberapa formula yang dianjurkan antara lain:

$|\varepsilon_i| = \beta_0 + \beta_1 X_i + V_i$

Dari model di atas, maka tahapan dalam uji Glejser adalah:

1. **Regresikan \( Y \) terhadap \( X \), didapatkan \( \varepsilon \) (residual/error).**  
2. **Regresikan \( |\varepsilon| \) (nilai absolut residual) terhadap \( X \).**  
3. **Merumuskan Hipotesis Uji \( t \):**

   - $( H_0 : \beta_i = 0 \)$
   - $( H_1 : \beta_i \neq 0 \)$, di mana $( i = 1, 2, \ldots, p \)$

   Tolak $( H_0 \)$ jika $( \text{Sig.} < \alpha \), di mana \( \alpha = 0,05 \)$.  

   Jika $( H_0 \)$ ditolak, maka terdapat heteroskedastisitas.
   
### CARA MENGATASI HETEROSKEDASTISITAS

Secara garis besar terdapat beberapa cara untuk mengatasi bila dalam model terdapat kasus heteroskedastisitas, antara lain:

#### Transformasi Variabel

Beberapa transformasi yang digunakan adalah: `ln`, `log`, `sqrt`, sinus, cosinus, `1/Y`, `1/X`, Box-Cox dan lain-lain.

#### Metode Kuadrat Terkecil Tertimbang (Weighted Least Square)

Model umum regresi linear:

$Y = \beta_0 + \beta_1 X_1 + \beta_2 X_2 + \dots + \beta_p X_p + \varepsilon$

## AUTO KORELASI 

  Uji  autokorelasi digunakan untuk melihat apakah terjadi korelasi antara suatu periode t denganp eriode sebelumnya (t -1). Secara sederhana adalah melihat apakah ada pengaruh antara variabel bebas terhadap variabel terikat, jadi tidak boleh ada korelasi antara observasi dengan data observasi sebelumnya. Sebagai contoh adalah pengaruh antara tingkat inflasi  bulanan  terhadap  nilai  tukar  rupiah  terhadap  dollar.  Data  tingkat  inflasi  pada  bulan tertentu, misalnya bulan Juni, akan dipengaruhi oleh tingkat inflasi bulan Mei. Berarti terdapat gangguan autokorelasi pada model tersebut.Uji  autokorelasi  hanya  dilakukan  pada  datatime  series  (runtut  waktu)dan  tidak perlu dilakukan pada data cross section seperti pada kuesioner di mana pengukuran semua variabel dilakukan secara serempak pada saat yang bersamaan.Didalam model regresi linear klasik mengasumsikan bahwa tidak terjadi autokorelasi, artinya kovarians antara \[e_i = e_j = 0\]. Artinya, error \[e_i\] yang berkaitan dengan data pengamatan ke-i tidak dipengaruhi oleh\[e_j\] yang berhubungan dengan data pengamatan ke-j. Dengan kata lain,
pada regresi klasik disyaratkan bahwa antara pengamatan yang satu \( y_i \) dengan pengamatan yang lain \( y_j \) saling bebas (independen).
  
  Jika terjadi korelasi, maka dinamakan ada problem autokorelasi. Autokorelasi muncul karena observasi yang berurutan sepanjang waktu berkaitan satu sama lainnya. Masalah ini timbul karena residual (kesalahan pengganggu) tidak bebas dari satu observasi ke observasi lainnya. Beberapa uji statistik yang sering dipergunakan adalah uji Durbin-Watson, uji dengan Run Test dan  jika  data  observasi  di  atas  100  data  sebaiknya menggunakan  uji Lagrange  Multiplier.

### PENDEKATAN METODE SECARA STATISTIKA

#### Uji Durbin-watson

Beberapa uji statistik yang dapat dipergunakan adalah uji Durbin-Watson, uji Run Test dan uji Lagrange Multiplier. Namun uji yang paling sering digunakan adalah uji Durbin-Watson.

Untuk menguji adanya autokorelasi pada lag-1:
$Y_t = \beta_0 + \beta_1 X_t + e_t$

Misalkan ada autokorelasi pada lag-1, \(\mathbb{E}(e_t e_{t-1}) \neq 0\):
$e_t = \rho e_{t-1} + v_t, \quad -1 < \rho < 1$

dengan \(\rho\) = koefisien otokorelasi atau otokovarians.

#### Hipotesis:
- \(H_0 : \rho = 0\)
- \(H_1 : \rho \neq 0\)

Statistik Durbin-Watson diperoleh dengan rumus sebagai berikut:
\[
d = \frac{\sum_{t=2}^n (e_t - e_{t-1})^2}{\sum_{t=1}^n e_t^2}
\]

Banyaknya pengamatan tinggal (\(n-1\)), nilai \(d\) dibandingkan dengan nilai \(d_L\) dan \(d_U\) pada yang diperoleh dari Tabel Durbin-Watson yang bersesuaian. Untuk mendapatkan nilai \(d\), data harus diketahui terlebih dahulu, yaitu:
- \( \alpha \): tingkat signifikansi,
- \( k \): banyaknya variabel independen, dan
- \( n \): banyaknya data.

Pengambilan keputusan berdasarkan kriteria yang disajikan pada Tabel 3.1.

**Tabel 5.1 Kriteria Pengambilan Keputusan di Uji Durbin-Watson**

| **Hipotesis Nol (H₀)**                      | **Keputusan**        | **Jika**                                  |
|---------------------------------------------|----------------------|-------------------------------------------|
| Tidak ada Autokorelasi Positif              | Tolak H₀             | \(0 < d_{hitung} < d_{L,\alpha}\)         |
| Tidak ada Autokorelasi Positif              | Tidak ada keputusan  | \(d_{L,\alpha} < d_{hitung} < d_{U,\alpha}\) |
| Tidak ada Autokorelasi Positif dan Negatif  | Terima H₀            | \(d_{U,\alpha} < d_{hitung} < 4 - d_{U,\alpha}\) |
| Tidak ada Autokorelasi Negatif              | Tidak ada keputusan  | \(4 - d_{U,\alpha} < d_{hitung} < 4 - d_{L,\alpha}\) |
| Tidak ada Autokorelasi Negatif              | Tolak H₀             | \(4 - d_{L,\alpha} < d_{hitung} < 4\)     |

### CARA MENGATASI AUTOKORELASI

Salah satu cara mengatasi masalah adanya autokorelasi adalah dengan menggunakan metode kuadrat terkecil yang umum (Generalized Least Squares, GLS). Misalkan suatu model regresi linear sederhana sebagai berikut :

\[
Y_{t} = \beta_0 + \beta_1 X_{t} + e_{t} \tag{3.1}
\]
Dalam praktik, biasanya ada anggapan bahwa error mengikuti autoregresi orde pertama, yang dirumuskan sebagai berikut:

\[
e_t = \rho e_{t-1} + v_t, \quad \text{dengan } -1 < \rho < 1
\tag{3.2}\]

di mana:

\[
v_t = e_t - \rho e_{t-1}
\]

Error \(v_t\) memenuhi semua asumsi klasik.


Persamaan model utama dapat ditulis sebagai:

\[
Y_t = \beta_0 + \beta_1 X_t + e_t \tag{3.1}
\]

##### Transformasi Model (Bila \(\rho\) diketahui)

Dari persamaan \((3.1)\), dibuat lag-1 sehingga menjadi:

\[
Y_{t-1} = \beta_0 + \beta_1 X_{t-1} + e_{t-1} \tag{5.5}
\]

Kemudian, persamaan \((3.2)\) dikalikan dengan \(\rho\):

\[
\rho Y_{t-1} = \rho \beta_0 + \rho \beta_1 X_{t-1} + \rho e_{t-1} \tag{3.3}
\]

Selanjutnya persamaan (3.2) dikurangi dengan persamaan (3.3):
\[
Y_t - \rho Y_{t-1} = \beta_1 (1 - \rho) + \beta_1 (X_t - \rho X_{t-1}) + v_t
\tag{3.4}
\]

Dengan:
\[
Y_t^* = Y_t - \rho Y_{t-1}, \quad X_t^* = X_t - \rho X_{t-1}, \quad \beta_1^* = \beta_1 (1 - \rho)
\tag{3.5}
\]

Pada keadaan ini kita akan kehilangan pengamatan pertama, sehingga agar tidak hilang digunakan formula:
\[
Y_1^* = Y_1 \sqrt{1 - \rho^2}, \quad X_1^* = X_1 \sqrt{1 - \rho^2}
\tag{3.6}
\]

Persamaan (3.6) disebut **Generalized Difference Equation**:

---

##### Kedua: Bila \(\rho\) tidak diketahui

Walaupun mudah penggunaannya, tetapi **generalized difference regression** dalam praktiknya susah, sebab jarang diketahui nilainya. Maka dari itu, sebagai suatu alternatif digunakan metode lain, yaitu sebagai berikut:

1. Metode selisih/perbedaan pertama (the first difference method)

Oleh karena terdapat data \(t\) dan \(t-1\), yaitu autokorelasi sempurna yang positif atau negatif, kita dapat menulis persamaan regresi sebagai berikut:
$Y_t - Y_{t-1} = \beta_1 (X_t - X_{t-1}) + v_t$

Di mana:
$\Delta_t = (X_t - X_{t-1}), \quad \Delta_t Y_t = \beta_1 \Delta_t X_t + v_t$

Di sini, \(\Delta_t\) disebut operator perbedaan pertama.

2. \(\rho\) didasarkan pada Statistik uji Durbin-Watson

$\hat{\rho} = 1 - \frac{d}{2}$

Untuk \(n\) kecil, Theil dan Nagar mengusulkan rumus sebagai berikut:
$\hat{\rho} = 1 - \frac{d}{2}$

Estimasi parameter \(\rho\) dapat dihitung menggunakan persamaan berikut:

$\hat{\rho} = \frac{n^2 \left(1 - \frac{d}{2}\right) + k^2}{n^2 - k^2}$

dengan:
- \(n\) = banyaknya observasi,
- \(d\) = statistik \(d\) Durbin-Watson,
- \(k\) = banyaknya parameter dalam model (termasuk intersep).

Parameter \(\rho\) juga dapat diduga berdasarkan error \(e_t\) dari model:

$e_t = \rho e_{t-1} + v_t$

Di sini, \(\rho\) dapat dihitung dengan meregresikan \(e_t\) terhadap \(e_{t-1}\) tanpa intersep, sehingga diperoleh estimasi \(\hat{\rho}\).


## NORMALITAS

  Uji normalitas digunakan untuk melihat apakah nilai residual terdistribusi normal atau tidak.Model regresi yang baik adalah memiliki residual yang terdistribusi normal.Dan untuk uji normalitas bukan dilakukan  pada  masing-masing  variabel  tetapi pada  nilai  residualnya.Sering  terjadi kesalahan yang jamak yaitu bahwa uji normalitas dilakukan pada masing-masing variabel.

  Uji  normalitas  dapat  dilakukan  dengan  uji  histogram, uji  Chi  Square,dan uji Kolmogorov Smirnov. Tidak ada metode yang paling baik atau paling  tepat. Namun,  jika menggunakan  pengujian metode grafik sering  menimbulkan perbedaan persepsi di antara beberapa pengamat, sehingga penggunaan uji normalitas dengan uji statistik  bebas  dari  keragu-raguan, meskipun  tidak ada  jaminannya.

  Berdasarkan pengalaman empiris beberapa ahli-ahli statistik, data yang banyaknya lebih dari 30 angka (n > 30), maka sudah dapat diasumsikan berdistribusi normal. Biasa dikatakan sebagai sampel besar.Namun untuk memberikan kepastian, data yang dimiliki berdistribusi normal atau tidak,sebaiknya digunakan uji normalitas. Karena belum tentu data yang lebih dari 30 bisa dipastikan berdistribusi normal, demikian sebaliknya data yang banyaknya kurang dari 30 belum tentu tidak berdistribusi normal.

### PENDEKATAN METODE SECARA STATISTIKA

#### Kolmogorov Smirnov

Pada Signifikansi Metode Kolmogorov-Smirnov menggunakan tabel pembanding Kolmogorov-Smirnov.**Kolmogorov-Smirnov (KS)** adalah uji statistik nonparametrik. Persyaratan KS adalah sebagai berikut;

• Data berskala interval atau ratio (kuantitatif)

• Data tunggal/ belum dikelompokkan pada tabel distribusi frekuensi

• Dapat untuk n besar maupun n kecil. Uji KS dilakukan dengan hipotesis sebagai berikut:

- \( H_0 \): Residual berdistribusi normal  
- \( H_1 \): Residual tidak berdistribusi normal  

Dengan \( \alpha = 0,05 \) atau \( 0,10 \), maka **Tolak \( H_0 \)** jika \( \text{Sig.} < \alpha \).

Nilai **Sig.** dapat diperoleh dengan menggunakan R Studio/software lainnya yang berhubungan dengan statistika.


#### Shapiro Wilk

Metode Shapiro-Wilk menggunakan data mentah yang belum diolah dalam tabel distribusi frekuensi. Data tersebut diurutkan dan dibagi menjadi dua kelompok untuk kemudian dikonversi dalam uji Shapiro-Wilk. Proses ini dapat dilanjutkan dengan transformasi nilai Z untuk menghitung luas di bawah kurva normal.

Persyaratan:
-   Data harus berskala interval atau rasio (kuantitatif).
-   Data merupakan data tunggal yang belum dikelompokkan dalam tabel distribusi frekuensi.
-   Data berasal dari sampel acak.

### Uji Shapiro-Wilk

Rumus untuk uji Shapiro-Wilk melibatkan perhitungan statistik \( W \) yang mengukur sejauh mana data mengikuti distribusi normal. Berikut adalah rumus statistik uji Shapiro-Wilk:

$W = \frac{\left( \sum_{i=1}^{n} a_i x_{(i)} \right)^2}{\sum_{i=1}^{n} (x_i - \bar{x})^2}$

Di mana:
- \( x_{(i)} \) adalah data yang diurutkan dari yang terkecil hingga yang terbesar.
- \( \bar{x} \) adalah rata-rata dari sampel data.
- \( a_i \) adalah koefisien yang tergantung pada urutan data dan ukuran sampel \( n \). Koefisien ini dapat dihitung menggunakan tabel khusus atau perangkat lunak statistik.

Berikut ini adalah tahapan-tahapan yang bisa diterapkan saat perhitungan:
1. **Urutkan data** \( x_1, x_2, ..., x_n \) dari yang terkecil hingga terbesar, sehingga \( x_{(1)} \leq x_{(2)} \leq ... \leq x_{(n)} \).
2. Hitung **rata-rata** \( \bar{x} \) dari data.
3. Tentukan koefisien \( a_i \) menggunakan tabel Shapiro-Wilk atau perangkat lunak statistik.
4. Hitung statistik uji \( W \) menggunakan rumus di atas.
5. Hitung **nilai p** dari statistik \( W \) dan bandingkan dengan tingkat signifikansi.

Uji Hipotesis yang diuji dalam uji Shapiro-Wilk adalah sebagai berikut:
- **Hipotesis nol (\( H_0 \))**: Data berasal dari distribusi normal.
- **Hipotesis alternatif (\( H_1 \))**: Data tidak berasal dari distribusi normal.

Dan Langkah-langkah untuk Uji Hipotesis adalah:
1. **Tentukan tingkat signifikansi** (\( \alpha \)): Umumnya digunakan \( \alpha = 0,05 \), yang berarti ada 5% kemungkinan untuk menolak hipotesis nol jika hipotesis nol benar.
2. **Hitung statistik uji \( W \)**: Gunakan rumus yang telah dijelaskan atau perangkat lunak statistik untuk menghitung nilai \( W \).
3. **Cari nilai p**: Nilai p untuk statistik \( W \) dapat dihitung menggunakan tabel distribusi atau perangkat lunak statistik.
4. **Bandingkan nilai p dengan \( \alpha \)**:
   - Jika \( p \leq \alpha \), **tolak \( H_0 \)** dan simpulkan bahwa data tidak berdistribusi normal.
   - Jika \( p > \alpha \), **gagal menolak \( H_0 \)** dan simpulkan bahwa data berdistribusi normal.

Tahap terakhir untuk Pengambilan Keputusan, Keputusan dalam uji Shapiro-Wilk didasarkan pada nilai p yang dihitung dari statistik uji \( W \):

- **Tolak \( H_0 \)** jika nilai p lebih kecil dari atau sama dengan tingkat signifikansi (\( p \leq \alpha \)). Ini berarti data tidak berdistribusi normal.
- **Gagal menolak \( H_0 \)** jika nilai p lebih besar dari tingkat signifikansi (\( p > \alpha \)). Ini berarti tidak ada bukti yang cukup untuk menolak asumsi distribusi normal pada data.

### CARA MENGATASI KETIDAKNORMALAN RESIDUAL 

Untuk mengatasi data yang tidak berdistribusi normal terdapat beberapa cara,
namun yang penulis bahas adalah dengan deteksi dan menghilangkan outlier.

#### Deteksi dan Menghilangkan Outlier

Outliers adalah data yang memiliki nilai sangat jauh dari nilai umumnya, atau
dengan kata lain memiliki nilai yang ekstrem. Adanya outliers ini dapat berpengaruh pada hasil uji asumsi, seperti uji normalitas, lineraritas, maupun homogenitas varians. Lebih parah lagi, outliers ini dapat berpengaruh pada pegambilan kesimpulan penelitian dari hasil uji statistik. Ada beberapa faktor yang menyebabkan munculnya data outliers, diantaranya adalah Kesalahan penginputan data, kesalahan pengambilan sampel, subjek penelitian yang mengerjakan secara asal-asalan dan Fakta di lapangan memang demikian Jika alasan munculnya outliers adalah karena kesalahan penginputan, maka bisa dikoreksi. Namun jika munculnya outliers adalah karena kesalahan pengambilan sampel atau subjek yang mengerjakan secara asal-asalan, maka lebih baik dibersihkan terlebih dahulu data tersebut sebelum dilakukan analisis statistik. Ada beberapa cara dalam mendeteksi outlier, salah satunya dengan menggunakan box-plot.

#### Transformasi Data 

Transformasi data adalah proses mengubah data yang ada menjadi format atau skala yang berbeda untuk tujuan analisis statistik atau pemodelan yang lebih baik. Tujuan utama dari transformasi data adalah untuk membuat data lebih memenuhi asumsi model atau meningkatkan kualitas analisis. Transformasi data dilakukan dengan mengubah data tergantung dari bentuk grafik kita. Sebelum melakukan transformasi data, kita harus tahu terlebih dahulu bagaimana bentuk grafik kita. Setelah kita mengetahui bagaimana bentuk grafik dari data kita, maka kita bisa melihat panduan berikut untuk mentransformasi data kita;

**Tabel 5.2 Panduan Transformasi Data Berdasarkan Grafik Histogram**

| **Bentuk Grafik Histogram**      | **Bentuk Transformasi Data** |
|-----------------------------------|-------------------------------|
| Moderate positive skewness       | SQRT(x)                      |
| Substantial positive skewness    | LG10(x)                      |
| Severe positive skewness         | 1/x                          |
| Moderate negative skewness       | SQRT(k-x)                    |
| Substantial negative skewness    | LG10(k-x)                    |
| Severe negative skewness         | 1/(k-x)                      |

Keterangan:
- **k** = nilai tertinggi dari data mentah \( x \).

## LINIERITAS

Linieritas adalah salah satu asumsi dari analisis regresi, apakah
garis regresi antara dua variabel yaitu variabel dependen dan
independen membentuk garis linier atau tidak. Analisis regresi
tidak dapat dilanjutkan, jika tidak linier. Perlunya mengetahui adakah sifat linear pada hubungan X dan Y mempengaruhi tingkat valid atau tidaknya model regresi yang dihasilkan. Jadi, sebagus apapun model regresi yang dihasilkan dengan R squared yang tinggi, namun jika data tersebut tidak memiliki sifat linear, maka kemungkinan akan terjadi kesalahan estimasi dan akan mempengaruhi hasil akhir dari uji tersebut.
Dengan melakukan Uji linearitas ini juga digunakan untuk mengkonfirmasikan apakah sifat linear antara dua variabel yang diidentifikasikan secara teori sesuai atau tidak dengan hasil observasi yang ada.  


### Contoh Soal Uji Linieritas

Misalkan Anda sedang menguji hubungan antara dua variabel, yaitu **X (pendapatan bulanan)** dan **Y (jumlah pengeluaran)**, dengan menggunakan data berikut:

| No  | X (Pendapatan Bulanan) | Y (Jumlah Pengeluaran) |
|-----|------------------------|------------------------|
| 1   | 2000                   | 1500                   |
| 2   | 3000                   | 2200                   |
| 3   | 4000                   | 3000                   |
| 4   | 5000                   | 3800                   |
| 5   | 6000                   | 4600                   |
| 6   | 7000                   | 5300                   |
| 7   | 8000                   | 6100                   |
| 8   | 9000                   | 6900                   |
| 9   | 10000                  | 7600                   |

Anda diminta untuk melakukan uji linieritas antara variabel **X** dan **Y** menggunakan **Uji Korelasi Pearson** dan **Uji Uji Linieritas (Linearity Test)** untuk menentukan apakah hubungan antara kedua variabel tersebut bersifat linier.

### Langkah-langkah Uji Linieritas

1. **Langkah 1: Visualisasi Data**  
   Sebelum melakukan uji statistik, kita dapat memvisualisasikan hubungan antara X dan Y menggunakan **scatter plot** untuk melihat apakah hubungan keduanya tampak linier.

2. **Langkah 2: Uji Hipotesis**  
   - **Hipotesis nol (\( H_0 \))**: Terdapat hubungan linier antara X dan Y.
   - **Hipotesis alternatif (\( H_1 \))**: Tidak terdapat hubungan linier antara X dan Y.

3. **Langkah 3: Uji Korelasi Pearson**  
   Uji ini dilakukan untuk menguji kekuatan dan arah hubungan linier antara X dan Y. Rumus uji Korelasi Pearson adalah:

   $r = \frac{n(\sum xy) - (\sum x)(\sum y)}{\sqrt{[n\sum x^2 - (\sum x)^2][n\sum y^2 - (\sum y)^2]}}$

   Di mana:
   - \( r \) adalah koefisien korelasi Pearson.
   - \( n \) adalah jumlah data.
   - \( \sum xy \), \( \sum x \), \( \sum y \), \( \sum x^2 \), dan \( \sum y^2 \) adalah jumlah-jumlah yang diperlukan dari data.

   **Jika \( |r| \) mendekati 1**, maka hubungan antara X dan Y cenderung linier.

4. **Langkah 4: Uji Linieritas**  
   Uji linieritas dilakukan untuk menguji apakah hubungan antara X dan Y benar-benar linier atau tidak. Salah satu metode untuk menguji linieritas adalah dengan menggunakan **Uji Linearity pada Regresi**.

   Misalkan model regresi liniernya adalah:

   $Y = \beta_0 + \beta_1 X + \epsilon$

   Dalam uji linieritas, kita dapat menguji apakah koefisien regresi (\( \beta_1 \)) signifikan atau tidak menggunakan uji t atau analisis residual untuk melihat pola ketidaksesuaian yang mungkin menunjukkan ketidaklinieran.

5. **Langkah 5: Interpretasi Hasil**  
   - Jika **nilai p untuk uji linieritas** lebih kecil dari tingkat signifikansi (\( \alpha = 0,05 \)), maka **tolak \( H_0 \)**, yang berarti hubungan antara X dan Y tidak linier.
   - Jika **nilai p lebih besar dari 0,05**, maka **gagal menolak \( H_0 \)**, yang berarti hubungan antara X dan Y dapat dianggap linier.

## MULTIKOLINIERITAS

  Istilah Multikolinearitas (kolinearitas ganda) pertama kali ditemukan oleh Ragnar Frisch yang berarti adanya hubungan linear yang sempurna atau pasti diantara beberapa atau semua variabel independen (bebas) dari model regresi ganda. Selanjutnya istilah multikolinearitas digunakan dalam arti yang lebih luas, yaitu terjadinya korelasi linear yang tinggi diantara variabel-variabel independen \( (X_1, X_2, \dots, X_p) \).

  Uji  multikolinearitas dilakukan  untuk  melihat apakah ada  atau  tidak korelasi yang  tinggi antara variabel-variabel bebas dalam suatu model regresi linear berganda. Jika ada korelasi yang tinggi di  antara variabel-variabel  bebasnya,  maka  hubungan  antara  variabel  bebas  terhadap  variabel terikatnya menjadi terganggu. Sebagai ilustrasi, adalah model regresi dengan variabel bebasnya motivasi, kepemimpinan dan kepuasan kerja dengan variabel terikatnya adalah kinerja. Logika sederhananya  adalah  bahwa  model  tersebut  untuk  mencari  pengaruh antara  motivasi,kepemimpinan dan kepuasan kerja terhadap kinerja. Jadi tidak boleh ada korelasi yang tinggi antara  motivasi  dengan  kepemimpinan,  motivasi  dengan  kepuasan  kerja  atau  antara kepemimpinan dengan kepuasan kerja. Alat statistik yang sering dipergunakan untuk menguji gangguan multikolinearitas adalah denganvariance  inflation  factor  (VIF),  korelasi  pearson  antara  variabel-variabel  bebas.

### KONSEKUENSI TERJADI MULTIKOLINEARITAS

#### Jika terjadi multikolinearitas yang sempurna, yaitu jika:
$\beta_1 X_1 + \beta_2 X_2 + \dots + \beta_p X_p = 0$

Maka dengan menggunakan metode estimasi OLS tidak dapat diperoleh koefisien regresi yang unik. Pada model regresi berganda dengan metode estimasi OLS, jika terjadi multikolinearitas sempurna di antara variabel independen, maka \((X'X)\) menjadi matriks singular, akibatnya invers dari \((X'X)\), yaitu \((X'X)^{-1}\), tidak dapat ditentukan secara unik. Dengan demikian nilai \(\beta_1, \beta_2, \dots, \beta_p\) tidak dapat diperoleh secara unik antara satu dengan yang lain.

---

#### Jika terjadi multikolinearitas yang mendekati sempurna 
(Korelasi yang tinggi di antara variabel independen), yaitu jika:
$\beta_1 X_1 + \beta_2 X_2 + \dots + \beta_p X_p \approx 0$

Jika \((X'X)\) merupakan matriks singular maka \(\text{det}(X'X) = 0\), tetapi jika terjadi multikolinearitas yang mendekati sempurna, \(\text{det}(X'X)\) mendekati 0, sehingga \(\text{var}(\hat{\beta})\) membesar (**over estimated**). Artinya, varians dari koefisien regresi membesar, sehingga **standard error** dari koefisien regresi membesar. Dengan kata lain, jika terjadi masalah multikolinearitas yang mendekati sempurna, maka hasil pendugaan dengan metode estimasi OLS masih tak bias, tetapi tidak efisien (variansnya tidak minimum).

---

##### Dampak dari membesarnya varians adalah:
1. Pengujian parameter regresi dengan statistik uji \(t\) menjadi tidak valid:
    - \(H_0 : \beta_i = 0\)  
    - \(H_1 : \beta_i \neq 0\)

2. Nilai \(t_{hitung} = \frac{\hat{\beta}_i}{s(\hat{\beta}_i)}\) akan mengecil jika \(s(\hat{\beta}_i)\) membesar, sehingga cenderung untuk **Terima H₀** (tidak signifikan).

### CARA MENANANGI TERJADINYA MULTIKOLINIERITAS 

#### Menggabungkan Data Cross Section dan Time Series

Data cross section merupakan data yang mencerminkan keadaan pada satu titik waktu tertentu (at a point of time), sedangkan data time series adalah data yang menunjukkan perubahan atau perkembangan suatu aktivitas dari waktu ke waktu (contohnya: data harga, produksi padi, pendapatan nasional, konsumsi nasional/regional, investasi nasional/regional, dan sebagainya). Analisis data cross section bersifat statis, karena tidak mempertimbangkan perubahan yang terjadi akibat waktu. Sebaliknya, analisis data time series bersifat dinamis, karena memperhitungkan perubahan yang disebabkan oleh faktor waktu.

Istilah seperti rata-rata tingkat kenaikan (rate increase) dan rata-rata tingkat pertumbuhan (rate of growth) biasanya dikaitkan dengan data yang bersifat berkala dalam kurun waktu tertentu (contohnya: data sepuluh tahun yang lalu, selama tiga periode pembangunan, atau selama sepuluh bulan terakhir).

Selain itu, analisis tren (trend analysis) juga termasuk jenis analisis dinamis yang sangat berguna untuk keperluan peramalan (forecasting). Data hasil peramalan ini memiliki manfaat penting dalam proses perencanaan (planning).

Teknik lainnya selain yang disebutkan di atas adalah dengan penggabungan data (data panel), yaitu data cross section dan time series secara bersama-sama dipergunakan dalam suatu analisis. Misalkan kita ingin mempelajari/meneliti permintaan mobil di Jakarta untuk golongan pendapatan menengah ke atas. Misalkan kita sudah mempunyai data berkala, selama kuartal I, II & III ( 15 tahun ) tentang jumlah mobil yang terjual (Q), rata-rata harga mobil (P), pendapatan masyarakat (Y) 
dan t menunjukkan waktu dengan model regresi sebagai berikut :

$Q_t = \beta_0 + \beta_1 P + \beta_2 Y + \varepsilon$


#### Mengeluarkan satu variabel atau lebih dan kesalahan spesifikasi

Jika dalam model terdapat kasus kolinearitas ganda yang serius, maka salah satu hal yang paling mudah adalah dengan mengeluarkan salah satu variabel yang berkorelasi dengan variabel lainnya. Misalkan dalam fungsi konsumsi, terdapat 2faktor yang mempengaruhi besarnya konsumsi (Y), yaitu pendapatan \( X_1 \), dan kekayaan \( X_2 \). Tetapi jika \( X_2 \) dikeluarkan dari model, maka seolah-olah hanya variabel pendapatan \( X_1 \) yang signifikan pengaruhnya terhadap Y. Akan tetapi dengan mengeluarkan satu variabel dari model regresi kita melakukan kesalahan spesifikasi (specification error). Kesalahan spesifikasi terjadi kalau kita melakukan kesalahan dalam menentukan spesifikasi model yang digunakan dalam analisis, maksudnya salah dalam menentukan variabel yang tepat/benar dalam suatu model regresi. Jadi kalau teori ekonomi mengatakan bahwa pendapatan dan kekayaan keduanya harus dimasukkan di dalam model regresi untuk menerangkan tingkah laku variabel konsumsi, keputusan untuk mengeluarkan variabel kekayaan dari model berarti melakukan kesalahan spesifik. Terdapat beberapa cara untuk mengeluarkan variabel dari model, antara lain : 
(i) Regresi stepwise, (ii) eliminasi langkah mundur (backward elimination). 

#### Transformasi Variabel-Variabel

Misalkan, kita mempunyai data berkala (*time series data*) mengenai konsumsi (Y), pendapatan (X₁), dan kekayaan (X₂). Salah satu alasan mengapa multikolinearitas terjadi antara pendapatan dan kekayaan ialah bahwa melalui perkembangan waktu, kedua variabel independen cenderung untuk bergerak dengan arah yang sama. Salah satu cara untuk membuat ketergantungan (*dependency*) antara kedua variabel tersebut caranya seperti berikut:

-   Model Awal
$Y_t = \beta_0 + \beta_1 X_{1t} + \beta_2 X_{2t} + \varepsilon_t$

-   Kemudian dibuat lag-1:
$ _{t-1} = \beta_0 + \beta_1 X_{1, t-1} + \beta_2 X_{2, t-1} + \varepsilon_{t-1}$

-   Selanjutnya dikurangkan, sehingga persamaannya menjadi:
$Y_t - Y_{t-1} = \beta_1 (X_{1t} - X_{1, t-1}) + \beta_2 (X_{2t} - X_{2, t-1}) + v_t$

dengan:
$v_t = \varepsilon_t - \varepsilon_{t-1}$

Ini lah yang dimaksud dengan perbedaan pertama (*first difference*).


#### Penambahan Data Baru 

Oleh karena adanya kolinearitas ganda merupakan gambaran sample (sample feature), ada kemungkinan bahwa untuk sampel lainnya yang mencakup variabelvariabel yang sama persoalan kolinearitas ganda mungkin tidak begitu serius seperti sampel pertama. Kadang-kadang hanya dengan menambah observasi (menambah nilai n), sudah dapat mengurangi persoalan kolinearitas ganda tersebut. 

#### Metode Lainnya 

Untuk metode lainnya yang dianjurkan untuk mengatasi multikolinearitas adalah 
sebagai berikut: 
1. Regresi Komponen Utama (Principal Component Regression) 
2. Regresi Ridge 
3. Regresi Kuadrat Terkecil Parsial (Partial Least Squares Regression) 
4. Regresi dengan Pendekatan Bayes 
5. Regresi Kontinum (Continuum Regression)

# Bab 4 : STUDI KASUS 

## REGRESI LINIER SEDERHANA

Terdapat data mengenai PENGARUH RATA-RATA LAMA SEKOLAH TERHADAP IPM DI KABUPATEN JAWA TIMUR TAHUN 2020.Berikut adalah data nya:

| Kabupaten      | RataRata_LamaSekolah | IPM   |
|----------------|----------------------|-------|
| Pacitan        | 7,6                 | 68,39 |
| Ponorogo       | 7,54                | 70,81 |
| Trenggalek     | 7,55                | 69,74 |
| Tulungagung    | 8,33                | 73    |
| Blitar         | 7,39                | 70,58 |
| Kediri         | 8,02                | 72,05 |
| Malang         | 7,42                | 70,36 |
| Lumajang       | 6,4                 | 65,46 |
| Jember         | 6,48                | 67,11 |
| Banyuwangi     | 7,16                | 70,62 |
| Bondowoso      | 5,93                | 66,43 |
| Situbondo      | 6,06                | 67,38 |
| Probolinggo    | 6,56                | 66,07 |
| Pasuruan       | 7,05                | 68,46 |
| Sidoarjo       | 10,5                | 80,29 |
| Mojokerto      | 8,54                | 72,97 |
| Jombang        | 8,54                | 72,97 |
| Nganjuk        | 8,21                | 71,73 |
| Madiun         | 7,81                | 71,73 |
| Magetan        | 7,84                | 71,96 |
| Ngawi          | 7,06                | 70,54 |
| Bojonegoro     | 7,33                | 69,04 |
| Tuban          | 6,95                | 68,4  |
| Lamongan       | 7,63                | 72,58 |
| Gresik         | 8,36                | 76,11 |
| Bangkalan      | 5,95                | 64,11 |
| Sampang        | 5,88                | 64,77 |
| Pamekasan      | 6,69                | 66,26 |
| Sumenep       | 5,71                | 66,43 |


### Tahapan Pengerjaan di R Studio 

1.) Input Data ke Dalam Software

Kita harus memasukkan data ke dalam format yang dapat diproses oleh perangkat R.Berikut adalah code nya;

```{r, echo =TRUE}
# Membuat data sebagai dataframe
data_IPM<- data.frame(
  Kabupaten = c("Pacitan", "Ponorogo", "Trenggalek", "Tulungagung", "Blitar", 
                "Kediri", "Malang", "Lumajang", "Jember", "Banyuwangi", 
                "Bondowoso", "Situbondo", "Probolinggo", "Pasuruan", "Sidoarjo", 
                "Mojokerto", "Jombang", "Nganjuk", "Madiun", "Magetan", 
                "Ngawi", "Bojonegoro", "Tuban", "Lamongan", "Gresik", 
                "Bangkalan", "Sampang", "Pamekasan", "Sumenep"),
  RataRata_LamaSekolah = c(7.6, 7.54, 7.55, 8.33, 7.39, 8.02, 7.42, 6.4, 6.48, 
                           7.16, 5.93, 6.06, 6.56, 7.05, 10.5, 8.54, 8.54, 8.21, 
                           7.81, 7.84, 7.06, 7.33, 6.95, 7.63, 8.36, 5.95, 5.88, 
                           6.69, 5.71),
  IPM = c(68.39, 70.81, 69.74, 73, 70.58, 72.05, 70.36, 65.46, 67.11, 70.62, 
          66.43, 67.38, 66.07, 68.46, 80.29, 72.97, 72.97, 71.73, 71.73, 71.96, 
          70.54, 69.04, 68.4, 72.58, 76.11, 64.11, 64.77, 66.26, 66.43)
)

print(data_IPM)
```

2.) Memastikan Data Bersih 

Sebelum melakukan analisis, data harus bersih. Berikut langkah-langkah yang dilakukan:

```{r, echo=TRUE}
# Cek missing values
sum(is.na(data_IPM))
```

3.) Membuat model Analisis Regresi 

Setelah berhasil mencetak data yang sama seperti data yang kita punya pada R studio, selanjutnya kita bisa mulai membuat model regresi linier dari data tersebut, dengan cara sebagai beriku:

```{r, echo=TRUE}
model_regresi<- lm(IPM ~ RataRata_LamaSekolah, data=data_IPM)
print(model_regresi)
#untuk melihat semua rangkuman di dalam model yang usdah dibuat
summary(model_regresi)
```
Berdasarkan output diatas, maka bisa dikatakan bahwa model regresi yang diperoleh adalah $$ y = 46.292 + 3.218X $$
4.) Melakukan Uji Asumsi 

a. HETEROSKEDASTISITAS

Pada uji ini kita akan melihat apakah data homogen atau tidak,berikut ini adalah cara nya. Namun,sebelum itu kita akan menginstall package "lmtest" 

```{r, echo=TRUE}
# Install library untuk uji Breusch-Pagan
library(lmtest)
# Install library untuk melihat hasil visualisasi(plot)
library(ggplot2)
# Uji Breusch-Pagan
model_regresi<- lm(IPM ~ RataRata_LamaSekolah, data=data_IPM)
bptest(model_regresi,studentize = FALSE)
# Plot residual vs. fitted
plot(model_regresi$fitted.values, model_regresi$residuals,
     main = "Residual vs Fitted Plot",
     xlab = "Fitted Values", ylab = "Residuals")
abline(h = 0, col = "khaki")
```

#### Uji Hipotesis:
- Hipotesis 
**H0**: Tidak ada heteroskedastisitas (residual memiliki varians yang konstan).
**H1**: Terdapat heteroskedastisitas (varians residual tidak konstan).

-Tingkat Signifikansi (alpha):
**α = 0.05** (5%).

- **Kesimpulan:** Jika p-value < 0.05, tolak H0: terdapat heteroskedastisitas.
Jika p-value >= 0.05, gagal menolak H0: tidak ada heteroskedastisitas pada data.

- Hasil: Berdasarkan output R, p-value = 0.7011 > 0.05. Maka data tidak ada heteroskedastisias.

b. AUTO KORELASI 

Autokorelasi pada data digunakan untuk mengecek apakah residual dari model regresi saling berkorelasi antara satu observasi dengan observasi lainnya dalam suatu urutan, terutama pada data deret waktu (time series). Hal ini penting karena asumsi dasar regresi linier klasik mengharuskan residual bersifat independen (tidak berkorelasi).Berikut ini adalah cara nya; 

```{r,echo=TRUE}
# Uji Durbin-Watson
dwtest(model_regresi)

```

#### Uji Hipotesis:
- **H0**: Tidak ada autokorelasi pada residual.
- **H1**: Terdapat autokorelasi pada residual.

-Tingkat Signifikansi (alpha):
**α = 0.05** (5%).

- **Kesimpulan:** Jika p-value < 0.05, tolak H0: terdapat autokorelasi pada residual.
Jika p-value >= 0.05, gagal menolak H0: tidak ada autokorelasi pada residual.

- Hasil: Berdasarkan output R, p-value =0.23 > 0.05. Maka data tidak ada autokorelasi pada residual.

c. NORMALITAS

Uji Normalitas pada data ini digunakan untuk mengecek apakah distribusi residual atau variabel tertentu mengikuti distribusi normal. Berikut adalah cara nya ;

```{r,echo=TRUE}
# Uji normalitas untuk Rata-rata Lama Sekolah
shapiro.test(data_IPM$RataRata_LamaSekolah)

# Uji normalitas untuk IPM
shapiro.test(data_IPM$IPM)
```

#### 1. Uji Hipotesis
- Hipotesis:
  - H0: Data berdistribusi normal.
  - H1: Data tidak berdistribusi normal.
  
-Tingkat Signifikansi (alpha):
**α = 0.05** (5%).

- **Kesimpulan:** Jika p-value < 0.05, maka data tidak normal. Sebaliknya, jika p-value >= 0.05, data berdistribusi normal.

- Hasil: Berdasarkan output R, p-value = 0.1756 > 0.05. Maka data berdistribusi normal.


d. LINIERITAS

Linieritas dalam analisis statistik digunakan untuk mengecek apakah hubungan antara variabel independen (prediktor) dan variabel dependen (respons) bersifat linear.Langkah pertama yang harus dilakukan untuk uji linieritas adalah menginstall packages "car".

```{r, echo=TRUE}
# Install library
library(car)
avPlots(model_regresi) #rata-rata
crPlots(model_regresi) #componen residuals
```
## REGRESI LINIER BERGANDA

Data yang digunakan sama seperti studi kasus di regresi linier sederhana hanya saja menambahkan 2 vaeriabel baru. Maka diperoleh data nya seperti berikut;

| KABUPATEN   | X1 (ANGKA HARAPAN HIDUP) | X2 (RATA-RATA LAMA SEKOLAH) | X3 (HARAPAN LAMA SEKOLAH) | IPM   |
|-------------|--------------------------|-----------------------------|---------------------------|-------|
| Pacitan     | 71.94                   | 7.5                         | 12.64                    | 68.39 |
| Ponorogo    | 72.77                   | 7.54                        | 12.73                    | 70.81 |
| Trenggalek  | 73.75                   | 7.55                        | 12.35                    | 69.74 |
| Tulungagung | 74.08                   | 8.0                         | 13.31                    | 72.96 |
| Blitar      | 73.52                   | 7.83                        | 12.46                    | 70.58 |
| Kediri      | 73.11                   | 7.42                        | 13.15                    | 72.05 |
| Malang      | 72.55                   | 7.42                        | 13.81                    | 70.36 |
| Lumajang    | 71.35                   | 6.48                        | 13.42                    | 67.11 |
| Jember      | 69.15                   | 6.85                        | 13.13                    | 67.11 |
| Banyuwangi  | 69.74                   | 6.46                        | 13.42                    | 67.11 |
| Bondowoso   | 66.74                   | 5.93                        | 13.28                    | 66.03 |
| Situbondo   | 68.35                   | 6.46                        | 13.15                    | 67.61 |
| Probolinggo | 67.29                   | 6.11                        | 12.85                    | 65.87 |
| Pasuruan    | 70.23                   | 6.74                        | 12.41                    | 68.67 |
| Sidoarjo    | 74.03                   | 8.01                        | 13.44                    | 73.68 |
| Mojokerto   | 73.24                   | 8.54                        | 12.88                    | 73.83 |
| Jombang     | 72.31                   | 7.65                        | 13.16                    | 71.39 |
| Nganjuk     | 71.54                   | 7.64                        | 12.86                    | 71.72 |
| Madiun      | 72.19                   | 7.31                        | 12.43                    | 71.70 |
| Magetan     | 72.93                   | 8.24                        | 14.03                    | 73.92 |
| Ngawi       | 71.56                   | 7.35                        | 12.39                    | 69.04 |
| Bojonegoro  | 71.64                   | 7.93                        | 13.48                    | 72.18 |
| Tuban       | 72.4                    | 7.92                        | 13.43                    | 72.58 |
| Lamongan    | 72.64                   | 7.96                        | 13.48                    | 73.11 |
| Gresik      | 72.66                   | 7.93                        | 13.43                    | 76.11 |
| Bangkalan   | 70.18                   | 5.95                        | 12.57                    | 66.11 |
| Sampang     | 68.03                   | 5.85                        | 12.67                    | 64.22 |
| Pamekasan   | 67.58                   | 6.69                        | 13.64                    | 66.85 |
| Sumenep    | 71.41                   | 5.71                        | 13.2                     | 66.43 |

### Tahapan Pengerjaan di R Studio 

1.) Input Data ke Dalam Software

Kita harus memasukkan data ke dalam format yang dapat diproses oleh perangkat R.Berikut adalah code nya;

```{r, echo=TRUE}
```{r, echo=TRUE}
data_IPM_berganda <- data.frame(
  KABUPATEN = c("Pacitan", "Ponorogo", "Trenggalek", "Tulungagung", "Blitar", "Kediri", 
                "Malang", "Lumajang", "Jember", "Banyuwangi", "Bondowoso", "Situbondo", 
                "Probolinggo", "Pasuruan", "Sidoarjo", "Mojokerto", "Jombang", "Nganjuk", 
                "Madiun", "Magetan", "Ngawi", "Bojonegoro", "Tuban", "Lamongan", "Gresik", 
                "Bangkalan", "Sampang", "Pamekasan", "Sumenep"),
  X1_ANGKA_HARAPAN_HIDUP = c(71.94, 72.77, 73.75, 74.08, 73.52, 72.61, 72.55, 70.1, 69.15, 70.65, 66.74, 69.13, 67.2, 70.23, 74.04, 72.53, 72.4, 71.54, 71.38, 72.59, 72.3, 71.56, 71.43, 72.4, 72.66, 70.18, 68.03, 67.58, 71.41),
  X2_RATA_RATA_LAMA_SEKOLAH = c(7.6, 7.54, 7.55, 8.33, 7.39, 8.02, 7.42, 6.4, 6.48, 7.16, 5.93, 
                                6.46, 6.11, 7.4, 10.5, 8.51, 8.54, 7.64, 7.81, 8.24, 7.06, 7.33, 
                                6.95, 7.92, 9.3, 5.95, 4.85, 6.69, 5.71),
  X3_HARAPAN_LAMA_SEKOLAH = c(12.64, 13.73, 12.35, 13.31, 12.46, 13.15, 13.18, 11.81, 13.42, 
                              12.8, 13.28, 13.15, 12.35, 12.41, 14.93, 12.88, 13.27, 12.86, 
                              13.16, 14.03, 12.7, 12.39, 12.21, 13.48, 13.73, 11.6, 12.37, 
                              13.64, 13.2),
  IPM = c(68.39, 70.81, 69.74, 73, 70.58, 72.05, 70.36, 65.46, 67.11, 70.62, 66.43, 67.38, 
          66.07, 68.6, 80.29, 73.83, 72.97, 71.72, 71.73, 73.92, 70.54, 69.04, 68.4, 72.58, 
          76.11, 64.11, 62.7, 66.26, 66.43)
)
print(data_IPM_berganda)
```
2.) Memastikan Data Bersih 

Sebelum melakukan analisis, data harus bersih. Berikut langkah-langkah yang dilakukan:

```{r, echo=TRUE}
# Cek missing values
sum(is.na(data_IPM_berganda))
```

3.) Membuat model Analisis Regresi 

Setelah berhasil mencetak data yang sama seperti data yang kita punya pada R studio, selanjutnya kita bisa mulai membuat model regresi linier dari data tersebut, dengan cara sebagai beriku:

```{r, echo=TRUE}
# Membuat model regresi linear
model_berganda<- lm(IPM ~ X1_ANGKA_HARAPAN_HIDUP + X2_RATA_RATA_LAMA_SEKOLAH + X3_HARAPAN_LAMA_SEKOLAH, data = data_IPM_berganda)
print(model_berganda)
#untuk melihat semua rangkuman di dalam model yang usdah dibuat
summary(model_berganda)
```

Berdasarkan output diatas, maka bisa dituliskan ke dalam model regresi seperti berikut; $$ Y= 19.8251 + 0.2614X1 + 2.4246X2 + 1.0521X3 $$
4.) Melakukan Uji Asumsi 

a. HETEROSKEDASTISITAS

Pada uji ini kita akan melihat apakah data homogen atau tidak,berikut ini adalah cara nya. Namun,sebelum itu kita akan menginstall package "lmtest" 

```{r, echo=TRUE}
# Install library untuk uji Breusch-Pagan
library(lmtest)
# Uji Breusch-Pagan
model_berganda<- lm(IPM ~ X1_ANGKA_HARAPAN_HIDUP + X2_RATA_RATA_LAMA_SEKOLAH + X3_HARAPAN_LAMA_SEKOLAH, data = data_IPM_berganda)
# Uji Breusch-Pagan menggunakan library lmtest
bptest(model_berganda) # Hasil uji Breusch-Pagan

```

#### Uji Hipotesis:
- Hipotesis 
**H0**: Tidak ada heteroskedastisitas (residual memiliki varians yang konstan).
**H1**: Terdapat heteroskedastisitas (varians residual tidak konstan).

-Tingkat Signifikansi (alpha):
**α = 0.05** (5%).

- **Kesimpulan:** Jika p-value < 0.05, tolak H0: terdapat heteroskedastisitas.
Jika p-value >= 0.05, gagal menolak H0: tidak ada heteroskedastisitas pada data.

- Hasil: Berdasarkan output R, p-value = 0.5492 > 0.05. Maka data tidak ada heteroskedastisias.

b. AUTO KORELASI 

Autokorelasi pada data digunakan untuk mengecek apakah residual dari model regresi saling berkorelasi antara satu observasi dengan observasi lainnya dalam suatu urutan, terutama pada data deret waktu (time series). Hal ini penting karena asumsi dasar regresi linier klasik mengharuskan residual bersifat independen (tidak berkorelasi).Berikut ini adalah cara nya; 

```{r,echo=TRUE}
model_berganda<- lm(IPM ~ X1_ANGKA_HARAPAN_HIDUP + X2_RATA_RATA_LAMA_SEKOLAH + X3_HARAPAN_LAMA_SEKOLAH, data = data_IPM_berganda)
# Uji Durbin-Watson menggunakan library lmtest
dwtest(model_berganda) # Hasil uji Durbin-Watson
```


#### Uji Hipotesis:
- **H0**: Tidak ada autokorelasi pada residual.
- **H1**: Terdapat autokorelasi pada residual.

-Tingkat Signifikansi (alpha):
**α = 0.05** (5%).

- **Kesimpulan:** Jika p-value < 0.05, tolak H0: terdapat autokorelasi pada residual.
Jika p-value >= 0.05, gagal menolak H0: tidak ada autokorelasi pada residual.

- Hasil: Berdasarkan output R, p-value = 0.148 > 0.05. Maka data tidak ada autokorelasi pada residual.

c. NORMALITAS

Uji Normalitas pada data ini digunakan untuk mengecek apakah distribusi residual atau variabel tertentu mengikuti distribusi normal. Berikut adalah cara nya ;


```{r,echo=TRUE}
# Uji Normalitas menggunakan uji Shapiro-Wilk
shapiro.test(model_berganda$residuals)
# Plot histogram residual
hist(model_berganda$residuals, main = "Histogram Residual", xlab = "Residual")

```

#### 1. Uji Hipotesis
- Hipotesis:
  - H0: Data berdistribusi normal.
  - H1: Data tidak berdistribusi normal.
  
-Tingkat Signifikansi (alpha):
**α = 0.05** (5%).

- **Kesimpulan:** Jika p-value < 0.05, maka data tidak normal. Sebaliknya, jika p-value >= 0.05, data berdistribusi normal.

- Hasil: Berdasarkan output R, p-value = 0.454 > 0.05. Maka data berdistribusi normal.


d. LINIERITAS

Linieritas dalam analisis statistik digunakan untuk mengecek apakah hubungan antara variabel independen (prediktor) dan variabel dependen (respons) bersifat linear.Langkah pertama yang harus dilakukan untuk uji linieritas adalah menginstall packages "car".

```{r, echo=TRUE}
# Plot Linieritas
plot(fitted(model_berganda), model_berganda$residuals)
abline(0, 0)

# Korelasi hanya pada kolom numerik
numeric_data <- data_IPM_berganda[sapply(data_IPM_berganda, is.numeric)]
cor(numeric_data, method = "pearson")
```

e. MULTIKOLINIERITAS 

Multikolinieritas digunakan untuk mengecek adanya hubungan yang sangat kuat (korelasi tinggi) antara dua atau lebih variabel independen dalam model regresi. 

```{r, echo=TRUE}
library(car)
#NonMultikolinieritas
vif(model_berganda)
vif.inv<-1/vif(model_berganda)
```


#### 1. Uji Hipotesis
- Hipotesis:
  - H0: Data berdistribusi normal.
  - H1: Data tidak berdistribusi normal.
  
-Tingkat Signifikansi (alpha):
**α = 0.05** (5%).

- **Kesimpulan:** Jika \( \frac{1}{VIF_k} \) < 0.1, maka kemungkinan besar terjadi **multikolinearitas**
Sebaliknya, jika \( \frac{1}{VIF_k} \) > 0.1, maka kemungkinan besar tidak terjadi **multikolinearitas**

**Hasil Perhitungan VIF**

- **X1_ANGKA_HARAPAN_HIDUP**: 1.757390 > 0.1
- **X2_RATA_RATA_LAMA_SEKOLAH**: 2.518234 > 0.1
- **X3_HARAPAN_LAMA_SEKOLAH**: 3.651215 > 0.1 

- Hasil: Dengan demikian, **tidak terdapat multikolinearitas** yang signifikan di antara variabel independen dalam data yang digunakan.

# DAFTAR PUSTAKA 

Abdul Aziz.Ekonometrika Teori&Praktik Eksperimen dengan MATLAB. Malang.2007

Reza Mubarak. Pengantar Ekonometrika Edisi Pertama. Duta Media Publishing.2021

Rasidin dan Bonar. Aplikasi Model Ekonometrika. IPB Press. 2018

Gujarati (2004) http://www.konsultanstatistik.com/2011/07/uji-asumsi-klasik-
lengkap.html
