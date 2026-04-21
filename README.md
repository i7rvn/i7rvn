<style>
  /* ===== إعدادات متجاوبة عامة ===== */
  * {
    box-sizing: border-box;
  }
  body {
    margin: 0;
    padding: 0;
    background-color: #0d1117; /* خلفية داكنة متوافقة مع الثيم */
  }
  /* جميع الصور تستجيب بشكل تلقائي */
  img {
    max-width: 100%;
    height: auto;
  }
  /* جداول الإحصائيات تصبح قابلة للتمرير أفقياً على الشاشات الصغيرة */
  table {
    display: block;
    width: 100% !important;
    overflow-x: auto;
    -webkit-overflow-scrolling: touch;
    border-spacing: 0 !important;
  }
  /* جعل الخلايا في صفوف عمودية على الجوال */
  @media screen and (max-width: 768px) {
    table tr {
      display: flex;
      flex-direction: column;
      width: 100%;
    }
    table td {
      display: block;
      width: 100% !important;
      padding: 10px 0 !important;
    }
    /* إزالة المسافات الكبيرة حول البطاقات */
    td[style*="padding: 20px"] {
      padding: 15px 5px !important;
    }
    /* تعديل عرض بطاقات الإحصائيات */
    img[width="400"],
    img[width="800"] {
      width: 100% !important;
      height: auto !important;
    }
    /* تكبير خط العناوين قليلاً للوضوح */
    .capsule-render-text {
      font-size: 24px !important;
    }
    /* أيقونات الأدوات تصبح أصغر */
    p[align="center"] span img {
      width: 40px !important;
      height: 40px !important;
    }
  }

  /* الأجهزة اللوحية (تابلت) */
  @media screen and (min-width: 769px) and (max-width: 1024px) {
    img[width="400"] {
      width: 350px !important;
    }
    img[width="800"] {
      width: 700px !important;
    }
    table td {
      padding: 15px !important;
    }
  }

  /* أجهزة سطح المكتب (حاسوب) - الإعدادات الافتراضية */
  @media screen and (min-width: 1025px) {
    /* الحفاظ على الأبعاد الأصلية */
    img[width="400"] {
      width: 400px !important;
    }
    img[width="800"] {
      width: 800px !important;
    }
  }

  /* إخفاء شريط التمرير الأفقي إذا لم يكن ضرورياً */
  ::-webkit-scrollbar {
    height: 5px;
    background: #1a1a2e;
  }
  ::-webkit-scrollbar-thumb {
    background: #ae00ff;
    border-radius: 10px;
  }
  /* دعم الوضع الداكن دائماً */
  .markdown-body {
    background-color: transparent;
  }
  /* جعل الأزرار والشارات قابلة للقراءة على الجوال */
  .badge-img {
    max-width: 100%;
    height: auto;
  }
  /* تحسين مظهر قسم About Me */
  div[style*="background: rgba(0,0,0,0.6)"] p {
    word-break: break-word;
    padding: 0 10px;
  }
  /* الروابط تبقى مرئية */
  a {
    text-decoration: none;
  }
</style>

