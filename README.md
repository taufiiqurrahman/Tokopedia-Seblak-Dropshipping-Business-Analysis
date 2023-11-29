A. Web Scraping

Dalam tahap web scraping, dilakukan pengambilan data dari halaman pencarian produk "seblak" di Tokopedia menggunakan Selenium dan BeautifulSoup. Proses ini membantu mengumpulkan informasi seperti nama produk, harga, penjual, kota, jumlah terjual, dan rating dari beberapa halaman situs.

B. Data Preparation

Tampilkan Beberapa Baris Data:

Data produk seblak yang berhasil diambil mencakup informasi tentang nama produk, nama toko, kota, harga, jumlah terjual, dan rating.
Pada tahap ini, ditemukan beberapa data duplikat yang kemudian dihapus.
Informasi Rangkuman Data:

Data setelah penghapusan duplikat memiliki 87 entri dengan 6 kolom.
Terdapat kolom dengan nilai null pada jumlah terjual dan rating, yang kemudian dihapus.
Cek Missing Value:

Setelah pembersihan data, tidak ada lagi nilai null pada dataframe.
Pembersihan dan Pengubahan Tipe Data:

Dilakukan pembersihan nilai dan perubahan tipe data pada kolom harga, jumlah terjual, dan rating untuk memastikan konsistensi data.
C. Business Understanding/Problem Statement

Problem Statement (SMART Framework):

Specific: Menganalisis target market dan preferensi pelanggan terhadap produk seblak di Tokopedia.
Measurable: Menggunakan web scraping untuk mendapatkan data numerik terkait produk seblak, ulasan, dan kompetitor.
Achievable: Web scraping efektif untuk analisis komprehensif seputar seblak di Tokopedia.
Relevant: Analisis ini membantu dalam pengambilan keputusan sebelum menjadi dropship seblak.
Time-bound: Pengumpulan data dan analisis dilakukan dalam satu bulan.
Key Metrics:

Listing: Menyertakan informasi tentang produk seblak, rating dan ulasan, jumlah penjualan, variasi harga, dan kompetitor.
D. Analysis

1. Statistik Deskriptif:

Harga rata-rata seblak: Rp23,471
Jumlah terjual rata-rata: 462
Rating rata-rata: 4.86
Distribusi harga cenderung skewness (2.95) dan kurtosis (9.78) positif, menunjukkan adanya ekor distribusi yang panjang.
2. Confidence Interval Pendapatan:

Menghitung interval kepercayaan (95%) dari distribusi pendapatan produk seblak.
3. Perbandingan Harga di Jabodetabek dan Luar Jabodetabek:

Mengamati perbedaan harga seblak di dua wilayah tersebut.
4. Korelasi Antara Harga dan Rating:

Menggunakan koefisien Pearson, Spearman, dan Kendall untuk mengetahui hubungan antara harga dan rating. Ditemukan korelasi yang signifikan.
E. Conclusion

Melalui analisis ini, dapat menyimpulkan bahwa:

Proses web scraping memberikan wawasan tentang produk seblak di Tokopedia.
Ada variasi harga dan preferensi pelanggan di berbagai wilayah.
Rating dan harga memiliki korelasi positif, artinya produk dengan harga lebih tinggi cenderung memiliki rating yang lebih baik.

Saran:
Segmentasi Wilayah:

Pertimbangkan strategi pricing yang sesuai dengan kondisi pasar di setiap wilayah.
Fokus pada daerah dengan permintaan tinggi dan persaingan rendah.
Optimasi Produk:

Identifikasi produk dengan jumlah penjualan tinggi dan rating baik, lalu analisis apa yang membuatnya diminati.
Pertimbangkan kerjasama dengan penjual yang populer atau mempertahankan stok produk yang memiliki rating tinggi.
Marketing:

Gunakan data ulasan untuk memahami kebutuhan pelanggan dan melakukan perbaikan produk.
Lakukan kampanye marketing berbasis rating untuk menarik perhatian pelanggan potensial.
Pengelolaan Stok:

Atur stok berdasarkan analisis jumlah terjual dan tren rating.
Pantau harga di wilayah Jabodetabek dan luar Jabodetabek untuk menyesuaikan strategi pricing.