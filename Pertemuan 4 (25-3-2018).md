
Hal-hal yang dilakukan hari ini:
1. Penjelasan mengenai Networking.
2. Meng-install beberapa app yang berhubungan dengan Networking.
3. Peragaan cara menggunakan Wireshark.
4. Simulasi pengerjaan CTF dengan materi Trivia dan Networking.


Cara mendapatkan Flag dari beberapa soal simulasi CTF
- Soal Welcome
    Flag tertera di soal.

  1.
    Port yang berhubungan dengan https?
    Jawabannya ada di penjelasan Mas Satria sebelumnya.
    Tetapi karena saya lupa, saya akhirnya searching hehe.
  2.
    Webserver yang digunakan oleh web yang tertera di link?
    Seharusnya bisa diselesaikan dengan menggunakan inspect elemen.
    Tetapi waktu itu saya mendapatkan jawabannya dengan memasukkan alamat web tersebut ke web yang memiliki tool untuk mengetahui webserver yang digunakan oleh alamat web yang di-input.
    3.
      Soal yang meminta kita untuk menemukan username/password/flag di sebuah file pcap(?).
      Caranya adalah dengan membuka file tersebut dengan wireshark lalu manfaatkan menu search.
      Voila, there's the flag!
    4.
      Soal yang meminta kita untuk mengetahui file misterius yang di-download orang dari catatan file pcap(?)-nya.
      Lakukan export object dari file pcap(?) tersebut dan BOOM! itu flag-nya keliatan.
      Saat itu saya tidak berhasil memecahkan soal ini karena saat meng-export object-nya,
      saya tidak langsung menyimpannya dengan extensi yang benar.
      Melainkan menyimpannya sebagai "all files".
      Ternyata hal tersebut menyebabkan hex-code dari file tersebut berubah sehingga file menjadi corrupt dan tidak bisa dibuka.
    5.
      Soal ssh.
      Saya tidak berhasil mengerjakan soal ini karena kurangnya pengetahuan saya mengenai penggunaan ssh.
      Ternyata caranya adalah mengetikkan "ssh username@ipaddress" lalu input password-nya.
      Setelah itu silahkan cari-cari file yang berisi flag-nya.
      Ilmu baru lainnya adalah cara membuka file yang berawalan "-" di terminal.
      Caranya adalah dengan menuliskan alamatnya. Contoh: "cat ~/-Readme.txt" (kalo ndak salah seh gitu).
