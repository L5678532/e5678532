# e5678532
<!DOCTYPE html>
<html>
<head>
<title>Belajar Membuat Form </title>
</head>
<body>
<form action=" formulir.html" method="get">
Nama: <input type="text" name="nama" value="Nama Kamu" />
<br />
Password: <input type="password" name="password" />
<br />
Jenis Kelamin : 
<input type="radio" name="jenis_kelamin" value="laki-laki" checked /> 
Laki - Laki
<input type="radio" name="jenis_kelamin" value="perempuan" /> 
Perempuan
<br />
Hobi: <input type="checkbox" name="hobi_baca" /> Membaca Buku
      <input type="checkbox" name="hobi_nulis" checked /> Menulis
      <input type="checkbox" name="hobi_mancing" /> Memancing
<br />
Asal Kota:
 <select name="asal_kota" >
     <option value="Kota Jakarta"> Jakarta</option>
     <option value="Kota Bandung">Bandung</option>
     <option value="Kota Semarang" selected>Semarang</option>
 </select>
<br />
Komentar Anda:
<textarea name="komentar" rows="5" cols="20">
Silahkan katakan isi hati anda
</textarea>
<br />
<input type="submit" value="Mulai Proses!" >
</form>
</body>
</html>
