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

<h2>KONDISI SWITCH</h2>

<h3>Code :</h3>

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>PHP Dasar</title>
    </head>
    <body>
        <h2>Kondisi Switch</h2>
        <?php
        $nama_hari = date("l");
        switch ($nama_hari) {
            case "Sunday":
                echo "Minggu";
                break;
            case "Monday":
                echo "Senin";
                break;
            case "Tuesday":
                echo "Selasa";
                break;
            default:
                echo "Sabtu";
        }
        echo "/$nama_hari";
        ?>
    </body>
    </html>

<h3>Output :</h3>

![Screenshot (279)](https://user-images.githubusercontent.com/118242692/226376430-c226ba4b-c752-4a0c-adf5-175961e13bd1.png)

<h2>PERULANGAN FOR</h2>

<h3>Code :</h3>

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>PHP Dasar</title>
    </head>
    <body>
        <h2>Perulangan For</h2>
        <?php
        echo "Perulangan 1 sampai 10 <br />";
        for ($i = 1; $i <= 10; $i++) {
            echo "Perulangan ke: " . $i . '<br />';
        }

        echo "Perulangan Menurun dari 10 ke 1 <br />";
        for ($i = 10; $i >= 1; $i--) {
            echo "Perulangan ke: " . $i . '<br />';
        }
        ?>
    </body>
    </html>

<h3>Output :</h3>
![Screenshot (280)](https://user-images.githubusercontent.com/118242692/226377174-10c2143b-b2ed-4d73-8aaf-49970b80146b.png)

<h2>PERULANGAN WHILE</h2>

<h3>Code :</h3>

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>PHP Dasar</title>
    </head>
    <body>
        <h2>Perulangan While</h2>
        <?php
        echo "Perulangan 1 sampai 10 <br />";
        $i = 1;
        while ($i <= 10) {
            echo "Perulangan ke: " . $i . '<br />';
            $i++;
        }
        ?>
    </body>
    </html>

<h3>Output :</h3>

![Screenshot (281)](https://user-images.githubusercontent.com/118242692/226378054-9faa89bf-1645-4c34-b731-db0cc63289c5.png)

<h2>PERULANGAN DOWHILE</h2>

<h3>Code :</h3>

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>PHP Dasar</title>
    </head>
    <body>
        <h2>Perulangan Dowhile</h2>
        <?php
        echo "Perulangan 1 sampai 10 <br />";
        $i = 1;
        do {
            echo "Perulangan ke: " . $i . '<br />';
            $i++;
        } while ($i <= 10);
        ?>
    </body>
    </html>

<h3>Output :</h3>

![Screenshot (282)](https://user-images.githubusercontent.com/118242692/226378425-f006d8f1-d9b7-4fec-95b8-c1c13d6524f3.png)

<h2>PRAKTIKUM 2</h2>

<h3>Code :</h3>

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>Praktikum 2</title>
    </head>
    <body>
        <h2>TUGAS</h2>
        <form class="form" method="post">
            <label>Nama: </label>
            <br>
            <input type="text" name="nama">
            <br>
            <label>Tanggal Lahir: </label>
            <br>
            <input type="text" name="tgl_lahir">
            <br>
            <label>Pekerjaan: </label>
            <br>
            <select name='pekerjaan'>
                <option value="-"> --- Pilih Pekerjaan --- </option>
                <option value='Software Developer'>Software Developer</option>
                <option value='Web Developer'>Web Developer</option>
                <option value='Mobile Developer'>Mobile Developer</option>
                <option value='Database Administrator'>Database Administrator</option>
                <option value="Cloud Engineer">Cloud Engineer</option>
            </select>
            <br>
            <br>
            <button type="submit">Kirim</button>
        </form>
        <h2>HASIL</h2>

        <?php
        # Memanggil Nama
        echo 'Nama: ' . $_POST['nama'];

        # Merubah Tanggal Lahir menjadi Umur (Tahun)
        $tgl_lahir = @$_POST['tgl_lahir'];

        $lahir = new DateTime($tgl_lahir);
        $hari_ini = new DateTime();

        $diff = $hari_ini->diff($lahir);

        # Memanggil fungsi umur yg sudah dibuat diatas
        echo "<br> Umur: " . $diff->y . " Tahun";

        # Memanggil pekerjaan
        echo "<br> Pekerjaan: " . $_POST['pekerjaan'];

        # Kondisi if pekerjaan untuk menentukan gaji
        $pekerjaan = @$_POST['pekerjaan'];

        if ($pekerjaan == "Software Developer") {
            echo '<br> Gaji: Rp. 8.000.000,-';
        } elseif ($pekerjaan == "Web Developer") {
            echo '<br> Gaji: Rp. 6.000.000,-';
        } elseif ($pekerjaan == "Mobile Developer") {
            echo '<br> Gaji: Rp. 10.000.000,-';
        } elseif ($pekerjaan == "Database Administrator") {
            echo '<br> Gaji: Rp. 13.000.000,-';
        } elseif ($pekerjaan == "Cloud Engineer") {
            echo '<br> Gaji: Rp. 9.000.000,-';
        }

        ?>
    </body>
    </html>
    
<h3>Output :</h3>

![Screenshot (283)](https://user-images.githubusercontent.com/118242692/226379248-a5a8e524-7a7d-4819-b2d7-a175cb34a49d.png)
