# apa itu `JavaScript Where To`

## Disclaimer

**Author banyak Mnegambil referensi di [w3schools](https://www.w3schools.com)

---

## Pnejelsan tentang `<script>`

nah jaid di html itu misal kita mau memauskan js bisa pakai `<script></script>`
Dan `<script>` itu ada 2 cara narok nya 

1. script internal ( DIDALAM HTML )
contoh nya gini

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <script></script>
</body>
</html>
```

## Oke jadi kita ada 2 metode kalau pakai internal

### 1. `<script>` yang di taroh di `head`

oke jaid script yang di tarok di head ini itu js nya bakal di peorses dulu sebelum html di proses
dan biasa nya script yng di taruh di head ini itu fungsi nya beda kalau di taruh di body emg bisa aja
sebenarnya kalau script yang di taruh di body di letakkan di head fungsi atau event nya bakal tetap jalan
tapi dia bikin browser kit itu ngelag 

contoh nya gini 

```html
<head>
  <script>
    alert("Script di head dijalankan pertama kali!");
  </script>
</head>
<body>
  <h1>Contoh Penempatan Script di Head</h1>
</body>
```

### 2. `<script>` Ynag di Trauh di body

oke jaid script yng di tarok di bagian body itu juga gunanya mirip sama kayk sbeelum nya tapi penemaptan nya 
dan fungsi nya juga beda, misal kalian ada fungsi untuk event funccion apa gitu atau yg berkaitan dengan
html dulu itu di rekomendasikan kalian taruh nya di body aja karna script yang di tarih di body bakla belih 
mempercepat brwoser

contoh code 

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p id="myId">my size is 10px</p>
    <button type="button" onclick="myIdTester()">try it</button>
    <script>
        function myIdTester(){
            document.getElementById("myId").style.fontSize ="30px"
        }
    </script>
</body>
</html>
```


Penjelasan:

- **Script di `<head>`** akan dieksekusi lebih awal, sementara script di **`<body>`** akan dieksekusi setelah seluruh halaman selesai dimuat.
- Perbedaan ini kadang mempengaruhi kinerja atau waktu pemuatan halaman di browser.

2. pakai metode external

jadi di js juga bis apakai file js external 

contoh sintax nya gini

```html
<script src="">../myJs.js</script>
```

tergantung file js kalian letak nya di mana

## Thanks For Reading 😁

## Referensi

📚 Materi ini diambil dan dirangkum dari [W3Schools](https://www.w3schools.com)  
![W3Schools](https://img.shields.io/badge/W3Schools-Reference-blue)
