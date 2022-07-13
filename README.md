<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width,initial-scale=1.0">
        <link rel="stylesheet" href="MUSIC.css">
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
        <script>
            $(function() {
                $(".hamburger").on("click", function() {
                    if($(".menu").hasClass("active")) {
                        $(".menu").removeClass("active");
                    }
                    else {
                        $(".menu").addClass("active")
                    }
                })
            });
        </script>
        <title>Quốc Thịnh và Hành trình trở thành nghệ sĩ nhân dân</title>
    </head>
    <body>
        <div class="banner">
            <div class="slogan">
                <h1 style="color:#FDFCFD">Quốc Thịnh và Hành trình trở thành nghệ sĩ nhân dân</h1>
                <p>Superhotpowermusic</p>
            </div>
        </div>

        <nav class="navbar flex">
            <h1 class="logo">MusicX</h1>
            <div class="menu">
                <a href="#">LỚP HỌC NHẠC</a>
                <a href=" https://hopamchuan.com/ ">Học hợp âm </a>
                <a href="#">ZALO</a>
                <a href=" https://www.facebook.com/tatca.dm.1 ">FACEBOOK</a>
                <a href="#">HẾT</a>  
            </div>
            <button class="hamburger">
                <span></span>
                <span></span>
                <span></span>
            </button>
        </nav>
