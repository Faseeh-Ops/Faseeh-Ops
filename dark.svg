<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1180 610" width="1180" height="610">
  <defs>
    <!-- Background Gradients -->
    <radialGradient id="bgGlow1" cx="20%" cy="30%" r="50%">
      <stop offset="0%" stop-color="#2563EB" stop-opacity="0.08" />
      <stop offset="100%" stop-color="#FFFFFF" stop-opacity="0" />
    </radialGradient>
    <radialGradient id="bgGlow2" cx="80%" cy="70%" r="50%">
      <stop offset="0%" stop-color="#06B6D4" stop-opacity="0.08" />
      <stop offset="100%" stop-color="#FFFFFF" stop-opacity="0" />
    </radialGradient>
    
    <!-- Accent Gradients -->
    <linearGradient id="accentGradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#2563EB">
        <animate attributeName="stop-color" values="#2563EB;#06B6D4;#10B981;#2563EB" dur="8s" repeatCount="indefinite" />
      </stop>
      <stop offset="50%" stop-color="#06B6D4">
        <animate attributeName="stop-color" values="#06B6D4;#10B981;#2563EB;#06B6D4" dur="8s" repeatCount="indefinite" />
      </stop>
      <stop offset="100%" stop-color="#10B981">
        <animate attributeName="stop-color" values="#10B981;#2563EB;#06B6D4;#10B981" dur="8s" repeatCount="indefinite" />
      </stop>
    </linearGradient>

    <!-- Glass Panel Borders with Shimmer -->
    <linearGradient id="shimmerBorder" x1="0%" y1="0%" x2="200%" y2="0%">
      <stop offset="0%" stop-color="rgba(15,23,42,0.03)" />
      <stop offset="50%" stop-color="rgba(15,23,42,0.15)" />
      <stop offset="100%" stop-color="rgba(15,23,42,0.03)" />
      <animate attributeName="x1" values="-100%;100%" dur="4s" repeatCount="indefinite" />
      <animate attributeName="x2" values="0%;200%" dur="4s" repeatCount="indefinite" />
    </linearGradient>

    <!-- Glow Filters -->
    <filter id="glow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="4" result="blur" />
      <feMerge>
        <feMergeNode in="blur" />
        <feMergeNode in="SourceGraphic" />
      </feMerge>
    </filter>
    
    <!-- Subtle Drop Shadow for Light Mode Glass Panels -->
    <filter id="panelShadow" x="-10%" y="-10%" width="120%" height="120%">
      <feDropShadow dx="0" dy="15" stdDeviation="25" flood-color="rgba(15,23,42,0.05)" />
    </filter>

    <!-- Grid Pattern -->
    <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
      <path d="M 40 0 L 0 0 0 40" fill="none" stroke="rgba(15,23,42,0.03)" stroke-width="1" />
    </pattern>
  </defs>

  <style>
    <![CDATA[
      .pill { transition: all 0.3s ease; cursor: pointer; }
      .pill:hover { transform: scale(1.05); }
      .pill rect { transition: all 0.3s ease; }
      .pill:hover rect { fill: rgba(37, 99, 235, 0.05); stroke: #2563EB; }
      .social-icon { transition: all 0.3s ease; cursor: pointer; }
      .social-icon:hover { fill: #2563EB; filter: drop-shadow(0 0 4px rgba(37, 99, 235, 0.3)); transform: translateY(-3px); }
    ]]>
  </style>

  <!-- Base Background -->
  <rect width="1180" height="610" fill="#FFFFFF" />
  <rect width="1180" height="610" fill="url(#grid)" />
  
  <!-- Floating Background Glows -->
  <circle cx="20%" cy="30%" r="400" fill="url(#bgGlow1)" pointer-events="none">
    <animate attributeName="cy" values="30%;35%;30%" dur="10s" repeatCount="indefinite" />
  </circle>
  <circle cx="80%" cy="70%" r="400" fill="url(#bgGlow2)" pointer-events="none">
    <animate attributeName="cy" values="70%;65%;70%" dur="12s" repeatCount="indefinite" />
  </circle>
  
  <!-- Floating Particles -->
  <g fill="rgba(15,23,42,0.15)">
    <circle cx="150" cy="150" r="1.5"><animate attributeName="cy" values="150;130;150" dur="6s" repeatCount="indefinite"/></circle>
    <circle cx="1050" cy="200" r="2"><animate attributeName="cy" values="200;220;200" dur="7s" repeatCount="indefinite"/></circle>
    <circle cx="500" cy="550" r="1.5"><animate attributeName="cy" values="550;530;550" dur="5s" repeatCount="indefinite"/></circle>
    <circle cx="750" cy="80" r="2.5"><animate attributeName="cy" values="80;100;80" dur="8s" repeatCount="indefinite"/></circle>
  </g>

  <!-- ======================== LEFT SIDE: ASCII PANEL ======================== -->
  <g transform="translate(40, 40)">
    <!-- Glass Panel -->
    <rect width="420" height="530" rx="16" fill="rgba(248,250,252,0.85)" stroke="url(#shimmerBorder)" stroke-width="1.5" filter="url(#panelShadow)" />
    <rect width="420" height="1" rx="16" fill="url(#accentGradient)" opacity="0.3" /> 
    
    <!-- Window Controls -->
    <circle cx="25" cy="25" r="6" fill="#EF4444" opacity="0.8" />
    <circle cx="45" cy="25" r="6" fill="#F59E0B" opacity="0.8" />
    <circle cx="65" cy="25" r="6" fill="#10B981" opacity="0.8" />

    <!-- ASCII Art & Terminal -->
    <g font-family="'Fira Code', Consolas, monospace" font-size="12" font-weight="600" fill="url(#accentGradient)">
      <tspan x="30" y="80" opacity="0">> SYS.INIT()...<animate attributeName="opacity" from="0" to="1" begin="0.1s" dur="0.2s" fill="freeze"/></tspan>
      <tspan x="30" y="100" opacity="0">> KERNEL LOADED<animate attributeName="opacity" from="0" to="1" begin="0.2s" dur="0.2s" fill="freeze"/></tspan>
      
      <tspan x="30" y="140" opacity="0">      .-:::::::::::::::::-.      <animate attributeName="opacity" from="0" to="1" begin="0.4s" dur="0.2s" fill="freeze"/></tspan>
      <tspan x="30" y="160" opacity="0">    .:::                 :::.    <animate attributeName="opacity" from="0" to="1" begin="0.5s" dur="0.2s" fill="freeze"/></tspan>
      <tspan x="30" y="180" opacity="0">   :::    [ AI KERNEL ]    :::   <animate attributeName="opacity" from="0" to="1" begin="0.6s" dur="0.2s" fill="freeze"/></tspan>
      <tspan x="30" y="200" opacity="0">  :::                       :::  <animate attributeName="opacity" from="0" to="1" begin="0.7s" dur="0.2s" fill="freeze"/></tspan>
      <tspan x="30" y="220" opacity="0">  :::     /-----------\     :::  <animate attributeName="opacity" from="0" to="1" begin="0.8s" dur="0.2s" fill="freeze"/></tspan>
      <tspan x="30" y="240" opacity="0">  :::    /  o       o  \    :::  <animate attributeName="opacity" from="0" to="1" begin="0.9s" dur="0.2s" fill="freeze"/></tspan>
      <tspan x="30" y="260" opacity="0">  :::   |       ^       |   :::  <animate attributeName="opacity" from="0" to="1" begin="1.0s" dur="0.2s" fill="freeze"/></tspan>
      <tspan x="30" y="280" opacity="0">  :::    \  \_______/  /    :::  <animate attributeName="opacity" from="0" to="1" begin="1.1s" dur="0.2s" fill="freeze"/></tspan>
      <tspan x="30" y="300" opacity="0">  :::     \-----------/     :::  <animate attributeName="opacity" from="0" to="1" begin="1.2s" dur="0.2s" fill="freeze"/></tspan>
      <tspan x="30" y="320" opacity="0">  :::                       :::  <animate attributeName="opacity" from="0" to="1" begin="1.3s" dur="0.2s" fill="freeze"/></tspan>
      <tspan x="30" y="340" opacity="0">   :::  >> STATUS: ONLINE  :::   <animate attributeName="opacity" from="0" to="1" begin="1.4s" dur="0.2s" fill="freeze"/></tspan>
      <tspan x="30" y="360" opacity="0">    ':::                 :::'    <animate attributeName="opacity" from="0" to="1" begin="1.5s" dur="0.2s" fill="freeze"/></tspan>
      <tspan x="30" y="380" opacity="0">      '-:::::::::::::::::-'      <animate attributeName="opacity" from="0" to="1" begin="1.6s" dur="0.2s" fill="freeze"/></tspan>
      
      <tspan x="30" y="420" opacity="0">MEMORY: [████████░░] 80%<animate attributeName="opacity" from="0" to="1" begin="1.8s" dur="0.2s" fill="freeze"/></tspan>
      <tspan x="30" y="440" opacity="0">CORES : [██████████] 100%<animate attributeName="opacity" from="0" to="1" begin="1.9s" dur="0.2s" fill="freeze"/></tspan>
      
      <tspan x="30" y="480" opacity="0">> AWAITING INPUT_ <animate attributeName="opacity" from="0" to="1" begin="2.1s" dur="0.2s" fill="freeze"/></tspan>
    </g>

    <!-- Moving Scanline -->
    <rect width="420" height="2" fill="url(#accentGradient)" opacity="0.2">
      <animate attributeName="y" values="-10;540;-10" dur="8s" repeatCount="indefinite" />
    </rect>
  </g>

  <!-- ======================== RIGHT SIDE: TERMINAL ======================== -->
  <g transform="translate(480, 40)">
    <!-- Glass Panel -->
    <rect width="660" height="530" rx="16" fill="rgba(248,250,252,0.85)" stroke="url(#shimmerBorder)" stroke-width="1.5" filter="url(#panelShadow)" />
    <rect width="660" height="1" rx="16" fill="url(#accentGradient)" opacity="0.3" />
    
    <!-- Greeting -->
    <text x="45" y="70" font-family="'Fira Code', Consolas, monospace" font-size="24" font-weight="700" fill="#0F172A">
      > Hi 👋 I'm Muhammad Faseeh Ali
    </text>

    <!-- Animated Typing Subtitle -->
    <g transform="translate(45, 110)" font-family="'Fira Code', Consolas, monospace" font-size="20" font-weight="600" fill="url(#accentGradient)">
      <text opacity="0">Frontend Engineer<animate attributeName="opacity" values="1;0;0;0;0;0" keyTimes="0;0.2;0.4;0.6;0.8;1" calcMode="discrete" dur="15s" repeatCount="indefinite" /></text>
      <text opacity="0">Full Stack Developer<animate attributeName="opacity" values="0;1;0;0;0;0" keyTimes="0;0.2;0.4;0.6;0.8;1" calcMode="discrete" dur="15s" repeatCount="indefinite" /></text>
      <text opacity="0">Open Source Contributor<animate attributeName="opacity" values="0;0;1;0;0;0" keyTimes="0;0.2;0.4;0.6;0.8;1" calcMode="discrete" dur="15s" repeatCount="indefinite" /></text>
      <text opacity="0">AI Engineer<animate attributeName="opacity" values="0;0;0;1;0;0" keyTimes="0;0.2;0.4;0.6;0.8;1" calcMode="discrete" dur="15s" repeatCount="indefinite" /></text>
      <text opacity="0">UI Enthusiast<animate attributeName="opacity" values="0;0;0;0;1;0" keyTimes="0;0.2;0.4;0.6;0.8;1" calcMode="discrete" dur="15s" repeatCount="indefinite" /></text>
      
      <!-- Blinking Cursor -->
      <rect x="290" y="-16" width="12" height="22" fill="#2563EB">
        <animate attributeName="opacity" values="1;0;1" dur="1s" repeatCount="indefinite" />
      </rect>
    </g>

    <!-- Info Section (Sequential Reveal) -->
    <g transform="translate(45, 180)" font-family="system-ui, -apple-system, sans-serif" font-size="16">
      <g opacity="0"><animate attributeName="opacity" from="0" to="1" dur="0.8s" begin="0.8s" fill="freeze" />
        <text y="0" font-family="'Fira Code', Consolas, monospace" fill="#475569" font-size="14">Location   :</text>
        <text x="130" y="0" fill="#0F172A" font-weight="600">Lahore</text>
      </g>
      <g opacity="0"><animate attributeName="opacity" from="0" to="1" dur="0.8s" begin="1.1s" fill="freeze" />
        <text y="35" font-family="'Fira Code', Consolas, monospace" fill="#475569" font-size="14">Education  :</text>
        <text x="130" y="35" fill="#0F172A" font-weight="600">Bachelors In Computer Science</text>
      </g>
      <g opacity="0"><animate attributeName="opacity" from="0" to="1" dur="0.8s" begin="1.4s" fill="freeze" />
        <text y="70" font-family="'Fira Code', Consolas, monospace" fill="#475569" font-size="14">Focus      :</text>
        <text x="130" y="70" fill="#0F172A" font-weight="600">AI Technologies</text>
      </g>
      <g opacity="0"><animate attributeName="opacity" from="0" to="1" dur="0.8s" begin="1.7s" fill="freeze" />
        <text y="105" font-family="'Fira Code', Consolas, monospace" fill="#475569" font-size="14">Portfolio  :</text>
        <text x="130" y="105" fill="#2563EB" font-weight="600">www.link.com</text>
      </g>
      <g opacity="0"><animate attributeName="opacity" from="0" to="1" dur="0.8s" begin="2.0s" fill="freeze" />
        <text y="140" font-family="'Fira Code', Consolas, monospace" fill="#475569" font-size="14">Email      :</text>
        <text x="130" y="140" fill="#0F172A" font-weight="600">fashiali412@gmail.com</text>
      </g>
    </g>

    <!-- Skills Section -->
    <g opacity="0"><animate attributeName="opacity" from="0" to="1" dur="0.8s" begin="2.3s" fill="freeze" />
      <text x="45" y="360" font-family="'Fira Code', Consolas, monospace" fill="#475569" font-size="14">> ls skills/</text>
      
      <g font-family="system-ui, -apple-system, sans-serif" font-weight="600" font-size="13" fill="#0F172A">
        <!-- Row 1 -->
        <g class="pill" transform="translate(45, 380)">
          <rect width="75" height="32" rx="16" fill="rgba(15,23,42,0.04)" stroke="rgba(15,23,42,0.08)"/>
          <text x="37.5" y="21" text-anchor="middle">React</text>
        </g>
        <g class="pill" transform="translate(130, 380)">
          <rect width="85" height="32" rx="16" fill="rgba(15,23,42,0.04)" stroke="rgba(15,23,42,0.08)"/>
          <text x="42.5" y="21" text-anchor="middle">Next.js</text>
        </g>
        <g class="pill" transform="translate(225, 380)">
          <rect width="85" height="32" rx="16" fill="rgba(15,23,42,0.04)" stroke="rgba(15,23,42,0.08)"/>
          <text x="42.5" y="21" text-anchor="middle">Node.js</text>
        </g>
        <g class="pill" transform="translate(320, 380)">
          <rect width="110" height="32" rx="16" fill="rgba(15,23,42,0.04)" stroke="rgba(15,23,42,0.08)"/>
          <text x="55" y="21" text-anchor="middle">TypeScript</text>
        </g>
        <g class="pill" transform="translate(440, 380)">
          <rect width="95" height="32" rx="16" fill="rgba(15,23,42,0.04)" stroke="rgba(15,23,42,0.08)"/>
          <text x="47.5" y="21" text-anchor="middle">Tailwind</text>
        </g>

        <!-- Row 2 -->
        <g class="pill" transform="translate(60, 422)">
          <rect width="80" height="32" rx="16" fill="rgba(15,23,42,0.04)" stroke="rgba(15,23,42,0.08)"/>
          <text x="40" y="21" text-anchor="middle">Python</text>
        </g>
        <g class="pill" transform="translate(150, 422)">
          <rect width="80" height="32" rx="16" fill="rgba(15,23,42,0.04)" stroke="rgba(15,23,42,0.08)"/>
          <text x="40" y="21" text-anchor="middle">Docker</text>
        </g>
        <g class="pill" transform="translate(240, 422)">
          <rect width="95" height="32" rx="16" fill="rgba(15,23,42,0.04)" stroke="rgba(15,23,42,0.08)"/>
          <text x="47.5" y="21" text-anchor="middle">Postgres</text>
        </g>
        <g class="pill" transform="translate(345, 422)">
          <rect width="65" height="32" rx="16" fill="rgba(15,23,42,0.04)" stroke="rgba(15,23,42,0.08)"/>
          <text x="32.5" y="21" text-anchor="middle">AWS</text>
        </g>
        <g class="pill" transform="translate(420, 422)">
          <rect width="60" height="32" rx="16" fill="rgba(15,23,42,0.04)" stroke="rgba(15,23,42,0.08)"/>
          <text x="30" y="21" text-anchor="middle">Git</text>
        </g>
        <g class="pill" transform="translate(490, 422)">
          <rect width="75" height="32" rx="16" fill="rgba(15,23,42,0.04)" stroke="rgba(15,23,42,0.08)"/>
          <text x="37.5" y="21" text-anchor="middle">Figma</text>
        </g>
      </g>
    </g>

    <!-- Social Icons -->
    <g opacity="0" fill="#475569" transform="translate(45, 480)">
      <animate attributeName="opacity" from="0" to="1" dur="1s" begin="2.6s" fill="freeze" />
      <text y="18" font-family="'Fira Code', Consolas, monospace" font-size="14">> Connect:</text>
      
      <g transform="translate(130, 0)">
        <path class="social-icon" d="M12 2C6.477 2 2 6.477 2 12c0 4.418 2.865 8.166 6.839 9.489.5.092.682-.217.682-.482 0-.237-.008-.866-.013-1.7-2.782.603-3.369-1.34-3.369-1.34-.454-1.156-1.11-1.464-1.11-1.464-.908-.62.069-.608.069-.608 1.003.07 1.531 1.03 1.531 1.03.892 1.529 2.341 1.087 2.91.831.092-.646.35-1.086.636-1.336-2.22-.253-4.555-1.11-4.555-4.943 0-1.091.39-1.984 1.029-2.683-.103-.253-.446-1.27.098-2.647 0 0 .84-.269 2.75 1.025A9.578 9.578 0 0112 6.836c.85.004 1.705.114 2.504.336 1.909-1.294 2.747-1.025 2.747-1.025.546 1.377.203 2.394.1 2.647.64.699 1.028 1.592 1.028 2.683 0 3.842-2.339 4.687-4.566 4.935.359.309.678.919.678 1.852 0 1.336-.012 2.415-.012 2.743 0 .267.18.578.688.48C19.138 20.164 22 16.418 22 12c0-5.523-4.477-10-10-10z"/>
        <path class="social-icon" transform="translate(36, 0)" d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/>
        <path class="social-icon" transform="translate(72, 0)" d="M18.244 2.25h3.308l-7.227 8.26 8.502 11.24H16.17l-5.214-6.817L4.99 21.75H1.68l7.73-8.835L1.254 2.25H8.08l4.713 6.231zm-1.161 17.52h1.833L7.084 4.126H5.117z"/>
        <path class="social-icon" transform="translate(108, 0)" d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-1 17.93c-3.95-.49-7-3.85-7-7.93 0-.62.08-1.21.21-1.79L9 15v1c0 1.1.9 2 2 2v1.93zm6.9-2.54c-.26-.81-1-1.39-1.9-1.39h-1v-3c0-.55-.45-1-1-1H8v-2h2c.55 0 1-.45 1-1V7h2c1.1 0 2-.9 2-2v-.41c2.93 1.19 5 4.06 5 7.41 0 2.08-.8 3.97-2.1 5.39z"/>
      </g>
    </g>
  </g>
</svg>
