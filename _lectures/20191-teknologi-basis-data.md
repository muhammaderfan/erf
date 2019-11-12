---
judul: "Teknologi Basis Data (A/B)"
tahun_akademik: "20191"
tahun_akademik2: "2019 Ganjil"
kontrak_kuliah: "https://docs.google.com/presentation/d/12B7nqzBANd9kuoQvt5sX9odd4Hgo7gbJJjwEstlD4Yg/edit?usp=sharing"
---

Matakuliah Teknologi Basis Data memberikan pemahaman dan penguasaan terkait proses dan skema kerja yang ada didalam sistem Database Management System (DBMS). Materi Teknologi Basis Data memiliki pendekatan lebih dalam dari sistem internal DBMS, tidak membahas mengenai Structured Query Language (SQL) dan dokumen teknis cara menggunakan/menjalankan SQL. Kaitannya dengan internal sistem DBMS mencakup pembahasan tentang Storage, Indexing, Tree-Structured Indexing, Multi-Dimensional Indexing, Hash-Based Indexing, dan External Sorting.

###### Week 1 - [Storage](https://docs.google.com/presentation/d/1zdPUK0oRs7aop4Kn-QQTnYZOemg-HjF_Hrjk6baZ-rg/edit?usp=sharing) (1)
>-	_memahami  konsep magnetic disk pada sistem komputer_
>-  _memahami kecepatan akses pada berbagai media akses dalam sistem komputer_
>-	_menjelaskan jenis RAID pada sistem penyimpanan_
>-	_menjelaskan perbedaan magnetic disk dan solid-state disk_

###### Week 2 - [Storage](https://docs.google.com/presentation/d/1zdPUK0oRs7aop4Kn-QQTnYZOemg-HjF_Hrjk6baZ-rg/edit?usp=sharing) (2)
>-	_memahami free space management_
>-	_menjelaskan pin pada proses baca tulis data pada memory_
>-	_mengetahui perbedaan antara DBMS dan sistem operasi_
>-	_memahami konsep dari heap files yang ada dalam page_

###### Week 3 - [Indexing](https://docs.google.com/presentation/d/1O7oxF0CwPjpBiijjLOrj2qx9eb8hwanP1gqmOMFeRYo/edit?usp=sharing) (1)
>-	_memahami konsep organisasi file dalam DBMS_
>-	_menjelaskan cost model yang memungkinkan terjadi pada operasi DBMS_
>-	_memahami proses scanning pada operasi DBMS_
>-	_mengerti tujuan dilakukan equality test pada masing-masing operasi_
>-	_memahami proses yang terjadi selama operasi range selection_

###### Week 4 - [Indexing](https://docs.google.com/presentation/d/1O7oxF0CwPjpBiijjLOrj2qx9eb8hwanP1gqmOMFeRYo/edit?usp=sharing) (2)
>-	_memahami algoritma yang umum digunakan dalam proses insertion_
>-	_memahami konsep deletion pada struktur index_
>-	_memahami konsep dari struktur index_
>-	_menjelaskan perbedaan antara clustered dan unclustered index_
>-	_memahami konsep dense dan sparse pada struktur index_

###### Week 5 - [Tree-Structured Indexing](https://docs.google.com/presentation/d/1uUQhF7oAS2HYQcFR8bzeo5tk2SbaEV6ntVJ9ne_H2ek/edit?usp=sharing) (1)
>-	_mereview kembali pemahaman tentang algoritma binary search_
>-	_memahami konsep umum dari ISAM_
>-	_menjelaskan konsep multi-level pada ISAM_
>-	_memahami kenapa konsep ISAM yang static masih baik digunakan_
>-	_menjelaskan efisiensi operasi pada pencarian_
>-	_memahami konsep dasar dari B+-trees_
>-	_menjelaskan konsep searching pada struktur index B+-trees_
>-	_menjelaskan konsep insert pada struktur index B+-trees_

###### Week 6 - [Tree-Structured Indexing](https://docs.google.com/presentation/d/1uUQhF7oAS2HYQcFR8bzeo5tk2SbaEV6ntVJ9ne_H2ek/edit?usp=sharing) (2)
>-	_memahami konsep distribusi node pada struktur index B+-trees_
>-	_memahami konsep delete pada struktur index B+-trees_
>-	_mengerti konsep duplicate node pada struktur index B+-trees_
>-	_memahami key compression pada struktur index B+-trees_
>-	_memahami bulk loading pada B+-trees_
>-	_mengerti model partisi pada B+-trees_

