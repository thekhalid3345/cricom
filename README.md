# cricom
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cricket News</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #007bff;
            color: white;
            padding: 15px;
            text-align: center;
            font-size: 24px;
            font-weight: bold;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #0056b3;
            padding: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
        }
        .container {
            padding: 20px;
            text-align: center;
        }
        .news-card {
            background: white;
            padding: 15px;
            margin: 15px auto;
            max-width: 600px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }
        footer {
            text-align: center;
            padding: 15px;
            background: #007bff;
            color: white;
            position: absolute;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>Cricket News Hub</header>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
    </nav>
    <div class="container" id="home">
        <h2>Latest Cricket News</h2>
        <div class="news-card">
            <h3>Breaking: India Wins Series</h3>
            <p>India secures a historic win against Australia in the final match.</p>
        </div>
        <div class="news-card">
            <h3>Player of the Month</h3>
            <p>Virat Kohli named player of the month after an incredible performance.</p>
        </div>
    </div>
    <div class="container" id="about">
        <h2>About Us</h2>
        <p>Welcome to Cricket News Hub, your ultimate source for the latest cricket updates and news.</p>
    </div>
    <footer>
        &copy; 2025 Cricket News Hub | All rights reserved
    </footer>
</body>
</html>
