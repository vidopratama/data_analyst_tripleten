# AB Testing

## English

### Data:

mkt_events :
- name — name of the marketing event.
-region — the region where the ad campaign will take place.
- start_dt — campaign start date.
- finish_dt — campaign end date.

events:
- user_id — unique user number.
- event_dt — event date and time.
- event_name — name of the event type.
- details — additional data regarding the event.

users :
- user_id — unique user number.
- first_date — registration date.
- region — region / country.
- device — the device used.

participants :
- user_id — unique user number.
- ab_test — experiment name.
- group — user experiment group.

### Objective :

1. Determine the analysis period.
2. Create an event funnel.
3. Conduct AB Testing.

### Libraries used :
pandas, numpy, datetime, matplotlib, seaborn, plotly, statsmodels

## Indonesia

### Data :

mkt_events :

- name — nama event pemasaran.
- regions — kawasan tempat kampanye iklan akan berlangsung.
- start_dt — tanggal awal kampanye.
- finish_dt — tanggal akhir kampanye.

events :

- user_id — nomor unik user.
- event_dt — tanggal dan waktu peristiwa.
- event_name — nama jenis peristiwa.
- details — data tambahan terkait peristiwa tersebut.

users :

- user_id — nomor unik user.
- first_date — tanggal pendaftaran.
- region — wilayah / negara.
- device — perangkat yang digunakan.

participants :

- user_id — nomor unik user.
- ab_test — nama eksperimen.
- group — kelompok eksperimen pengguna.

### Tujuan :

1. Menentukan periode analisa.
2. Membuat corong peristiwa.
3. Melakukan AB Testing.

### Library yang digunakan :
pandas, numpy, datetime, matplotlib, seaborn, plotly, statsmodels

