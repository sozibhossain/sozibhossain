3 files changed
+275
-107
README.md
Loading diff
assets/hero.svg
<svg xmlns="http://www.w3.org/2000/svg" width="1200" height="460" viewBox="0 0 1200 460" role="img" aria-labelledby="title desc">
  <title id="title">Md. Sozib Hossain — Full-Stack Web and Mobile App Developer</title>
  <desc id="desc">Animated portfolio banner showing an end-to-end product delivery system.</desc>
  <defs>
    <linearGradient id="panel" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0" stop-color="#0d100d"/>
      <stop offset="1" stop-color="#070907"/>
    </linearGradient>
    <radialGradient id="glow" cx="50%" cy="50%" r="50%">
      <stop offset="0" stop-color="#c7ff4a" stop-opacity=".2"/>
      <stop offset="1" stop-color="#c7ff4a" stop-opacity="0"/>
    </radialGradient>
    <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
      <path d="M 40 0 L 0 0 0 40" fill="none" stroke="#f2f0e8" stroke-opacity=".045" stroke-width="1"/>
    </pattern>
    <filter id="softGlow" x="-80%" y="-80%" width="260%" height="260%">
      <feGaussianBlur stdDeviation="6" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <path id="orbitPath" d="M 922 107 a 132 132 0 1 1 -1 0" pathLength="100"/>
  </defs>
  <rect width="1200" height="460" rx="18" fill="#070907"/>
  <rect x="1" y="1" width="1198" height="458" rx="17" fill="none" stroke="#f2f0e8" stroke-opacity=".16"/>
  <rect width="1200" height="460" rx="18" fill="url(#grid)"/>
  <ellipse cx="940" cy="230" rx="320" ry="260" fill="url(#glow)" opacity=".32">
    <animate attributeName="opacity" values=".2;.48;.2" dur="5s" repeatCount="indefinite"/>
  </ellipse>
  <!-- top rail -->
  <circle cx="30" cy="28" r="4" fill="#c7ff4a"><animate attributeName="opacity" values="1;.25;1" dur="1.8s" repeatCount="indefinite"/></circle>
  <text x="44" y="33" fill="#c7ff4a" font-family="Consolas,monospace" font-size="11" font-weight="700" letter-spacing="2">AVAILABLE FOR SELECTED PROJECTS</text>
  <text x="1168" y="33" text-anchor="end" fill="#999f96" font-family="Consolas,monospace" font-size="11" letter-spacing="1.4">BANGLADESH / UTC+6</text>
  <line x1="24" y1="52" x2="1176" y2="52" stroke="#f2f0e8" stroke-opacity=".12"/>
  <!-- identity -->
  <text x="64" y="106" fill="#999f96" font-family="Consolas,monospace" font-size="13" font-weight="700" letter-spacing="3">MD. SOZIB HOSSAIN</text>
  <text x="64" y="174" fill="#f2f0e8" font-family="Segoe UI,Arial,sans-serif" font-size="58" font-weight="760" letter-spacing="-2">Full-stack web &amp;</text>
  <text x="64" y="238" fill="#f2f0e8" font-family="Segoe UI,Arial,sans-serif" font-size="58" font-weight="760" letter-spacing="-2">mobile developer</text>
  <text x="64" y="302" fill="#c7ff4a" font-family="Georgia,serif" font-size="34" font-style="italic">who ships real products.
    <animate attributeName="opacity" values=".72;1;.72" dur="3.4s" repeatCount="indefinite"/>
  </text>
  <line x1="64" y1="329" x2="556" y2="329" stroke="#f2f0e8" stroke-opacity=".18"/>
  <text x="64" y="360" fill="#b8bcb4" font-family="Segoe UI,Arial,sans-serif" font-size="15">Interfaces · APIs · databases · realtime · mobile · release</text>
  <!-- delivery system -->
  <g transform="translate(714 72)">
    <rect width="422" height="318" rx="8" fill="url(#panel)" stroke="#f2f0e8" stroke-opacity=".2"/>
    <line x1="0" y1="42" x2="422" y2="42" stroke="#f2f0e8" stroke-opacity=".12"/>
    <circle cx="18" cy="21" r="3" fill="#62665f"/><circle cx="30" cy="21" r="3" fill="#62665f"/>
    <circle cx="42" cy="21" r="3" fill="#c7ff4a"><animate attributeName="opacity" values=".3;1;.3" dur="2s" repeatCount="indefinite"/></circle>
    <text x="211" y="25" text-anchor="middle" fill="#777d75" font-family="Consolas,monospace" font-size="9" letter-spacing="1.5">PRODUCT DELIVERY SYSTEM / LIVE</text>
    <circle cx="211" cy="166" r="111" fill="none" stroke="#f2f0e8" stroke-opacity=".08"/>
    <circle cx="211" cy="166" r="82" fill="none" stroke="#c7ff4a" stroke-opacity=".2" stroke-dasharray="3 8">
      <animateTransform attributeName="transform" type="rotate" from="0 211 166" to="360 211 166" dur="18s" repeatCount="indefinite"/>
    </circle>
    <circle cx="211" cy="166" r="55" fill="#0d100d" stroke="#c7ff4a" stroke-opacity=".5"/>
    <circle cx="211" cy="166" r="44" fill="none" stroke="#c7ff4a" stroke-opacity=".13">
      <animate attributeName="r" values="40;50;40" dur="3s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values=".3;0;.3" dur="3s" repeatCount="indefinite"/>
    </circle>
    <text x="211" y="158" text-anchor="middle" fill="#999f96" font-family="Consolas,monospace" font-size="9" letter-spacing="1.4">END-TO-END</text>
    <text x="211" y="181" text-anchor="middle" fill="#f2f0e8" font-family="Segoe UI,Arial,sans-serif" font-size="19" font-weight="700">SHIP</text>
    <g fill="#0d100d" stroke="#f2f0e8" stroke-opacity=".22">
      <rect x="24" y="81" width="105" height="42" rx="4"/>
      <rect x="293" y="81" width="105" height="42" rx="4"/>
      <rect x="24" y="213" width="105" height="42" rx="4"/>
      <rect x="293" y="213" width="105" height="42" rx="4"/>
    </g>
    <g fill="#f2f0e8" font-family="Consolas,monospace" font-size="11" font-weight="700" text-anchor="middle">
      <text x="76" y="106">WEB</text><text x="345" y="106">BACKEND</text>
      <text x="76" y="238">MOBILE</text><text x="345" y="238">RELEASE</text>
    </g>
    <g fill="#c7ff4a">
      <circle r="5" filter="url(#softGlow)"><animateMotion dur="7s" repeatCount="indefinite" path="M 129 102 C 190 42 234 42 293 102 C 358 166 350 201 293 234 C 225 278 188 277 129 234 C 57 183 60 148 129 102"/></circle>
      <circle r="3" opacity=".75"><animateMotion begin="-3.5s" dur="7s" repeatCount="indefinite" path="M 129 102 C 190 42 234 42 293 102 C 358 166 350 201 293 234 C 225 278 188 277 129 234 C 57 183 60 148 129 102"/></circle>
    </g>
    <line x1="24" y1="278" x2="398" y2="278" stroke="#f2f0e8" stroke-opacity=".1"/>
    <text x="24" y="300" fill="#999f96" font-family="Consolas,monospace" font-size="9" letter-spacing="1.2">9 LIVE PRODUCTS</text>
    <text x="398" y="300" text-anchor="end" fill="#c7ff4a" font-family="Consolas,monospace" font-size="9" letter-spacing="1.2">PRODUCTION READY</text>
  </g>
  <!-- bottom progress -->
  <rect x="0" y="442" width="1200" height="18" rx="0 0 18 18" fill="#0d100d"/>
  <rect x="0" y="442" width="190" height="2" fill="#c7ff4a">
    <animate attributeName="x" values="-190;1200" dur="4.5s" repeatCount="indefinite"/>
  </rect>
