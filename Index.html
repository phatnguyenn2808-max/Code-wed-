<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hello Kitty Store - Final Optimized 🎀</title>
    <link href="https://googleapis.com" rel="stylesheet">
    <style>
        :root { --pink: #ffafcc; --pink-light: #ffc2d1; --bg: #fff5f8; --text: #5e548e; }
        * { box-sizing: border-box; -webkit-tap-highlight-color: transparent; }
        body { font-family: 'Quicksand', sans-serif; background: var(--bg); color: var(--text); margin: 0; overflow-x: hidden; touch-action: pan-y; }

        /* --- NƠ & HOA RƠI --- */
        .ribbon { position: fixed; top: 10px; right: 10px; font-size: 40px; z-index: 1100; animation: bounce 2s infinite; }
        @keyframes bounce { 0%, 100% { transform: translateY(0); } 50% { transform: translateY(-10px); } }
        .petal { position: fixed; top: -10%; z-index: 99; pointer-events: none; animation: fall linear forwards; }
        @keyframes fall { to { transform: translateY(110vh) rotate(360deg); } }

        /* --- NAVBAR & SIDEBAR --- */
        nav { background: white; padding: 12px 15px; display: flex; align-items: center; justify-content: space-between; box-shadow: 0 2px 10px rgba(255,175,204,0.2); position: sticky; top: 0; z-index: 1000; }
        .logo { font-weight: 700; color: var(--pink); display: flex; align-items: center; gap: 5px; }
        #sidebar { position: fixed; top: 0; left: -280px; width: 260px; height: 100%; background: white; transition: 0.3s; z-index: 2001; padding: 20px; border-radius: 0 30px 30px 0; box-shadow: 5px 0 15px rgba(0,0,0,0.1); }
        .sidebar-active { left: 0 !important; }
        .menu-link { display: block; padding: 15px; color: var(--text); text-decoration: none; font-weight: 700; border-radius: 15px; margin-bottom: 8px; cursor: pointer; border: 1px solid #fff0f5; }

        .container { padding: 15px; max-width: 900px; margin: auto; }
        .section-title { text-align: center; color: var(--pink); font-size: 1.4rem; margin: 30px 0 15px; border-bottom: 3px solid var(--pink-light); padding-bottom: 8px; font-weight: 800; }
        
        /* --- DANH MỤC MUA (20-50-100-200-500) --- */
        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(140px, 1fr)); gap: 15px; }
        .card { background: white; padding: 20px; border-radius: 30px; text-align: center; border: 3px solid var(--pink-light); transition: 0.3s; cursor: pointer; }
        .card:hover { transform: translateY(-8px); border-color: var(--pink); }
        .card img { width: 50px; margin-bottom: 5px; }
        .price { background: var(--pink); color: white; padding: 5px 12px; border-radius: 20px; font-weight: 700; display: inline-block; }

        /* --- MỤC NẠP TIỀN (SỬA LẠI) --- */
        .pay-box { background: white; padding: 25px; border-radius: 30px; border: 3px dashed var(--pink-light); text-align: center; margin-bottom: 20px; }
        input, select { width: 100%; padding: 12px; border-radius: 12px; border: 1px solid #eee; margin-bottom: 10px; outline: none; font-family: inherit; }
        .qr-frame { background: white; padding: 15px; border-radius: 20px; display: inline-block; border: 2px solid var(--pink-light); margin: 15px 0; }
        .btn-pink { width: 100%; padding: 15px; border: none; border-radius: 15px; background: var(--pink); color: white; font-weight: bold; cursor: pointer; }

        /* --- LỊCH SỬ ĐƠN --- */
        .bill-card { background: white; padding: 20px; border-radius: 25px; border: 2px solid var(--pink-light); margin-bottom: 20px; text-align: left; }
        .bill-header { display: flex; justify-content: space-between; border-bottom: 1px dashed var(--pink-light); padding-bottom: 10px; margin-bottom: 10px; font-weight: 800; color: var(--pink); }
        .btn-copy { width: 100%; padding: 10px; border: none; border-radius: 12px; background: var(--pink); color: white; font-weight: bold; cursor: pointer; margin-top: 10px; }

        .page { display: none; }
        .active-page { display: block !important; }
        #overlay { display: none; position: fixed; inset: 0; background: rgba(0,0,0,0.2); z-index: 2000; backdrop-filter: blur(4px); }
    </style>
</head>
<body>

    <div class="ribbon">🎀</div>

    <nav>
        <div onclick="toggleMenu()" style="cursor:pointer; font-size:1.5rem; color:var(--pink)">☰</div>
        <div class="logo">KITTY<span>CLOUD</span> ☁️</div>
        <div style="width:25px"></div>
    </nav>

    <div id="sidebar">
        <center><img src="https://pngimg.com" width="60"></center>
        <h3 style="color:var(--pink); text-align:center;">MENU 🎀</h3>
        <div class="menu-link" onclick="showPage('home')">🌸 Danh Mục Mua</div>
        <div class="menu-link" onclick="showPage('pay')">💳 Nạp Tiền / QR</div>
        <div class="menu-link" onclick="showPage('history')">⏳ Lịch Sử Đơn</div>
        <div class="menu-link" onclick="showPage('settings')">⚙️ Cài Đặt</div>
        <div class="menu-link" onclick="toggleMenu()" style="color:#ffafcc; text-align:center; margin-top:30px;">✕ Đóng</div>
    </div>
    <div id="overlay" onclick="toggleMenu()"></div>

    <div class="container">
        
        <!-- TRANG CHỦ: MỤC MUA (20-50-100-200-500) -->
        <div id="page-home" class="page active-page">
            <div class="section-title">☁️ CLOUD PHONE</div>
            <div class="grid">
                <div class="card" onclick="askBuy('Cloud 20k')"><img src="https://pngimg.com"><h4>Cloud SVIP</h4><div class="price">20.000đ</div></div>
                <div class="card" onclick="askBuy('Cloud 50k')"><img src="https://pngimg.com"><h4>Cloud SVIP</h4><div class="price">50.000đ</div></div>
                <div class="card" onclick="askBuy('Cloud 100k')"><img src="https://pngimg.com"><h4>Cloud SVIP</h4><div class="price">100.000đ</div></div>
                <div class="card" onclick="askBuy('Cloud 200k')"><img src="https://pngimg.com"><h4>Cloud SVIP</h4><div class="price">200.000đ</div></div>
                <div class="card" onclick="askBuy('Cloud 500k')"><img src="https://pngimg.com"><h4>Cloud SVIP</h4><div class="price">500.000đ</div></div>
            </div>

            <div class="section-title" style="margin-top:40px;">📶 DATA UNLIMIT</div>
            <div class="grid">
                <div class="card" onclick="askBuy('Data 20k')"><img src="https://pngimg.com" style="filter:hue-rotate(150deg)"><h4>Data 5G</h4><div class="price">20.000đ</div></div>
                <div class="card" onclick="askBuy('Data 50k')"><img src="https://pngimg.com" style="filter:hue-rotate(150deg)"><h4>Data 5G</h4><div class="price">50.000đ</div></div>
                <div class="card" onclick="askBuy('Data 100k')"><img src="https://pngimg.com" style="filter:hue-rotate(150deg)"><h4>Data 5G</h4><div class="price">100.000đ</div></div>
                <div class="card" onclick="askBuy('Data 200k')"><img src="https://pngimg.com" style="filter:hue-rotate(150deg)"><h4>Data 5G</h4><div class="price">200.000đ</div></div>
                <div class="card" onclick="askBuy('Data 500k')"><img src="https://pngimg.com" style="filter:hue-rotate(150deg)"><h4>Data 5G</h4><div class="price">500.000đ</div></div>
            </div>
        </div>

        <!-- TRANG NẠP TIỀN (SỬA LẠI QR & FORM) -->
        <div id="page-pay" class="page">
            <div class="section-title">💳 NẠP TIỀN TÀI KHOẢN</div>
            <div class="pay-box">
                <p style="font-weight:bold; color:var(--pink);">NẠP THẺ CÀO AUTO</p>
                <select><option>Viettel</option><option>Mobi</option><option>Vina</option></select>
                <select>
                    <option>20.000đ</option><option>50.000đ</option><option>100.000đ</option><option>200.000đ</option><option>500.000đ</option>
                </select>
                <input type="text" placeholder="Mã số thẻ"><input type="text" placeholder="Số Seri">
                <button class="btn-pink">GỬI THẺ NGAY 🌸</button>
            </div>
            <div class="pay-box">
                <p style="font-weight:bold; color:var(--pink);">QUÉT MÃ QR BANK / MOMO</p>
                <div class="qr-frame">
                    <img src="https://qrserver.com" width="160" style="border-radius:10px;">
                </div>
                <p style="font-size:0.9rem;"><b>MB BANK:</b> 0123.456.789<br><b>Chủ TK:</b> HELLO KITTY<br>Nội dung: <b>NAPTIEN</b></p>
            </div>
        </div>

        <!-- TRANG LỊCH SỬ -->
        <div id="page-history" class="page">
            <div class="section-title">⏳ CHI TIẾT ĐƠN HÀNG</div>
            <div class="bill-card">
                <div class="bill-header"><span>#CLOUD778</span><span>10:30 - 07/04</span></div>
                <p>📍 IP: <b>103.155.xx.xx</b></p>
                <p>👤 User: <b>admin_kitty</b></p>
                <p>🔑 Pass: <b>kitty123</b></p>
                <button class="btn-copy" onclick="alert('Đã sao chép!')">Sao chép thông tin</button>
            </div>
            <div class="bill-card">
                <div class="bill-header"><span>#DATA112</span><span>09:15 - 07/04</span></div>
                <p>🔗 Link V2Ray:</p>
                <p style="word-break:break-all; font-size:0.7rem; background:#f5f5f5; padding:10px; border-radius:10px;">vmess://eyJhZGQiOiI0NS4xMjQuOTQuIiwicG9ydCI6IjQ0MyIsImlkIjoiZjI3Z...</p>
                <button class="btn-copy" onclick="alert('Đã sao chép Link!')">Sao chép Link</button>
            </div>
        </div>

        <!-- TRANG CÀI ĐẶT -->
        <div id="page-settings" class="page">
            <div class="section-title">⚙️ CÀI ĐẶT</div>
            <div class="pay-box">
                <p><b>Chủ TK:</b> HELLO KITTY 🎀</p>
                <p><b>Số dư:</b> <span style="color:var(--pink); font-weight:bold;">1.500.000đ</span></p>
                <hr style="border:1px solid #fff5f8; margin:20px 0;">
                <input type="password" placeholder="Mật khẩu cũ">
                <input type="password" placeholder="Mật khẩu mới">
                <button class="btn-pink">LƯU CÀI ĐẶT</button>
            </div>
        </div>

    </div>

    <script>
        function toggleMenu() {
            const s = document.getElementById('sidebar');
            const o = document.getElementById('overlay');
            s.classList.toggle('sidebar-active');
            o.style.display = s.classList.contains('sidebar-active') ? 'block' : 'none';
        }
        function showPage(id) {
            document.querySelectorAll('.page').forEach(p => p.classList.remove('active-page'));
            document.getElementById('page-' + id).classList.add('active-page');
            toggleMenu();
            window.scrollTo(0,0);
        }
        function askBuy(item) {
            if (confirm("🎀 Bạn muốn mua " + item + " không?")) {
                alert("Mua thành công! Xem thông tin tại Lịch Sử 🌸");
            }
        }
        setInterval(() => {
            const p = document.createElement('div');
            p.innerHTML = "🌸"; p.className = 'petal';
            p.style.left = Math.random() * 100 + 'vw';
            p.style.animationDuration = Math.random() * 3 + 2 + 's';
            document.body.appendChild(p);
            setTimeout(() => p.remove(), 5000);
        }, 500);
    </script>
</body>
</html>
