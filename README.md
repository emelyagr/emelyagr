- 👋 Hi, I’m @emelyagr
- ✨ I’m interested in Information security and Steganography
- 🌱 I’m currently learning in Moscow Plekhanov Russian University of Economics
- 👀 (C) Emelyanov Grigory Andreevich. All rights reserved. Use (copying, collection, processing, storage, distribution, provision and other actions, and other reproduction in any form) of any materials, articles, books, courses, program codes, programs and all contained materials (and information) without full indication of the author and sources and/or permission of the author is prohibited.
- ✨(С) Емельянов Григорий Андреевич. Все права защищены. Использование (копирование, сбор, обработка, хранение, распространение, предоставление и другие действия, и иное воспроизведение в какой бы то ни было форме) любых материалов, статей, книг, курсов, программных кодов, программ и всех содержащихся материалов (и информации) без полного указания автора и источников и/или разрешения автора запрещено.
<!---
emelyagr/emelyagr is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=emelyagr&theme=tokyonight&show_icons=true)](https://github.com/anuraghazra/github-readme-stats)

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Космическое движение</title>
    <style>
        body {
            margin: 0;
            overflow: hidden;
            background-color: black;
            color: white;
        }
        .star {
            position: absolute;
            width: 5px;
            height: 5px;
            background-color: white;
            border-radius: 50%;
            animation: twinkle 1s infinite alternate;
        }
        @keyframes twinkle {
            0% { opacity: 1; }
            100% { opacity: 0.5; }
        }
    </style>
</head>
<body>

<script>
    function createStar() {
        const star = document.createElement('div');
        star.className = 'star';
        const x = Math.random() * window.innerWidth;
        const y = Math.random() * window.innerHeight;
        star.style.transform = `translate(${x}px, ${y}px)`;
        document.body.appendChild(star);

        // Анимация движения звезды
        let directionX = Math.random() < 0.5 ? 1 : -1;
        let directionY = Math.random() < 0.5 ? 1 : -1;

        setInterval(() => {
            const currentX = parseFloat(star.style.transform.split('(')[1]);
            const currentY = parseFloat(star.style.transform.split(',')[1]);
            star.style.transform = `translate(${currentX + directionX}px, ${currentY + directionY}px)`;

            // Меняем направление, если звезда выходит за границы
            if (currentX > window.innerWidth || currentX < -5) directionX *= -1;
            if (currentY > window.innerHeight || currentY < -5) directionY *= -1;
        }, 50);
    }

    // Создаем звезды
    for (let i = 0; i < 100; i++) {
        createStar();
    }
</script>

</body>
