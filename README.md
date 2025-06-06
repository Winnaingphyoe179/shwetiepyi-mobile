# shwetiepyi-mobile
<!DOCTYPE html>
<html lang="my">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shwe Tie Pyi Mobile</title>
    <style>
        body {
            font-family: 'Myanmar Sans Pro', sans-serif; /* မြန်မာစာ Font ထည့်ဖို့ */
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #007bff;
            color: white;
            padding: 15px 0;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        .phone-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
            padding: 20px 0;
        }
        .phone-card {
            border: 1px solid #ddd;
            border-radius: 8px;
            overflow: hidden;
            text-align: center;
            padding-bottom: 15px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
            transition: transform 0.2s;
        }
        .phone-card:hover {
            transform: translateY(-5px);
        }
        .phone-card img {
            width: 100%;
            height: 200px;
            object-fit: contain; /* ပုံအချိုးအစား မပျက်အောင် */
            background-color: #eee;
            padding: 10px 0;
        }
        .phone-card h3 {
            margin: 15px 0 10px;
            color: #007bff;
        }
        .phone-card p {
            font-size: 0.9em;
            color: #555;
            padding: 0 10px;
        }
        .price {
            font-weight: bold;
            color: #28a745;
            font-size: 1.1em;
            margin-top: 10px;
        }
        footer {
            text-align: center;
            padding: 20px;
            margin-top: 30px;
            background-color: #333;
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <h1>ရွှေတံခွန် မိုဘိုင်းလ်</h1>
        <p>နောက်ဆုံးပေါ် ဖုန်းများ ရှာဖွေလိုက်ပါ</p>
    </header>

    <div class="container">
        <h2>လက်ရှိရရှိနိုင်သော ဖုန်းများ</h2>
        <div class="phone-grid">
            <div class="phone-card">
                <img src="https://via.placeholder.com/300x200?text=iPhone+15" alt="iPhone 15">
                <h3>iPhone 15 Pro Max</h3>
                <p>A17 Bionic Chip, 6.7-inch Super Retina XDR display, 48MP Camera.</p>
                <div class="price">1,800,000 MMK</div>
            </div>

            <div class="phone-card">
                <img src="https://via.placeholder.com/300x200?text=Samsung+S24" alt="Samsung Galaxy S24">
                <h3>Samsung Galaxy S24 Ultra</h3>
                <p>Snapdragon 8 Gen 3, 6.8-inch Dynamic AMOLED 2X, 200MP Camera.</p>
                <div class="price">1,700,000 MMK</div>
            </div>

            <div class="phone-card">
                <img src="https://via.placeholder.com/300x200?text=Xiaomi+14" alt="Xiaomi 14">
                <h3>Xiaomi 14 Ultra</h3>
                <p>Snapdragon 8 Gen 3, 6.73-inch AMOLED, Leica optics, 50MP Camera.</p>
                <div class="price">1,200,000 MMK</div>
            </div>

            <div class="phone-card">
                <img src="https://via.placeholder.com/300x200?text=Google+Pixel+8" alt="Google Pixel 8 Pro">
                <h3>Google Pixel 8 Pro</h3>
                <p>Google Tensor G3, 6.7-inch Super Actua display, advanced AI features.</p>
                <div class="price">1,400,000 MMK</div>
            </div>

            <div class="phone-card">
                <img src="https://via.placeholder.com/300x200?text=OnePlus+12" alt="OnePlus 12">
                <h3>OnePlus 12</h3>
                <p>Snapdragon 8 Gen 3, 6.82-inch LTPO AMOLED, Hasselblad Camera.</p>
                <div class="price">1,000,000 MMK</div>
            </div>

            <div class="phone-card">
                <img src="https://via.placeholder.com/300x200?text=Oppo+Find+X7" alt="Oppo Find X7 Ultra">
                <h3>Oppo Find X7 Ultra</h3>
                <p>Snapdragon 8 Gen 3, 6.82-inch AMOLED, HyperTone Camera.</p>
                <div class="price">1,300,000 MMK</div>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2025 Shwe Tie Pyi Mobile. All rights reserved.</p>
    </footer>
</body>
</html>
