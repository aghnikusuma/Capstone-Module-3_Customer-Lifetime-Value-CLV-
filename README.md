# Capstone Project Module 3: Memprediksi Customer Lifetime Value (CLV)

# Project Overview
Tujuan: Memprediksi Customer Lifetime Value (CLV) dari data pelanggan asuransi, sekaligus mengidentifikasi faktor-faktor yang paling berpengaruh. Output proyek mencakup model prediktif serta insight bisnis yang dapat diimplementasikan.

CLV adalah metrik penting yang mencerminkan total nilai finansial yang dapat dihasilkan dari satu pelanggan sepanjang hubungan bisnis.

## Brief Summary

- **Analisis**: Menggunakan machine learning untuk memprediksi nilai CLV.
- **Model Terpilih**: Gradient Boosting Regressor pada target log(CLV), dibandingkan dengan Random Forest dan Linear Regression.
- **Evaluasi**: MAE, RMSE, R², serta cross-validation stability di skala log dan skala asli.
- **Interpretasi fitur**: Menggunakan Random Forest (hasil tuning) untuk memperoleh insight yang lebih transparan terhadap kontribusi fitur.

## Dataset

- Jumlah observasi: 5.669 baris
- Fitur utama:
  - **Pelanggan**: Employment Status, Marital Status, Education, Income
  - **Produk**: Vehicle Class, Coverage, Renew Offer Type, Number of Policies
  - **Keuangan**: Monthly Premium Auto, Total Claim Amount, Customer Lifetime Value

## Insight Bisnis

- Pelanggan dengan jumlah polis lebih banyak dan premi bulanan lebih tinggi cenderung memiliki nilai CLV yang tinggi. Ini membuka peluang untuk strategi *upselling* ke pelanggan yang saat ini hanya memiliki 1 produk.
- Karena faktor demografis tidak terlalu berpengaruh, pendekatan personalisasi sebaiknya difokuskan pada riwayat produk dan transaksi, bukan semata pada usia, status menikah, atau pendidikan.
- Pelanggan dengan CLV tinggi bisa menjadi target utama program loyalitas dan retensi, sementara pelanggan dengan nilai rendah tapi potensi tinggi (misalnya premi rendah tapi stabil) bisa disasar untuk *cross-selling*.

