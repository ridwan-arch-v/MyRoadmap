# Pengenalan JavaScript (JS)

## Disclaimer

**Author banyak Mnegambil referensi di [w3schools](https://www.w3schools.com)

## Apa itu JavaScript?

Jadi, JS itu bahasa pemrograman yang lagi populer banget. Biasanya dipakai buat ngatur logika, validasi data, dan banyak hal lainnya.

---

## 1.1 JavaScript Bisa Ubah Isi Konten HTML

Dengan JS, kita bisa ubah-ubah konten yang ada di HTML. Contohnya kayak gini:

> **Sumber:**  
> www.w3schools.com

---

### Contoh Kode

```html
<!DOCTYPE html>
<html>
<body>

<h2>What Can JavaScript Do?</h2>

<p id="demo">JavaScript can change HTML content.</p>

<button type="button" onclick="document.getElementById('demo').innerHTML = 'Hello JavaScript!'">Click Me!</button>

</body>
</html>
```

### Penjelasan

Nah, di contoh ini kita punya paragraf dengan id `demo` dan sebuah tombol. Jadi, kalo tombolnya diklik, bakal ada perintah ini yang dijalankan:

`document.getElementById("demo").innerHTML = "Hello JavaScript!"`

### Yuk, Pecah Satu-satu

- `document.getElementById`  
  Ini buat pilih elemen HTML pake ID-nya.

- `("demo")`  
  Ini ID yang kita pilih, dalam hal ini `demo`.

- `.innerHTML =`  
  Ini buat ganti isi dari elemen yang kita pilih tadi.

- `"Hello JavaScript!"`  
  Nah, ini adalah isi baru yang bakal muncul setelah tombol diklik.

Jadi, pas tombolnya diklik, JS bakal cari elemen dengan ID `demo` dan ganti teksnya jadi `"Hello JavaScript!"`. Gampang, kan?

---

## JavaScript Bisa Ngubah Nilai Atribut HTML

Dalam contoh ini JavaScript mengubah nilai srcatribut (sumber) dari sebuah <img>tag:

[![Klik Me](https://img.shields.io/badge/Klik%20Me-Go%20To%20simulation-white?labelColor=5A7D7C&style=for-the-badge&link=https://github.com/ridwan-arch-v/MyRoadmap/tree/main/src/ilustration/introduce_atribut_changes.html)](https://github.com/ridwan-arch-v/MyRoadmap/tree/main/src/ilustration/introduce_atribut_changes.html)

## Js Bisa ngubah css

oek jadi disini js itu bisa ngubah elemnt css ygy

### Contoh Sintax

```js
function myButton() {
    document.getElementById("myId").style.color = "aqua";
}
```

**Dan ini adalah contoh dengan html**

```html
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ubah Warna Teks</title>
</head>
<body>
    <p id="myId" style="font-size: 20px;">This font size is 20 px</p>
    <button type="button" onclick="myButton()">Try It</button>
    <script src="pl.js"></script>
</body>
</html>
```

jadi ketika tombolm di clik maka font akan merubah warna nya menjadi aqua

## Js Bisa neymbunyiin element Html pakai `display`

```js
document.getElementById("myId").style.display = "none"
```

### Jadi Hanya dnegan `.style.display =`
kita bisa menatur html dngean id `myId`

## Js Bisa juga Menambhakan sesuatu di html

Contoh sintax

```js
document.getElementById("mydemo").style.display='block'
```

>example in Html

```html
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ubah Warna Teks</title>
</head>
<body>
    <p id="myId" style="font-size: 20px;">This font size is 20 px</p>
    <p id="mydemo" style="display: none;">Hello, I am now visible!</p>
    <button type="button" onclick="myBlock()">Try It</button>
    <script src="pl.js"></script>
</body>
</html>

```

### pl.js

```js
function myBlock(){
    document.getElementById("mydemo").style.display='block'
}
```

## Thanks For Reading 😁

## Referensi

📚 Materi ini diambil dan dirangkum dari [W3Schools](https://www.w3schools.com)  
![W3Schools](https://img.shields.io/badge/W3Schools-Reference-blue)
