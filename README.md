# Game
GaholisN 
<!DOCTYPE html>
<html lang="zh-TW">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>GaholisN 最終戰線 (完整版)</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* --- 核心設定 --- */
        body { 
            font-family: 'PingFang TC', 'Microsoft JhengHei', sans-serif; 
            background-color: #0f172a; /* Slate 900 */
            color: white;
            overflow: hidden; 
            user-select: none; 
            touch-action: manipulation;
        }

        /* --- 特效動畫 --- */
        @keyframes float { 0%, 100% { transform: translateY(0); } 50% { transform: translateY(-10px); } }
        @keyframes pulse-gold { 0% { box-shadow: 0 0 0 0 rgba(234, 179, 8, 0.7); } 70% { box-shadow: 0 0 0 10px rgba(234, 179, 8, 0); } 100% { box-shadow: 0 0 0 0 rgba(234, 179, 8, 0); } }
        @keyframes pop-damage { 0% { transform: scale(0.5) translateY(0); opacity: 0; } 20% { transform: scale(1.2) translateY(-10px); opacity: 1; } 100% { transform: scale(1) translateY(-30px); opacity: 0; } }
        @keyframes shake { 0%, 100% { transform: translateX(0); } 20% { transform: translateX(-5px); } 40% { transform: translateX(5px); } 60% { transform: translateX(-5px); } 80% { transform: translateX(5px); } }
