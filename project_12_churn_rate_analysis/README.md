# Churn Rate Analysis

## English

### Data:

- gender — User gender. 0 = female, 1 = male.
- Near_Location — whether the user lives or works near the gym location. 0 = far, 1 = close.
- Partner — whether the user is an employee of a partner company (the gym has a partner company and its employees are entitled to discounts; in this case, the gym stores information about the companies their customers work for). 0 = not a partner, 1 = partner.
- Promo_friends — whether the user initially signed up via a “refer a friend” offer (they used a friend's promo code when paying for their first membership). 0 = no, 1 = yes.
- Phone — whether the user provides their phone number. 0 = no, 1 = yes.
- Contract_period — 1 month, 3 months, 6 months, or 12 months (1 year).
- Group_visits — whether the user took part in group sessions. 0 = no, 1 = yes.
- Age — The user's age.
- Avg_additional_charges_total — the total amount of money spent to pay for other services in the fitness center: cafe, athletic goods, cosmetics, massage, etc.
- Month_to_end_contract — remaining months before the contract ends.
- Lifetime — time (in months) since the customer's first visit to the fitness center.
- Avg_class_frequency_total — average frequency of visits per week over the customer's lifetime.
- Avg_class_frequency_current_month — average frequency of visits per week throughout the current month.
- Churn — actual churn for the corresponding month. 0 = stay, 1 = leave.

### Objective :

1. Study overall user characteristics.
2. Study the factors that influence user churn rate.
3. Create a machine learning model.
4. Create a user cluster.
5. Study user clusters.
6. Determine the user cluster with the smallest possibility of users unsubscribing.

### Libraries used:

pandas, seaborn, matplotlib, sklearn, scipy

## Indonesia

### Data :

- gender — Jenis kelamin pengguna. 0 = perempuan, 1 = laki-laki.
- Near_Location — apakah pengguna tinggal atau bekerja di dekat lokasi pusat kebugaran. 0 = jauh, 1 = dekat.
- Partner — apakah pengguna adalah karyawan perusahaan mitra (pusat kebugaran ini memiliki perusahaan mitra dan para karyawannya berhak untuk mendapatkan diskon; dalam hal ini, pusat kebugaran menyimpan informasi tentang perusahaan tempat kerja pelanggan mereka). 0 = bukan mitra, 1 = mitra.
- Promo_friends — apakah pengguna awalnya melakukan pendaftaran melalui penawaran "ajak teman" (mereka menggunakan kode promo teman saat membayar keanggotaan pertama mereka). 0 = tidak, 1 = ya.
- Phone — apakah pengguna memberikan nomor telepon mereka. 0 = tidak, 1 = ya.
- Contract_period — 1 bulan, 3 bulan, 6 bulan, atau 12 bulan (1 tahun).
- Group_visits — apakah pengguna mengambil bagian dalam sesi kelompok. 0 = tidak, 1 = ya.
- Age — Umur pengguna.
- Avg_additional_charges_total — jumlah total uang yang dikeluarkan untuk membayar layanan lain di pusat kebugaran: kafe, barang atletik, kosmetik, pijat, dll.
- Month_to_end_contract — sisa bulan sebelum kontrak berakhir.
- Lifetime — waktu (dalam bulan) sejak kunjungan pertama pelanggan ke pusat kebugaran.
- Avg_class_frequency_total — frekuensi rata-rata kunjungan per minggu selama masa hidup (lifetime) pelanggan.
- Avg_class_frequency_current_month — frekuensi rata-rata kunjungan per minggu sepanjang bulan yang sedang berjalan.
- Churn — churn aktual untuk bulan terkait. 0 = tinggal, 1 = keluar.

### Tujuan :

1. Mempelajari karakteristik pengguna secara keseluruhan.
2. Mempelajari faktor-faktor yang mempengaruhi churn rate pengguna.
3. Membuat model machine learning.
4. Membuat klaster pengguna.
5. Mempelajari klaster pengguna.
6. Menentukan klaster pengguna dengan kemungkinan terkecil pengguna berhenti berlangganan.

### Library yang digunakan :

pandas, seaborn, matplotlib, sklearn, scipy
