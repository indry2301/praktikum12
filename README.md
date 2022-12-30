# praktikum12
# Pengertian String pada Python
String adalah jenis yang paling populer di bahasa pemrograman. Kita bisa membuatnya hanya dengan melampirkan karakter dalam tanda kutip. Python memperlakukan tanda kutip tunggal sama dengan tanda kutip ganda. Membuat string semudah memberi nilai pada sebuah variabel.
# Escape Characters Python
Dibawah ini adalah tabel dari daftar karakter escape atau karakter non-printable yang dapat diwakili/ditulis dengan awalan notasi backslash.
- \a untuk bell atau alert.
- \b untuk backspace.
- \n untuk newline.
- \s untuk space.
- \t untuk tab.
# Operator Spesial String Python
- "+" Menambahkan nilai pada kedua sisi operator.
- "*" Membuat string baru, menggabungkan beberapa salinan dari string yang sama.
# Source Code:
![carbon (1)](https://user-images.githubusercontent.com/115906333/210037679-9d7fd723-5ea5-48fb-ba52-c2ca0b55da67.png) 
# Penjelasan setiap program:
- Untuk menghitung jumlah karakter, gunakan fungsi len().
     print(len(txt))
- Cara mengambil satu karakter pada string yaitu dengan menggunakan kurung siku [] dan deklarasi nomor di dalam kurung siku dengan urutan ARRAY dan menggunakan titik dua lalu masukan nomor ARRAY selanjutnya. Untuk mengambil karakter terakhir, gunakan *index [-1]**. Sedangkan untuk mengambil karakter *index ke-2 sampai ke-4, gunakan index [2:5].
     print(txt[-1])
     print(txt[2:5]) 
- Jika ingin menghilangkan spasi pada string, gunakan method replace(). Method replace() mengganti semua kemunculan string lama dengan yang baru atau paling banyak kemunculan.
- Di dalam method replace, kita dapat menggunakan 2 cara, yang pertama bisa menggunakan (txt.replace(" ", "")) dan kedua dengan cara (txt.replace(txt[5], "")).
     print(txt.replace(" ", " "))
- Untuk mengubah text menjadi huruf besar, gunakan method upper(). Sedangkan jika ingin mengubah text menjadi huruf kecil, menggunakan method lower().
     print(txt.upper())
     print(txt.lower())
- Untuk mengganti karakter 'H' menjadi karakter 'J', gunakan method replace().
     print(txt.replace("h", "J"))
     print()
# Outputnya seperti ini:
![Screenshot (295)](https://user-images.githubusercontent.com/115906333/210037701-6231d3ae-a42d-4e7d-a921-5c2848eef164.png)

