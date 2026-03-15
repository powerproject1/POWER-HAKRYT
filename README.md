[15.03.2026 13:43] #𝓟𝓞𝓦𝓔𝓡𝓜𝓞𝓓 POWERLAY ᛜᛄᛄᛋᛪⰓᛁᚤᚳ: `html
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TurboBoost Telegram - Бесплатная накрутка подписчиков</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        :root {
            --primary: #0088cc;
            --secondary: #00bfff;
            --success: #4caf50;
            --danger: #f44336;
            --warning: #ff9800;
            --dark: #1a1a1a;
            --light: #f8f9fa;
            --gradient: linear-gradient(135deg, #0088cc, #00bfff);
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, sans-serif;
            line-height: 1.6;
            color: var(--dark);
            background: var(--light);
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* Header */
        header {
            background: white;
            padding: 20px 0;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            position: sticky;
            top: 0;
            z-index: 100;
        }

        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 2rem;
            font-weight: bold;
            background: var(--gradient);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .stats-bar {
            display: flex;
            gap: 30px;
            align-items: center;
        }

        .stat-item {
            text-align: center;
        }

        .stat-number {
            font-size: 1.5rem;
            font-weight: bold;
            color: var(--primary);
        }

        .stat-label {
            font-size: 0.9rem;
            color: #666;
        }

        /* Main Section */
        main {
            padding: 40px 0;
        }

        .boost-card {
            background: white;
            border-radius: 20px;
            padding: 40px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            margin-bottom: 30px;
        }

        .boost-header {
            text-align: center;
            margin-bottom: 30px;
        }

        .boost-header h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            background: var(--gradient);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .boost-header p {
            color: #666;
            font-size: 1.1rem;
        }

        .form-group {
            margin-bottom: 25px;
        }

        .form-group label {
            display: block;
            margin-bottom: 8px;
            font-weight: 600;
            color: #333;
        }

        .form-control {
            width: 100%;
            padding: 15px;
            border: 2px solid #e0e0e0;
            border-radius: 10px;
            font-size: 16px;
            transition: all 0.3s;
        }

        .form-control:focus {
            outline: none;
            border-color: var(--primary);
            box-shadow: 0 0 0 3px rgba(0,136,204,0.1);
        }

        .input-group {
            display: flex;
            gap: 10px;
            align-items: stretch;
        }

        .input-group .form-control {
            flex: 1;
        }

        .quick-amounts {
            display: flex;
            gap: 10px;
            margin-top: 10px;
            flex-wrap: wrap;
        }

        .quick-btn {
            padding: 8px 16px;
            border: 2px solid #e0e0e0;
            background: white;
            border-radius: 8px;
            cursor: pointer;
            transition: all 0.3s;
            font-weight: 500;
        }
[15.03.2026 13:43] #𝓟𝓞𝓦𝓔𝓡𝓜𝓞𝓓 POWERLAY ᛜᛄᛄᛋᛪⰓᛁᚤᚳ: .quick-btn:hover {
            border-color: var(--primary);
            background: var(--primary);
            color: white;
        }

        .boost-btn {
            width: 100%;
            padding: 18px;
            background: var(--gradient);
            color: white;
            border: none;
            border-radius: 10px;
            font-size: 18px;
            font-weight: bold;
            cursor: pointer;
            transition: all 0.3s;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
        }

        .boost-btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 20px rgba(0,136,204,0.3);
        }

        .boost-btn:disabled {
            opacity: 0.6;
            cursor: not-allowed;
            transform: none;
        }

        /* Progress Section */
        .progress-section {
            display: none;
            margin-top: 30px;
            padding: 20px;
            background: #f8f9fa;
            border-radius: 10px;
        }

        .progress-bar-container {
            background: #e0e0e0;
            border-radius: 10px;
            height: 30px;
            overflow: hidden;
            margin-bottom: 15px;
        }

        .progress-bar {
            height: 100%;
            background: var(--gradient);
            border-radius: 10px;
            transition: width 0.3s ease;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-weight: bold;
        }

        .progress-info {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 15px;
            margin-top: 15px;
        }

        .progress-item {
            text-align: center;
            padding: 10px;
            background: white;
            border-radius: 8px;
        }

        .progress-value {
            font-size: 1.5rem;
            font-weight: bold;
            color: var(--primary);
        }

        .progress-label {
            font-size: 0.9rem;
            color: #666;
        }

        /* Features Section */
        .features {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }

        .feature-card {
            background: white;
            padding: 25px;
            border-radius: 15px;
            text-align: center;
            transition: all 0.3s;
            border: 2px solid transparent;
        }

        .feature-card:hover {
            border-color: var(--primary);
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.1);
        }

        .feature-icon {
            font-size: 3rem;
            color: var(--primary);
            margin-bottom: 15px;
        }

        .feature-title {
            font-size: 1.3rem;
            font-weight: bold;
            margin-bottom: 10px;
        }

        .feature-description {
            color: #666;
            line-height: 1.6;
        }

        /* Results Section */
        .results-section {
            display: none;
            margin-top: 30px;
            padding: 30px;
            background: linear-gradient(135deg, #4caf50, #45a049);
            border-radius: 15px;
            color: white;
            text-align: center;
        }

        .results-title {
            font-size: 2rem;
            margin-bottom: 15px;
        }

        .results-stats {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .result-item {
            background: rgba(255,255,255,0.2);
            padding: 15px;
            border-radius: 10px;
        }

        .result-value {
            font-size: 2rem;
            font-weight: bold;
        }
[15.03.2026 13:43] #𝓟𝓞𝓦𝓔𝓡𝓜𝓞𝓓 POWERLAY ᛜᛄᛄᛋᛪⰓᛁᚤᚳ: .result-label {
            font-size: 0.9rem;
            opacity: 0.9;
        }

        /* Notification */
        .notification {
            position: fixed;
            top: 20px;
            right: 20px;
            padding: 15px 20px;
            border-radius: 10px;
            color: white;
            font-weight: 500;
            z-index: 1000
