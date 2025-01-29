# js output

## Referensi

📚 Materi ini diambil dan dirangkum dari [W3Schools](https://www.w3schools.com)  
![W3Schools](https://img.shields.io/badge/W3Schools-Reference-blue)

## Disclaimer

**Author banyak Mnegambil referensi di [w3schools](https://www.w3schools.com)**

---

## Js Bisa mengeluarkan berbagai halk bisa di console atau di server oke kita bahas untuk pemula 

### 1.1 menulis html pakai `.innerHTML = "string" or num ;`

jadi maksud nya .inner html ini kita bisa nulis html tanpa mengubah nya di html
nah itu bis adi pakai di div span atau `p` atau h atau yg lain nya lah

contoh nya kayak gini 

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>This is a test</h1>
    <p id="myId"></p>
    <p>if You want to write click the button on bottom</p>
    <button type="button" onclick="viewMyId()">click Me</button>
    <script>
        function viewMyId() {
            document.getElementById("myId").innerHTML= "Helloo Im Writed by Button";
        }
    </script>
</body>
</html>
```

jadi ketika tombol di tekan akan memanggil fungsi `viewMyId` dan akan menulis di id `myId`
dnegan kalimat = `Helloo Im Writed by Button`

---

### 1.2 menulis ke dalam html nya langsung tanpa perantara

oke jadi untuk menulis nya kita pakai namanya `document.write("string" or num)`
oke saya akan buat 2 contoh yg beresiko dan yg gk beresiko

**tidak Beresiko**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>this is h1</h1>
    <h2>this is h2</h2>
    <script>
        document.write(" im string ")
    </script>
</body>
</html>
```

jadi kalau kalian run di browswer akan ada langsung text ` im string `

**Beresiko**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>this is sampah </h1>
    <h2>this is samppah </h2>
    <button type="button" onclick="deleteAll()">delete all samppah</button>
    <script>
        function deleteAll(){
            window.alert("are you sure ?")
            document.write("You compite clean the sampah")
        }
    </script>
</body>
</html>
```

jadi disini misal klain klik buttuon nya kalian akan langsung mengahpus semua file html yg ada dab akan di
gantikan oleh output dari `document.write()`

>Catatan kalau kalian mau pakai document.write() pastikan ngak ada perantara nya ya
>sola nya dia bakal lengsung menganti ke situ

### 1.3 apa itu window alert?

nah jadi window alet itu kayak peringatan aja misal di contoh code yg beresiko tadi
kalau kalain klik buttuon nya bakal ada tu notif dari web nya tergnatung server pesan nya apa
kalau dari code tadi itu pesnanya `are you sure ?` nah gitu lah kira kira

### 1.4 console.log js 

jadi console.log js ini bisa nya id gunaka untuk debuginbiar tau masalaha nya di mana
soal nya bakal ketauan dampai di mana langkah yg berhasil 

contoh code console log

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h3>tes console</h3>
    <span>2</span> <span> + </span> <span>2</span> <span> = </span> <span id="answerInHere"></span>
    <p>if you view the answer clik the button on bottom</p>
    <button type="button" onclick="operationMath()">View Answer</button>
    <script>
        function operationMath(){
            let span1 = 2;
            let span2 = 2;
            let question = span1 + span2;
            document.getElementById("answerInHere").innerHTML = question;
            console.log(`The answer is ${question}`);
        }
    </script>
</body>
</html>
```

## Oke smapai sini aja ya lanjut lagi 