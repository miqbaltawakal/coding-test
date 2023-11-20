# Software Engineer (Fullstack) Test

### Komunitas Z saat ini sedang mencari talenta terbaik bangsa untuk diberikan pelatihan secara gratis, untuk kemudian mengabdi kepada bangsa dan negara. Komunitas tersebut membutuhkan data untuk diseleksi dalam beasiswa yang sedang mereka laksanakan.

Buatlah sebuah form yang dapat mengakomodasi data sebagai berikut:

|      Data     |     Tipe      | Keterangan |
| ------------- | ------------- |------------|
| Nama  | String  | 
| NIK  | Number  |
| No. KK  | Number  |
| Foto KTP  | File  | Maksimal 2MB, format JPG/JPEG/PNG/BMP |
| Foto KK  | File  | Maksimal 2MB, format JPG/JPEG/PNG/BMP |
| Usia  | Number  | Berumur lebih dari atau sama dengan 25 tahun |
| Foto KTP  | File  |
| Jenis Kelamin  | Enum  |
| Foto KTP  | File  |
| Provinsi  | Enum / String  | Berisikan pilihan seluruh Provinsi di Indonesia atau diisi secara bebas tanpa pilihan |
| Kab/Kota  | Enum / String  | Berisikan pilihan seluruh Kab/Kota berdasarkan Provinsi yang dipilih atau diisi secara bebas tanpa pilihan |
| Kecamatan  | Enum / String  | Berisikan pilihan seluruh Kecamatan berdasarkan Kab/Kota yang dipilih atau diisi secara bebas tanpa pilihan |
| Kelurahan/Desa  | Enum / String  | Berisikan pilihan seluruh Kelurahan berdasarkan Kecamatan yang dipilih atau diisi secara bebas tanpa pilihan |
| Alamat  | String  | Tidak lebih panjang dari 255 karakter |
| RT  | String/Number  |
| RW  | String/Number  |
| Alasan Mengikuti Tujuan Beasiswa | String | - Berkontribusi sebagai WNI <br> - Melanjutkan cita-cita <br> - Tergolong keluarga yang kurang mampu, atau <br> - lain-lain: … (bisa diisi sendiri) |

Setiap data bersifat <b>required (harus diisi)</b>. Sebelum data di-submit dalam aplikasi, pemohon harus mencentang kolom yang bertuliskan:
>`Saya menyatakan bahwa data yang diisikan adalah benar dan siap mempertanggungjawabkan apabila ditemukan ketidaksesuaian dalam data tersebut.`

### Ketentuan:
- Boleh menggunakan bahasa Javascript. Stack/framework/library bersifat bebas.
- Jika peserta membuat kolom Provinsi, Kab/Kota, Kecamatan dan Kelurahan menjadi pilihan daftar wilayah gunakan emsifa API Service (Free Service) . Dokumentasinya ada pada tautan berikut https://www.emsifa.com/api-wilayah-indonesia/
- Tidak perlu membuat backend service. Cukup simulasikan saja proses pengiriman yang memakan waktu respon sesuai yang telah dijelaskan. Biasanya jangka waktu respon untuk form tersebut adalah 1500 milisekon.
- Sukses atau gagalnya pengiriman dapat disimulasikan menggunakan Math.random().
- Data form yang di-submit wajib ditampilan pada suatu halaman (halaman preview data).
- Projek wajib disimpan dalam <b>public repository</b> Git, boleh di Github, Gitlab, atau hosting lainnya.
- Projek di-hosting menggunakan hosting service, misalnya Github Pages/Netlify/Surge/Render/Firebase Hosting/dsb. Disarankan menggunakan service yang menyediakan free-tier plan (tidak berbayar).

### Catatan:
1. Readable code and easy to understanding.
1. Push to Git (Github/Gitlab) Repository; Commit history check sample (http://karma-runner.github.io/4.0/dev/git-commit-msg.html)

Submit your Git (Github/Gitlab) Repository URL (Public) to email:
(lingkarrasioteknologi@gmail.com / muhammad.tawaqall@gmail.com)
