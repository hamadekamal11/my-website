<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>موقع الأنمي - Anime Hub</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
            margin: 0;
            padding: 0;
            direction: rtl;
        }
        header {
            background-color: #333;
            color: white;
            padding: 15px;
            text-align: center;
        }
        nav {
            background-color: #4CAF50;
            overflow: hidden;
            text-align: center;
        }
        nav a {
            display: inline-block;
            color: white;
            padding: 14px 20px;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin-top: 20px;
        }
        .anime-card {
            width: 250px;
            margin: 10px;
            background: white;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
            overflow: hidden;
            text-align: center;
        }
        .anime-card img {
            width: 100%;
            height: 350px;
            object-fit: cover;
        }
        .anime-card h3 {
            color: #333;
            padding: 10px;
        }
        .anime-card p {
            color: #777;
            padding: 0 10px;
            font-size: 14px;
        }
        .anime-card a {
            display: block;
            background-color: #4CAF50;
            color: white;
            padding: 10px;
            text-decoration: none;
            border-radius: 0 0 8px 8px;
        }
        .anime-card a:hover {
            background-color: #45a049;
        }
        footer {
            text-align: center;
            background-color: #333;
            color: white;
            padding: 20px;
            margin-top: 20px;
        }
    </style>
</head>
<body>

<header>
    <h1>موقع الأنمي</h1>
    <p>أفضل الأنميات لمشاهدتها الآن!</p>
</header>

<nav>
    <a href="#action">أكشن</a>
    <a href="#comedy">كوميديا</a>
    <a href="#drama">دراما</a>
    <a href="#mystery">غموض</a>
</nav>

<div class="container">
    <!-- أكشن -->
    <div class="anime-card" id="action">
        <img src="https://upload.wikimedia.org/wikipedia/en/thumb/7/7f/Demon_Slayer_-_Kimetsu_no_Yaiba%2C_volume_1.jpg/220px-Demon_Slayer_-_Kimetsu_no_Yaiba%2C_volume_1.jpg" alt="Demon Slayer">
        <h3>قاتل الشياطين</h3>
        <p>أنمي أكشن رائع حول صائد شياطين يسعى للانتقام.</p>
        <a href="https://www.crunchyroll.com/demon-slayer" target="_blank">مشاهدة الآن</a>
    </div>

    <!-- كوميديا -->
    <div class="anime-card" id="comedy">
        <img src="https://upload.wikimedia.org/wikipedia/en/6/68/KonoSuba_light_novel_volume_1_cover.jpg" alt="Konosuba">
        <h3>كونوسوبا</h3>
        <p>أنمي كوميدي عن مغامرات فاشلة في عالم خيالي.</p>
        <a href="https://www.crunchyroll.com/konosuba" target="_blank">مشاهدة الآن</a>
    </div>

    <!-- دراما -->
    <div class="anime-card" id="drama">
        <img src="https://upload.wikimedia.org/wikipedia/en/9/9c/Your_Lie_in_April_Volume_1_Cover.jpg" alt="Your Lie in April">
        <h3>كذبتك في أبريل</h3>
        <p>أنمي درامي مؤثر عن الموسيقى والحب.</p>
        <a href="https://www.crunchyroll.com/your-lie-in-april" target="_blank">مشاهدة الآن</a>
    </div>

    <!-- غموض -->
    <div class="anime-card" id="mystery">
        <img src="https://upload.wikimedia.org/wikipedia/en/6/66/Steins%3BGate_anime.jpg" alt="Steins Gate">
        <h3>ستاينز غيت</h3>
        <p>أنمي غموض وسفر عبر الزمن مليء بالمفاجآت.</p>
        <a href="https://www.crunchyroll.com/steins-gate" target="_blank">مشاهدة الآن</a>
    </div>
</div>

<footer>
    <p>&copy; 2025 موقع الأنمي | جميع الحقوق محفوظة</p>
</footer>

</body>
</html>
