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
- string
- numbers
- bolean

apa itu string num dan bolean?

#### A. String
string itu adalah code yang berbentuk text bebas dan string juga itu di tandai dnegfan text yang di awali oleh tanda `"text"` atau `'text'` sma aja 

**Sintax Tring**

```js
console.log("im a string")
```

#### B. Numbers
kalau ini itu kebalikan nya dari string kalau sting kan text atau huruf ya nah tapi kalau numbres ini itu adalah bilangn atau angka

**Sintax Numbers**

```js
a = 1;
b = 2;
c = a + b;
console.log(c + 5) //Output Nya 8
```

#### C. Bolean
kalau bolean ini itu campuran atau gabungan antara string dan num tapi bedanya dia itu cuman bisa antara
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


