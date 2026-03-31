<p align="center">
  <svg width="900" height="260" viewBox="0 0 900 260" xmlns="http://www.w3.org/2000/svg">

    <!-- FUNDO -->
    <rect width="100%" height="100%" fill="black"/>

    <!-- GRADIENTE CENTRAL -->
    <radialGradient id="core" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#000000"/>
      <stop offset="50%" stop-color="#020202"/>
      <stop offset="100%" stop-color="#000000"/>
    </radialGradient>

    <rect width="100%" height="100%" fill="url(#core)"/>

    <!-- PARTÍCULAS DINÂMICAS -->
    <g fill="white">

      <!-- LOOP DE PARTÍCULAS (ENTRANDO E SAINDO DO CENTRO) -->

      <!-- esquerda -> centro -->
      <circle r="1.5">
        <animate attributeName="cx" values="0;450;0" dur="12s" repeatCount="indefinite"/>
        <animate attributeName="cy" values="40;130;220" dur="14s" repeatCount="indefinite"/>
        <animate attributeName="opacity" values="0;0.8;0" dur="12s" repeatCount="indefinite"/>
      </circle>

      <!-- direita -> centro -->
      <circle r="1.3">
        <animate attributeName="cx" values="900;450;900" dur="13s" repeatCount="indefinite"/>
        <animate attributeName="cy" values="200;120;40" dur="15s" repeatCount="indefinite"/>
        <animate attributeName="opacity" values="0;0.7;0" dur="13s" repeatCount="indefinite"/>
      </circle>

      <!-- topo -> centro -->
      <circle r="1.2">
        <animate attributeName="cx" values="200;450;700" dur="16s" repeatCount="indefinite"/>
        <animate attributeName="cy" values="0;130;0" dur="16s" repeatCount="indefinite"/>
        <animate attributeName="opacity" values="0;0.6;0" dur="16s" repeatCount="indefinite"/>
      </circle>

      <!-- baixo -> centro -->
      <circle r="1.6">
        <animate attributeName="cx" values="700;450;200" dur="18s" repeatCount="indefinite"/>
        <animate attributeName="cy" values="260;130;260" dur="18s" repeatCount="indefinite"/>
        <animate attributeName="opacity" values="0;0.8;0" dur="18s" repeatCount="indefinite"/>
      </circle>

    </g>

    <!-- AURA ENERGÉTICA -->
    <circle cx="450" cy="130" r="70" fill="none" stroke="white" stroke-width="0.3" opacity="0.2">
      <animate attributeName="r" values="60;80;60" dur="6s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.1;0.4;0.1" dur="6s" repeatCount="indefinite"/>
    </circle>

    <!-- NÚCLEO -->
    <circle cx="450" cy="130" r="55" fill="black">
      <animate attributeName="r" values="50;60;50" dur="5s" repeatCount="indefinite"/>
    </circle>

    <!-- GLOW DO TEXTO -->
    <defs>
      <filter id="glow">
        <feGaussianBlur stdDeviation="2" result="coloredBlur"/>
        <feMerge>
          <feMergeNode in="coloredBlur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
    </defs>

    <!-- NOME -->
    <text x="50%" y="48%" text-anchor="middle"
      fill="white"
      font-size="40"
      font-family="Orbitron, Arial, sans-serif"
      letter-spacing="3"
      filter="url(#glow)">

      JORGE LUIS DIAS
    </text>

    <!-- SUBTÍTULO -->
    <text x="50%" y="65%" text-anchor="middle"
      fill="#CCCCCC"
      font-size="15"
      font-family="Arial, sans-serif"
      letter-spacing="4">

      SQL • PYTHON • MACHINE LEARNING
    </text>

    <!-- LINHA DE ENERGIA -->
    <line x1="200" y1="190" x2="700" y2="190"
      stroke="white" stroke-width="0.6" opacity="0.2">

      <animate attributeName="stroke-dasharray"
        values="0,1000;200,800;0,1000"
        dur="5s"
        repeatCount="indefinite"/>
    </line>

  </svg>
</p>




