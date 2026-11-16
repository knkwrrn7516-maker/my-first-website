
<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Shop</title>
   
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f4f7fb;
        }

        /* เมนูด้านบน */
        nav {
            background-color: #1e40af;
            padding: 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        nav h2 {
            color: white;
            margin: 0;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
        }

        /* ส่วนต้อนรับ */
        .hero {
            text-align: center;
            padding: 80px 20px;
            background-color: white;
        }

        .hero h1 {
            color: #1e40af;
            font-size: 36px;
        }

        .hero p {
            color: #666;
        }

        /* ปุ่ม */
        .btn {
            display: inline-block;
            background-color: #2563eb;
            color: white;
            padding: 12px 25px;
            border-radius: 8px;
            text-decoration: none;
        }

        /* ส่วนบริการ */
        .services {
            padding: 40px 20px;
            text-align: center;
        }

        .container {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }

        .card {
            background-color: white;
            padding: 25px;
            width: 220px;
            border-radius: 12px;
            box-shadow: 0 3px 10px #ddd;
        }

        .card h3 {
            color: #1e40af;
        }

        footer {
            background-color: #1e40af;
            color: white;
            text-align: center;
            padding: 20px;
        }
        .shop-image {
    width: 80%;
    max-width: 700px;
    height: 300px;
    object-fit: cover;
    border-radius: 15px;
    display: block;
    margin: 20px auto;
}
.card img {
    width: 100%;
    height: 150px;
    object-fit: cover;
    border-radius: 10px;
    margin-top: 10px;
}
footer {
    background: linear-gradient(135deg, #173b8f, #2563eb);
    color: white;
    text-align: center;
    padding: 55px 20px;
}

footer h2 {
    font-size: 30px;
    margin-bottom: 12px;
}

footer p {
    color: #e5edff;
    margin: 12px 0;
}

.contact-buttons {
    display: flex;
    justify-content: center;
    gap: 15px;
    flex-wrap: wrap;
    margin-top: 25px;
}

.contact-buttons a {
    text-decoration: none;
    padding: 13px 25px;
    border-radius: 10px;
    font-weight: bold;
    transition: 0.3s;
}

.facebook-btn {
    background: white;
    color: #1e40af;
}

.phone-btn {
    background: #16a34a;
    color: white;
}

.contact-buttons a:hover {
    transform: translateY(-4px);
    opacity: 0.9;
}
    </style>
</head>

<body>

    <nav>
        <h2>ช่างใหญ่ปลายคลอง</h2>
        <div>
            <a href="#">หน้าแรก</a>
            <a href="#services">บริการ</a>
            <a href="#contact">ติดต่อ</a>
        </div>
    </nav>

    <section class="hero">
        <h1>ยินดีต้อนรับสู่ร้านของเรา</h1>
        <p>บริการด้วยใจ ใส่ใจในทุกคุณภาพ</p>
         <img src="images/shop.jpg"
         class="shop-image"
         alt="ภาพหน้าร้าน">

        <a href="#contact" class="btn">ติดต่อเรา</a>
    </section>

    <section class="services" id="services">
        <h2>บริการของเรา</h2>

        <div class="container">

            <div class="card">
    <h3>ซ่อมรถจักรยานยนต์</h3>
    <img src="images/service1.jpg" alt="งานซ่อมรถ">
    <p>รับซ่อมรถจักรยานยนต์ ดูแลและตรวจเช็กสภาพรถ</p>
</div>

<div class="card">
    <h3>รับทำพ่วงข้าง</h3>
    <img src="images/service2.jpg" alt="งานทำพ่วงข้าง">
    <p>รับทำพ่วงข้างตามความต้องการของลูกค้า</p>
</div>

<div class="card">
    <h3>ผลงานของทางร้าน</h3>
    <img src="images/service3.jpg" alt="ผลงานพ่วงข้าง">
    <p>ชมตัวอย่างผลงานการทำพ่วงข้างของทางร้าน</p>
</div>

        </div>
    </section>

    <footer id="contact">

    <h2>ติดต่อร้านช่างใหญ่ปลายคลอง</h2>

    <p>รับซ่อมรถจักรยานยนต์และรับทำพ่วงข้าง</p>

    <p>ยินดีให้บริการและให้คำปรึกษาทุกวัน</p>

    <div class="contact-buttons">

        <a href="https://www.facebook.com/tanawat.totong.1"
           target="_blank"
           class="facebook-btn">
           Facebook ร้าน
        </a>

        <a href="tel:0630592445"
           class="phone-btn">
           โทร 063-059-2445
        </a>

    </div>

    <p style="margin-top:30px; font-size:13px;">
        © 2026 ร้านช่างใหญ่ปลายคลอง
    </p>

</footer>

</body>
</html>
