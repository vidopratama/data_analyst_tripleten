# Paket Prabayar Megaline Manakah yang Lebih Baik

## English
### Data:
User Data:

    user_id — User ID
    first_name — user's first name
    last_name — user's last name
    age — user's age (years)
    city — the city where the user lives
    reg_date — subscription start date (dd, mm, yy)
    plan — phone plan name
    churn_date — the date the user stopped using the service (if the value is missing or not there, it means the service plan was being used when this data was generated)

Call Data:

    id — A unique telephone session ID
    user_id — ID of the user making the call
    call_date — call date
    duration — call duration (in minutes)

Message Data:

    id — Unique SMS ID
    user_id — ID of the user who sent the SMS
    message_date — the date the SMS was sent

Internet Data:

    id — A unique web session ID
    user_id — User ID
    session_date — web session date
    mb_used — volume of data consumed during session (in megabytes)

Phone Package Data:

    messages_included — monthly SMS allocation
    mb_per_month_included — monthly data volume allocation (in megabytes)
    minutes_included — monthly allocation of calling minutes
    usd_monthly_fee — monthly fee in US dollars
    usd_per_gb — price per extra gigabyte of data if the package allocation limit has been exceeded (1 GB = 1024 megabytes)
    usd_per_message — price per SMS if the package allocation limit has been exceeded
    usd_per_minute — price per minute if the package allocation limit has been exceeded (for example, if a package has an allocation of 100 minutes, then usage starting from the 101st minute will be charged)
    plan_name — phone plan name

### Goal:

Determine which prepaid plan generates more revenue to match advertising budget.

### Libraries used:

pandas, matplotlib, numpy, scipy

## Indonesia
### Data:
Data Pengguna:

    user_id — ID pengguna
    first_name — nama depan pengguna
    last_name — nama belakang pengguna
    age — usia pengguna (tahun)
    city — kota tempat tinggal pengguna
    reg_date — tanggal mulai berlangganan (dd, mm, yy)
    plan — nama paket telepon
    churn_date — tanggal pengguna berhenti menggunakan layanan (jika nilainya hilang atau tidak ada, berarti paket layanan sedang digunakan saat data ini dibuat)

Data Panggilan:

    id — ID sesi telepon unik
    user_id — ID pengguna yang melakukan panggilan
    call_date — tanggal panggilan
    duration — durasi panggilan (dalam menit)

Data Pesan:

    id — ID SMS unik
    user_id — ID pengguna yang mengirim SMS
    message_date — tanggal SMS dikirim

Data Internet:

    id — ID sesi web unik
    user_id — ID pengguna
    session_date — tanggal sesi web
    mb_used — volume data yang dihabiskan selama sesi (dalam megabita)

Data Paket Telepon:

    messages_included — alokasi SMS bulanan
    mb_per_month_included — alokasi volume data bulanan (dalam megabita)
    minutes_included — alokasi menit panggilan bulanan
    usd_monthly_fee — biaya bulanan dalam dolar AS
    usd_per_gb — harga per ekstra gigabita data jika telah melebihi batas alokasi paket (1 GB = 1024 megabita)
    usd_per_message — harga per SMS jika telah melebihi batas alokasi paket
    usd_per_minute — harga per menit jika telah melebihi batas alokasi paket (misalnya, jika paket memiliki alokasi 100 menit, maka penggunaan mulai dari menit ke-101 akan dikenakan biaya)
    plan_name — nama paket telepon

### Tujuan:

Menentukan paket prabayar mana yang menghasilkan lebih banyak pendapatan agar sesuai dengan anggaran iklan.

### Library yang digunakan:
pandas, matplotlib, numpy, scipy
