<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Men Haqimda</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            font-family: 'Roboto', sans-serif;
            background-color: #f4f4f4;
            color: #333;
        }
        .header {
            background-color: #24292e;
            color: white;
            padding: 30px;
            text-align: center;
        }
        .header h1 {
            margin: 0;
        }
        .container {
            max-width: 900px;
            margin: 40px auto;
            padding: 0 20px;
        }
        .section {
            margin-bottom: 40px;
        }
        .section h2 {
            color: #0366d6;
        }
        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        .project {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 6px rgba(0,0,0,0.1);
        }
        .project h3 {
            margin-top: 0;
        }
        .footer {
            text-align: center;
            padding: 20px;
            background: #ddd;
            color: #555;
        }
    </style>
</head>
<body>

<div class="header">
    <h1>Salom, men Abdulla Halimov</h1>
    <p>Orta yoshdagi Python dasturchi</p>
</div>

<div class="container">

    <div class="section">
        <h2>🧑‍💻 Men haqimda</h2>
        <p>Men dasturlashni yaxshi ko‘raman va asosan Python, Telegram botlari, va web-ishlab chiqish bilan shug‘ullanaman. Hozirda o‘z loyihalarim ustida ishlayapman.</p>
    </div>

    <div class="section">
        <h2>🚀 Loyiha(lar)</h2>
        <div class="projects">
            <div class="project">
                <h3>📦 Qur'on Telegram Bot</h3>
                <p>Foydalanuvchiga sura tarjimasi va audioni chiqaradi.</p>
                <a href="https://github.com/username/Quran-Bot">GitHub sahifasi →</a>
            </div>
            <div class="project">
                <h3>📦 Yuk tashish e'lon bot</h3>
                <p>Yuk e'lonlarini avtomatik formatlaydi va kontaktni tugma bilan yashiradi.</p>
                <a href="https://github.com/username/ShippingBot">GitHub sahifasi →</a>
            </div>
        </div>
    </div>

    <div class="section">
        <h2>📫 Bog‘lanish</h2>
        <p>Email: <a href="mailto:youremail@example.com">youremail@example.com</a></p>
        <p>Telegram: <a href="https://t.me/username">@username</a></p>
    </div>

</div>

<div class="footer">
    &copy; 2025 Abdulla Halimov. GitHub uchun portfolio.
</div>

</body>
</html>

