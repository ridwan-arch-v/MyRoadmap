# Pengenalan JavaScript (JS)

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
