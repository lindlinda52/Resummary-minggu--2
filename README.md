 # Resummary Two week
1. **JavaScript dasar - introduction**
- Javascrip yaitu bahasa pemograman dan juga dapat membuat website menjadi interaktif dan dinamis.
- Ada 6 tipe data fundamental pada Javascript:
1. Number:Tipe data number adalah tipe data yang mengandung semua angka. contoh angkat pada KTP
2. string:identik dengan simbol single quotes('')/ double quotes("") yang ada pada PC keyboard kita.
3. boolean: yang hanya mempunyai 2 buah nilai.
2 buah nilai tersebut adalah TRUE (benar) or FALSE (salah).
4. null: diartikan tidak memiliki nilai atau sama dengan 0
5. Undifined:Tipe data undefined adalah tipe data yang merepresentasikan varibel/data yang tidak memiliki nilai.
6. object:Tipe data pbject dapat menyimpan data dengan tipe data apapun (number, string, boolean, dan lainnya).

**Ada 3 cara mendefinisikan sebuah variabel**
- var : tempat untuk menyimpan sebuah nilai
- let :  let digunakan untuk variabel yang dinamis/dapat diubah
- const : tidak dapat merubah value dari sebuah constant variable. Biasanya digunakan untuk menggambarkan konstanta sebuah nilai. Seperti konstanta pi = 3.14.

- **Arithmetic operator adalah operator yang melibatkan operasi matematika**.

| Operator |Arithmetic |
| ----------- | ----------- |
| Perkalian | * |
| Penjumlahan | + | 
|Pengurangan | _ |
| Pembagian | / |
|Modulus | % |

```
//Perkalian
function perkalian(bil1, bil2) {
    return bil1 * bil2;
  }
  console.log(perkalian(20, 5))

//Penjumlahan

function Penjumlahan(nilai1, nilai2){
    return nilai1-nilai2;
}
    console.log(Penjumlahan(500,200))
//pengurangan

function Pengurangan(nilai1, nilai2){
    return nilai1-nilai2;
}
    console.log(Pengurangan(50,20))

//pembagian
  function pembagian(nilai1, nilai2){
    return nilai1/nilai2;
}
  console.log(pembagian(80,20))

//Modulus
function modulus(nilai1, nilai2){
    return nilai1 % nilai2;
}
  console.log(modulus(5,2))
```
- **nilai1 & nilai2 termasuk parameter sedangkan angka adalah argument contoh 80,20** 

- **Comparison Operator**
- Comparison operator yaitu operator yang dimana membandingkan antara nilai satu dengan nilai lainnya.
dan hasil operasi yang melibatkan comparison operator adalah antara true or false.

Simbol |Comparison operator |
| ----------- | ----------- |
Lebih kecil dari : <
Lebih besar dari: >
Lebih kecil atau sama dengan: <=
Lebih besar atau sama dengan: >=
Sama dengan: ===
Tidak sama dengan: !==

## JAVASCRIPT - SCOPE
- Scope adalah Menentukan suatu variabel bisa diakses pada scope tertentu atau tidak.

- Di dalam scope terdapat Global & lokal, global adalah yang berarti variabel yang kita buat dapat diakses dimanapun dalam suatu file dan Agar menjadi Global Scope, suatu variabel harus dideklarasikan diluar Blocks. sedangkan Lokal Scope yang berarti kita mendeklarasikan variabel didalam blocks seperti function, conditional, dan looping, itu artinya variabel hanya bisa di akses di dalam blocks saja.
 
### JAVASCRIPT - FUNCTION
-Apa itu function pada Javascript: Fungsi JavaScript adalah blok kode yang dirancang untuk melakukan tugas tertentu yang dijalankan ketika "sesuatu" memanggilnya (memanggilnya).

-Ex:
```
function myFunction(p1, p2) {
  return p1 * p2;   // maka fungsi tersebut mengembalikan produk dari p1 and p2 ketika kita memanggil myFunction.
}
```

| Parameter |Argument|
| ----------- | ----------- |
| Parameter fungsi tercantum di dalam tanda kurung () dalam definisi fungsi.|Argumen fungsi adalah nilai yang diterima oleh fungsi saat dipanggil.
|Contoh Syntax: Fungsi Penambahan |
 
 ```
 function penambahan(x, y) {
   return x + y
}

console.log(penambahan(2, 4)) // dari contoh ini yang disebut parameter adalah (x,y) setelah function var penambahan sedangkan argument yaitu nilai (2,4).
```

#### DOM 
- Dom merupakan singkatan dari Document Object Model yang dimana Dengan adanya DOM ini, JavaScript diberi akses untuk membuat HTML menjadi dinamis, seperti:

1. Mengubah element HTML pada halaman website.
2. Mengubah attribute HTML pada halaman website.
3. Mengubah CSS style pada halaman website.
4. Menambah dan/atau menghapus element maupun attribute HTML.
5. Menambah HTML event (contoh: efek klik pada mouse, hover pada mouse, dan lain-lain) pada halaman website.
6. Berinteraksi dengan semua HTML event di website. 

* Ketika kita ingin mengubah nilai properti dari element HTML, kita bisa menggunakan DOM Property dan untuk memanggil fungsi dari suatu element HTML, kita bisa menggunakan DOM Method.

### Misalnya kita mempunyai element HTML sebagai berikut:
```
<input id="umur" type="text" value="20" />
Untuk mengakses value dari <input> di atas, maka bisa dilakukan dengan cara sebagai berikut:

let umur = document.getElementById("umur").value;

console.log(umur); // Output: 20
```
*Penjelasan kode di atas
 document adalah akar dari semua objek di sebuah website. Jadi untuk mengakses element HTML apapun di satu website, selalu dimulai dengan objek document ini.
getElementById merupakan method dari objek document.
value merupakan properti dari objek element HTML yang dikembalikan dari method getElementById yaitu ``` <input> ```*


| Macam" DOM Method |Untuk Mengakses Element HTML|
| ----------- | ----------- |
| getElementById(id) | *Method yang ini sudah kita lihat beberapa kali dari contoh-contoh sebelumnya. Kita bisa menggunakan getElementById untuk mengakses element HTML berdasarkan nilai id-nya.* |
| getElementsByTagName(tag) | *Untuk mengakses element-element HTML berdasarkan jenis tag-nya, kita bisa menggunakan getElementsByTagName.* | 
|getElementsByClassName(className) | *Untuk mengakses element-element HTML berdasarkan nilai attribute class-nya, kita bisa menggunakan getElementsByClassName.* |
| querySelectorAll(cssSelector) | *Untuk mengakses element-element HTML berdasarkan CSS Selector-nya HTML, kita bisa menggunakan querySelectorAll.*|










  
 


