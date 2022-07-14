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
                <a href=" https://hopamchuan.com/ ">Hợp âm </a>
                <a href="#">ZALO</a>
                <a href=" https://www.facebook.com/tatca.dm.1 ">FACEBOOK</a>
                <a href="bai java.io/javacript.html/"<Bàitậpcủatôi </a>
                <a href="#">HẾT</a>  
            </div>
            <button class="hamburger">
                <span></span>
                <span></span>
                <span></span>
            </button>
        </nav>

        <div class="benefit">
            <span class="icon">
                <img src="https://www.kindpng.com/picc/m/149-1492010_music-logo-png-182-take-off-your-pants.png" alt="icon">
            </span>

            <h1 class="disclaim">Giới thiệu các dạng dụng cụ âm nhạc</h1>

            <div class="container">
                <div class="content">
                    <h3>Đàn Guitar</h3>
                    <p>Cây đàn guitar là một công cụ âm nhạc phổ biến trên toàn thế giới. Guitar tạo ra âm thanh bằng cách sử dụng một hộp gỗ hoặc nhựa và gỗ rỗng (cho một cây guitar acoustic), hoặc thông qua bộ khuếch đại điện và loa). Đâylà một loại nhạc cụ có phím và dây.</p>
                </div>
                <div class="content">
                    <h3>Đàn Tranh</h3>
                    <p>Cây đàn guitar là một công cụ âm nhạc phổ biến trên toàn thế giới. Guitar tạo ra âm thanh bằng cách sử dụng một hộp gỗ hoặc nhựa và gỗ rỗng (cho một cây guitar acoustic), hoặc thông qua bộ khuếch đại điện và loa). Đâylà một loại nhạc cụ có phím và dây.</p>
                </div>
                <div class="content">
                    <h3>Đàn Piano</h3>
                    <p>Đàn piano là một nhạc cụ thuộc bộ dây phím, trong đó âm thanh được phát ra khi búa đàn đánh vào dây, đây là một nhạc cụ sử dụng bàm phím, người chơi sẽ dùng đôi bàn tay chạm vào từng phím đàn để búa đàn đánh vào ra từ đó phát ra âm thanh</p>
                </div>
                <div class="content">
                    <h3>Đàn Violin</h3>
                    <p>Đàn Violin thường được sử dụng trong nhiều thể loại nhạc khác nhau. Phổ biến nhất là trong các dàn nhạc giao hưởng cổ điển, nhạc Jazz, Pop..... Đàm Violin cơ bản gồm bốn dây, mỗi dây cách nhau một quãng năm đúng. Violin được phát triển vào thế kỉ 16 tại Italia.</p>
                </div>
            </div>
        </div>
    </body>
</html>
