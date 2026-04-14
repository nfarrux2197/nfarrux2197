<div align="center">

# 👋 Hi, I'm <a href="https://github.com/nfarrux2197">Farrux</a>
<p><em>Backend Developer — Python, Flask, Django</em></p>

<img src="./assets/profile_eye.svg" alt="Animated eye" width="160"/>

</div>

---

## 📊 Stats & Visitors

- Profile views (live):  
  <img src="https://komarev.com/ghpvc/?username=nfarrux2197&style=flat-square" alt="Profile views" />

- Quick GitHub stats:  
  <img src="https://github-readme-stats.vercel.app/api?username=nfarrux2197&show_icons=true&theme=radical" alt="GitHub stats" />

---

## 💻 Technologies

### Backend & Fullstack
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white) ![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white) ![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=white) ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)

### Frontend
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white) ![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E) ![Jinja2](https://img.shields.io/badge/Jinja2-323232?style=for-the-badge&logo=jinja&logoColor=white)

### Databases & Tools
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

---

## 📬 Contact

<div align="center">
<a href="https://t.me/GG_LOLIMNOTDIE_GG"><img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"/></a>
<a href="https://www.linkedin.com/in/farrux-nurmetov-a031493a0/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:nfarrux2197@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/></a>
</div>

<?xml version="1.0" encoding="UTF-8"?>
<svg xmlns="http://www.w3.org/2000/svg" width="320" height="80" viewBox="0 0 320 80" role="img" aria-label="Animated eye">
  <defs>
    <linearGradient id="g" x1="0" x2="1">
      <stop offset="0" stop-color="#6EE7B7"/>
      <stop offset="1" stop-color="#60A5FA"/>
    </linearGradient>
  </defs>

  <!-- Eye background -->
  <g transform="translate(20,10)">
    <ellipse cx="60" cy="30" rx="90" ry="30" fill="#0f172a" opacity="0.08"/>
    <ellipse cx="60" cy="30" rx="82" ry="26" fill="white"/>
    <!-- iris -->
    <circle cx="60" cy="30" r="16" fill="url(#g)">
      <animate attributeName="r" dur="2.4s" values="14;18;14" repeatCount="indefinite" />
      <animate attributeName="cx" dur="3.2s" values="58;62;58" repeatCount="indefinite" />
    </circle>
    <!-- pupil -->
    <circle cx="60" cy="30" r="7" fill="#061826">
      <animate attributeName="r" dur="2.4s" values="6;8;6" repeatCount="indefinite" />
    </circle>

    <!-- highlight -->
    <circle cx="52" cy="24" r="3.2" fill="white" opacity="0.9">
      <animate attributeName="cy" dur="4s" values="24;26;24" repeatCount="indefinite" />
    </circle>

    <!-- blinking eyelid -->
    <path d="M-5,30 C30,-4 90,-4 125,30" fill="#0f172a">
      <animate attributeName="d" dur="6s" repeatCount="indefinite"
        values="
          M-5,30 C30,-4 90,-4 125,30;
          M-5,30 C30,30 90,30 125,30;
          M-5,30 C30,-4 90,-4 125,30
        " />
    </path>
  </g>

  <!-- label and live views placeholder -->
  <g transform="translate(170,20)" font-family="Segoe UI, Roboto, Arial" fill="#0f172a">
    <text x="0" y="18" font-size="12" fill="#374151">Profile</text>
    <text x="0" y="38" font-size="20" font-weight="700" fill="#0f172a">Views</text>

    <!-- animated bars -->
    <g transform="translate(80,6)">
      <rect x="0" y="20" width="6" height="24" rx="2" fill="#60A5FA">
        <animate attributeName="height" dur="2s" values="8;28;12;28" repeatCount="indefinite" />
        <animate attributeName="y" dur="2s" values="36;20;32;20" repeatCount="indefinite" />
      </rect>
      <rect x="12" y="8" width="6" height="36" rx="2" fill="#34D399">
        <animate attributeName="height" dur="2.2s" values="16;36;20;36" repeatCount="indefinite" />
        <animate attributeName="y" dur="2.2s" values="32;8;28;8" repeatCount="indefinite" />
      </rect>
      <rect x="24" y="14" width="6" height="30" rx="2" fill="#A78BFA">
        <animate attributeName="height" dur="1.8s" values="10;30;14;30" repeatCount="indefinite" />
        <animate attributeName="y" dur="1.8s" values="40;14;36;14" repeatCount="indefinite" />
      </rect>
    </g>
  </g>
</svg>
