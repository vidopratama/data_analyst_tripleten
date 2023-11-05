# Project SQL

## English

### data :

public.books :

- book_id — Book ID
- author_id — Author ID
- title — book title
- num_pages — number of pages
- publication_date — publication date
- publisher_id — Publisher ID

public.authors :

- author_id — Author ID
- author — author name

public.publishers :

- publisher_id — Publisher ID
- publisher — publisher name

public.publishers :

- rating_id — Rating ID
- book_id — Book ID
- username — the name of the user who rated the book
- rating — the rating value given is max 5

public.reviews :

- review_id — Review ID
- book_id — Book ID
- username — the name of the user reviewing the book
- text — review text


### Objective :

1. Number of books released after January 1, 2000.
2. Number of user reviews and average rating for each book.
3. Identify the publisher that has published the largest number of books, with more than 50 pages.
4. Identify authors with the highest average book ratings: find books with a rating of at least 50.
5. Average number of review texts among users who rated more than 50 books.

### Libraries used:
pandas, sqlalchemy

## Indonesia

### data :

public.books :

- book_id — ID buku
- author_id — ID penulis
- title — judul buku
- num_pages — jumlah halaman
- publication_date — tanggal penerbitan
- publisher_id — ID penerbit

public.authors :

- author_id — ID penulis
- author — nama penulis

public.publishers :

- publisher_id — ID penerbit
- publisher — nama penerbit

public.publishers :

- rating_id — ID rating
- book_id — ID buku
- username — nama pengguna yang memberi rating buku
- rating — nilai rating yang diberikan max 5

public.reviews :

- review_id — ID ulasan
- book_id — ID buku
- username — nama pengguna yang mengulas buku
- text — teks ulasan


### Tujuan :

1. Jumlah buku yang dirilis setelah tanggal 1 Januari 2000.
2. Jumlah ulasan pengguna dan rating rata-rata untuk setiap buku.
3. Identifikasi penerbit yang telah menerbitkan jumlah buku terbanyak, dengan jumlah halaman lebih dari 50.
4. Identifikasi penulis dengan rating rata-rata buku tertinggi: temukan buku dengan rating minimal 50.
5. Jumlah rata-rata teks ulasan di antara pengguna yang memberi rating terhadap lebih dari 50 buku.

### Library yang digunakan :
pandas, sqlalchemy