<!-- هنا يبدأ الكود الأصلي كما هو بالضبط دون أي تعديل -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,50:3b1d78,100:ff4fd8&height=260&section=header&text=Infinity%0ACodes&fontSize=54&fontColor=ffffff&animation=fadeIn&fontAlignY=38&descSize=28&descAlignY=60" />
</p>
<!-- Typing Animation (User's Phrases) -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3500&pause=800&color=AE00FF&center=true&vCenter=true&width=900&lines=Web+Developer;SaaS+Builder;Telegram+Bot+Developer;AI+%26+Backend+Learner" alt="Typing SVG" />
</p>

<!-- Profile Views & Stylish Badges -->
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=i7rvn&label=Profile%20Views&color=AE00FF&style=for-the-badge&abbreviated=true" alt="Profile Views" />
  <img src="https://img.shields.io/badge/Status-Always_Building-111827?style=for-the-badge&logo=rocket&logoColor=FF69B4" alt="Status" />
  <img src="https://img.shields.io/badge/Portfolio-Infinity-000000?style=for-the-badge&logo=About.me&logoColor=white&labelColor=6A0DAD" alt="Portfolio Badge" />
</p>

<!-- Neon Divider -->
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:000000,50:3b1d78,100:ff4fd8&height=4&section=header&text=&fontSize=0" width="100%" />

<!-- About Me Section (3D Card with User's Content) -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:000000,50:3b1d78,100:ff4fd8&height=70&section=header&text=About%20Me&fontSize=28&fontColor=ffffff&animation=fadeIn" />
</p>
    <p><strong style="color: #BD5FFF;">🔭 I’m currently working on</strong> — Website Building & AI-Powered SaaS</p>
    <p><strong style="color: #BD5FFF;">🌱 I’m currently learning</strong> — Advanced AI, Backend Scaling, LLM Ops</p>
    <p><strong style="color: #BD5FFF;">🤝 I’m looking to collaborate on</strong> — Telegram Bots, Open Source AI Tools</p>
    <p><strong style="color: #BD5FFF;">💬 Ask me about</strong> — AI, Bots, SaaS Architecture, Full‑Stack Dev</p>
    <p><strong style="color: #BD5FFF;">🌐 Portfolio</strong> — <a href="https://infinityy-portfolio.netlify.app" style="color: #FF69B4; text-decoration: none; border-bottom: 1px dotted #AE00FF;">infinityy-portfolio.netlify.app</a></p>
  </div>
</div>

<!-- Neon Divider -->
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:000000,50:3b1d78,100:ff4fd8&height=4&section=header&text=&fontSize=0" width="100%" />

<!-- Stats & Activity (3D Cards Layout) -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:000000,50:3b1d78,100:ff4fd8&height=70&section=header&text=Analytics%20and%20Activity&fontSize=28&fontColor=ffffff&animation=fadeIn" />
</p>
<table align="center" style="border-collapse: separate; border-spacing: 20px;">
  <tr>
    <!-- GitHub Stats Card -->
    <td align="center" style="background: rgba(0,0,0,0.6); border-radius: 20px; padding: 20px; border: 1px solid rgba(189,95,255,0.3); box-shadow: 0 15px 35px -5px rgba(138,43,226,0.5); backdrop-filter: blur(4px);">
      <img width="400" src="https://github-readme-stats.vercel.app/api?username=i7rvn&show_icons=true&theme=radical&hide_border=true&bg_color=000000&title_color=BD5FFF&icon_color=AE00FF&text_color=ffffff&border_radius=15&ring_color=AE00FF&count_private=true" alt="GitHub Stats" />
    </td>
    <!-- Streak Stats Card -->
    <td align="center" style="background: rgba(0,0,0,0.6); border-radius: 20px; padding: 20px; border: 1px solid rgba(174,0,255,0.3); box-shadow: 0 15px 35px -5px rgba(138,43,226,0.5); backdrop-filter: blur(4px);">
      <img width="400" src="https://github-readme-streak-stats.herokuapp.com/?user=i7rvn&theme=radical&hide_border=true&background=000000&ring=BD5FFF&fire=FF69B4&currStreakLabel=AE00FF&sideLabels=ffffff&dates=cccccc&stroke=6A0DAD" alt="GitHub Streak" />
    </td>
  </tr>
  <tr>
    <!-- Top Languages Card (Full Width) -->
    <td colspan="2" align="center" style="background: rgba(0,0,0,0.6); border-radius: 20px; padding: 20px; border: 1px solid rgba(189,95,255,0.3); box-shadow: 0 15px 35px -5px rgba(138,43,226,0.5); backdrop-filter: blur(4px);">
      <img width="800" src="https://github-readme-stats.vercel.app/api/top-langs/?username=i7rvn&layout=compact&theme=radical&hide_border=true&bg_color=000000&title_color=BD5FFF&text_color=ffffff&border_radius=15&langs_count=8&card_width=800" alt="Top Languages" />
    </td>
  </tr>
</table>

<br/>

<!-- Neon Divider -->
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:000000,50:3b1d78,100:ff4fd8&height=4&section=header&text=&fontSize=0" width="100%" />

<!-- Neon Skill Badges (Glowing, User's Stack Enhanced) -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:000000,50:3b1d78,100:ff4fd8&height=70&section=header&text=Core%20Stack%20and%20Tools&fontSize=28&fontColor=ffffff&animation=fadeIn" />
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white&labelColor=000000&color=6A0DAD" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB&labelColor=000000&color=BD5FFF" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white&labelColor=000000&color=AE00FF" />
  <img src="https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D&labelColor=000000&color=6A0DAD" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black&labelColor=000000&color=BD5FFF" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white&labelColor=000000&color=AE00FF" />
  <img src="https://img.shields.io/badge/AI_Developer-412991?style=for-the-badge&logo=openai&logoColor=white&labelColor=000000&color=BD5FFF" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white&labelColor=000000&color=AE00FF" />
  <img src="https://img.shields.io/badge/Telegram-Bot-000000?style=for-the-badge&logo=telegram&logoColor=26A5E4&labelColor=000000&color=6A0DAD" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white&labelColor=000000&color=6A0DAD" />
</p>

<br/>

<!-- Neon Divider -->
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:000000,50:3b1d78,100:ff4fd8&height=4&section=header&text=&fontSize=0" width="100%" />

<!-- Languages & Tools Icons (Horizontal, Large, User's Set) -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:000000,50:3b1d78,100:ff4fd8&height=70&section=header&text=Languages%20And%20Tools&fontSize=28&fontColor=ffffff&animation=fadeIn" />
</p>
<p align="center">
  <span style="white-space: nowrap;">
    <a href="https://www.python.org"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="55"/></a>
    <a href="https://reactjs.org/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" width="55"/></a>
    <a href="https://www.typescriptlang.org/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" width="55"/></a>
    <a href="https://vuejs.org/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vuejs/vuejs-original-wordmark.svg" width="55"/></a>
    <a href="https://www.javascript.com/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="55"/></a>
    <a href="https://nodejs.org/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" width="55"/></a>
    <a href="https://www.html.com/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" width="55"/></a>
    <a href="https://www.w3.org/Style/CSS/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" width="55"/></a>
    <a href="https://git-scm.com/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" width="55"/></a>
    <a href="https://www.linux.org/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" width="55"/></a>
    <a href="https://www.mongodb.com/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" width="55"/></a>
    <a href="https://www.mysql.com/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" width="55"/></a>
    <a href="https://www.postgresql.org/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" width="55"/></a>
    <a href="https://www.php.net/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" width="55"/></a>
    <a href="https://www.android.com/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/android/android-plain.svg" width="55"/></a>
    <a href="https://www.java.com/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" width="55"/></a>
  </span>
</p>
<!-- Neon Divider -->
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:000000,50:3b1d78,100:ff4fd8&height=4&section=header&text=&fontSize=0" width="100%" />

<!-- Support Section (User's Buy Me a Coffee) -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:000000,50:3b1d78,100:ff4fd8&height=70&section=header&text=Support%20My%20Work&fontSize=28&fontColor=ffffff&animation=fadeIn" />
</p>

<p align="center">
  <a href="https://www.buymeacoffee.com/i7rvn">
    <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="50" width="210" alt="i7rvn" />
  </a>
</p>

<br/>

<!-- Footer Wave (User's Gradient) -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,50:3b1d78,100:ff4fd8&height=160&section=footer" alt="Footer Wave" />
</p>

</div>
