<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>UK Software & Solution - Autocount OneSales PalmPos</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background-image: url('https://via.placeholder.com/1200x400'); /* 替换为您的背景图片URL */
            background-size: cover;
            background-position: center;
            color: white;
            padding: 60px 0;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        header h1 {
            font-size: 3rem;
            margin: 0;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }
        header p {
            font-size: 1.2rem;
            text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.5);
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: rgba(51, 51, 51, 0.9);
            padding: 10px 0;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
            transition: background 0.3s ease, transform 0.3s ease;
        }
        nav a:hover {
            background-color: #575757;
            transform: translateY(-3px);
        }
        .container {
            padding: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }
        .product-info, .contact-info {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            margin-bottom: 20px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .product-info:hover, .contact-info:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 12px rgba(0, 0, 0, 0.2);
        }
        .product-info h2, .contact-info h2 {
            color: #4CAF50;
        }
        .product-info ul {
            list-style-type: none;
            padding: 0;
        }
        .product-info ul li {
            padding: 10px 0;
            border-bottom: 1px solid #eee;
        }
        .product-info ul li:last-child {
            border-bottom: none;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
            box-shadow: 0 -4px 6px rgba(0, 0, 0, 0.1);
        }
        .hidden {
            display: none;
        }
        .card {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            margin-bottom: 20px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 12px rgba(0, 0, 0, 0.2);
        }
        .product-image {
            max-width: 100%;
            border-radius: 10px;
            margin-top: 20px;
        }
    </style>
</head>
<body>

<header>
    <h1>UK Software & Solution</h1>
    <p>您的商业解决方案专家</p>
</header>

<nav>
    <a href="#home">首页</a>
    <a href="#product-details">产品详情</a>
    <a href="#contact">联系我们</a>
</nav>

<div class="container" id="home">
    <div class="card product-info">
        <h2>Autocount OneSales PalmPos</h2>
        <p>Autocount OneSales PalmPos是一款功能强大的销售点（POS）系统，专为零售和餐饮业设计。它可以帮助您简化销售流程，提高效率，并提供详细的销售报告。</p>
        <p>主要特点：</p>
        <ul>
            <li>易于使用的界面</li>
            <li>实时库存管理</li>
            <li>多种支付方式支持</li>
            <li>详细的销售报告和分析</li>
        </ul>
    </div>
</div>

<div class="container hidden" id="product-details">
    <div class="card">
        <h2>产品详情</h2>
        <p>了解更多关于Autocount OneSales PalmPos的详细信息：</p>
        <ul>
            <li><strong>版本：</strong>标准版、专业版</li>
            <li><strong>兼容性：</strong>Windows, macOS</li>
            <li><strong>支持：</strong>24/7 客户支持</li>
        </ul>
        <img src="https://via.placeholder.com/800x400" alt="Autocount OneSales PalmPos" class="product-image"> <!-- 替换为您的产品图片URL -->
    </div>
</div>

<div class="container hidden" id="contact">
    <div class="card contact-info">
        <h2>联系我们</h2>
        <p><strong>地址：</strong>123 软件大道，科技城，英国</p>
        <p><strong>电话：</strong>+44 123 456 7890</p>
        <p><strong>邮箱：</strong>info@uksoftwaresolution.com</p>
    </div>
</div>

<footer>
    <p>&copy; 2023 UK Software & Solution. 保留所有权利。</p>
</footer>

<script>
    document.querySelectorAll('nav a').forEach(link => {
        link.addEventListener('click', function(e) {
            e.preventDefault();
            document.querySelectorAll('.container').forEach(div => {
                div.classList.add('hidden');
            });
            document.querySelector(this.getAttribute('href')).classList.remove('hidden');
        });
    });
</script>

</body>
</html>
