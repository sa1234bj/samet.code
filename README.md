<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Prime Logic Dijital | Geleceği Kodla</title>
    <!-- Google Fontları -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&family=JetBrains+Mono&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #00d2ff;
            --accent: #3a7bd5;
            --bg-dark: #0a0a0b;
            --card-bg: #161b22;
            --text-main: #f0f6fc;
        }
        body {
            font-family: 'Inter', sans-serif;
            background-color: var(--bg-dark);
            color: var(--text-main);
            margin: 0;
            scroll-behavior: smooth;
        }
        header {
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            background: radial-gradient(circle at center, #1b2735 0%, #090a0f 100%);
            text-align: center;
            border-bottom: 2px solid var(--primary);
        }
        h1 {
            font-size: 4rem;
            margin: 0;
            background: linear-gradient(to right, var(--primary), var(--accent));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            font-family: 'JetBrains Mono', monospace;
        }
        .container { max-width: 1100px; margin: auto; padding: 50px 20px; }
        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 25px; }
        .card {
            background: var(--card-bg);
            padding: 30px;
            border-radius: 15px;
            border: 1px solid #30363d;
            transition: 0.3s;
        }
        .card:hover { border-color: var(--primary); transform: translateY(-5px); }
        .badge {
            background: #238636;
            padding: 4px 12px;
            border-radius: 20px;
            font-size: 0.8rem;
            font-weight: bold;
        }
        .footer { text-align: center; padding: 100px 0; border-top: 1px solid #30363d; }
        .btn {
            padding: 12px 30px;
            background: linear-gradient(135deg, var(--primary), var(--accent));
            color: white;
            text-decoration: none;
            border-radius: 8px;
            font-weight: bold;
            transition: opacity 0.2s;
        }
    </style>
</head>
<body>

<header>
    <h1>PRIME LOGIC</h1>
    <p style="font-size: 1.2rem; opacity: 0.8;">11. Sınıf Yazılım Öğrencisi • Dijital Girişimci • Teknoloji Üreticisi</p>
    <div style="margin-top: 30px;">
        <a href="#projeler" class="btn">Projelerimi Gör</a>
    </div>
</header>

<div class="container" id="projeler">
    <section>
        <h2 style="border-left: 4px solid var(--primary); padding-left: 15px; margin-bottom: 40px;">Vizyoner Çalışmalar</h2>
        <div class="grid">
            <div class="card">
                <span class="badge">BİTTİ</span>
                <h3>Akıllı Scooter Pro</h3>
                <p>Teknofest 2026 için geliştirilen, teknik raporu ve başvurusu tamamlanmış inovatif ulaşım projem.</p>
            </div>
            <div class="card">
                <span class="badge">AKTİF</span>
                <h3>Prime Logic Dijital</h3>
                <p>Web tasarım, logo ve kurumsal kimlik hizmetleri sunduğumuz profesyonel dijital ajans girişimi.</p>
            </div>
            <div class="card">
                <span class="badge">TEKNİK</span>
                <h3>Python & Geliştirme</h3>
                <p>Arduino ve Python ile geliştirilen donanımsal çözümler ve veri yönetimi algoritmaları.</p>
            </div>
        </div>
    </section>

    <section style="margin-top: 80px;">
        <h2>Neden Biz?</h2>
        <p>Okul pansiyonundaki etüt salonlarında, yaşıtlarım oyun oynarken ben geleceği kodluyorum. Disiplinli çalışma, grafik eğitimindeki estetik bakış açısı ve yazılım bilgimi Prime Logic çatısı altında birleştiriyorum.</p>
    </section>
</div>

<footer class="footer">
    <p>Gelecek kodlayanlarındır.</p>
    <p style="opacity: 0.5;">© 2026 Prime Logic Dijital</p>
</footer>

</body>
</html>
