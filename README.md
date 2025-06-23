# Capstone Project Module 3: Predicting Customer Lifetime Value (CLV)

## Projek Overview:
Tujuan: untuk memprediksi Customer Lifetime Value (CLV) pada data pelanggan dari perusahaan asuransi dengan mendalami faktor-faktor yang berpengaruh, dengan membuat model prediksi dan insight yang dapat digunakan dalam bisnis.

CLV adalah metrik penting yang mencerminkan total nilai keuangan yang bisa dihasilkan oleh pelanggan selama hubungan bisnis berlangsung.

Analisis:  Pemodelan yang diterapkan yakni menggunakan machine learning untuk memprediksi nilai CLV secara akurat.


## Dataset
- Total observasi: 5.669 baris
  
| Dimensi   | Fitur                                                             |
| --------- | ----------------------------------------------------------------- |
| Pelanggan | Employment Status, Marital Status, Education, Income              |
| Produk    | Vehicle Class, Coverage, Renew Offer Type, Number of Policies     |
| Keuangan  | Monthly Premium Auto, Total Claim Amount, Customer Lifetime Value |

## Insight Bisnis: 
- Pelanggan dengan jumlah polis lebih banyak dan premi bulanan lebih tinggi cenderung memiliki nilai CLV yang tinggi. Ini membuka peluang untuk strategi upselling ke pelanggan yang saat ini hanya memiliki 1 produk.
- Karena faktor demografis tidak terlalu berpengaruh, pendekatan personalisasi sebaiknya difokuskan pada riwayat produk dan transaksi, bukan semata pada usia, status menikah, atau pendidikan.
- Pelanggan dengan CLV tinggi bisa menjadi target utama program loyalitas dan retensi, sementara pelanggan dengan nilai rendah tapi potensi tinggi (misalnya premi rendah tapi stabil) bisa disasar untuk cross-selling.
