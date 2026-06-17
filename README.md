<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to Goodwaller</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }

        .container {
            background: white;
            border-radius: 20px;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
            padding: 60px 40px;
            max-width: 600px;
            text-align: center;
            animation: slideIn 0.6s ease-out;
        }

        @keyframes slideIn {
            from {
                opacity: 0;
                transform: translateY(-30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        h1 {
            color: #333;
            font-size: 3.5em;
            margin-bottom: 20px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            animation: fadeIn 0.8s ease-out;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        p {
            color: #666;
            font-size: 1.2em;
            line-height: 1.8;
            margin-bottom: 30px;
        }

        .emoji {
            font-size: 1.5em;
            margin-right: 10px;
        }

        .button {
            display: inline-block;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 15px 40px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            font-size: 1.1em;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            box-shadow: 0 10px 25px rgba(102, 126, 234, 0.4);
        }

        .button:hover {
            transform: translateY(-3px);
            box-shadow: 0 15px 35px rgba(102, 126, 234, 0.6);
        }

        .decorative-shape {
            position: absolute;
            border-radius: 50%;
            opacity: 0.1;
        }

        .shape1 {
            width: 300px;
            height: 300px;
            background: #667eea;
            top: -100px;
            left: -100px;
        }

        .shape2 {
            width: 200px;
            height: 200px;
            background: #764ba2;
            bottom: -50px;
            right: -50px;
        }
    </style>
</head>
<body>
    <div class="decorative-shape shape1"></div>
    <div class="decorative-shape shape2"></div>
    
    <div class="container">
        <h1><span class="emoji">👋</span>Hello, World!</h1>
        <p>Welcome to my first HTML page! This is where amazing things begin.</p>
        <a href="#" class="button">Explore More</a>
    </div>
</body>
</html>
