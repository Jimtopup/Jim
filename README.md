pkg update
pkg install nodejs unzip
termux-setup-storage<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Topup Wallet - Egytopup Clone</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        body {
            background-color: #f4f6f9;
            color: #333;
        }
        header {
            background-color: #1e3a8a;
            color: white;
            padding: 15px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        header .logo {
            font-size: 24px;
            font-weight: bold;
        }
        header nav a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
            font-weight: 500;
        }
        .container {
            max-width: 1200px;
            margin: 40px auto;
            padding: 0 20px;
        }
        .hero {
            text-align: center;
            margin-bottom: 40px;
        }
        .hero h1 {
            color: #1e3a8a;
            font-size: 32px;
            margin-bottom: 10px;
        }
        .services {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1-fr));
            gap: 20px;
        }
        .card {
            background: white;
            padding: 20px;
            border-radius: 8px;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            transition: transform 0.2s;
        }
        .card:hover {
            transform: translateY(-5px);
        }
        .card img {
            width: 80px;
            height: 80px;
            margin-bottom: 15px;
        }
        .card h3 {
            margin-bottom: 10px;
            font-size: 20px;
        }
        .card button {
            background-color: #10b981;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            font-weight: bold;
        }
        .card button:hover {
            background-color: #059669;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #1e3a8a;
            color: white;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

    <header>
        <div class="logo">MyTopup</div>
        <nav>
            <a href="#">হোম</a>
            <a href="#">লগইন</a>
            <a href="#">নিবন্ধন</a>
        </nav>
    </header>

    <div class="container">
        <div class="hero">
            <h1>সহজে এবং দ্রুত টপ-আপ করুন</h1>
            <p>আপনার পছন্দের গেম বা মোবাইল রিচার্জ করুন মুহূর্তের মধ্যে</p>
        </div>

        <div class="services">
            <!-- সার্ভিস ১ -->
            <div class="card">
                <img src="https://placeholder.com" alt="Free Fire">
                <h3>Free Fire Diamond</h3>
                <button onclick="orderNow('Free Fire')">টপ-আপ করুন</button>
            </div>
            <!-- সার্ভিস ২ -->
            <div class="card">
                <img src="https://placeholder.com" alt="PUBG">
                <h3>PUBG Mobile UC</h3>
                <button onclick="orderNow('PUBG Mobile')">টপ-আপ করুন</button>
            </div>
            <!-- সার্ভিস ৩ -->
            <div class="card">
                <img src="https://placeholder.com" alt="Mobile Recharge">
                <h3>মোবাইল রিচার্জ</h3>
                <button onclick="orderNow('Mobile Recharge')">রিচার্জ করুন</button>
            </div>
        </div>
    </div>

    <script>
        function orderNow(serviceName) {
            alert(serviceName + " এর জন্য অর্ডার পেজটি শীঘ্রই আসছে!");
        }
    </script>
</body>
</html>
