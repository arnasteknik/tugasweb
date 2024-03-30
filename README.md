
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Latihan Program</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #b2c6fc;
            color: #030303;
            text-align: left;
            padding: 3px;
            text-transform: none;
            font-weight: bold;
        }
        header h1 {
            margin: 5px 0;
        }
        header p{
            color: blue;
            font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
        }
        nav {
            background-color: #fff;
            text-align: left;
            padding: 15px;
            border-top: 2px solid #0e0be6;
            border-bottom: 2px solid #0e0be6;
        }
        nav a {
            text-decoration: none;
            color: #050505;
            margin: 0 15px;
            font-weight: normal;
            font-family: 'lucida console', sans-serif;
        }
            nav a:not(:last-child) {
            position: relative;
        }
        nav a:not(:last-child):after {
            content: '|';
            position: relative;
            right: -5px;
            top: 50%;
            transform: translateY(-50%);
        }
        nav a:hover {
            color: #0e0be6; /* Warna tautan saat dihover */
        }
        nav a:active {
        color: red; /* Warna tautan setelah diklik */
    }
        .footer {
            text-align: left;
            margin-top: 20px;
        }
        .footer p {
            margin: 10px 0;
        }
        .footer hr {
            border: 1px solid #7a7777;
            margin: 10px 0;
        }
        .footer p1 {
            font-family: 'Times New Roman', Times, serif;
            font-size: small;
        }
    </style>
</head>
<body>
    <header>
        <h1>Programming WEB dengan HTML</h1>
        <p>Teknologi Informatika</p>
    </header>
    <nav>
        <a href="Home maf.html">Home        </a>
        <a href="profil maf.html">Profile     </a>
        <a href="About maf.html">About       </a>
        <a href="Gallery maf (2).html">Gallery     </a>
        <a href="Kontak maf.html">Contact     </a>
    </nav>
    <div class="footer">
        <p>Selamat Datang,</p>
        <p>Terimakasih anda telah bergabung dan berkunjung pada website perdana kami, situs ini merupakan program latihan dalam hyperlink pemrograman web1.</p>
        <p>Semoga website ini dapat menginspirasi Anda pada waktu liburan.</p>
        <p>Apabila ada yang ingin didiskusikan silahkan hubungi saya melalui <a href="Kontak maf.html">Contact</a>.</p>
        <br>
        <hr>
        <p1 class="admin-text">Created by <a href="profile.html">Mafrokhah </a>&copy; 2024</p1>
    </div>
</body>
</html>
