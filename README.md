# Churn-Prediction

Digunakan model Logistic Regression dengan data yang dioversampling untuk mengklasifikasi apakah pelanggan akan berhenti berlangganan atau tidak.

Variabel yang dapat memprediksi apakah pelanggan akan churn atau tidak adalah:
   - Contract Renewal
   
     Tidak ditemukan pelanggan yang memperbarui kontraknya akan diberi label churn(warna jingga). Berarti untuk mengurangi tingkat churn, 
     perusahaan perlu membuat program perpanjangan kontrak yang menarik.
   - Data Plan
   
     Pelanggan yang dikategorikan churn memiliki Paket data yang lebih rendah dibandingkan yang tidak.
   - Data Usage
   
     Pelanggan yang dikatogirkan churn memiliki penggunaan data yang lebih rendah dibandingkan yang tidak.
   - Cust Serv Calls\n
     Kebanyakan pelanggan yang menelpon layanan pelanggan sebanyak 0-3 dikategorikan tidak churn. 
     Pelanggan yang menghubungi >3 punya kecendrungan untuk berhenti berlangganan.
   - Roam Mins/n
     Pelanggan yang berhenti berlanggan melakukan roaming lebih rendah dibandingkan yang tetap berlangganan.

Variabel yang tidak berkaitan signifikan dengan pola churn pelanggan:
   - AccountWeeks \n
     Lamanya seseorang sudah jadi pengguna produk tidak berkaitan dengan pola churn pelanggan. 
     Hal ini berarti, perusahaan tidak perlu mengkhawatirkan apakah pengguna baru akan menjadi pengguna yang loyal atau tidak.
   - DayMins /n
     Tidak terlihat hubungan signifikan antara churn dengan durasi panggilan yang dilakukan pengguna.
   - DayCalls
     Jumlah panggilan tiap hari tidak berkaitan dengan pola churn pelanggan.
   - MonthlyCharge
     Harga paket yang ditawarkan kepada pengguna tidak memiliki hubungan signifikan terhadap keputusan untuk berhenti berlangganan.
   - OverageFee
     Biaya yang dikeluarkan pengguna saat melewati limit paket, tidak memiliki hubungan signifikan dengan keputusan untuk berhenti berlangganan.