<p align="center">
  <svg width="900" height="260" viewBox="0 0 900 260" xmlns="http://www.w3.org/2000/svg">

    <!-- FUNDO -->
    <rect width="100%" height="100%" fill="black"/>

    <!-- GRADIENTE CENTRAL -->
    <radialGradient id="core" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#000000"/>
      <stop offset="50%" stop-color="#020202"/>
      <stop offset="100%" stop-color="#000000"/>
    </radialGradient>

    <rect width="100%" height="100%" fill="url(#core)"/>

    <!-- PARTÍCULAS DINÂMICAS -->
    <g fill="white">

      <!-- LOOP DE PARTÍCULAS (ENTRANDO E SAINDO DO CENTRO) -->

      <!-- esquerda -> centro -->
      <circle r="1.5">
        <animate attributeName="cx" values="0;450;0" dur="12s" repeatCount="indefinite"/>
        <animate attributeName="cy" values="40;130;220" dur="14s" repeatCount="indefinite"/>
        <animate attributeName="opacity" values="0;0.8;0" dur="12s" repeatCount="indefinite"/>
      </circle>

      <!-- direita -> centro -->
      <circle r="1.3">
        <animate attributeName="cx" values="900;450;900" dur="13s" repeatCount="indefinite"/>
        <animate attributeName="cy" values="200;120;40" dur="15s" repeatCount="indefinite"/>
        <animate attributeName="opacity" values="0;0.7;0" dur="13s" repeatCount="indefinite"/>
      </circle>

      <!-- topo -> centro -->
      <circle r="1.2">
        <animate attributeName="cx" values="200;450;700" dur="16s" repeatCount="indefinite"/>
        <animate attributeName="cy" values="0;130;0" dur="16s" repeatCount="indefinite"/>
        <animate attributeName="opacity" values="0;0.6;0" dur="16s" repeatCount="indefinite"/>
      </circle>

      <!-- baixo -> centro -->
      <circle r="1.6">
        <animate attributeName="cx" values="700;450;200" dur="18s" repeatCount="indefinite"/>
        <animate attributeName="cy" values="260;130;260" dur="18s" repeatCount="indefinite"/>
        <animate attributeName="opacity" values="0;0.8;0" dur="18s" repeatCount="indefinite"/>
      </circle>

    </g>

    <!-- AURA ENERGÉTICA -->
    <circle cx="450" cy="130" r="70" fill="none" stroke="white" stroke-width="0.3" opacity="0.2">
      <animate attributeName="r" values="60;80;60" dur="6s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.1;0.4;0.1" dur="6s" repeatCount="indefinite"/>
    </circle>

    <!-- NÚCLEO -->
    <circle cx="450" cy="130" r="55" fill="black">
      <animate attributeName="r" values="50;60;50" dur="5s" repeatCount="indefinite"/>
    </circle>

    <!-- GLOW DO TEXTO -->
    <defs>
      <filter id="glow">
        <feGaussianBlur stdDeviation="2" result="coloredBlur"/>
        <feMerge>
          <feMergeNode in="coloredBlur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
    </defs>

    <!-- NOME -->
    <text x="50%" y="48%" text-anchor="middle"
      fill="white"
      font-size="40"
      font-family="Orbitron, Arial, sans-serif"
      letter-spacing="3"
      filter="url(#glow)">

      JORGE LUIS DIAS
    </text>

    <!-- SUBTÍTULO -->
    <text x="50%" y="65%" text-anchor="middle"
      fill="#CCCCCC"
      font-size="15"
      font-family="Arial, sans-serif"
      letter-spacing="4">

      SQL • PYTHON • MACHINE LEARNING
    </text>

    <!-- LINHA DE ENERGIA -->
    <line x1="200" y1="190" x2="700" y2="190"
      stroke="white" stroke-width="0.6" opacity="0.2">

      <animate attributeName="stroke-dasharray"
        values="0,1000;200,800;0,1000"
        dur="5s"
        repeatCount="indefinite"/>
    </line>

  </svg>
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?color=FFFFFF&size=22&center=true&vCenter=true&width=500&lines=Data+Science;Machine+Learning;Python+%7C+SQL+%7C+Analytics" />
</p>

<h3 align="center">Building intelligence from data</h3>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=venom&color=0:000000,100:111111&height=300&section=header&text=Jorge%20Dias&fontSize=65&fontAlignY=50&fontColor=50C878&font=Orbitron&animation=fadeIn"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?color=50C878&size=25&center=true&vCenter=true&width=500&lines=Estudante+de+Ciências+de+Dados;Python+%7C+Análise+de+Dados;Machine+Learning;SQL" />
</p>



## 🛠️ Tecnologias

![Python](https://img.shields.io/badge/Python-000?style=for-the-badge&logo=python)
![SQL](https://img.shields.io/badge/SQL-000?style=for-the-badge&logo=mysql)
![Pandas](https://img.shields.io/badge/Pandas-000?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/Numpy-000?style=for-the-badge&logo=numpy)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-CC2927?style=for-the-badge&logo=mysql&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=numpy&logoColor=white)


![Python](https://img.shields.io/badge/Python-000000?style=for-the-badge&logo=python&logoColor=white)

![Python](https://img.shields.io/badge/Python-000?style=flat&logo=python)
![Python](https://img.shields.io/badge/Python-000?style=for-the-badge&logo=python)
<p align="center">
  <img src="https://img.shields.io/badge/Python-0A0A0A?style=flat&logo=python&logoColor=50C878"/>
  <img src="https://img.shields.io/badge/SQL-0A0A0A?style=flat&logo=mysql&logoColor=00AEEF"/>
</p>

<p align="center">
  <img height="150em" src="https://github-readme-stats.vercel.app/api?username=jrgdias&show_icons=true&theme=tokyonight&hide_border=true"/>
  <img height="150em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jrgdias&layout=compact&theme=tokyonight&hide_border=true"/>
</p>
