<!DOCTYPE html>
<html>
<head>
    <title>Buttons</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>AFO-Aplikacija za Finansijske Obračune</title>

    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha2/dist/css/bootstrap.min.css" integrity="sha384-aFq/bzH65dt+w6FI2ooMVUpc+21e0SRygnTpmBvdBgSdnuTN7QbdgL+OapgHtvPp" crossorigin="anonymous">
</head>
<style>
    body{
        background-color: gray;

    }
    h1{
        margin-left: 27%;
    }
</style>
<body>
    <h1 style="color: white;">AFO-Aplikacija za Finansijske Obračune</h1> </h1><br><br><br><br><br>

    <div class="container mt-5">
        <div class="text-center">
            <button class="btn btn-warning d-inline-block mx-1" onclick="document.location='financialPage.html'">Izračunaj kamatu</button>
            <button class="btn btn-warning d-inline-block mx-1" onclick="document.location='ulaganja.html'">Izračunaj ulaganja</button>
            <button class="btn btn-warning d-inline-block mx-1" onclick="document.location='stednja.html'">Izračunaj štednju</button>
            <button class="btn btn-warning d-inline-block mx-1" onclick="document.location='troskovi.html'">Izračunaj troškove</button>
        </div>
    </div>
</body>
</html>
