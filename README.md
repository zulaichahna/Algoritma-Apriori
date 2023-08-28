# Algoritma-Apriori
## Deskripsi
Banyaknya jumlah perguruan tinggi di Indonesia menjadi tantangan bagi masing-masing perguruan tinggi baik negeri maupun swasta agar dapat terus meningkatkan jumlah peminat dan mahasiswanya. Hal tersebut dapat diperoleh jika suatu perguruan tinggi mampu menentukan strategi promosi yang tepat. Dalam hal ini, perguruan tinggi dapat memanfaatkan data diri mahasiswa yang diterima di tahun sebelumnya untuk menganalisis keterkaitan antara program studi yang dipilih dengan SLTA asal, provinsi asal, kabupaten asal, atau kecamatan asal. Proses analisis ini menggunakan algoritma apriori yang diimplementasikan menggunakan Python. Hasil analisis tersebut kemudian dapat digunakan untuk membantu menentukan strategi promosi yang tepat.
## Data 
Data yang digunakan adalah data mahasiswa yang diterima di tahun sebelumnya, dengan variabel program studi yang ditempuh, SLTA asal, provinsi asal, kabupaten asal, dan kecamatan asal. Data diri mahasiswa diperoleh dengan persetujuan kepala bidang akademik. Data tersebut dipilih karena sesuai dengan kebutuhan untuk dapat mencapai tujuan.
## Software
Software yang digunakan yaitu, Microsoft Excel untuk melakukan seleksi data dan transformasi data, serta Jupyter Notebook untuk melakukan data cleaning dan proses analisis menggunakan Python.
## Proses Mining/Analisis
Pada tahap ini algoritma apriori mulai diimplementasikan dengan menggunakan bahasa pemrograman Python untuk menemukan pola atau aturan asosiasi dari kombinasi 2 itemset, antara program studi dengan provinsi asal, kabupaten asal, atau SLTA asal. Proses analisis meliputi:
### Analisis Pola Frekuensi Tinggi
Tahap ini dimaksudkan untuk mencari kombinasi item yang nilai support-nya memenuhi syarat minimal yang telah ditentukan sebelumnya. Nilai support atau nilai penunjang adalah nilai persentase kemunculan dari suatu kombinasi item di dalam basis data. Kombinasi atau himpunan item-item disebut dengan itemset. K-itemset adalah itemset yang berisi k item (misalnya, 1-itemset, 2-itemset, dst.). Contohnya: 
2-itemset (F2) = {Kopi, Susu}, 
3-itemset (F3) = {Susu, Pampers, Sirup}, dan seterusnya.  
### Pembentukan Aturan Asosiasi
Aturan asosiasi diperoleh dengan cara mencari nilai confidence dari kombinasi itemset yang terbentuk pada proses analisis pola frekuensi tinggi yang memenuhi nilai minimal support. Nilai confidence atau nilai kepastian adalah kuatnya hubungan antar item dalam aturan asosiasi. Nilai confidence ini juga berarti berapa persen kemungkinan bahwa seseorang akan memiliki A dan B secara bersamaan.
### Pembentukan Aturan Asosisasi Final
Aturan asosiasi final didapatkan melalui proses filtering untuk mendapatkan aturan asosiasi terbaik yang memenuhi nilai minimal lift ratio dan nilai minimal confidence yang telah ditetapkan. 

