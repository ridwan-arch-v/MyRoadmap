# Js statement

## Referensi

📚 Materi ini diambil dan dirangkum dari [W3Schools](https://www.w3schools.com)  
![W3Schools](https://img.shields.io/badge/W3Schools-Reference-blue)

## Disclaimer

**Author banyak Mnegambil referensi di [w3schools](https://www.w3schools.com)**

---

## Apa Itu Js Stattement

jadi gampang nya gini, itu kayak bagaiman cara kita memberikan intruksi ke computer.
misal gini kalian punya kawan yang ga ngerti bahasa kalian, tapi kakau kalian pakai bahsa
isyarat atau bahasa yg dia ngerti pasti dia bakal tau nah sama juga kyak gini.

## Apa Aja Statement Di js?

nah di js itu sebenarnya ada banyak statement:
mulai dari `velue`,`Operators`,`KeyWord`,`Expression`,`Comment`
Oke kita bahas 1 per satu ygy

---

### 1.1 Velue ( Nilai )
jadi si velue ini ada 3 bagian yg berbeda yaitu :
<<<<<<< HEAD
- `string`
- `number`s
- bolean

apa itu `string` num dan bolean?

#### A. String
`string` itu adalah code yang berbentuk text bebas dan `string` juga itu di tandai dnegfan text yang di awali oleh tanda `"text"` atau `'text'` sma aja 
=======
- string
- numbers
- bolean

apa itu string num dan bolean?

#### A. String
string itu adalah code yang berbentuk text bebas dan string juga itu di tandai dnegfan text yang di awali oleh tanda `"text"` atau `'text'` sma aja 
>>>>>>> main

**Sintax Tring**

```js
<<<<<<< HEAD
console.log("im a `string`")
```

#### B. `numbers`
kalau ini itu kebalikan nya dari `string` kalau sting kan text atau huruf ya nah tapi kalau numbres ini itu adalah bilangn atau angka

**Sintax `numbers`**
=======
console.log("im a string")
```

#### B. Numbers
kalau ini itu kebalikan nya dari string kalau sting kan text atau huruf ya nah tapi kalau numbres ini itu adalah bilangn atau angka

**Sintax Numbers**
>>>>>>> main

```js
a = 1;
b = 2;
c = a + b;
console.log(c + 5) //Output Nya 8
```

#### C. Bolean
<<<<<<< HEAD
kalau bolean ini itu campuran atau gabungan antara `string` dan num tapi bedanya dia itu cuman bisa antara
=======
kalau bolean ini itu campuran atau gabungan antara string dan num tapi bedanya dia itu cuman bisa antara
>>>>>>> main
> [!NOTE]
> Jadi ke empat Nilai Ini adalah bolean 0 dan true itu smaa dan 1 dengan true juga sama funginya
> `0`,`1`,`true`,`false`

**Sintax Bolean**

```js
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Car Lock Simulation</title>
</head>
<body>
    <h2>Car Lock Simulation</h2>
    <button onclick="checkCarStatus()">Check Car Status</button>
    <button onclick="unlockCar()">Unlock Car</button>
    <button onclick="lockCar()">Lock Car</button>
    <p id="statusMessage"></p>

    <script>
        let carLocked = true;

        function checkCarStatus() {
            if (carLocked) {
                document.getElementById("statusMessage").textContent = "The car is locked.";
            } else {
                document.getElementById("statusMessage").textContent = "The car is unlocked.";
            }
        }

        function unlockCar() {
            if (carLocked) {
                carLocked = false;
                document.getElementById("statusMessage").textContent = "The car is unlocked.";
            } else {
                document.getElementById("statusMessage").textContent = "The car is already unlocked.";
            }
        }

        function lockCar() {
            if (!carLocked) {
                carLocked = true;
                document.getElementById("statusMessage").textContent = "The car is locked.";
            } else {
                document.getElementById("statusMessage").textContent = "The car is already locked.";
            }
        }
    </script>
</body>
</html>
```

---

<<<<<<< HEAD
## 1.2 Opeator ( tugas )

**apa itu operator**
operator adalah suatu simbol yang kita gunakan untuk mengoprasikan variabel.
oepartor juga ada bayak jenis nya ada oepartor aritmatika ada oprator logika dan maish banyak lagi.
oke kali inikita bahsa yg mudha mudah aja dulu
oke di bawha ini adalah list unk operator dasar javascript

### `+` = penjumlahan [read more](#tambah)

### `-` = pengurangan [read more](#kurang)
  
### `*` = perkalian [read more](#kali)
  
### `/` = pembagian [read more](#bagi)
  
### `==` = logika sama dengan [read more](#samadengan)
  
### `&&` = logika dan [read more](#dan)
  
---

### EXAMPLE  
<div id="tambah">
    <h3>contoh untuk penjumlahan</h3>


**Penjumlahan** (+):
Antara dua angka (`number`): kalau yag di operasikan itu `number` dan `number` maka output nya itu kayak matematika kehitung nya

```js

let a = 5;
let b = 3;
let result = a + b; // 8
```

**Antara `string` dan angka** (`number` + `string`):  kalau dalam kondisi ini misal ada `string` dan `number`s maka `string` aka tetap menjadi `string` tetapi `number` akan di ubah menjadi `string` bukan anggka

```js

let a = "Hello";
let b = 5;
let result = a + b; // "Hello5"
```

**Antara dua `string`**: misal yg di tambha itu `string` maka `string` nya bakal di gabung

```js
let a = "Hello";
let b = " World";
let result = a + b; // "Hello World"
```

>[!NOTE]
>kalau penjumlahan ini kita bisa mengoprasikan antara `string` dan num maupun sebalik nya
</div>

---

<div id="kurang">
    <h3>contoh untuk pengurangan</h3>

**Pengurangan (-)**:
misal yang di opearikan itu angka dan angka maka sistem akan mengoprasikan sebagai tugas matematika

```javascript
let a = 10;
let b = 3;
let result = a - b; // 7
```

**Antara angka dan `string`**: misal salah satu variabel berbel berbentuk `string` maka sistem akan mengkonfersi `string` menjadi `number`s kayak contoh di bawah 

```javascript
let a = "10";
let b = 3;
```

`let result = a - b; // 7`

>[!NOTE]
> dari contoh di atas kita tahu bahwa kalau misal misal salah satu variabel berbel berbentuk `string` maka `string` akan di ubah menjadi `number` untuk bisa di operasika
> Lalu untuk Studi kasus selnajutnya 
> misal ke dual varabel adalah `string` maka output nya akan NaN Kayak Contoh Di bawha ini


```javascript
let a = "hello";
let b = "world";
let result = a - b; // NaN 
```

</div>

---

<div id="kali">
    <h3>contoh untuk perkalian</h3>

**PERKALAN** (`*`)
di perkalian itu kita hanya bisa mengoprasikan nya dalam bentuk `number` bukan `string`

**Antara angka dan angka**
seperti yg sudah saya bilamg tadi kalo js cuman bisa angka dan aangka kalau string bisa aja asal string nua itu bernilai number dan string nya bakal di konversi ke umber jug ujung ujung nya

    ex = let stringNumVelue = "10" //This is a stringVelueNumber

**Perkalian Antara String Dan Number**

```js
let a = "10";
let b = 5;
let c = a * b; //output 15//
```
>[!NOTE]
>Jadi Klau String Nya iTu Angka Bukan Huruf sistem bisa mengkonferis ke bentuk number variabel nya

**Perkalian Antara Num Dan Num**
kalau yg ini baru normal karna ini ememang standart nya

```js
let a = 10;
let b = 5;
let c = a * b; //output 15//
```

**Perkalian Antara String Dan String**
kalau 2 2 veriabel nya bernilau string maka hasil nya `NaN`

```js
let a = "abcd";
let b = "apcb"
let c = a * b //output NaN//
```

</div>

---

<div id="bagi">
    <h3>contoh untuk pembagian</h3>

### Oke Kita Masuk ke Pembagian (`/`)
sebenar nya smaa aja pembagian ini kayak perkalian cuman beda `/` simbol aja nya 

### Gua Ulang Seklai Lgi
>[!NOTE]
> pembagian ini kayak perkalian cuman beda `/` simbol aja nya

**Antara dua angka (number)**: proses nya jaid matematika

```js
let a = 10;
let b = 2;
let result = a / b; // 5
```


**Antara angka dan string** (string yang dapat dikonversi menjadi angka): misla slaah satu string bisa di konfrsi menjadi angka maka proses maish bisa di lakaukan

```js
let a = "10"; // string
let b = 2;    // number
let result = a / b; // 5 (string "10" diubah menjadi angka 10, lalu dibagi 2)
```

**Antara dua string:** kalau 2 2 nya string maka hasil nya `NaN`

```js
let a = "10";
let b = "2";
let result = a / b; // 5 (string "10" dan "2" diubah menjadi angka dan dibagi)
```

**Antara angka dan string yang berisi huruf** misal slaah satu variabel itu string yang nilai nya gk bsia do konfersi ke number kayak huruf maka hasil nya `NaN`

```js
let a = 10;
let b = "hello"; // string non-numeric
let result = a / b; // NaN
```

**Pembagian dengan angka 0**: misal angka nya di bagi smaa angka 0, hasilnya adalah Infinity (positif atau negatif, tergantung tanda)

```js
let a = 10;
let b = 0;
let result = a / b; // Infinity
```

**Pembagian 0 dengan angka lainnya**: kalak bilangan yg mau di bagi itu 0 maka haisl nya tetap 0

```js
let a = 0;
let b = 5;
let result = a / b; // 0
```

>[!NOTE]
>Pembagian (/) akan mengkonversi string yang bisa diubah menjadi angka dan melakukan pembagian.
Jika string berisi karakter non-numerik (misalnya huruf), hasilnya adalah NaN.
Pembagian dengan 0 dapat menghasilkan Infinity atau -Infinity, tergantung pada tanda operandnya.
</div>

---

<div id="samadengan">
    <h3>contoh untuk logika sama dengan</h3>
</div>
<div id="dan">
    <h3>contoh untuk logika dan</h3>
</div>
=======

>>>>>>> main
