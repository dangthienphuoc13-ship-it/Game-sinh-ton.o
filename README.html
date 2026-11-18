# Game-sinh-ton.o
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <title>Mini Battle Royale 3D (Free Fire Style)</title>
    <style>
        body { margin: 0; overflow: hidden; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; user-select: none; }
        #ui-layer {
            position: absolute; top: 0; left: 0; width: 100%; height: 100%;
            pointer-events: none;
        }
        /* Tâm ngắm */
        #crosshair {
            position: absolute; top: 50%; left: 50%;
            width: 20px; height: 20px;
            transform: translate(-50%, -50%);
            color: #00ff00; font-size: 24px; text-align: center; line-height: 20px;
            text-shadow: 0 0 3px #000;
        }
        /* Bảng thông số góc trên phải (Alive / Kills) */
        #stats {
            position: absolute; top: 20px; right: 20px;
            display: flex; gap: 15px;
        }
        .stat-box {
            background: rgba(0, 0, 0, 0.7); color: white;
            padding: 8px 15px; border-radius: 5px;
            font-weight: bold; font-size: 16px; border-left: 4px solid #ff9900;
        }
        /* Thanh máu góc dưới */
        #hp-container {
            position: absolute; bottom: 30px; left: 50%;
            transform: translateX(-50%);
            width: 300px; background: rgba(0,0,0,0.7);
            padding: 5px; border-radius: 5px; text-align: center;
        }
        #hp-bar {
            width: 100%; height: 20px; background: #2ecc71;
            transition: width 0.2s; border-radius: 3px;
        }
        #hp-text {
            color: white; font-weight: bold; font-size: 14px;
            margin-top: 3px;
        }
        /* Cảnh báo ngoài vòng bo */
        #zone-warning {
            position: absolute; top: 80px; left: 50%; transform: translateX(-50%);
            color: #ff3333; font-weight: bold; font-size: 20px;
            text-shadow: 1px 1px 2px black; display: none;
        }
        /* Màn hình bắt đầu / Kết thúc */
        #overlay {
            position: absolute; top: 0; left: 0; width: 100%; height: 100%;
            background: rgba(0, 0, 0, 0.8);
            display: flex; flex-direction: column; justify-content: center; align-items: center;
            color: white; pointer-events: auto; z-index: 10;
        }
        button {
            padding: 15px 40px; font-size: 20px; font-weight: bold;
            background: #ff9900; color: black; border: none; border-radius: 5px;
            cursor: pointer; margin-top: 20px;
        }
        button:hover { background: #ffaa22; }
    </style>
</head>
<body>

<div id="ui-layer">
    <div id="crosshair">+</div>
    <div id="stats">
        <div class="stat-box">SỐNG SÓT: <span id="alive-count">11</span></div>
        <div class="stat-box">HẠ GỤC: <span id="kill-count">0</span></div>
    </div>
    <div id="zone-warning">⚠️ BẠN ĐANG Ở NGOÀI VÒNG BO! ⚠️</div>
    <div id="hp-container">
        <div id="hp-bar"></div>
        <div id="hp-text">HP: 200 / 200</div>
    </div>
</div>

<div id="overlay">
    <h1 id="overlay-title" style="color: #ff9900; font-size: 48px; margin-bottom: 10px;">MINI BATTLE ROYALE</h1>
    <p id="overlay-desc" style="font-size: 18px; text-align: center; line-height: 1.6;">
        Di chuyển: <b>W, A, S, D</b> | Nhảy: <b>Space</b> | Xoay góc nhìn: <b>Chuột</b> | Bắn: <b>Chuột trái</b><br>
        Tiêu diệt toàn bộ kẻ địch và chạy vào vòng bo xanh để giành BOOYAH!
    </p>
    <button
