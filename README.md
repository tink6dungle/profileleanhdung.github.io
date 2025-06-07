<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <title>myprofile</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
      body {
            min-height: 100vh;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Arial, sans-serif;
            /* Animated gradient background */
            background: linear-gradient(270deg, #74ebd5, #ACB6E5, #ffb347, #ffcc33, #74ebd5);
            background-size: 1000% 1000%;
            animation: gradientMove 12s ease-in-out infinite;
        }
        @keyframes gradientMove {
            0% {background-position:0% 50%;}
            50% {background-position:100% 50%;}
            100% {background-position:0% 50%;}
        }
        .container {
            max-width: 400px;
            margin: 60px auto;
            background: #fff;
            border-radius: 18px;
            box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.2);
            padding: 32px 24px;
            text-align: center;
        }
        .avatar {
            width: 110px;
            height: 110px;
            border-radius: 50%;
            object-fit: cover;
            border: 4px solid #74ebd5;
            margin-bottom: 18px;
            animation: bounce 2s infinite;
        }
        @keyframes bounce {
            0%, 100% { transform: translateY(0);}
            50% { transform: translateY(-18px);}
        }
        h1 {
            margin: 0 0 8px 0;
            font-size: 2em;
            color: #333;
        }
        .desc {
            color: #666;
            margin-bottom: 18px;
        }
        .links a {
            display: inline-block;
            margin: 8px 10px;
            padding: 10px 22px;
            border-radius: 25px;
            background: #74ebd5;
            color: #222;
            text-decoration: none;
            font-weight: 500;
            transition: background 0.2s;
        }
        .links a:hover {
            background: #ACB6E5;
        }
    </style>
</head>
<body>
    <div class="container">
        <img class="avatar" src="https://oj.thptchuyenhatinh.edu.vn/avatar/__sized__/avatar/1024-thumbnail-135x135-70.jpg" alt="Avatar">
        <h1>Lê Anh Dũng</h1>
        <div class="desc">Học sinh - Hà Tĩnh</div>
  <div class="links">
            <a href="mailto:gld020510@gmail.com" style="background:#ffb347; color:#fff;">Email</a>
            <a href="https://www.facebook.com/profile.php?id=100095213373088" target="_blank" style="background:#ACB6E5; color:#fff;">phở bò</a>
            <a href="https://oj.thptchuyenhatinh.edu.vn/user" target="_blank" style="background: #74ebd5; color:#fff;">oj</a>
        </div>
</body>
</html>
