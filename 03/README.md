# Pengenalan Model Bahasa Besar

1. Pelajari dan Pahami teori yang ada [disini](https://rpradeepmenon.medium.com/introduction-to-large-language-models-and-the-transformer-architecture-534408ed7e61)
2. Kuasai tutorial tentang [LLM di python](https://huggingface.co/docs/transformers/llm_tutorial)

# Penguasaan Bahasa Pemrograman Rust
1. Latihan sebanyak 8 jam mengikuti buku [8 Jam Belajar Rust](./8jamrust.pdf) sertakan buktinya. (nilai:5)
2. Praktekkan ownership,reference,borrowing,clone,copy,scope,mutable,dangling,slice disertakan contoh deklarasi dan contoh penggunaannya sebanyak 10 contoh. (nilai:5)
   - ownership adalah fitur rust yang memastikan memori dikelola dengan aman.
   - reference adalah cara untuk meminjam nilai tanpa mengambil kepemilikan.
   - borrowing adalah konsep meminjam nilai dari pemiliknya.
   - clone adalah  cara untuk membuat salinan yang mendalam dari suatu nilai.
   - copy adalahtrait yang dapat diterapkan pada tipe data yang berukuran tetap dan dapat disalin bit demi bit.
   - scope adalah jangkauan dimana suatu variabel valid dan tersedia.
   - mutable adalah memungkinkan modifikasi data  yang diacu. deklarasikan menggunakan kata kunci mut.
   - dangling adalah referensi yang menunjuk ke lokasi memori yang telah dibebaskan atau tidak valid.
   - slice adalah bagian dari koleksi yang kontinu seperti array.
4. Praktekkan contoh pembuatan dan pemanggilan struct dan function sebanyak 10. (nilai:5)
5. Praktekkan cara memisahkan fungsi dan memanggilnya dari file berbeda di rust. (nilai:5)
6. Praktekkan cara penggunaan dan perbedaan perintah cargo run dan cargo build, serta penjelasan setiap baris di file cargo.toml. (nilai:5)
     - cargo build digunakan untuk mengkomplasi kode tanpa menjalankan program.
     - cargo run digunakan untuk mengkompilasi kode (jika diperlukan) dan menjalankan executable yang dihasilkan.
8. Jelaskan kegunaan crates.io. (nilai:5) Crates.io adalah repositori online untuk proyek-proyek Rust. Ini adalah tempat di mana pengembang Rust dapat membagikan dan menemukan paket-paket (dikenal sebagai "crates") yang dapat digunakan dalam pengembangan perangkat lunak mereka.  
9. Jelaskan perbedaan membuat library dan file utama di rust. (nilai:5)
    library = terdiri dari beberapa modul dan fungsi-fungsi yang bisa dipanggil oleh kode di luar library.
    file utama = untuk membuat aplikasi yang mandiri atau program yang berdiri sendiri.
11. Praktekkan membuat web service di rust dengan panduan dari [inarust.github.io](https://inarust.github.io/). (nilai:5)


# Penguasaan Hugging Face

1. Jelaskan apa itu Hugging Face Candle dan praktekkan cara penggunaannya.(nilai : 10) Hugging Face Candle adalah sebuah proyek open-source yang dikembangkan oleh Hugging Face untuk menyediakan library yang kuat dan mudah digunakan untuk pengembangan dan penelitian dalam bidang Natural Language Processing (NLP) dan Deep Learning. 
2. Jelaskan per baris kode program dan jalankan [phi](https://github.com/mymyid/phi). (nilai:10)
3. Jelaskan per baris kode program dan jalankan [rwkv](https://github.com/mymyid/rwkv). (nilai:10)
4. Jelaskan per baris kode program dan jalankan [mistral](https://github.com/mymyid/mistral). (nilai:10)
5. Analisis perbedaan dari ketiga model llm tersebut dari waktu generasi kalimat, akurasi dan kebutuhan komputasinya. (Nilai : 10)
6. Jealskan bagaimana cara mengatasi error di rust pada saat menjalankan aplikasi ini. (Nilai : 10)
