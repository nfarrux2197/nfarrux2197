<div align="center">

  <!-- Эксклюзивная астрономическая SVG-анимация -->
  <svg width="820" height="300" viewBox="0 0 820 300" xmlns="http://www.w3.org/2000/svg" style="border-radius: 20px; background: #05050f; box-shadow: 0 0 30px rgba(0, 255, 200, 0.15);">
    <defs>
      <!-- Градиент небулы -->
      <radialGradient id="nebula1" cx="25%" cy="35%" r="65%" fx="20%" fy="25%">
        <stop offset="0%" stop-color="#2a0066"/>
        <stop offset="70%" stop-color="#0f0022"/>
        <stop offset="100%" stop-color="#05050f"/>
      </radialGradient>
      <radialGradient id="nebula2" cx="75%" cy="65%" r="55%" fx="80%" fy="70%">
        <stop offset="0%" stop-color="#003366"/>
        <stop offset="100%" stop-color="#05050f"/>
      </radialGradient>
      <!-- Свечение звезды -->
      <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
        <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
        <feMerge>
          <feMergeNode in="coloredBlur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
    </defs>

    <!-- Тёмный космос -->
    <rect width="820" height="300" fill="#05050f"/>

    <!-- Небулы -->
    <ellipse cx="180" cy="110" rx="240" ry="130" fill="url(#nebula1)" opacity="0.75"/>
    <ellipse cx="650" cy="190" rx="190" ry="140" fill="url(#nebula2)" opacity="0.65"/>

    <!-- Много мерцающих звёзд -->
    <!-- Маленькие -->
    <circle cx="60" cy="45" r="2" fill="#ffffff">
      <animate attributeName="opacity" values="0.3;1;0.3" dur="2.8s" repeatCount="indefinite"/>
    </circle>
    <circle cx="140" cy="85" r="1.8" fill="#ffffff">
      <animate attributeName="opacity" values="0.4;1;0.4" dur="3.4s" repeatCount="indefinite"/>
    </circle>
    <circle cx="280" cy="55" r="2.5" fill="#ffffff">
      <animate attributeName="opacity" values="0.2;1;0.2" dur="2.2s" repeatCount="indefinite"/>
    </circle>
    <circle cx="410" cy="120" r="1.5" fill="#ffffff">
      <animate attributeName="opacity" values="0.5;1;0.5" dur="4.1s" repeatCount="indefinite"/>
    </circle>
    <circle cx="520" cy="40" r="2.2" fill="#ffffff">
      <animate attributeName="opacity" values="0.3;1;0.3" dur="2.9s" repeatCount="indefinite"/>
    </circle>
    <circle cx="690" cy="95" r="1.9" fill="#ffffff">
      <animate attributeName="opacity" values="0.4;1;0.4" dur="3.7s" repeatCount="indefinite"/>
    </circle>
    <circle cx="760" cy="220" r="2" fill="#ffffff">
      <animate attributeName="opacity" values="0.25;1;0.25" dur="2.5s" repeatCount="indefinite"/>
    </circle>

    <!-- Яркие звёзды со свечением -->
    <g filter="url(#glow)">
      <circle cx="95" cy="195" r="4.5" fill="#ffeebb">
        <animate attributeName="r" values="3.8;5.2;3.8" dur="3.6s" repeatCount="indefinite"/>
      </circle>
      <circle cx="620" cy="75" r="5.5" fill="#aaffff">
        <animate attributeName="r" values="4.5;6.5;4.5" dur="4.2s" repeatCount="indefinite"/>
      </circle>
    </g>

    <!-- Падающий метеор с хвостом -->
    <g>
      <line x1="380" y1="20" x2="480" y2="110" stroke="#bbddff" stroke-width="3" stroke-linecap="round" opacity="0.9">
        <animate attributeName="x1" values="380;720" dur="7s" repeatCount="indefinite"/>
        <animate attributeName="x2" values="480;820" dur="7s" repeatCount="indefinite"/>
        <animate attributeName="y1" values="20;140" dur="7s" repeatCount="indefinite"/>
        <animate attributeName="y2" values="110;230" dur="7s" repeatCount="indefinite"/>
        <animate attributeName="opacity" values="0;0.9;0" dur="7s" repeatCount="indefinite"/>
      </line>
      <!-- Хвост метеора -->
      <line x1="360" y1="10" x2="410" y2="55" stroke="#88ccff" stroke-width="1.5" opacity="0.6">
        <animate attributeName="x1" values="360;700" dur="7s" repeatCount="indefinite"/>
        <animate attributeName="x2" values="410;750" dur="7s" repeatCount="indefinite"/>
        <animate attributeName="y1" values="10;130" dur="7s" repeatCount="indefinite"/>
        <animate attributeName="y2" values="55;175" dur="7s" repeatCount="indefinite"/>
        <animate attributeName="opacity" values="0;0.6;0" dur="7s" repeatCount="indefinite"/>
      </line>
    </g>

    <!-- Текст в космическом стиле -->
    <text x="410" y="235" font-family="system-ui, Arial Black" font-size="48" font-weight="900" fill="#00ffcc" text-anchor="middle" letter-spacing="-2">
      FARRUX
    </text>
    <text x="410" y="265" font-family="system-ui, Arial" font-size="17" fill="#88ffdd" text-anchor="middle" opacity="0.95">
      Backend Alchemist • Python Sorcerer • Tashkent → Stars
    </text>
  </svg>

  <h1>👋 Привет, я <a href="https://github.com/nfarrux2197">Farrux Nurmetov</a></h1>
  <p><em>Backend Alchemist • Строю масштабируемые системы, которые работают даже под космической нагрузкой</em></p>

</div>

---

## 🔥 Обо мне

Я — backend-разработчик из Ташкента, который превращает идеи в надёжные, быстрые и красивые системы.  
Специализируюсь на высоконагруженных приложениях, чистом коде и современных технологиях.

**В фокусе сейчас:**
- Микросервисы и event-driven архитектура
- Высокая производительность (Django + FastAPI + Redis)
- Docker, CI/CD, оптимизация баз данных
- Интеграция AI в backend-проекты

---

## 💻 Технологический стек

### Backend
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)

### Инфраструктура
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## 📬 Давай на связи

<div align="center">
  <a href="https://t.me/GG_LOLIMNOTDIE_GG"><img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"/></a>
  <a href="https://www.linkedin.com/in/farrux-nurmetov-a031493a0/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:nfarrux2197@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/></a>
</div>

---

**Сделано в Ташкенте с 🔥 и любовью к космосу** 🌌
