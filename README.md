<!DOCTYPE html>
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

<html>
          <head>
                    <title>alert box</title>
          </head>
          <body>
                    <script language ="JavaScript">
                              <!--window.alert("Ini merupakan pesan untuk anda")-->
                    </script>
          </body>
</html>

<html>
          <head>
                    <title> Skrip JavaScript</title>
          </head>
          <body>
                    Percobaan memakai java script:<br>
                    <script language ="JavaScript>">
                              <!--
                                        document.write("Selamat mencoba javascript<br>");
                                        document.write("Semoga sukses")-->
                    </script>
          </body>
</html>

<html>
          <head>
                    <title>Pemasukan data</title>
          </head>
          <body>
                    <script language = "javascript">
                              <!--
                                        var nama = prompt ("siapa nama anda ?","Masukan nama anda");
                                        document.write("Hai,"+ nama);//-->
                    </script>
          </body>
</html>

<html>
          <head>
                    <title>Contoh program javascript</title>
                    <script language = "javascript">
                              function pesan () {
                                        alert (" memanggil javascript lewat body onload")
                              }
                    </script>
          </head>
          <body onload=pesan()>
          </body>
</html>

<html>
          <head>
                    <title>Contoh program javascript</title>
                    <script language = "JavaScript">
                              function test (val1,val2)
                              {
                                        document.write ("<br>"+"perkalian":val1*val2"+"<br>")
                                        document.write (val1*val2)
                                        document.write ("<br>"+"pembagian":val1/val2"+"<br>")
                                        document.write (val1/val2)
                                        document.write ("<br>"+"penjumlahan":val1+val2"+"<br>")
                                        document.write (val1+val2)
                                        document.write ("<br>"+"pengurangan":val1-val2"+"<br>")
                                        document.write (val1-val2)
                                        document.write ("<br>"+"modulus":val1%val2"+"<br>")
                                        document.write (val1%val2)
                              }
                    </script>
          </head>
          <body>
                    <input type="button" name="button1" value="arithmetic" onclick="test"(9,4)> 
                    </body>
</html>

<html>
<head>
          <title> contoh if-else</title>
          </head>
          <body>
                    <script language="javascript">
                              <!--
                                        var nilai = prompt("nilai (0-100):",0);
                                        var hasil = "";
                                        if (nilai >=60)
                                        hasil = "lulus";
                              else
                              hasil = "tidak lulus";
                    document.write("hasil :"+hasil);
                                        //-->
                              </script>
                    </body>
</html>

<html>
          <head>
                    <title>Contoh program javascript</title>
                    <script language="javascript">
                              function test ()
                              {
                                        vall=window.prompt("Inout nilai (1-5):")
                                        switch (vall)
                                        {
                                                  case "1":
                                                  document.write("bilangan satu")
                                                  break
                                                  case "2":
                                                  document.write("bilangan dua")
                                                  break
                                                  case "3":
                                                  document.write("bilangan tiga")
                                                  break
                                                  case "4":
                                                  document.write("bilangan empat")
                                                  break
                                                  case "5":
                                                  document.write("bilangan lima")
                                                  break
                                                  default:
                                                            document.write("bilangan lainnya")
                                                  
                                        }
                              }
                    </script>
          </head>
          <body>
                    <input type="button" name="button1" value="switch" onclick=test()>
          </body>
</html>

<html>
          <head>
                    <script language="javascript">
                              function test () {
                                        var vall=document.kirim.T1.value
                                        if (vall%2==0)
                                        document.kirim.T2.value="Bilangan genap"
                              else document.kirim.T2.value="Bilangan ganjil"
                              }
                              </script>
          </head>
          <body>
                    <from method="post" name="kirim">
                              <p>Bil <input type="text" name="T1" size="20">
                                        Merupakan Bil <input type="text" name="T2" size="20"></p>
                                        <p><input type="button" value="Tebak" name="B1" onclick=test()></p>
                    </from>
          </head>
          </html>
          
<html>
          <head>
                    <title>Objec dokumen</title>
          </head>
          <body>
                    <script language="javascript">
                              <!--
                                        function ubahwarnaLB(warna) {
                                                  document.bgcolor=warna;
                                        }
                                        function ubahwarnaLB(warna) {
                                                  document.fgcolor=warna;
                                        }
                                        //-->
                    </script>

                    <h1>tes</h1>
                    <form>
                              <input type="button" value="Latar belakang hijau" onclick="ubahwarnaLB('GREEN')">
                              <input type="button" value="Latar belakang putih" onclick="ubahwarnaLB('WHITE')">
                              <input type="button" value="teks kuning" onclick="ubahwarnaLD('YELLOW')">
                              <input type="button" value="teks biru" onclick="ubahwarnaLD('Blue')">
                    </form>
          <script language="javascript">
          <!--
                    document.write("Dimodifikasi terakhir pada " +
                    document.lastModified);
          //-->
          <script>
          </body>
</html>
