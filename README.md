<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>الفحل عمران</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #0f172a;
            color: #f8fafc;
            display: flex;
            flex-direction: column;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }

        header {
            margin-top: 20px;
            margin-bottom: 25px;
            text-align: center;
            max-width: 600px;
        }

        header h1 {
            font-size: 2.8rem;
            color: #fbbf24;
            text-shadow: 0 4px 10px rgba(0, 0, 0, 0.5);
            letter-spacing: 1px;
            margin-bottom: 12px;
        }

        header p {
            font-size: 1.2rem;
            color: #e2e8f0;
            line-height: 1.6;
            font-weight: 500;
        }

        .card {
            background: #1e293b;
            border-radius: 16px;
            overflow: hidden;
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.5), 0 8px 10px -6px rgba(0, 0, 0, 0.5);
            max-width: 450px;
            width: 100%;
            text-align: center;
            border: 1px solid #334155;
            transition: transform 0.3s ease;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        .img-container {
            width: 100%;
            height: 550px;
            overflow: hidden;
            position: relative;
        }

        .img-container img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            display: block;
        }

        .card-body {
            padding: 20px;
        }

        .card-body h2 {
            font-size: 1.3rem;
            color: #fbbf24;
        }

        footer {
            margin-top: auto;
            padding: 20px 0;
            color: #64748b;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>

    <header>
        <h1>الفحل عمران</h1>
        <p>كل سنة وانت طيب يا اخويا، عقبال مليون سنة وتتحقق كل اللي نفسك فيه وتتجوز سيدني سويني! ❤️🎉</p>
    </header>

    <div class="card">
        <div class="img-container">
            <!-- تأكد من أنك رفعت ملف الصورة باسم omran.jpg في نفس المجلد -->
            <img src="omran.jpg" alt="الفحل عمران - صورة احتفالية">
        </div>
        <div class="card-body">
            <h2>🔥 أحلى عريس مستقبلي</h2>
        </div>
    </div>

    <footer>
        &copy; 2026 جميع الحقوق محفوظة - الفحل عمران
    </footer>

</body>
</html>