###### Week 7 - Quiz ([A](https://docs.google.com/forms/d/e/1FAIpQLScjODf8uljtewZVaw7m1DxrARUtln_2JCS1p-F6fv0i3wC0Rw/viewform?usp=sf_link)/[B](https://docs.google.com/forms/d/e/1FAIpQLSdQqef2jDdYd0t2ZmPCu_Y_Nl-ioio_MhpWZaDUM86aWB6gpg/viewform?usp=sf_link))
>-	_mahasiswa mampu memahami konsep baca/tulis data dari DBMS_
>-	_mahasiswa mampu memahami konsep dasar indexing pada DBMS_

###### Week 8 - [UTS](https://docs.google.com/forms/d/e/1FAIpQLSesfUro95JBYxViChjAssMvoDXtM_-OaDiYRHsklvBnr5e-FQ/viewform?usp=sf_link)

###### Week 9 - [Multi-Dimensional Indexing](https://docs.google.com/presentation/d/1xnA_0NIjhZhdv7VSkTWFtG5LR1Zl1nAWZWh1YWcMuRE/edit?usp=sharing) (1)
>-	_memahami konsep point quad trees_
>-	_memahami operasi search pada point quad trees_
>-	_memahami inserting data pada point quad trees_
>-	_memahami region queries pada point quad trees_
>-	_memahami balanced construction pada k-d trees_
>-	_memahami operasi-operasi yang ada pada K-D-B-Trees_
>-	_memahami splitting pada point dan region page di K-D-B Trees_

###### Week 10 - [Multi-Dimensional Indexing](https://docs.google.com/presentation/d/1xnA_0NIjhZhdv7VSkTWFtG5LR1Zl1nAWZWh1YWcMuRE/edit?usp=sharing) (2)
>-	_memahami konsep dasar R-Trees_
>-	_memahami konsep searching dan inserting pada R-Trees_
>-	_menjelaskan Bit Interleaving dan Z-Ordering pada UB-Trees_
>-	_memahami kaitan antara B+-trees dengan Z-Codes_
>-	_memahami range queries pada UB-Trees_
>-	_memahami konsep spaces pada tree yang memiliki dimensi yang banyak_

###### Week 11 - [Hash-Based Indexing](https://docs.google.com/presentation/d/13wqWz4iFHp-cgSSQTMOlwmtmWqRqIg-p_BBSVmakZfY/edit?usp=sharing) (1)
>-	_mereview kembali pemahaman tentang hash-based indexing_
>-	_memahami konsep dasar dari hash-based indexing_
>-	_menjelaskan static hash pada hash-based indexing_
>-	_memahami konsep fungsi pada hash-based indexing_
>-	_memahami konsep search pada hash-based indexing_
>-	_memahami konsep insertion pada hash-based indexing_

###### Week 12 - [Hash-Based Indexing](https://docs.google.com/presentation/d/13wqWz4iFHp-cgSSQTMOlwmtmWqRqIg-p_BBSVmakZfY/edit?usp=sharing) (2)
>-	_memahami procedures pada hash-based indexing_
>-	_menjelaskan tentang linear hashing_
>-	_memahami konsep insertion pada linear hashing_
>-	_memahami konsep procedures pada linear hashing_

###### Week 13 - External Sorting (1)
>-	_mereview kembali pemahaman terkait query SQL dalam DBMS_
>-	_mereview kembali pemahaman terkait algoritma sorting_
>-	_memahami konsep sorting pada DBMS_
>-	_memahami konsep two-way merge sorting_

###### Week 14 - External Sorting (2)
>-	_memahami external memory merge sorting_
>-	_memahami perbandingan antara two-way dan external sorting_
>-	_memahami konsep replacement pada operasi sorting_
>-	_menjelaskan kaitan antara B+-trees dan sorting_

###### Week 15 - Quiz (A/B)
>-	_mahasiswa mampu memahami konsep multi-dimensi indexing pada DBMS_
>-	_mahasiswa mampu memahami konsep sorting pada DBMS_

###### Week 16 - UAS