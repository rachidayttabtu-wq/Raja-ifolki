<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ifolki raja - المنتجات التقليدية</title>
    <style>
        body {
            font-family: 'Tahoma', sans-serif;
            margin: 0;
            background-color: #fff8f0;
            color: #333;
        }
        header {
            background-color: #d4af37;
            color: white;
            padding: 15px 0;
            text-align: center;
            font-size: 1.8rem;
            font-weight: bold;
        }
        nav {
            background-color: #333;
            display: flex;
            justify-content: center;
            gap: 20px;
            padding: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            color: #d4af37;
        }
        .about {
            text-align: center;
            padding: 20px;
            max-width: 800px;
            margin: auto;
        }
        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 15px;
            padding: 20px;
        }
        .product {
            background-color: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0px 3px 8px rgba(0,0,0,0.1);
            text-align: center;
        }
        .product img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        .product h3 {
            margin: 10px 0;
            color: #d4af37;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 15px;
        }
        .social a {
            color: #d4af37;
            margin: 0 10px;
            text-decoration: none;
            font-size: 1.2rem;
        }
    </style>
</head>
<body>

<header>
    ifolki raja
</header>

<nav>
    <a href="#about">عن البراند</a>
    <a href="#products">المنتجات</a>
    <a href="#contact">تواصل معنا</a>
</nav>

<section class="about" id="about">
    <h2>عن ifolki raja</h2>
    <p>متجر متخصص في بيع أجمل المنتجات التقليدية المغربية، من القفاطين الراقية، الفخار المزخرف، والزّرابي اليدوية، بجودة عالية ولمسة أصيلة.</p>
</section>

<section class="products" id="products">
    <div class="product">
        <img src="https://i.imgur.com/EgRrFfL.jpg" alt="قفطان">
        <h3>قفطان مغربي</h3>
    </div>
    <div class="product">
        <img src="https://i.imgur.com/kJ5rB6Z.jpg" alt="فخار">
        <h3>فخار مزخرف</h3>
    </div>
    <div class="product">
        <img src="https://i.imgur.com/SyYfdfA.jpg" alt="زرابي">
        <h3>زربية أمازيغية</h3>
    </div>
</section>

<footer id="contact">
    <p>تواصل معنا عبر:</p>
    <div class="social">
        <a href="https://wa.me/212600000000" target="_blank">واتساب</a>
        <a href="https://instagram.com/" target="_blank">انستغرام</a>
    </div>
    <p>© 2025 ifolki raja - جميع الحقوق محفوظة</p>
</footer>

</body>
</html>

