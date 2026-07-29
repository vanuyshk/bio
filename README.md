<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Мой сайт</title>

    <style>
        *{
            margin:0;
            padding:0;
            box-sizing:border-box;
            font-family:Arial,sans-serif;
        }

        body{
            background:#111;
            color:white;
        }

        header{
            background:#1f1f1f;
            padding:20px;
            text-align:center;
        }

        nav a{
            color:white;
            text-decoration:none;
            margin:0 15px;
        }

        .hero{
            height:80vh;
            display:flex;
            flex-direction:column;
            justify-content:center;
            align-items:center;
            text-align:center;
            background:linear-gradient(135deg,#4f46e5,#7c3aed);
        }

        .hero h1{
            font-size:50px;
            margin-bottom:15px;
        }

        .hero p{
            font-size:20px;
            margin-bottom:25px;
        }

        button{
            padding:15px 30px;
            border:none;
            border-radius:10px;
            background:white;
            color:#4f46e5;
            font-size:18px;
            cursor:pointer;
        }

        button:hover{
            transform:scale(1.05);
        }

        footer{
            padding:20px;
            text-align:center;
            background:#1f1f1f;
        }
    </style>
</head>
<body>

<header>
    <h2>Мой сайт</h2>
    <nav>
        <a href="#">Главная</a>
        <a href="#">Обо мне</a>
        <a href="#">Контакты</a>
    </nav>
</header>

<section class="hero">
    <h1>Добро пожаловать!</h1>
    <p>Этот сайт размещён на GitHub Pages.</p>
    <button onclick="hello()">Нажми меня</button>
</section>

<footer>
    © 2026 Мой сайт
</footer>

<script>
function hello(){
    alert("Спасибо за посещение!");
}
</script>

</body>
</html>
