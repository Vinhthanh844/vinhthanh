# vinhthanh
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DPI ADR - Tăng Tốc Độ Nhạy Android</title>
    <style>
        :root {
            --primary-color: #e74c3c;
            --dark-color: #2c3e50;
            --light-color: #ecf0f1;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #1a1a1a;
            color: var(--light-color);
            text-align: center;
        }

        header {
            background-color: var(--primary-color);
            padding: 40px 20px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.5);
        }

        h1 { margin: 0; font-size: 2.5rem; text-transform: uppercase; }
        p.subtitle { font-size: 1.1rem; opacity: 0.9; }

        .container {
            max-width: 600px;
            margin: 40px auto;
            padding: 20px;
            background: #252525;
            border-radius: 15px;
            border: 1px solid #333;
        }

        .features {
            text-align: left;
            display: inline-block;
            margin: 20px 0;
        }

        .features li {
            margin: 10px 0;
            list-style: none;
        }

        .features li::before {
            content: "✔️";
            margin-right: 10px;
        }

        .contact-box {
            background: #333;
            padding: 20px;
            border-radius: 10px;
            margin-top: 30px;
        }

        .phone-number {
            display: block;
            font-size: 1.8rem;
            color: #2ecc71;
            text-decoration: none;
            font-weight: bold;
            margin: 15px 0;
        }

        .btn-call {
            display: inline-block;
            background-color: #2ecc71;
            color: white;
            padding: 15px 30px;
            text-decoration: none;
            font-weight: bold;
            border-radius: 50px;
            transition: transform 0.3s;
        }

        .btn-call:hover {
            transform: scale(1.05);
            background-color: #27ae60;
        }

        footer {
            margin-top: 50px;
            font-size: 0.8rem;
            color: #777;
            padding-bottom: 30px;
        }
    </style>
</head>
<body>

    <header>
        <h1>DPI ADR CHUYÊN NGHIỆP</h1>
        <p class="subtitle">Giải pháp tăng độ nhạy, giảm giật lag cho mọi dòng máy Android</p>
    </header>

    <div class="container">
        <h2>Tại sao nên chọn chúng tôi?</h2>
        <ul class="features">
            <li>Tối ưu DPI chuẩn cho từng dòng máy.</li>
            <li>Hỗ trợ kéo tâm cực mượt cho game thủ.</li>
            <li>An toàn 100%, không gây hại máy.</li>
            <li>Hỗ trợ cài đặt từ A-Z.</li>
        </ul>

        <div class="contact-box">
            <h3>LIÊN HỆ MUA HÀNG NGAY</h3>
            <a href="tel:0372433729" class="phone-number">0372433729</a>
            <a href="tel:0372433729" class="btn-call">GỌI ĐIỆN TƯ VẤN NGAY</a>
        </div>
    </div>

    <footer>
        &copy; 2024 Bán DPI ADR. All rights reserved.
    </footer>

</body>
</html>

