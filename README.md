[index.html](https://github.com/user-attachments/files/25618445/index.html)
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>栖屿涂料 - 赋空间以自然之色</title>
    <style>
        :root {
            --primary-color: #2c3e50; /* 深邃石墨色 */
            --accent-color: #8da399;  /* 栖屿绿 - 莫兰迪色系 */
            --bg-light: #f9f9f9;
        }

        body { font-family: "Microsoft YaHei", sans-serif; margin: 0; color: #333; line-height: 1.6; }
        
        /* 导航栏 */
        nav { display: flex; justify-content: space-between; align-items: center; padding: 20px 10%; background: #fff; position: sticky; top: 0; z-index: 1000; box-shadow: 0 2px 5px rgba(0,0,0,0.05); }
        .logo { font-size: 24px; font-weight: bold; color: var(--primary-color); letter-spacing: 2px; }
        .nav-links a { margin-left: 30px; text-decoration: none; color: #666; transition: 0.3s; }
        .nav-links a:hover { color: var(--accent-color); }

        /* 英雄横幅区 */
        .hero { 
            height: 80vh; 
            background: linear-gradient(rgba(0,0,0,0.3), rgba(0,0,0,0.3)), url('https://images.unsplash.com/photo-1589939705384-5185137a7f0f?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80'); 
            background-size: cover;
            background-position: center;
            display: flex; flex-direction: column; justify-content: center; align-items: center; color: #fff; text-align: center;
        }
        .hero h1 { font-size: 3rem; margin-bottom: 10px; letter-spacing: 5px; }
        .hero p { font-size: 1.2rem; opacity: 0.9; }

        /* 产品展示 */
        .products { padding: 80px 10%; background: var(--bg-light); text-align: center; }
        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 30px; margin-top: 40px; }
        .product-card { background: #fff; padding: 20px; border-radius: 8px; transition: transform 0.3s; cursor: pointer; }
        .product-card:hover { transform: translateY(-10px); }
        .color-drop { width: 60px; height: 60px; border-radius: 50% 50% 50% 0; transform: rotate(-45deg); margin: 0 auto 20px; }

        /* 页脚 */
        footer { background: var(--primary-color); color: #fff; padding: 50px 10%; text-align: center; }
    </style>
</head>
<body>

<nav>
    <div class="logo">栖屿 | QIYU</div>
    <div class="nav-links">
        <a href="#">首页</a>
        <a href="#">产品系列</a>
        <a href="#">色彩灵感</a>
        <a href="#">关于我们</a>
    </div>
</nav>

<section class="hero">
    <h1>栖于自然，屿见色彩</h1>
    <p>高品质环保涂料，为你打造会呼吸的家</p>
</section>

<section class="products">
    <h2>核心产品系列</h2>
    <div class="grid">
        <div class="product-card">
            <div class="color-drop" style="background: #e0d5c1;"></div>
            <h3>原石系列</h3>
            <p>提取深山矿石质感，还原最纯粹的触感。</p>
        </div>
        <div class="product-card">
            <div class="color-drop" style="background: #a7bcad;"></div>
            <h3>林间系列</h3>
            <p>净味环保，把森林的清新带入卧室。</p>
        </div>
        <div class="product-card">
            <div class="color-drop" style="background: #8799a3;"></div>
            <h3>晨雾系列</h3>
            <p>丝绒般柔滑，光泽内敛，适配现代极简风。</p>
        </div>
    </div>
</section>

<footer>
    <p>© 2026 栖屿涂料有限公司 版权所有</p>
    <p>联系电话：400-xxx-xxxx | 地址：中国·某个美丽的城市</p>
</footer>

</body>
</html>
