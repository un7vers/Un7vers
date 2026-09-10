
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Make a wish for the future while giving support to a vision & A Dream</title>
    <style>
        :root {
            --primary: #00D632; /* Cash App Green */
            --primary-dark: #00b32a;
            --bg-dark: #0F172A;
            --card-bg: #1E293B;
            --text-main: #F8FAFC;
            --text-muted: #94A3B8;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
        }

        body {
            background-color: var(--bg-dark);
            color: var(--text-main);
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }

        .container {
            background-color: var(--card-bg);
            border-radius: 24px;
            padding: 40px 30px;
            width: 100%;
            max-width: 420px;
            text-align: center;
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.3), 0 10px 10px -5px rgba(0, 0, 0, 0.2);
            border: 1px solid rgba(255, 255, 255, 0.05);
        }

        .profile-img {
            width: 90px;
            height: 90px;
            background: linear-gradient(135deg, var(--primary), #00ff62);
            border-radius: 50%;
            margin: 0 auto 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 36px;
            font-weight: bold;
            color: var(--bg-dark);
            box-shadow: 0 0 20px rgba(0, 214, 50, 0.2);
        }

        h1 {
            font-size: 24px;
            margin-bottom: 8px;
            font-weight: 700;
        }

        .cashtag {
            color: var(--primary);
            font-weight: 600;
            font-size: 16px;
            margin-bottom: 30px;
            display: inline-block;
            background: rgba(0, 214, 50, 0.1);
            padding: 6px 16px;
            border-radius: 20px;
        }

        .jar-container {
            position: relative;
            width: 120px;
            height: 150px;
            margin: 0 auto 35px;
        }

        .jar {
            width: 100%;
            height: 100%;
            border: 5px solid var(--text-main);
            border-radius: 20px 20px 40px 40px;
            position: relative;
            overflow: hidden;
            background: rgba(255, 255, 255, 0.02);
        }

        .jar::before {
            content: '';
            position: absolute;
            top: 0;
            left: 15%;
            width: 70%;
            height: 12px;
            border-bottom: 5px solid var(--text-main);
            border-left: 5px solid var(--text-main);
            border-right: 5px solid var(--text-main);
            border-radius: 0 0 10px 10px;
        }

        .coin {
            width: 24px;
            height: 24px;
            background: #FBBF24;
            border: 2px solid #D97706;
            border-radius: 50%;
            position: absolute;
            top: -30px;
            left: 50%;
            transform: translateX(-50%);
            z-index: 10;
        }

        @keyframes dropCoin {
            0% { top: -30px; transform: translateX(-50%) rotate(0deg); opacity: 1; }
            70% { top: 110px; transform: translateX(-50%) rotate(360deg); opacity: 1; }
            100% { top: 115px; transform: translateX(-50%) rotate(380deg); opacity: 1; }
        }

        .preset-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 12px;
            margin-bottom: 16px;
        }

        .btn-preset {
            background-color: rgba(255, 255, 255, 0.05);
            border: 2px solid transparent;
            color: var(--text-main);
            padding: 14px;
            font-size: 16px;
            font-weight: 600;
            border-radius: 12px;
            cursor: pointer;
            transition: all 0.2s ease;
        }

        .btn-preset:hover {
            background-color: rgba(255, 255, 255, 0.1);
        }

        .btn-preset.active {
            border-color: var(--primary);
            background-color: rgba(0, 214, 50, 0.1);
            color: var(--primary);
        }

        .custom-input-container {
            position: relative;
            margin-bottom: 30px;
        }

        .custom-input-container span {
            position: absolute;
            left: 16px;
            top: 50%;
            transform: translateY(-50%);
            font-size: 18px;
            font-weight: 600;
            color: var(--text-muted);
            transition: color 0.2s;
        }

        .custom-input {
            width: 100%;
            background-color: rgba(255, 255, 255, 0.05);
            border: 2px solid transparent;
            border-radius: 12px;
            padding: 16px 16px 16px 35px;
            color: var(--text-main);
            font-size: 18px;
            font-weight: 600;
            outline: none;
            transition: all 0.2s;
        }

        .custom-input:focus {
            border-color: var(--primary);
            background-color: rgba(255, 255, 255, 0.08);
        }

        .custom-input:focus + span {
            color: var(--primary);
        }

        .btn-submit {
            width: 100%;
            background-color: var(--primary);
            color: #000000;
            border: none;
            padding: 18px;
            font-size: 18px;
            font-weight: 700;
            border-radius: 14px;
            cursor: pointer;
            transition: transform 0.1s, background-color 0.2s;
            box-shadow: 0 4px 14px rgba(0, 214, 50, 0.3);
        }

        .btn-submit:hover {
            background-color: var(--primary-dark);
        }

        .btn-submit:active {
            transform: scale(0.98);
        }

        /* Hide arrow buttons inside numbers input */
        input::-webkit-outer-spin-button,
        input::-webkit-inner-spin-button {
            -webkit-appearance: none;
            margin: 0;
        }
        input[type=number] {
            -moz-appearance: textfield;
        }
    </style>
</head>
<body>

    <div class="container">
        <div class="profile-img">$</div>
        <h1>The Wishing Well</h1>
        <div class="cashtag">Thad Jacob</div>

        <div class="jar-container">
            <div id="coin" class="coin" style="display: none;"></div>
            <div class="jar"></div>
        </div>

        <div class="preset-grid">
            <button class="btn-preset" onclick="selectPreset(1, this)">$1</button>
            <button class="btn-preset" onclick="selectPreset(5, this)">$5</button>
            <button class="btn-preset" onclick="selectPreset(10, this)">$10</button>
        </div>

        <div class="custom-input-container">
            <input type="number" id="customAmount" class="custom-input" placeholder="Custom Amount" oninput="clearPresets()" min="1">
            <span>$</span>
        </div>

        <button class="btn-submit" onclick="sendTip()">Send Up Your Wish</button>
    </div>

    <script>
        let selectedAmount = 0;

        function animateCoin() {
            const coin = document.getElementById('coin');
            coin.style.display = 'none';
            // Trigger reflow to restart animation
            void coin.offsetWidth; 
            coin.style.display = 'block';
            coin.style.animation = 'dropCoin 0.6s forwards cubic-bezier(0.25, 0.46, 0.45, 0.94)';
        }

        function selectPreset(amount, button) {
            document.querySelectorAll('.btn-preset').forEach(btn => btn.classList.remove('active'));
            button.classList.add('active');
            document.getElementById('customAmount').value = '';
            selectedAmount = amount;
            animateCoin();
        }

        function clearPresets() {
            document.querySelectorAll('.btn-preset').forEach(btn => btn.classList.remove('active'));
            const customVal = document.getElementById('customAmount').value;
            selectedAmount = customVal ? parseFloat(customVal) : 0;
        }

        function sendTip() {
            // If custom input has a value, prioritize it
            const customVal = document.getElementById('customAmount').value;
            if (customVal) {
                selectedAmount = parseFloat(customVal);
            }

            // Construct link (Redirects to baseline handle if no amount is picked)
            let baseUrl = "https://cash.app";
            if (selectedAmount > 0) {
                baseUrl += `/${selectedAmount}`;
            }
            
            window.open(baseUrl, '_blank');
        }
    </script>
</body>
</html>
