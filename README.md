<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <title>سينما أونلاين</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #111;
            color: white;
            text-align: center;
        }

        header {
            background-color: #000;
            padding: 20px;
            font-size: 30px;
            color: red;
        }

        .movie-container {
            margin-top: 40px;
        }

        .movie-card {
            background-color: #1c1c1c;
            width: 300px;
            margin: auto;
            padding: 15px;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(255,0,0,0.5);
        }

        .movie-card img {
            width: 100%;
            border-radius: 10px;
        }

        .movie-title {
            margin: 10px 0;
            font-size: 20px;
        }

        .play-btn {
            background-color: red;
            border: none;
            padding: 10px 20px;
            color: white;
            font-size: 16px;
            cursor: pointer;
            border-radius: 5px;
        }

        .play-btn:hover {
            background-color: darkred;
        }
    </style>
</head>
<body>

<header>
🎥 سينما أونلاين
</header>

<div class="movie-container">
    <div class="movie-card">
        <img src="https://via.placeholder.com/300x400" alt="Movie Poster">
        <div class="movie-title">اسم الفيلم</div>
        <button class="play-btn" onclick="playMovie()">▶ تشغيل</button>
    </div>
</div>

<script>
    function playMovie() {
        alert("سيتم تشغيل الفيلم 🎬");
    }
</script>

</body>
</html>