</svg>
assets/pipeline.svg
<svg xmlns="http://www.w3.org/2000/svg" width="1200" height="210" viewBox="0 0 1200 210" role="img" aria-labelledby="title desc">
  <title id="title">From idea to live product</title>
  <desc id="desc">An animated seven-stage production pipeline.</desc>
  <defs>
    <pattern id="grid" width="32" height="32" patternUnits="userSpaceOnUse">
      <path d="M32 0H0V32" fill="none" stroke="#f2f0e8" stroke-opacity=".035"/>
    </pattern>
    <filter id="glow" x="-100%" y="-100%" width="300%" height="300%"><feGaussianBlur stdDeviation="5" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
  </defs>
  <rect width="1200" height="210" rx="14" fill="#070907"/>
  <rect x="1" y="1" width="1198" height="208" rx="13" fill="none" stroke="#f2f0e8" stroke-opacity=".14"/>
  <rect width="1200" height="210" rx="14" fill="url(#grid)"/>
  <text x="36" y="38" fill="#999f96" font-family="Consolas,monospace" font-size="11" font-weight="700" letter-spacing="2">DELIVERY PIPELINE / FROM IDEA TO PRODUCTION</text>
  <text x="1164" y="38" text-anchor="end" fill="#c7ff4a" font-family="Consolas,monospace" font-size="10" letter-spacing="1.5">SYSTEM ACTIVE</text>
  <line x1="86" y1="105" x2="1114" y2="105" stroke="#f2f0e8" stroke-opacity=".14" stroke-width="2"/>
  <line x1="86" y1="105" x2="1114" y2="105" stroke="#c7ff4a" stroke-opacity=".45" stroke-width="2" stroke-dasharray="8 18">
    <animate attributeName="stroke-dashoffset" values="0;-52" dur="2s" repeatCount="indefinite"/>
  </line>
  <g font-family="Consolas,monospace" text-anchor="middle">
    <g transform="translate(86 105)"><circle r="12" fill="#0d100d" stroke="#c7ff4a"/><circle r="4" fill="#c7ff4a"/><text y="-26" fill="#f2f0e8" font-size="11" font-weight="700">IDEA</text><text y="40" fill="#62665f" font-size="9">01</text></g>
    <g transform="translate(257 105)"><circle r="12" fill="#0d100d" stroke="#c7ff4a"/><circle r="4" fill="#c7ff4a"/><text y="-26" fill="#f2f0e8" font-size="11" font-weight="700">DESIGN</text><text y="40" fill="#62665f" font-size="9">02</text></g>
    <g transform="translate(429 105)"><circle r="12" fill="#0d100d" stroke="#c7ff4a"/><circle r="4" fill="#c7ff4a"/><text y="-26" fill="#f2f0e8" font-size="11" font-weight="700">BUILD</text><text y="40" fill="#62665f" font-size="9">03</text></g>
    <g transform="translate(600 105)"><circle r="12" fill="#0d100d" stroke="#c7ff4a"/><circle r="4" fill="#c7ff4a"/><text y="-26" fill="#f2f0e8" font-size="11" font-weight="700">INTEGRATE</text><text y="40" fill="#62665f" font-size="9">04</text></g>
    <g transform="translate(771 105)"><circle r="12" fill="#0d100d" stroke="#c7ff4a"/><circle r="4" fill="#c7ff4a"/><text y="-26" fill="#f2f0e8" font-size="11" font-weight="700">TEST</text><text y="40" fill="#62665f" font-size="9">05</text></g>
    <g transform="translate(943 105)"><circle r="12" fill="#0d100d" stroke="#c7ff4a"/><circle r="4" fill="#c7ff4a"/><text y="-26" fill="#f2f0e8" font-size="11" font-weight="700">DEPLOY</text><text y="40" fill="#62665f" font-size="9">06</text></g>
    <g transform="translate(1114 105)"><circle r="16" fill="#c7ff4a" fill-opacity=".12" stroke="#c7ff4a"><animate attributeName="r" values="13;18;13" dur="2.2s" repeatCount="indefinite"/><animate attributeName="fill-opacity" values=".08;.22;.08" dur="2.2s" repeatCount="indefinite"/></circle><circle r="5" fill="#c7ff4a" filter="url(#glow)"/><text y="-26" fill="#c7ff4a" font-size="11" font-weight="700">LIVE</text><text y="40" fill="#62665f" font-size="9">07</text></g>
  </g>
  <circle r="6" fill="#c7ff4a" filter="url(#glow)">
    <animateMotion path="M86 105H1114" dur="5.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0;1;1;0" keyTimes="0;.06;.94;1" dur="5.5s" repeatCount="indefinite"/>
  </circle>
  <text x="36" y="184" fill="#62665f" font-family="Consolas,monospace" font-size="9" letter-spacing="1.2">WEB · BACKEND · DATABASE · MOBILE · APP STORE · PLAY STORE</text>
  <text x="1164" y="184" text-anchor="end" fill="#62665f" font-family="Consolas,monospace" font-size="9" letter-spacing="1.2">BUILT FOR REAL USERS</text>
</svg>
