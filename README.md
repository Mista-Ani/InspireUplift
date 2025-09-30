<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>InspireUplift - CelebrateMe</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: Arial, sans-serif;
            padding: 15px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            color: #333;
        }
        .container {
            max-width: 100%;
        }
        .hero {
            text-align: center;
            padding: 30px 15px;
            background: white;
            border-radius: 15px;
            margin: 10px 0;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }
        .hero h1 {
            font-size: 2em;
            margin-bottom: 10px;
            color: #667eea;
        }
        .email-form {
            background: white;
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
            margin: 15px 0;
            text-align: center;
        }
        input[type="email"] {
            width: 100%;
            padding: 15px;
            margin: 10px 0;
            border: 2px solid #e1e1e1;
            border-radius: 10px;
            font-size: 16px;
        }
        button {
            background: #667eea;
            color: white;
            padding: 15px 30px;
            border: none;
            border-radius: 10px;
            cursor: pointer;
            font-size: 16px;
            font-weight: bold;
            width: 100%;
            margin: 10px 0;
        }
        .whatsapp-btn {
            background: #25D366;
            display: block;
            padding: 15px;
            color: white;
            text-decoration: none;
            border-radius: 10px;
            margin: 15px 0;
            font-weight: bold;
            text-align: center;
        }
        .features {
            margin: 20px 0;
        }
        .feature {
            background: white;
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            margin: 15px 0;
            text-align: center;
        }
        .feature h3 {
            color: #667eea;
            margin-bottom: 10px;
        }
        #successMessage {
            display: none;
            color: #25D366;
            margin-top: 20px;
            padding: 15px;
            background: rgba(37, 211, 102, 0.1);
            border-radius: 10px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="hero">
            <h1>🎉 InspireUplift</h1>
            <p>Welcome to CelebrateMe - Palace of Peace</p>
            <p>Celebrating Personalities • Building Community</p>
        </div>

        <div class="features">
            <div class="feature">
                <h3>🌟 Celebrating People</h3>
                <p>Share inspiring stories of everyday heroes</p>
            </div>
            <div class="feature">
                <h3>🎂 Birthday Joy</h3>
                <p>Make every birthday special</p>
            </div>
            <div class="feature">
                <h3>🤝 Brand Partnerships</h3>
                <p>Authentic celebrations for teams</p>
            </div>
        </div>

        <div class="email-form">
            <h3>Join Our Community! 🌈</h3>
            <p>Be the first to get early access</p>
            
            <form id="emailForm">
                <input type="email" placeholder="Enter your email" required>
                <button type="submit">Join Now</button>
            </form>
            
            <div id="successMessage">
                <h3>🎉 Welcome!</h3>
                <p>Thank you for joining InspireUplift!</p>
                <p>Join our WhatsApp community:</p>
                <a href="https://chat.whatsapp.com/YOUR_LINK_HERE" class="whatsapp-btn">💬 Join WhatsApp Group</a>
                <p><small>We'll email you when we launch!</small></p>
            </div>
        </div>
    </div>

    <script>
        document.getElementById('emailForm').addEventListener('submit', function(e) {
            e.preventDefault();
            document.getElementById('successMessage').style.display = 'block';
            this.style.display = 'none';
        });
    </script>
</body>
</html>function
