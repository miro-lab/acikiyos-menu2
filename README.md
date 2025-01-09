<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Acıkıyo's Menü</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f8f8f8;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #ff6f00;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .menu-category {
            margin: 20px;
            padding: 10px;
            background: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 5px;
        }
        .menu-category h2 {
            color: #ff6f00;
        }
        .menu-item {
            display: flex;
            justify-content: space-between;
            padding: 5px 0;
            border-bottom: 1px solid #ddd;
        }
        .menu-item:last-child {
            border-bottom: none;
        }
        footer {
            text-align: center;
            margin: 20px 0;
            color: #666;
        }
    </style>
</head>
<body>

<header>
    <h1>Acıkıyo's Menü</h1>
    <p>Lezzetli yemekler, sıcak bir ortamda!</p>
</header>

<main>
    <div class="menu-category">
        <h2>Kahvaltılıklar</h2>
        <div class="menu-item">
            <span>Serpme Kahvaltı</span>
            <span>100 TL</span>
        </div>
        <div class="menu-item">
            <span>Menemen</span>
            <span>50 TL</span>
        </div>
        <div class="menu-item">
            <span>Tost Çeşitleri</span>
            <span>40 TL</span>
        </div>
    </div>

    <div class="menu-category">
        <h2>Çorbalar</h2>
        <div class="menu-item">
            <span>Mercimek Çorbası</span>
            <span>30 TL</span>
        </div>
        <div class="menu-item">
            <span>Ezogelin Çorbası</span>
            <span>30 TL</span>
        </div>
    </div>

    <div class="menu-category">
        <h2>Ana Yemekler</h2>
        <div class="menu-item">
            <span>Izgara Köfte</span>
            <span>120 TL</span>
        </div>
        <div class="menu-item">
            <span>Tavuk Şiş</span>
            <span>110 TL</span>
        </div>
    </div>
</main>

<footer>
    <p>© 2025 Acıkıyo's | Tüm Hakları Saklıdır.</p>
</footer>

</body>
</html>
