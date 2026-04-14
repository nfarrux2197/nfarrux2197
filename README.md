<div align="center">

# 👋 Hi, I'm <a href="https://github.com/nfarrux2197">Farrux</a>
<p><em style="color:#9CA3AF">Backend Developer — Python · Flask · Django</em></p>

<!-- Dark aesthetic SVG -->
<img src="./assets/profile_eye.svg" alt="Animated eye" width="560" style="max-width:100%; border-radius:12px; box-shadow: 0 8px 30px rgba(8,10,16,0.7)"/>

</div>

---

## 📊 Stats & Visitors

- Profile views (live):  
  <img src="https://komarev.com/ghpvc/?username=nfarrux2197&style=flat-square" alt="Profile views" />

- GitHub stats (dark):  
  <img src="https://github-readme-stats.vercel.app/api?username=nfarrux2197&show_icons=true&theme=dark" alt="GitHub stats" />

---

## 💻 Technologies (Aesthetic dark badges)

<div align="center">
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-111827?style=for-the-badge&logo=flask&logoColor=white)
![Django](https://img.shields.io/badge/Django-0B1220?style=for-the-badge&logo=django&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-1F3B63?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-1E293B?style=for-the-badge&logo=docker&logoColor=white)
</div>

---

## 📬 Contact

<div align="center">
<a href="https://t.me/GG_LOLIMNOTDIE_GG"><img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"/></a>
<a href="https://www.linkedin.com/in/farrux-nurmetov-a031493a0/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:nfarrux2197@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/></a>
</div>

<!-- Tip: поменяй theme=dark на другие темы в github-readme-stats по желанию -->

<?xml version="1.0" encoding="UTF-8"?>
<svg xmlns="http://www.w3.org/2000/svg" width="560" height="140" viewBox="0 0 560 140" role="img" aria-label="Aesthetic dark animated eye">
  <defs>
    <linearGradient id="neon" x1="0" x2="1">
      <stop offset="0" stop-color="#7C3AED"/>
      <stop offset="0.5" stop-color="#06B6D4"/>
      <stop offset="1" stop-color="#60A5FA"/>
    </linearGradient>
    <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="8" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <radialGradient id="irisGrad" cx="30%" cy="35%">
      <stop offset="0" stop-color="#E6F3FF"/>
      <stop offset="0.25" stop-color="#7C3AED"/>
      <stop offset="1" stop-color="#031026"/>
    </radialGradient>
  </defs>

  <!-- dark rounded panel background -->
  <rect x="6" y="6" rx="14" width="548" height="128" fill="#071123" opacity="0.98"/>
  <g filter="url(#glow)">
    <rect x="8" y="8" rx="12" width="544" height="124" fill="none" stroke="url(#neon)" stroke-opacity="0.06" stroke-width="2"/>
  </g>

  <!-- decorative corner accents -->
  <path d="M20 20 L52 20" stroke="#1F2937" stroke-width="2" stroke-linecap="round" opacity="0.6"/>
  <path d="M540 120 L508 120" stroke="#1F2937" stroke-width="2" stroke-linecap="round" opacity="0.6"/>

  <!-- center eye group -->
  <g transform="translate(80,10)">
    <!-- outer subtle shadow -->
    <ellipse cx="200" cy="60" rx="180" ry="44" fill="#000" opacity="0.25"/>
    <!-- sclera -->
    <path d="M20 60 C80 10 320 10 380 60 C320 110 80 110 20 60 Z" fill="#081225"/>
    <path d="M32 60 C86 22 314 22 368 60 C314 98 86 98 32 60 Z" fill="#0B1220" stroke="#081827" stroke-width="0.6"/>

    <!-- iris group -->
    <g id="iris" transform="translate(160,60)">
      <circle r="34" fill="url(#irisGrad)" />
      <circle r="18" fill="#021627" opacity="0.9">
        <animate attributeName="r" dur="2.6s" values="17;20;17" repeatCount="indefinite" />
      </circle>
      <!-- neon ring -->
      <circle r="44" fill="none" stroke="url(#neon)" stroke-width="1.6" opacity="0.22">
        <animateTransform attributeName="transform" attributeType="XML" type="rotate" from="0" to="360" dur="18s" repeatCount="indefinite"/>
      </circle>
      <!-- glossy highlight -->
      <ellipse cx="-12" cy="-10" rx="8" ry="5" fill="white" opacity="0.9">
        <animate attributeName="cx" dur="4s" values="-14;-10;-14" repeatCount="indefinite"/>
      </ellipse>
    </g>

    <!-- pupil -->
    <g transform="translate(240,70)">
      <circle cx="-80" cy="-10" r="12" fill="#000" opacity="0.95">
        <animate attributeName="r" dur="2.8s" values="10;13;10" repeatCount="indefinite"/>
      </circle>
      <!-- tiny moving spark -->
      <circle cx="-92" cy="-22" r="2.2" fill="#FFFFFF" opacity="0.9">
        <animate attributeName="cx" dur="3.4s" values="-94;-90;-94" repeatCount="indefinite"/>
        <animate attributeName="cy" dur="3.4s" values="-24;-20;-24" repeatCount="indefinite"/>
      </circle>
    </g>

    <!-- subtle animated noise lines for aesthetic -->
    <g stroke="#0EA5A4" stroke-opacity="0.06" stroke-width="1">
      <path d="M40 30 Q120 18 200 30 T360 30">
        <animate attributeName="d" dur="7s" repeatCount="indefinite"
          values="
            M40 30 Q120 18 200 30 T360 30;
            M40 32 Q120 12 200 32 T360 32;
            M40 30 Q120 18 200 30 T360 30
          "/>
      </path>
    </g>

    <!-- right side "Views" badge area -->
    <g transform="translate(420,22)" font-family="Segoe UI, Roboto, Arial" fill="#9CA3AF">
      <text x="0" y="12" font-size="10" fill="#6B7280">Profile</text>
      <text x="0" y="34" font-size="18" font-weight="700" fill="#E6EEF8">Views</text>
      <!-- animated bars -->
      <g transform="translate(48,8)">
        <rect x="0" y="24" width="6" height="20" rx="2" fill="#60A5FA">
          <animate attributeName="height" dur="2.2s" values="10;24;12;24" repeatCount="indefinite" />
          <animate attributeName="y" dur="2.2s" values="34;24;32;24" repeatCount="indefinite" />
        </rect>
        <rect x="10" y="10" width="6" height="34" rx="2" fill="#7C3AED">
          <animate attributeName="height" dur="2.6s" values="16;34;20;34" repeatCount="indefinite" />
          <animate attributeName="y" dur="2.6s" values="34;10;28;10" repeatCount="indefinite" />
        </rect>
        <rect x="20" y="16" width="6" height="28" rx="2" fill="#06B6D4">
          <animate attributeName="height" dur="1.8s" values="12;28;14;28" repeatCount="indefinite" />
          <animate attributeName="y" dur="1.8s" values="36;16;34;16" repeatCount="indefinite" />
        </rect>
      </g>
    </g>
  </g>

  <!-- tiny floating particles -->
  <g fill="#60A5FA" opacity="0.12">
    <circle cx="32" cy="28" r="2">
      <animate attributeName="cy" dur="6s" values="28;22;28" repeatCount="indefinite"/>
    </circle>
    <circle cx="500" cy="46" r="1.6">
      <animate attributeName="cx" dur="5s" values="500;490;500" repeatCount="indefinite"/>
    </circle>
    <circle cx="460" cy="92" r="1.2">
      <animate attributeName="cy" dur="4.5s" values="92;86;92" repeatCount="indefinite"/>
    </circle>
  </g>

</svg><div align="center">

# 👋 Hi, I'm <a href="https://github.com/nfarrux2197">Farrux</a>
<p><em style="color:#9CA3AF">Backend Developer — Python · Flask · Django</em></p>

<!-- Dark aesthetic SVG -->
<img src="./assets/profile_eye.svg" alt="Animated eye" width="560" style="max-width:100%; border-radius:12px; box-shadow: 0 8px 30px rgba(8,10,16,0.7)"/>

</div>

---

## 📊 Stats & Visitors

- Profile views (live):  
  <img src="https://komarev.com/ghpvc/?username=nfarrux2197&style=flat-square" alt="Profile views" />

- GitHub stats (dark):  
  <img src="https://github-readme-stats.vercel.app/api?username=nfarrux2197&show_icons=true&theme=dark" alt="GitHub stats" />

---

## 💻 Technologies (Aesthetic dark badges)

<div align="center">
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-111827?style=for-the-badge&logo=flask&logoColor=white)
![Django](https://img.shields.io/badge/Django-0B1220?style=for-the-badge&logo=django&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-1F3B63?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-1E293B?style=for-the-badge&logo=docker&logoColor=white)
</div>

---

## 📬 Contact

<div align="center">
<a href="https://t.me/GG_LOLIMNOTDIE_GG"><img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"/></a>
<a href="https://www.linkedin.com/in/farrux-nurmetov-a031493a0/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:nfarrux2197@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/></a>
</div>

<!-- Tip: поменяй theme=dark на другие темы в github-readme-stats по желанию -->

<?xml version="1.0" encoding="UTF-8"?>
<svg xmlns="http://www.w3.org/2000/svg" width="560" height="140" viewBox="0 0 560 140" role="img" aria-label="Aesthetic dark animated eye">
  <defs>
    <linearGradient id="neon" x1="0" x2="1">
      <stop offset="0" stop-color="#7C3AED"/>
      <stop offset="0.5" stop-color="#06B6D4"/>
      <stop offset="1" stop-color="#60A5FA"/>
    </linearGradient>
    <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="8" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <radialGradient id="irisGrad" cx="30%" cy="35%">
      <stop offset="0" stop-color="#E6F3FF"/>
      <stop offset="0.25" stop-color="#7C3AED"/>
      <stop offset="1" stop-color="#031026"/>
    </radialGradient>
  </defs>

  <!-- dark rounded panel background -->
  <rect x="6" y="6" rx="14" width="548" height="128" fill="#071123" opacity="0.98"/>
  <g filter="url(#glow)">
    <rect x="8" y="8" rx="12" width="544" height="124" fill="none" stroke="url(#neon)" stroke-opacity="0.06" stroke-width="2"/>
  </g>

  <!-- decorative corner accents -->
  <path d="M20 20 L52 20" stroke="#1F2937" stroke-width="2" stroke-linecap="round" opacity="0.6"/>
  <path d="M540 120 L508 120" stroke="#1F2937" stroke-width="2" stroke-linecap="round" opacity="0.6"/>

  <!-- center eye group -->
  <g transform="translate(80,10)">
    <!-- outer subtle shadow -->
    <ellipse cx="200" cy="60" rx="180" ry="44" fill="#000" opacity="0.25"/>
    <!-- sclera -->
    <path d="M20 60 C80 10 320 10 380 60 C320 110 80 110 20 60 Z" fill="#081225"/>
    <path d="M32 60 C86 22 314 22 368 60 C314 98 86 98 32 60 Z" fill="#0B1220" stroke="#081827" stroke-width="0.6"/>

    <!-- iris group -->
    <g id="iris" transform="translate(160,60)">
      <circle r="34" fill="url(#irisGrad)" />
      <circle r="18" fill="#021627" opacity="0.9">
        <animate attributeName="r" dur="2.6s" values="17;20;17" repeatCount="indefinite" />
      </circle>
      <!-- neon ring -->
      <circle r="44" fill="none" stroke="url(#neon)" stroke-width="1.6" opacity="0.22">
        <animateTransform attributeName="transform" attributeType="XML" type="rotate" from="0" to="360" dur="18s" repeatCount="indefinite"/>
      </circle>
      <!-- glossy highlight -->
      <ellipse cx="-12" cy="-10" rx="8" ry="5" fill="white" opacity="0.9">
        <animate attributeName="cx" dur="4s" values="-14;-10;-14" repeatCount="indefinite"/>
      </ellipse>
    </g>

    <!-- pupil -->
    <g transform="translate(240,70)">
      <circle cx="-80" cy="-10" r="12" fill="#000" opacity="0.95">
        <animate attributeName="r" dur="2.8s" values="10;13;10" repeatCount="indefinite"/>
      </circle>
      <!-- tiny moving spark -->
      <circle cx="-92" cy="-22" r="2.2" fill="#FFFFFF" opacity="0.9">
        <animate attributeName="cx" dur="3.4s" values="-94;-90;-94" repeatCount="indefinite"/>
        <animate attributeName="cy" dur="3.4s" values="-24;-20;-24" repeatCount="indefinite"/>
      </circle>
    </g>

    <!-- subtle animated noise lines for aesthetic -->
    <g stroke="#0EA5A4" stroke-opacity="0.06" stroke-width="1">
      <path d="M40 30 Q120 18 200 30 T360 30">
        <animate attributeName="d" dur="7s" repeatCount="indefinite"
          values="
            M40 30 Q120 18 200 30 T360 30;
            M40 32 Q120 12 200 32 T360 32;
            M40 30 Q120 18 200 30 T360 30
          "/>
      </path>
    </g>

    <!-- right side "Views" badge area -->
    <g transform="translate(420,22)" font-family="Segoe UI, Roboto, Arial" fill="#9CA3AF">
      <text x="0" y="12" font-size="10" fill="#6B7280">Profile</text>
      <text x="0" y="34" font-size="18" font-weight="700" fill="#E6EEF8">Views</text>
      <!-- animated bars -->
      <g transform="translate(48,8)">
        <rect x="0" y="24" width="6" height="20" rx="2" fill="#60A5FA">
          <animate attributeName="height" dur="2.2s" values="10;24;12;24" repeatCount="indefinite" />
          <animate attributeName="y" dur="2.2s" values="34;24;32;24" repeatCount="indefinite" />
        </rect>
        <rect x="10" y="10" width="6" height="34" rx="2" fill="#7C3AED">
          <animate attributeName="height" dur="2.6s" values="16;34;20;34" repeatCount="indefinite" />
          <animate attributeName="y" dur="2.6s" values="34;10;28;10" repeatCount="indefinite" />
        </rect>
        <rect x="20" y="16" width="6" height="28" rx="2" fill="#06B6D4">
          <animate attributeName="height" dur="1.8s" values="12;28;14;28" repeatCount="indefinite" />
          <animate attributeName="y" dur="1.8s" values="36;16;34;16" repeatCount="indefinite" />
        </rect>
      </g>
    </g>
  </g>

  <!-- tiny floating particles -->
  <g fill="#60A5FA" opacity="0.12">
    <circle cx="32" cy="28" r="2">
      <animate attributeName="cy" dur="6s" values="28;22;28" repeatCount="indefinite"/>
    </circle>
    <circle cx="500" cy="46" r="1.6">
      <animate attributeName="cx" dur="5s" values="500;490;500" repeatCount="indefinite"/>
    </circle>
    <circle cx="460" cy="92" r="1.2">
      <animate attributeName="cy" dur="4.5s" values="92;86;92" repeatCount="indefinite"/>
    </circle>
  </g>

</svg>
