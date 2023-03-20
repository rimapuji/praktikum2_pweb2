<h1>PEMOGRAMAAN WEB</h1>

Nama : Rima Puji Lestari

NIM : 312110517

Kelas : TI.2021.A3

<hr>
<h2>PHP DASAR</h2>

<h3>Code :</h3>

    <!DOCTYPE html>
      <html lang="en">
      <head>
          <meta charset="UTF-8">
          <title>PHP Dasar</title>
      </head>
      <body>
          <h1>Belajar PHP Dasar</h1>
          <?php
          echo "Hello World";
          ?>
      </body>
      </html>

<h3>Output :</h3>

![Screenshot (272)](https://user-images.githubusercontent.com/118242692/226268741-925e3c2e-0250-4690-85ee-3662d900fc74.png)

<h2>VARIABLE PHP</h2>

<h3>Code :</h3>

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>PHP Dasar</title>
    </head>
    <body>
        <h1>Belajar PHP Dasar</h1>
        <?php
        echo "Hello World";
        ?>

        <h2>Menggunakan Variable</h2>
        <?php
        $nim = "312110517";
        $nama = 'Rima Puji Lestari';
        echo "NIM : " . $nim . "<br>";
        echo "Nama : $nama";
        ?>
    </body>
    </html>

<h3>Output :</h3>

![Screenshot (274)](https://user-images.githubusercontent.com/118242692/226269906-e3844fd2-c534-4fa5-9515-b227ff1f5ca0.png)

<h2>PREDEFINE VARIABLE $_GET</h2>

<h3>Code :</h3>

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>PHP Dasar</title>
    </head>
    <body>
        <h1>Predefine Variable</h1>
        <?php
        echo 'Selamat Datang ' . $_GET['nama'];
        ?>
    </body>
    </html>

<h3>Output :</h3>

![Screenshot (275)](https://user-images.githubusercontent.com/118242692/226270549-a7c24bc1-d052-41b9-aabc-b5540246509c.png)

<h2>FORM INPUT</h2>

<h3>Code :</h3>

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>PHP Dasar</title>
    </head>
    <body>
        <h2>Form Input</h2>
        <form method="post">
            <label>Nama: </label>
            <input type="text" name="nama">
            <input type="submit" value="Kirim">
        </form>
        <?php
        echo 'Selamat Datang ' . $_POST['nama'];
        ?>
    </body>
    </html>

<h3>Output :</h3>

![Screenshot (276)](https://user-images.githubusercontent.com/118242692/226369444-531234be-472d-40de-ba67-a856106ed7ed.png)

<h2>OPERATOR</h2>

<h3>Code :</h3>

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>PHP Dasar</title>
    </head>
    <body>
        <h2>Operator</h2>
        <?php
        $gaji = 1000000;
        $pajak = 0.1;
        $thp = $gaji - ($gaji * $pajak);
        echo "Gaji sebelum pajak = Rp. $gaji <br>";
        echo "Gaji yang dibawa pulang = Rp. $thp";
        ?>
    </body>
    </html>
    </body>

<h3>Output :</h3>

![Screenshot (277)](https://user-images.githubusercontent.com/118242692/226370176-d14a8181-d177-4eff-8328-6e1e38b07d54.png)

<h2>KONDISI IF</h2>

<h3>Code :</h3>

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>PHP Dasar</title>
    </head>
    <body>
        <h2>Kondisi IF</h2>
        <?php
        $nama_hari = date("l");
        if ($nama_hari == "Sunday") {
            echo "Minggu";
        } elseif ($nama_hari == "Monday") {
            echo "Senin";
        } else {
            echo "Selasa";
        }
        ?>
    </body>
    </html>

<h3>Output :</h3>

![Screenshot (278)](https://user-images.githubusercontent.com/118242692/226370659-04108166-62eb-48b6-9372-615202125866.png)


