
hello

file:///Users/mini/Desktop/%E1%84%8B%E1%85%B0%E1%86%B8%E1%84%80%E1%85%A2%E1%84%87%E1%85%A1%E1%86%AF%20%E1%84%8E%E1%85%AC%E1%84%8C%E1%85%A9%E1%86%BC.html

[Uploading 웹개발 최종.html…]()<!DOCTYPE html><img width="543" alt="스크린샷 2024-12-11 오후 4 20 36" src="https://github.com/user-attachments/assets/a6aac0a7-294b-4367-96ef-7d0603263a81" />
<img width="543" alt="스크린샷 2024-12-11 오후 4 17 10" src="https://github.com/user-attachments/assets/c5a49537-2488-48cc-bcdb-be5a332298e1" />
<img width="551" alt="스크린샷 2024-12-11 오후 4 16 16" src="https://github.com/user-attachments/assets/5e027747-3658-4247-931e-c088b853ed3e" />
<img width="960" alt="스크린샷 2024-12-11 오후 4 11 03" src="https://github.com/user-attachments/assets/8853ee25-f61b-4968-a966-cb8f28dea63b" />

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>웹개발 기말 과제 </title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background-color: #f4f4f4;
            position: relative;
            overflow-x: hidden;
        }

        header {
            background-color: lightblue;
            color: #fff;
            text-align: center;
            padding: 1rem 0;
        }

        .title-section {
            text-align: center;
            padding: 1rem;
            background-color: #f4f4f4;
        }

        .title-section h2 {
            margin: 0.5rem 0;
            font-size: 2rem;
            color: #333;
        }

        .title-section p {
            font-size: 1rem;
            color: #666;
        }

        .main-photo {
            text-align: center;
            margin: 1rem;
        }

        .main-photo img {
            width: 80%;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .main-photo .description {
            margin-top: 0.5rem;
            font-size: 1.2rem;
            color: lightblue;
        }

        .album {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1rem;
            padding: 1rem;
        }

        .album-item {
            position: relative;
            overflow: hidden;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .album-item img {
            width: 100%;
            height: auto;
            display: block;
            transition: transform 0.3s ease;
        }

        .album-item:hover img {
            transform: scale(1.1);
        }

        .album-item .description {
            margin-top: 0.5rem;
            font-size: 1rem;
            color: #555;
        }

        footer {
            text-align: center;
            padding: 1rem;
            background-color: #333;
            color: #fff;
        }

        /* Snowflake styling */
        .snowflake {
            position: fixed;
            top: -10px;
            left: 50%;
            font-size: 1rem;
            color: white;
            opacity: 0.8;
            pointer-events: none;
            animation: fall linear infinite;
        }

        @keyframes fall {
            0% {
                transform: translateY(0) translateX(0);
            }
            100% {
                transform: translateY(100vh) translateX(-50px);
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>MY WINTER FAVORITE MOVIES</h1>
    </header>

    <div class="title-section">
        <h2>겨울 영화 3편 추천</h2>
        <p>“겨울 방학을 맞이하여 겨울에 보기 좋은 영화 3편을 소개합니다.” </p>  

        <p>길고 긴 방학 속 영화 3편 정도 보는 것 어떨까요?</p> 
            
        <p>겨울이 생각나는 영화들입니다.</p>
            
    </div>

    <div class="main-photo">
        <img src="/Users/mini/Desktop/웹개발 사진 /스크린샷 2024-12-11 오후 4.11.03.png" alt="Main Image">
        <div class="description">겨울 영화 3편....</div>
    </div>

    <div class="album">
        <div class="album-item">
            <img src="/Users/mini/Desktop/웹개발 사진 /스크린샷 2024-12-11 오후 4.16.16.png" alt="Image 1">
            <div class="description">헤어질 결심 </div>
            <p>완벽한 미장센과 이야기 흐름</p> 

            <p>추운겨울 바다가 떠오르는 영화</p>
                
             <p>안개 속에서 헤메이는 사람들</p>
        </div>
        <div class="album-item">
            <img src="/Users/mini/Desktop/웹개발 사진 /스크린샷 2024-12-11 오후 4.17.10.png" alt="Image 2">
            <div class="description">러브레터</div>
            <p>겨울 영화의 기본 </p>
            <p>당신은 잘 지내나요?</p>
            <p>올 겨울 눈이 많이오면 다시금 생각나는 영화</p>
        </div>
        <div class="album-item">
            <img src="/Users/mini/Desktop/웹개발 사진 /스크린샷 2024-12-11 오후 4.20.36.png" alt="Image 3">
            <div class="description">시애틀에 잠 못 이루는 밤 </div>
            <p>라디오로 시작된 이야기</p>
            <p>색다른 연말 영화를 원한다면</p>
            <p>운명을 믿는다면 </p>
        </div>
    </div>

    <footer>
        <p>&copy; 2201709 박정민</p>
    </footer>

    <script>
        // JavaScript for snow effect
        function createSnowflake() {
            const snowflake = document.createElement('div');
            snowflake.classList.add('snowflake');
            snowflake.style.left = Math.random() * 100 + 'vw';
            snowflake.style.animationDuration = Math.random() * 3 + 2 + 's';
            snowflake.style.fontSize = Math.random() * 10 + 10 + 'px';
            snowflake.textContent = '❄';

            document.body.appendChild(snowflake);

            setTimeout(() => {
                snowflake.remove();
            }, 5000);
        }

        setInterval(createSnowflake, 200);
    </script>
</body>
</html>

