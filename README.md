# Lab2Web

```s
NAMA    : ALIYAH ASMARANI
NIM     : 312210203
KELAS   : TI.22.A.2
MATKUL  : PEMROGRAMAN WEB
SEMESTER 3
```

## 1. Membuat Dokumen HTML

### > Input / Code HTML
![image](https://github.com/Aliyahasmarani/Lab2Web/assets/115197672/c96e97b3-798a-4974-bd57-a7400244f95c)

### > Output (setelah dibuka di browser)
![image](https://github.com/Aliyahasmarani/Lab2Web/assets/115197672/903c3701-1eb9-4ef9-8fb7-a884ed6eafda)

## 2. Mendeklarasikan CSS Internal

### Kemudian tambahkan deklarasi CSS Internal pada head dokumen
![image](https://github.com/Aliyahasmarani/Lab2Web/assets/115197672/4240c867-42ff-407a-b007-863a9a605e06)

![image](https://github.com/Aliyahasmarani/Lab2Web/assets/115197672/0f75e78f-127b-4abc-8afb-b6cbe4b8ca33)

## 3. Menambahkan Inline CSS
Kemudian, tambahkan deklarasi inline CSS pada tag `<p>`
![image](https://github.com/Aliyahasmarani/Lab2Web/assets/115197672/a2242717-f499-43f5-895e-678c7cfc2ae7)

Save kembali dan refresh di browser. Dan lihat lah perubahannya
![image](https://github.com/Aliyahasmarani/Lab2Web/assets/115197672/a1f62de6-e9ea-4ba8-9439-e33bc0da12af)

## 4. Membuat CSS Eksternal

### > Kita buat file baru dengan nama file `style_eksternal.css`. kemudian buat deklarasi css sebagai berikut:

![image](https://github.com/Aliyahasmarani/Lab2Web/assets/115197672/1f460430-730a-4367-929f-2f7935bd97c9)

### > Kemudian, tambahkan tag `<link>` untuk memanggil file css yang sudah dibuat tadi pada bagian `<head>` di file css.

![image](https://github.com/Aliyahasmarani/Lab2Web/assets/115197672/1c5158ea-8614-4f8f-b5fc-2502955d0a35)

### > Dan inilah Output atau Hasil dari deklarasi css diatas:

![image](https://github.com/Aliyahasmarani/Lab2Web/assets/115197672/ab5a8db3-3906-49cb-9706-71a72661fd50)

## 5. Menambahkan CSS Selector

### > Selanjutnya, menambahkan CSS Selector menggunakan ID dan Class Selector pada file `style_eksternal.css` yang sebelumnya kita buat. lalu tambahkan kode berikut:

![image](https://github.com/Aliyahasmarani/Lab2Web/assets/115197672/f0c12875-5db7-4a4e-8747-782676b8e59e)

### > Output nya sebagai berikut:

![image](https://github.com/Aliyahasmarani/Lab2Web/assets/115197672/9f056b35-f7ac-464c-bf29-ebe6b50e8fa6)

## PERTANYAAN DAN TUGAS

### 1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini

```
Saya disini mencoba menaruh logo Universitas Pelita Bangsa di bagian kanan kiri header.
```
Input:

![image](https://github.com/Aliyahasmarani/Lab2Web/assets/115197672/26ea1531-f0be-4eb2-a509-bd6c23ac191d)

Output:

![image](https://github.com/Aliyahasmarani/Lab2Web/assets/115197672/dfb42162-b63b-4cc2-b814-781f2884d2bd)

### 2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!

```
Perbedaannya sangat signifikan diantara pendeklarasi CSS elemen h1 dengan #intro h1
Kalau Mendeklarasi hi {...} : Ini berarti setiap elemen <h1> akan diberi gaya yang sama sesuai dengan aturan yang diberikan dalam deklarasi tersebut.

> Kalau Mendeklarasi #intro h1 {...} : Deklarasi CSS ini akan mempengaruhi elemen <h1> yang terdapat dalam elemen dengan ID "intro". Dalam hal ini, elemen <h1> hanya akan menerima aturan gaya jika mereka berada dalam struktur hierarki di bawah elemen dengan ID "intro". Ini berarti elemen-elemen <h1> yang berada di luar struktur ini tidak akan terpengaruh oleh aturan gaya ini.
```

### 3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!
```
Singkatnya, urutan prioritas penampilan CSS adalah: Inline CSS > Internal CSS > External CSS. Namun, dalam semua kasus, urutan dalam dokumen HTML juga dapat mempengaruhi bagaimana CSS diterapkan jika tingkat spesifikasitasnya sama.
```

Contohnya sebagai berikut:

Code Inline:
![image](https://github.com/Aliyahasmarani/Lab2Web/assets/115197672/4dae4398-52aa-4f5c-aa3d-d90cec184149)

Code Eskternal:

![image](https://github.com/Aliyahasmarani/Lab2Web/assets/115197672/128266e6-1cca-49f7-97b9-24945a62f4a2)

Jika kita memakai keduanya, maka yang akan muncul hanya yang di inline. yang dieksternal tidak akan terpakai.

### 4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya! `( <p id="paragraf-1" class="text-paragraf"> )`

```
Ketika sebuah elemen HTML memiliki ID dan class, CSS akan mengatur tampilan elemen tersebut berdasarkan kedua selector tersebut. Namun, ada aturan prioritas yang menentukan deklarasi mana yang akan diaplikasikan oleh browser. Aturan ini disebut "Specificity."
```

CONTOH:

Code HTML:
![image](https://github.com/Aliyahasmarani/Lab2Web/assets/115197672/7e13b29e-0565-4e49-acdf-ed37f8c35bf6)

Code CSS:
![image](https://github.com/Aliyahasmarani/Lab2Web/assets/115197672/f8613e3a-9f0f-42e5-ab1f-d4f886d7610a)

Output:
![image](https://github.com/Aliyahasmarani/Lab2Web/assets/115197672/33e190fe-0733-4540-a373-bbb18e9e451e)

```
Dalam contoh ini, teks pada elemen <p> akan ditampilkan dengan warna biru karena deklarasi CSS yang menggunakan ID memiliki spesifikitas lebih tinggi daripada deklarasi yang menggunakan class. Jadi, browser akan mengikuti aturan spesifikitas CSS dan mengaplikasikan deklarasi CSS dengan ID.
```













