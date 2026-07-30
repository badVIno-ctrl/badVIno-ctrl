<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 210" width="1200" height="210" role="img" aria-label="badVIno — VioraStudio">
  <defs>
    <linearGradient id="sheen" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#8FB6CE"/>
      <stop offset="38%" stop-color="#E6EDF3"/>
      <stop offset="52%" stop-color="#FFFFFF"/>
      <stop offset="68%" stop-color="#5EC8F2"/>
      <stop offset="100%" stop-color="#2E7BA6"/>
      <animateTransform attributeName="gradientTransform" type="translate"
        values="-0.45 0; 0.45 0; -0.45 0" dur="11s" repeatCount="indefinite"
        calcMode="spline" keyTimes="0;0.5;1" keySplines=".37 0 .63 1;.37 0 .63 1"/>
    </linearGradient>

    <linearGradient id="w1" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%"  stop-color="#5EC8F2" stop-opacity="0"/>
      <stop offset="55%" stop-color="#5EC8F2" stop-opacity=".38"/>
      <stop offset="100%" stop-color="#9FD8F0" stop-opacity=".62"/>
    </linearGradient>
    <linearGradient id="w2" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%"  stop-color="#143650" stop-opacity="0"/>
      <stop offset="60%" stop-color="#143650" stop-opacity=".85"/>
      <stop offset="100%" stop-color="#2E7BA6" stop-opacity=".9"/>
    </linearGradient>

    <path id="curve" d="M64,132 C 300,104 520,158 806,120"/>
    <path id="rule"  d="M66,152 C 300,124 520,178 812,140"/>
  </defs>

  <style>
    .bg   { fill:#0B0F14 }
    .name { font-family:"Trebuchet MS","Segoe UI",system-ui,sans-serif;
            font-size:74px; font-weight:700; letter-spacing:-.5px }
    .tag  { font-family:"Trebuchet MS","Segoe UI",system-ui,sans-serif;
            font-size:15px; font-weight:600; letter-spacing:3.4px; fill:#7E93A6 }
    @media (prefers-color-scheme: light) {
      .bg  { fill:#F2F7FB }
      .tag { fill:#5A6E80 }
    }
  </style>

  <rect class="bg" x="0" y="0" width="1200" height="210"/>

  <g transform="translate(0,0)">
    <path d="M0,150 C 210,112 340,192 560,154 C 780,116 900,192 1200,138 L1200,210 L0,210 Z" fill="url(#w2)">
      <animateTransform attributeName="transform" type="translate"
        values="0 0; -46 5; 0 0" dur="13s" repeatCount="indefinite"
        calcMode="spline" keyTimes="0;0.5;1" keySplines=".37 0 .63 1;.37 0 .63 1"/>
    </path>
    <path d="M0,168 C 240,132 380,204 620,168 C 860,132 980,200 1200,158 L1200,210 L0,210 Z" fill="url(#w1)" opacity=".55">
      <animateTransform attributeName="transform" type="translate"
        values="0 0; 38 -6; 0 0" dur="17s" repeatCount="indefinite"
        calcMode="spline" keyTimes="0;0.5;1" keySplines=".37 0 .63 1;.37 0 .63 1"/>
    </path>
  </g>

  <path d="M940,26 C 1010,64 1060,52 1150,96" fill="none" stroke="#5EC8F2" stroke-opacity=".26" stroke-width="2">
    <animate attributeName="stroke-opacity" values=".12;.34;.12" dur="7s" repeatCount="indefinite"
      calcMode="spline" keyTimes="0;0.5;1" keySplines=".37 0 .63 1;.37 0 .63 1"/>
  </path>
  <path d="M900,64 C 990,104 1030,84 1160,140" fill="none" stroke="#5EC8F2" stroke-opacity=".14" stroke-width="1.5"/>

  <text class="name" fill="url(#sheen)">
    <textPath href="#curve" startOffset="0">badVIno</textPath>
  </text>

  <use href="#rule" fill="none" stroke="#5EC8F2" stroke-opacity=".55" stroke-width="2" stroke-dasharray="760" stroke-dashoffset="760">
    <animate attributeName="stroke-dashoffset" from="760" to="0" dur="1.6s" begin="0.15s" fill="freeze"
      calcMode="spline" keyTimes="0;1" keySplines=".22 1 .36 1"/>
  </use>

  <text class="tag" x="68" y="188">VIORASTUDIO · WEB APPS · INTERACTIVE UI · AI SYSTEMS</text>
</svg>
