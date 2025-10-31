<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<title>Halaman UNINDRA</title>
<style>
    body {
        background-color: yellow;
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
    }

    /* Header: logo + teks sejajar */
    .header {
        display: flex;
        justify-content: center;
        align-items: center;
        gap: 15px;
        margin-top: 15px;
    }

    .header img {
        width: 90px;
        height: auto;
    }

    .header-text {
        text-align: center;
        line-height: 1.2;
    }

    .header-text h1 {
        color: blue;
        font-size: 24px;
        margin: 0;
    }

    .header-text h2 {
        color: blue;
        font-size: 24px;
        margin: 0;
    }

    marquee {
        color: red;
        font-size: 18px;
        font-weight: bold;
        margin-top: 5px;
    }

    hr {
        border: none;
        height: 5px;
        background-color: black;
        margin: 10px 0 20px 0;
    }

    /* --- TABEL LUAR --- */
    .outer-table {
        border: 3px solid black;
        padding: 1px;
        margin: auto;
        width: 600px;
        background-color: white;
    }

    /* --- TABEL DALAM --- */
    table.inner-table {
        border-collapse: separate;
        border-spacing: 3px;
        width: 100%;
        font-size: 16px;
    }

    table.inner-table td {
        border: 2px solid black;
        padding: 8px;
        background-color: white;
    }

    table.inner-table td:nth-child(1) {
        width: 90px;
        font-weight: bold;
    }

    table.inner-table td:nth-child(2) {
        width: 10px;
        text-align: center;
    }

    /* Input tanpa kotak */
    input[type="text"] {
        width: 98%;
        padding: 4px;
        border: none;
        outline: none;
        font-size: 15px;
        background-color: transparent;
    }

    .button {
        text-align: center;
        margin-top: 10px;
    }

    button {
        padding: 6px 25px;
        font-size: 15px;
        cursor: pointer;
        border: 2px solid black;
        background-color: white;
    }

    .content {
        width: 500px;
        margin: 15px auto;
        font-size: 16px;
    }

    ol {
        margin-top: 5px;
        margin-bottom: 10px;
    }
</style>
</head>
<body>

    <div class="header">
        <img src="logo-None-universitas-indraprasta-pgri.jpg" alt="Logo UNINDRA">
        <div class="header-text">
            <h1>UNIVERSITAS INDRAPRASTA PGRI</h1>
            <h2>(UNINDRA)</h2>
        </div>
    </div>

    <marquee>Jl. Nangka No.58 Tanjung Barat - JakSel</marquee>

    <hr size="5">

    <!-- TABEL LUAR -->
    <div class="outer-table">
        <table class="inner-table">
            <tr>
                <td>Nama</td>
                <td>:</td>
                <td><input type="text" placeholder="Masukkan nama Anda"></td>
            </tr>
            <tr>
                <td>NPM</td>
                <td>:</td>
                <td><input type="text" placeholder="Masukkan NPM Anda"></td>
            </tr>
        </table>
    </div>

    <div class="button">
        <button>SIMPAN</button>
    </div>

    <div class="content">
        <b>FTIK :</b>
        <ol type="A">
            <li>Informatika</li>
            <li>Teknik Arsitektur</li>
            <li>Teknik Industri</li>
        </ol>

        <b>MIPA :</b>
        <ol type="I">
            <li>Matematika</li>
            <li>Fisika</li>
            <li>Biologi</li>
        </ol>
    </div>

</body>
</html>
