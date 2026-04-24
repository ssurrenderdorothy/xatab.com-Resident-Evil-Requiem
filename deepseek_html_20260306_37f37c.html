<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Конверт для Иры</title>
  <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&display=swap" rel="stylesheet" />
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      user-select: none;
    }

    body {
      min-height: 100vh;
      background: linear-gradient(145deg, #fddae0 0%, #f7a8b8 100%);
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      font-family: 'Great Vibes', cursive;
      overflow-x: hidden;
      position: relative;
    }

    /* Инструкция */
    .instruction {
      position: fixed;
      top: 20px;
      left: 50%;
      transform: translateX(-50%);
      background: rgba(255, 245, 240, 0.9);
      backdrop-filter: blur(8px);
      padding: 12px 24px;
      border-radius: 60px;
      font-size: 1.5rem;
      font-family: 'Great Vibes', cursive;
      color: #b13e5c;
      box-shadow: 0 6px 18px rgba(0,0,0,0.15);
      cursor: pointer;
      z-index: 20;
      transition: opacity 0.5s ease;
      pointer-events: none;
      letter-spacing: 1px;
    }

    .instruction.hide {
      opacity: 0;
      visibility: hidden;
    }

    /* Обёртка конверта — кликабельная зона */
    .envelope-wrapper {
      cursor: pointer;
      margin: 20px auto;
      z-index: 10;
    }

    /* Конверт */
    .envelope {
      position: relative;
      width: 320px;
      height: 200px;
      background: #fff5ef;
      border-radius: 8px 8px 12px 12px;
      box-shadow: 0 15px 30px rgba(0, 0, 0, 0.2);
      transition: transform 0.3s ease;
    }

    .envelope:hover {
      transform: scale(1.02);
    }

    /* Нижняя часть (тело) */
    .envelope .body {
      position: absolute;
      bottom: 0;
      width: 100%;
      height: 140px;
      background: #fde9e0;
      border-radius: 0 0 12px 12px;
      z-index: 1;
    }

    /* Верхний клапан */
    .envelope .flap {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100px;
      background: #ffe6da;
      border-radius: 8px 8px 0 0;
      clip-path: polygon(0% 0%, 100% 0%, 50% 55%);
      z-index: 3;
      transform-origin: top;
      transition: transform 0.8s cubic-bezier(0.23, 1, 0.32, 1);
      box-shadow: 0 2px 6px rgba(0,0,0,0.05);
    }

    /* Левый боковой клапан */
    .envelope .left-flap {
      position: absolute;
      top: 0;
      left: 0;
      width: 50%;
      height: 140px;
      background: #f7dfd1;
      clip-path: polygon(0% 0%, 100% 0%, 50% 100%);
      z-index: 2;
      transition: transform 0.6s ease;
      transform-origin: left;
    }

    /* Правый боковой клапан */
    .envelope .right-flap {
      position: absolute;
      top: 0;
      right: 0;
      width: 50%;
      height: 140px;
      background: #f7dfd1;
      clip-path: polygon(100% 0%, 0% 0%, 50% 100%);
      z-index: 2;
      transition: transform 0.6s ease;
      transform-origin: right;
    }

    /* Анимация открытия */
    .envelope.open .flap {
      transform: rotateX(180deg);
      z-index: 0;
    }

    .envelope.open .left-flap {
      transform: translateX(-100%) rotateY(20deg);
      opacity: 0;
    }

    .envelope.open .right-flap {
      transform: translateX(100%) rotateY(-20deg);
      opacity: 0;
    }

    /* Текст сообщения */
    .message {
      position: fixed;
      bottom: 15%;
      left: 50%;
      transform: translateX(-50%) scale(0.8);
      background: rgba(255, 248, 245, 0.95);
      backdrop-filter: blur(12px);
      padding: 18px 36px;
      border-radius: 70px;
      font-size: 2.3rem;
      font-family: 'Great Vibes', cursive;
      font-weight: bold;
      color: #bc4e6c;
      text-align: center;
      white-space: nowrap;
      box-shadow: 0 18px 35px rgba(0, 0, 0, 0.2);
      border: 1px solid rgba(255, 200, 200, 0.6);
      opacity: 0;
      visibility: hidden;
      transition: all 0.5s ease;
      z-index: 25;
      letter-spacing: 1px;
      pointer-events: none;
    }

    .message.show {
      opacity: 1;
      visibility: visible;
      transform: translateX(-50%) scale(1);
      bottom: 25%;
    }

    /* Летающие сердечки */
    .heart {
      position: fixed;
      bottom: -20px;
      width: 32px;
      height: 32px;
      pointer-events: none;
      z-index: 99;
      animation: floatHeart 6s linear forwards;
      filter: drop-shadow(0 4px 8px rgba(0,0,0,0.2));
    }

    .heart svg {
      width: 100%;
      height: 100%;
      display: block;
    }

    @keyframes floatHeart {
      0% {
        transform: translateY(0) rotate(0deg);
        opacity: 1;
      }
      80% {
        opacity: 0.9;
      }
      100% {
        transform: translateY(-100vh) rotate(25deg);
        opacity: 0;
      }
    }

    /* Адаптивность */
    @media (max-width: 550px) {
      .envelope {
        width: 260px;
        height: 170px;
      }
      .message {
        font-size: 1.6rem;
        white-space: nowrap;
        padding: 12px 24px;
      }
      .instruction {
        font-size: 1.2rem;
        padding: 8px 18px;
      }
    }

    /* для touch — легкий отклик */
    .envelope-wrapper:active .envelope {
      transform: scale(0.99);
    }
  </style>
</head>
<body>

  <div class="instruction" id="instruction">нажми на меня</div>

  <div class="envelope-wrapper" onclick="openEnvelope()">
    <div class="envelope" id="envelope">
      <div class="flap"></div>
      <div class="left-flap"></div>
      <div class="right-flap"></div>
      <div class="body"></div>
    </div>
  </div>

  <div class="message" id="message">Ира — лучшая девочка на свете</div>

  <script>
    function openEnvelope() {
      const envelope = document.getElementById("envelope");
      const instruction = document.getElementById("instruction");
      // Если уже открыто — не повторяем
      if (envelope.classList.contains("open")) return;
      
      envelope.classList.add("open");
      instruction.classList.add("hide");
      
      setTimeout(() => {
        const msg = document.getElementById("message");
        msg.classList.add("show");
      }, 1500);
    }

    function createHeart() {
      const heart = document.createElement("div");
      heart.classList.add("heart");
      heart.style.left = Math.random() * 100 + "vw";
      heart.style.animationDuration = 4 + Math.random() * 4 + "s"; // разнообразие
      heart.innerHTML = `<svg viewBox="0 0 24 24" fill="url(#heartGrad)" xmlns="http://www.w3.org/2000/svg">
        <defs>
          <linearGradient id="heartGrad" x1="0%" y1="0%" x2="100%" y2="100%">
            <stop offset="0%" stop-color="#ff5e7e"/>
            <stop offset="100%" stop-color="#ff2d55"/>
          </linearGradient>
        </defs>
        <path d="M12 21.35l-1.45-1.32C5.4 15.36 2 12.28 2 8.5 2 6.42 3.42 5 5.5 5c1.54 0 2.99 1.04 3.5 2.44C9.51 6.04 10.96 5 12.5 5 14.58 5 16 6.42 16 8.5c0 3.78-3.4 6.86-8.55 11.54L12 21.35z"/>
      </svg>`;
      document.body.appendChild(heart);
      
      setTimeout(() => {
        if (heart && heart.remove) heart.remove();
      }, 7000);
    }

    // Запускаем сердечки с радостью
    setInterval(createHeart, 320);
  </script>
</body>
</html>
