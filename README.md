# html
HTML sebagai script dasar pemograman web
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="description" content="Software Akuntansi Online">
    <meta name="keywords" content="HTML, CSS, JavaScript, Accounting, Akuntansi, Tutorial, Online, Software, Aplikasi, Web">
    <meta name="author" content="Budiono">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Akuntansi Online - Rangkaidata.com</title>
  </head>
  <body>
    <form> berisi form </form>
    <script>/* berisi script javascript */</script>
  </body>
</html> 
```

Dari Script dasar HTML diatas, dapat dijelaskan sebagai berikut:

1. Mendefiniskan type dokumen adalah dokumen HTML
```
<!DOCTYPE html>
```
2. Mendefinisikan root dari tag HTML.
```
<html lang="en">
</html>
```
3. Metadata dokumen HTML seperti judul, dan informasi dasar seputar gambaran web. Info metadata hanya dibaca oleh Browser.
```
<head>
  <meta charset="UTF-8">
  <meta name="description" content="Software Akuntansi Online">
  <meta name="keywords" content="HTML, CSS, JavaScript, Accounting, Akuntansi, Tutorial, Online, Software, Aplikasi, Web">
  <meta name="author" content="Budiono">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Akuntansi Online - Rangkaidata.com</title>
</head>

```
3.1. Mendefiniskan standar karakter yang sudah berlaku umum seperti karakter Unicode UTF-8. Sehingga bisa dicerna Browser.
```
<meta charset="UTF-8">
```

3.2. Mendefinisikan keyword untuk dibaca oleh mesin pencarian di Browser (Search engine).
```
<meta name="keywords" content="HTML, CSS, JavaScript, Accounting, Akuntansi, Tutorial, Online, Software, Aplikasi, Web">
```

3.3. Menjelaskan gambaran umum dari web.
```
<meta name="description" content="Software Akuntansi Online">
```
3.4. Informasi si pembuat web.
```
<meta name="author" content="Budiono">
```
3.5. Memberikan memberikan skala layar dari browser ke skala 1. Sehingga berguna untuk mendefiniskan panjang dan lebar layar nantinya.
```
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```
3.6. Memberikan judul web di tab Browser.
```
<title>Akuntansi Online - Rangkaidata.com</title>
```
4. Selanjutnya adalah berisi body atau isi dari halaman web tersebut. Isi dari halaman web bisa berisi form input, tombol submit, script javascript dan lainnya.
```
<body>
<form> berisi form </form>
<script>/* berisi script javascript */</script>
</body>
```
