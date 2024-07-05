<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>个人网页</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f5f5f5;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #8B0000;
            color: white;
            text-align: center;
            padding: 1em 0;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #8B0000;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 1em;
            padding: 0.5em 0;
        }
        nav a:hover {
            border-bottom: 2px solid #FFD700;
        }
        .container {
            max-width: 1000px;
            margin: 2em auto;
            padding: 1em;
            background-color: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .section-title {
            border-left: 5px solid #8B0000;
            padding-left: 10px;
            margin-bottom: 1em;
            font-size: 1.5em;
        }
        .profile, .contact {
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
        }
        .profile img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
        }
        .profile h2 {
            margin: 0.5em 0;
        }
        .contact-info {
            margin: 1em 0;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            gap: 1em;
            justify-content: center;
        }
        .gallery img {
            width: 100%;
            max-width: 300px;
            border: 5px solid #f5f5f5;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>
    <header>
        <h1>个人网页</h1>
    </header>
    <nav>
        <a href="#profile">个人简介</a>
        <a href="#portfolio">作品集</a>
        <a href="#contact">联系方式</a>
    </nav>
    <div class="container">
        <section id="profile">
            <h2 class="section-title">个人简介</h2>
            <div class="profile">
                <img src="path/to/your/profile-pic.jpg" alt="Profile Picture">
                <h2>您的名字</h2>
                <p>这里是您的个人简介。您可以介绍您的背景、兴趣、职业生涯等。</p>
            </div>
        </section>
        <section id="portfolio">
            <h2 class="section-title">作品集</h2>
            <div class="gallery">
                <img src="path/to/design1.jpg" alt="Design 1">
                <img src="path/to/design2.jpg" alt="Design 2">
                <img src="path/to/design3.jpg" alt="Design 3">
                <!-- Add more images as needed -->
            </div>
        </section>
        <section id="contact">
            <h2 class="section-title">联系方式</h2>
            <div class="contact">
                <p>微信: your-wechat-id</p>
                <p>Email: your-email@example.com</p>
                <p>电话: 123-456-7890</p>
            </div>
        </section>
    </div>
</body>
</html>
