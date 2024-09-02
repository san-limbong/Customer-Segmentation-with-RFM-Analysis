# Customer-Segmentation-with-RFM-Analysis

## Overview
Dataset yang disediakan pada kursus latihan di Progate pada Study SQL yang memberikan wawasan tentang aktivitas penjualan dari sebuah toko online yang berlangsung dari 1 Juli 2018 hingga 31 Juli 2018. Dataset ini mencakup berbagai item yang terdaftar pada situs,  910 baris penjualan serta 325 pengguna yang terdaftar. Tabel yang tersedia meliputi `items`, `sales_records` dan `users`.

## Tujuan 
Tujuan utama dari pengembangan proyek ini adalah untuk memfasilitasi pengembangan strategi peningkatan kualitas penjualan melalui analisa. Dengan memanfaatkan Analisis RFM (Recency, Frequency, Monetary), bisnis dapat memperoleh wawasan yang lebih mendalam tentang perilaku dan preferensi pelanggan.
Pertanyaan Utama:

## Pertanyaan Analisis:
1. Bagaimana angka total untuk pendapatan (revenue), laba, dan persentase laba website pembelanjaan?
2. Bagaimana gambaran grafik penjualan harian dalam rentang waktu selama 2 minggu
3. Apa 5 item yang berkontribusi paling banyak terhadap pendapatan?
4. Cari tahu persentase laba dan laba dari 5 item penghasil pendapatan teratas
5. Apa 5 item penghasil pendapatan terburuk?
6. Cari tahu 5 item dengan penghasilan laba terburuk
7. Cari tahu keuntungan total dan tingkat keuntungan item tergantung pada gender.
8. Cari tahu 5 jumlah pengguna teratas yang melakukan pembelian terbanyak.
9. Bagaimana Pemetaan atau Segmentasi Customer yang menggunakan Produk kita?

## Dashboard
Berikut ini merupakan implementasi dashboard dengan Google Looker Studio [Klik Disini](https://lookerstudio.google.com/u/0/reporting/4d8ca57b-c7d5-458a-a311-81475ceca044/page/6F89D)

![dashboard](https://github.com/user-attachments/assets/4f511fe9-81ed-4b0e-8c0d-c2812ec61582)


## Segment Analysis
Perusahaan telah membagi basis pelanggannya berdasarkan nilai recency, frequency, dan monetary, yang menunjukkan pendekatan strategis untuk memahami dan mengelola hubungan pelanggan. Setiap segmen mewakili kategori pelanggan yang berbeda dengan perilaku pembelian dan potensi nilai yang berbeda untuk perusahaan.

Berikut ini pemetaan atau persebaran dari segmentasi pengguna menggunakan tree map.
![tree map](https://github.com/user-attachments/assets/dfebf8d4-ba9c-4250-8204-888d0a56ad09)

Berdasarkan pemetaan tersebut, berikut rangkuman saran yang dapat digunakan untuk menunjang kebutuhan bisnis.

| **Segmen Pelanggan**           | **Aktivitas**                                                                                          | **Tips yang Dapat Diterapkan**                                                                                   |
|--------------------------------|-------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------|
| **Champions**                  | Membeli baru-baru ini, sering membeli, dan membelanjakan paling banyak!                              | Berikan hadiah. Bisa menjadi adopter awal untuk produk baru. Akan mempromosikan merek Anda.                      |
| **Loyal Customers**            | Menghabiskan uang dengan baik dan sering. Responsif terhadap promosi.                               | Tawarkan produk dengan nilai lebih tinggi. Minta ulasan. Ajak mereka untuk lebih terlibat.                     |
| **Potential Loyalist**         | Pelanggan baru-baru ini, tetapi menghabiskan jumlah yang baik dan membeli lebih dari sekali.          | Tawarkan program keanggotaan/loyalitas, dan rekomendasikan produk lain.                                        |
| **Recent Customers**           | Membeli paling baru, tetapi tidak sering.                                                             | Berikan dukungan onboarding, berikan mereka kesuksesan awal, dan mulai membangun hubungan.                      |
| **Promising**                  | Pembeli baru-baru ini, tetapi belum menghabiskan banyak.                                               | Ciptakan kesadaran merek, dan tawarkan uji coba gratis.                                                         |
| **Customers Needing Attention**| Nilai recency, frequency, dan monetary di atas rata-rata. Mungkin tidak membeli baru-baru ini.        | Buat penawaran terbatas, dan rekomendasikan berdasarkan pembelian sebelumnya. Reaktivasi mereka.                 |
| **About To Sleep**             | Nilai recency, frequency, dan monetary di bawah rata-rata. Akan kehilangan mereka jika tidak diaktifkan kembali. | Bagikan sumber daya berharga, rekomendasikan produk/renewal populer dengan diskon, dan hubungi mereka kembali. |
| **At Risk**                    | Menghabiskan banyak uang dan sering membeli. Tetapi sudah lama. Perlu dibawa kembali!                | Kirim email pribadi untuk menghubungi kembali, tawarkan pembaruan, dan sediakan sumber daya yang berguna.       |
| **Can’t Lose Them**            | Membeli dengan nilai terbesar dan sering. Tetapi belum kembali dalam waktu lama.                      | Menangkan mereka kembali melalui pembaruan atau produk baru, jangan biarkan mereka kalah bersaing, berbicara dengan mereka. |
| **Hibernating**                | Pembelian terakhir lama, dengan pengeluaran rendah dan jumlah pesanan rendah.                        | Tawarkan produk relevan lainnya dan diskon khusus. Ciptakan kembali nilai merek.                                |
| **Lost**                       | Nilai recency, frequency, dan monetary terendah.                                                       | Bangkitkan minat dengan kampanye jangkauan, abaikan jika tidak ada tanggapan.                                   |



Referensi:
[1](https://github.com/hhuseyincosgun/Online-Retail-EDA-RFM-Analysis/tree/main)
[2](https://www.putler.com/rfm-analysis/#Method_1_Simple_Fixed_Ranges)
[3](https://medium.com/@hhuseyincosgun/customer-segmentation-rfm-analysis-recency-frequency-monetary-5b29d5d45e35)
