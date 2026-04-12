# yilinwang.github.io
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yilin | Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <nav>
        <div class="logo">YILIN</div>
        <ul>
            <li><a href="#work">Work</a></li>
            <li><a href="#about">About</a></li>
        </ul>
    </nav>

    <main>
        <section id="work" class="grid">
            <div class="item">
                <img src="your-image-1.jpg" alt="Project 1">
                <p>项目名称 / 2026</p>
            </div>
            <div class="item">
                <img src="your-image-2.jpg" alt="Project 2">
                <p>项目名称 / 2026</p>
            </div>
            </section>
    </main>
</body>
</html>

/* 设置字体和基础呼吸感 */
body {
    margin: 0;
    padding: 0 5%;
    background-color: #fcfcfc; /* 极浅米色，比纯白更有质感 */
    color: #333;
    font-family: "Georgia", serif; /* 经典的衬线字体 */
    line-height: 1.6;
}

nav {
    display: flex;
    justify-content: space-between;
    padding: 40px 0;
    text-transform: uppercase;
    letter-spacing: 2px;
}

.grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(400px, 1fr));
    gap: 40px;
    margin-top: 50px;
}

.item img {
    width: 100%;
    filter: grayscale(20%); /* 稍微降低饱和度提升艺术感 */
    transition: filter 0.3s ease;
}

.item img:hover {
    filter: grayscale(0%);
}

.item p {
    font-style: italic;
    margin-top: 15px;
    font-size: 0.9em;
}
