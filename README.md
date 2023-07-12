Introduction
Taksi hijau (Green Cab/ Boro Taxis) adalah salah satu jenis kendaraan umum di Kota New York untuk melayani perjalanan penumpang dari suatu tempat ke tempat lain. Taksi hijau ini mulai beroperasi sejak bulan Agustus 2013 dan dilisensikan oleh TLC (Taxi and Limousine Commission), sebuah badan pemerintahan di Kota New York. Permintaan layanan perjalanan dari taksi ini bisa dipesan langsung di jalan (street-hail) atau dipesan melalui panggilan ke pangkalan (dispatch). Zona perjalanan yang dapat dilalui oleh taksi hijau tersebar di beberapa wilayah (borough) Kota New York, yaitu Manhattan, Bronx, Brooklyn, Queens, dan Staten Island. Aturan zona perjalanan untuk taksi hijau dapat dilihat melalui link berikut: https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page. 

Problem Background
Dari data yang sudah dilakukan cleaning sebelumnya, penulis tertarik untuk mengamati rute perjalanan yang sering dilalui taksi hijau untuk setiap wilayah (Borough) dengan periode perjalanan dimulai dari tanggal 1 Januari - 31 Januari 2023. Informasi awal yang ingin didapatkan yaitu apakah rute perjalanan yang sering dilalui taksi untuk setiap wilayah, terpusat di satu lokasi, dua lokasi, atau bahkan lebih. Ada kemungkinan dimana rute perjalanan terpusat pada 2 lokasi 'bolak-balik' yaitu rute perjalanan yang sering dilalui dari A ke B dan sebaliknya dari B ke A. Jika temuan (insight) tersebut benar adanya maka temuan ini mungkin akan berguna bagi supir taksi hijau (stakeholder) dalam menentukan lokasi yang tepat untuk mencari penumpang sehingga dapat memaksimalkan pesanan yang diterima, tentunya dengan mengikuti aturan zona perjalanan yang telah ditentukan. Sebagai ilustrasi ketika supir taksi telah mengantarkan penumpang dari tempat A ke tempat B, tidak butuh waktu yang lama supir taksi mendapatkan pesanan kembali dari tempat B ke tempat A, begitu juga sebaliknya. Tentu terdapat faktor luar yang dapat mempengaruhi cepat lambatnya supir taksi mendapatkan pesanan salah satunya dari banyaknya mobil yang tersedia di suatu lokasi atau wilayah, namun dalam analisis ini kita dapat mengesampingkan faktor-faktor tersebut (Project Limitation). Hasil dari analisis yang dilakukan mungkin akan berdampak pada jumlah mobil yang dapat mengalami penumpukkan di suatu lokasi, namun hasil analisis ini semata-mata hanya untuk memberikan informasi secara umum bahwa dalam mencari penumpang ada kemungkinan (peluang) supir taksi lebih cepat dalam mendapatkan pesanan dengan melihat riwayat perjalanan yang telah dilakukan sebelumnya di lokasi tersebut.

Business Problem
Banyaknya pesanan yang diterima oleh supir taksi hijau tentunya tidak lepas dari bagaimana cara supir taksi hijau mendapatkan penumpang. Terdapat dua cara supir taksi hijau mendapatkan penumpang yaitu dengan langsung mencari penumpang di pinggir jalan atau menunggu pesanan masuk dari penumpang di suatu pangkalan. Tentunya cara-cara tersebut bisa dimaksimalkan dengan memperhatikan kondisi (tempat dan waktu) agar lebih cepat mendapatkan penumpang. Sebagai seorang supir taksi tentunya ingin memaksimalkan pesanan yang diterima dari segi waktu untuk mendapatkan pesanan kembali.

Business Task
Menentukan kondisi yang tepat bagi supir taksi hijau agar lebih dapat memaksimalkan pesanan yang diterima untuk setiap masing-masing wilayah (Borough) dengan melihat riwayat perjalanan taksi hijau di bulan Januari.

Project Organization
------------

    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── processed      <- The final, canonical data sets for analysis.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- The document will consist of a detailed analysis and visualization.
    │
    ├── notebooks          <- Jupyter notebooks. A naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    └── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
                              generated with `pip freeze > requirements.txt`

--------