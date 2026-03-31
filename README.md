<svg width="900" height="260" viewBox="0 0 900 260" xmlns="http://www.w3.org/2000/svg">

  <rect width="100%" height="100%" fill="black"/>

  <radialGradient id="core" cx="50%" cy="50%" r="50%">
    <stop offset="0%" stop-color="#000000"/>
    <stop offset="50%" stop-color="#020202"/>
    <stop offset="100%" stop-color="#000000"/>
  </radialGradient>

  <rect width="100%" height="100%" fill="url(#core)"/>

  <g fill="white">

    <circle r="1.5">
      <animate attributeName="cx" values="0;450;0" dur="12s" repeatCount="indefinite"/>
      <animate attributeName="cy" values="40;130;220" dur="14s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.8;0" dur="12s" repeatCount="indefinite"/>
    </circle>

    <circle r="1.3">
      <animate attributeName="cx" values="900;450;900" dur="13s" repeatCount="indefinite"/>
      <animate attributeName="cy" values="200;120;40" dur="15s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.7;0" dur="13s" repeatCount="indefinite"/>
    </circle>

  </g>

  <circle cx="450" cy="130" r="55" fill="black">
    <animate attributeName="r" values="50;60;50" dur="5s" repeatCount="indefinite"/>
  </circle>

  <text x="50%" y="48%" text-anchor="middle"
    fill="white"
    font-size="40"
    font-family="Arial"
    letter-spacing="3">
    JORGE LUIS DIAS
  </text>

  <text x="50%" y="65%" text-anchor="middle"
    fill="#CCCCCC"
    font-size="15"
    letter-spacing="4">
    SQL • PYTHON • MACHINE LEARNING
  </text>

</svg>
