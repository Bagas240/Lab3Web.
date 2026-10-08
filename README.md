# Laporan Praktikum 3 

Nama : Bagas Arya Ramadhan 
Nim : 312510328
Kelas : I251D

---

### 1. Membuat Dokumen HTML

![image alt](https://github.com/Bagas240/Lab3Web./blob/main/image/Screenshot%202026-10-08%20223355.png?raw=true)

enjelasan

Kode tersebut merupakan struktur awal halaman web sebelum diberikan styling CSS.

Elemen <header> digunakan untuk bagian judul halaman, sedangkan <nav> digunakan sebagai bagian navigasi. Bagian `<div id="intro">` nantinya digunakan sebagai target ID Selector.

Pada bagian tombol terdapat dua class, yaitu button dan btn-primary. Kedua class tersebut nantinya akan digunakan untuk memberikan style menggunakan Class Selector.

### 2. Menambahkan CSS Internal

![image alt](https://github.com/Bagas240/Lab3Web./blob/main/image/Screenshot%202026-10-08%20223604.png?raw=true)

CSS Internal ditulis langsung di dalam dokumen HTML menggunakan tag `<style>` yang ditempatkan pada bagian `<head>.`

Pada kode tersebut:

`body` mengatur jenis font halaman.
`header` mengatur tinggi minimum dan garis bawah header.
`h1` mengatur ukuran, warna, posisi teks, dan padding judul.
`h1 i` memberikan style khusus pada elemen` <i>` yang berada di dalam` <h1>.`

Dengan CSS Internal, tampilan halaman mulai berubah tanpa harus membuat file CSS terpisah.

### 3. Menambahkan Inline CSS

![image alt](https://github.com/Bagas240/Lab3Web./blob/main/image/Screenshot%202026-10-08%20223401.png?raw=true)

Penjelasan

Inline CSS merupakan CSS yang ditulis langsung pada tag HTML menggunakan atribut `style.`

Pada kode tersebut terdapat dua property:

`text-align: center;` digunakan untuk membuat teks berada di tengah.
`color: #ccd8e4;` digunakan untuk memberikan warna pada teks.

Berbeda dengan Internal dan External CSS, Inline CSS secara langsung diterapkan pada elemen HTML tertentu.

### 4. Membuat CSS Eksternal

![image alt](https://github.com/Bagas240/Lab3Web./blob/main/image/Screenshot%202026-10-08%20223800.png?raw=true)

Penjelasan

Selector `nav` digunakan untuk mengatur tampilan area navigasi.

Selector `nav a` digunakan untuk mengatur link yang berada di dalam navigasi.

Sementara itu:

`nav a:hover`

digunakan untuk memberikan perubahan tampilan ketika cursor diarahkan ke link navigasi.

Dengan External CSS, aturan styling tidak lagi ditulis langsung di file HTML sehingga kode menjadi lebih terorganisir.

### 5. Menghubungkan CSS Eksternal dengan HTML


![image alt](https://github.com/Bagas240/Lab3Web./blob/main/image/Screenshot%202026-10-08%20223833.png?raw=true)

Penjelasan

Atribut `rel="stylesheet"` menunjukkan bahwa file yang dihubungkan merupakan stylesheet.

Atribut `href` menunjukkan lokasi atau nama file CSS yang akan digunakan.

Dengan demikian, aturan CSS yang berada di `style_eksternal.css` dapat diterapkan pada halaman HTML.

### 6. Menambahkan ID Selector

![image alt](https://github.com/Bagas240/Lab3Web./blob/main/image/Screenshot%202026-10-08%20223940.png?raw=true)

Penjelasan

ID Selector ditandai dengan simbol `#.`

Pada kode tersebut:

`#intro`

digunakan untuk memilih elemen HTML yang memiliki:

`id="intro"`

Sedangkan:

`#intro h1`

digunakan untuk memilih elemen `<h1>` yang berada di dalam elemen dengan ID `intro.`

CSS tersebut memberikan background, border, tinggi minimum, padding, serta pengaturan warna dan posisi judul.

### 7. Menambahkan Class Selector

![image alt](https://github.com/Bagas240/Lab3Web./blob/main/image/Screenshot%202026-10-08%20224002.png?raw=true)

Penjelasan

Class Selector menggunakan tanda titik `(.)` sebelum nama class.

Pada kode:

`.button`

CSS diterapkan kepada elemen yang memiliki:

`class="button"`

Kemudian:

`.btn-primary`

digunakan untuk memberikan background tambahan pada elemen yang memiliki class `btn-primary.`

Pada HTML sebelumnya terdapat:

`<a class="button btn-primary" href="#intro">
    Informasi selengkapnya.
</a>`

Artinya satu elemen dapat menggunakan lebih dari satu class. Class `button` memberikan style dasar tombol, sedangkan `btn-primary` memberikan warna background khusus.

### 8. Screenshoot Live Server 1 

![image alt](https://github.com/Bagas240/Lab3Web./blob/main/image/Screenshot%202026-10-08%20224238.png?raw=true)

### 9. Screenshoot Liver Server 2

![image alt](https://github.com/Bagas240/Lab3Web./blob/main/image/Screenshot%202026-10-08%20224042.png?raw=true)

### 9. Screenshoot Liver Server 3

![image alt](https://github.com/Bagas240/Lab3Web./blob/main/image/Screenshot%202026-10-08%20224122.png?raw=true)

### 10. Screenshoot Liver Server 4

![image alt](https://github.com/Bagas240/Lab3Web./blob/main/image/Screenshot%202026-10-08%20230410.png?raw=true)

