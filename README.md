# Lab5Web


1. Mengenal Java Script

<html lang="en">
<head>
    <title>Mengenal JavaScript</title>
</head>
<body>
    <h1>Pengenalan JavaScript</h1>
    <h3>Contoh document.write dan console.log</h3>
    <script>
        document.write("Hello World");
        console.log("Hello World");
    </script>
</body>
</html>

![Screenshot (273)](https://github.com/user-attachments/assets/deb6f5cb-d30e-4a5b-a4e2-f083530f6f5c)


2. Pemakaian Alert sebagai property window.

<html>
<head>
    <title>Alert Box</title>
</head>
<body>
<script>
    window.alert("Ini merupakan pesan untuk anda");
</script>
</body>
</html>

![Screenshot (274)](https://github.com/user-attachments/assets/997ef64a-1d47-4259-b1b6-f35fa364ba89)


3. Pemakaian method dalam objek
<!DOCTYPE html>
<html>
<head>
    <title>skrip javascript</title>
</head>
<body>
percobaan memakai javascript:<br>
<script>
    document.write("selamat mencoba javascript<br>");
    document.write("semoga sukses!")
</script>
</body>
</html>

![Screenshot (275)](https://github.com/user-attachments/assets/90359093-9ebd-4951-b7cc-e4966e2b2ea3)


4. pemakaian prompt

<html>
<head>
    <title>pemasukan data</title>
</head>
<body>
<script language="javascript">
   var nama = prompt ("Siapa nama anda?", "Masukan nama anda?");
   document.write("hai, "+ suci);
</script>
</body>
</html>

![Screenshot (276)](https://github.com/user-attachments/assets/34d7218f-db04-499b-9506-b3947bd32fa9)


5. pembuatan fungsi dan cara memanggilnya

<html>
<head>
    <title>contoh program javascript</title>
    <script language="javascript">
        function pesan(){
          alert ("memanggil javascript lewat body onload")
        }
    </script>
</head>
<body onload=pesan()>
</body>
</html>

![Screenshot (277)](https://github.com/user-attachments/assets/100e09b5-f4c2-4649-bbb5-31df05b7e566)



6. Operasi dasar aritmatika

<html>
<head>
    <title>contoh program javascript</title>

    <script language="javascript">
        function test (val1,val2)
    {
        document.write("<br>"+"perkalian : val1*val2 "+"<br>")
        document.write(val1*val2)
        document.write("<br>"+"pembagian : val1/val2 "+"<br>")
        document.write(val1/val2)
        document.write("<br>"+"penjumlahan : val1+val2 "+"<br>")
        document.write(val1+val2)
        document.write("<br>"+"pengurangan : val1-val2 "+"<br>")
        document.write(val1-val2)
        document.write("<br>"+"modulus : val1%val2 "+"<br>")
        document.write(val1%val2)
    }
    </script>
</head>
<body>
    <input type="button" name="button1" value="arithmetic" onclick="test(9,4)">
</body>
</html>

![Screenshot (278)](https://github.com/user-attachments/assets/d68adfe0-f024-4875-bb91-53b879f4df91)

![Screenshot (279)](https://github.com/user-attachments/assets/dd90ee18-4124-4255-bc84-946d2cc870f1)



7. seleksi kondisi if-else

<html>
<head>
    <title>contoh if-else</title>
</head>
<body>
    <script language="javascript">
        var nilai = prompt("nilai (0-100): ", 0);
        var hasil = "";
        if (nilai >= 60)
        hasil = "lulus";
        else
        hasil = "tidak lulus";
        document.write("hasil: " + hasil);
    </script>
</body>
</html>

![Screenshot (282)](https://github.com/user-attachments/assets/90e28592-b7cf-49ba-b78c-5138155e4425)


8. penggunaan operator switch untuk seleksi kondisi

<html>
<head>
    <title>Contoh Program JavaScript</title>
    <script language="javascript">
        function test() {
            var val1 = window.prompt("Input nilai (1-5):");
            switch (val1) {
                case "1":
                    document.write("bilangan satu");
                    break;
                case "2":
                    document.write("bilangan dua");
                    break;
                case "3":
                    document.write("bilangan tiga");
                    break;
                case "4":
                    document.write("bilangan empat");
                    break;
                case "5":
                    document.write("bilangan lima");
                    break;
                default:
                    document.write("bilangan lainnya");
            }
        }
    </script>
</head>
<body>
    <input type="button" name="button1" value="Cek Bilangan" onclick="test()">
</body>
</html>

![Screenshot (283)](https://github.com/user-attachments/assets/2c37123a-074d-4548-80e5-8ef88c51b86e)

![Screenshot (285)](https://github.com/user-attachments/assets/ac4c1bcb-8d29-4e54-ac0c-1e57111da5cf)

![Screenshot (286)](https://github.com/user-attachments/assets/5afba207-6ffd-4160-875d-8b2caf15528e)


9. form input

<html>
<head>
    <title>Contoh Program JavaScript</title>
    <script language="javascript">
        function test() {
            var val1 =document.kirim.T1.value
            if (val1%2==0)
                document.kirim.T2.value="bilangan genap"
            else
                document.kirim.T2.value="bilangan ganjil"
        }
    </script>
</head>
<body>
   <form method="POST" name="kirim">
        <p>BIL <input type="text" name="T1" size="20">MERUPAKAN BIL <input type="text" name="T2" size="20"></p>
        <p><input type="button" value="TEBAK" name="B1" onclick=test()></p>
   </form>
</body>
</html>

![Screenshot (287)](https://github.com/user-attachments/assets/2989290e-86b7-4cd3-b0d7-1ad273295467)


10. form button
<html>
<head>
    <title>objek document</title>
</head>
<body>
    <script language="javascript">
    <!--
        function ubahWarnaLB(warna) {
            document.bgColor = warna;
        }
        
        function ubahWarnaLD(warna) {
            document.fgColor = warna;
        }
     //>
    </script>

    <h1>tes</h1>
    <form>
        <input type="button" value="Latar Belakang Hijau" onClick="ubahWarnaLB('GREEN')">
        <input type="button" value="Latar Belakang Putih" onClick="ubahWarnaLB('WHITE')">
        <input type="button" value="Teks Kuning" onClick="ubahWarnaLD('YELLOW')">
        <input type="button" value="Teks Biru" onClick="ubahWarnaLD('BLUE')">
    </form>
    <script language="javascript">
        <!--
        document.write("Dimodifikasi terakhir pada " + document.lastModified);
        //-->
    </script>
</body>
</html>

![Screenshot (288)](https://github.com/user-attachments/assets/7816e25d-b413-4f6d-937f-5e32b5f78cb3)

![Screenshot (289)](https://github.com/user-attachments/assets/aa83296e-f7a1-4848-b4bd-36cb927a0e59)

![Screenshot (290)](https://github.com/user-attachments/assets/9815a266-c96f-4e09-81ff-855c61448507)

![Screenshot (291)](https://github.com/user-attachments/assets/c485f186-b2cc-432e-a61d-044dae4a77e7)

11. HTML DOM
<!-- File: daftar_menu.html -->
<html>
<head>
    <title>Daftar Menu</title>
    <script>
        function hitung(ele) {
            var total = document.getElementById('total').value;
            total = (total == "") ? 0 : parseInt(total);
            var harga = 0;

            if (ele.checked) {
                harga = ele.value;
                total += parseInt(harga);
            } else {
                harga = ele.value;
                if (total > 0) 
                    total -= parseInt(harga);
            }

            document.getElementById('total').value = total;
        }
    </script>
</head>
<body>
    <h1>Daftar Menu Makanan</h1>
    <label><input type="checkbox" value="5000" id="menu1" onclick="hitung(this);"> Ayam Goreng Rp. 5.000</label><br />
    <label><input type="checkbox" value="3000" id="menu2" onclick="hitung(this);"> Tempe Goreng Rp. 3.000</label><br />
    <label><input type="checkbox" value="2500" id="menu3" onclick="hitung(this);"> Telur Dadar Rp. 2.500</label><br />
    <strong>Total Bayar: Rp. <input id="total" type="text" /></strong>
</body>
</html>

![Screenshot (292)](https://github.com/user-attachments/assets/53b068a0-f09b-4ef2-a682-54707b9f3ee3)

