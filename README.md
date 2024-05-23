<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Arin Seramik</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f2f2f2;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #444;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 10px;
        }
        section {
            padding: 20px;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            grid-gap: 20px;
            justify-content: center;
        }
        .gallery img {
            width: 100%;
            height: auto;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Arin Seramik</h1>
        <p>Sizin İçin Özel Tasarlanmış Seramik Ürünler</p>
    </header>
    <nav>
        <a href="#products">Ürünlerimiz</a>
        <a href="#about">Hakkımızda</a>
        <a href="#contact">İletişim</a>
    </nav>
    <section id="products">
        <h2>Ürünlerimiz</h2>
        <div class="gallery">
            <!-- Buraya ürünlerinizin resimlerini ekleyin -->
            <img src="urun1.jpg" alt="Ürün 1">
            <img src="urun2.jpg" alt="Ürün 2">
            <!-- Daha fazla ürün ekleyebilirsiniz -->
        </div>
    </section>
    <section id="about">
        <h2>Hakkımızda</h2>
        <p>Arin Seramik, el yapımı seramik ürünlerin özel tasarımlarını sunar. Her bir ürünümüz ustalarımızın emeğiyle özenle hazırlanır ve sizin evinizi, ofisinizi veya herhangi bir mekanı güzelleştirmek için tasarlanır.</p>
    </section>
    <section id="contact">
        <h2>İletişim</h2>
        <p>Bizimle iletişime geçmek için aşağıdaki bilgileri kullanabilirsiniz:</p>
        <p>Telefon: 0123 456 789</p>
        <p>Email: info@arinseramik.com</p>
    </section>
    <footer>
        <p>&copy; 2024 Arin Seramik - Tüm hakları saklıdır.</p>
    </footer>
</body>
</html>
