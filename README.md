<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 300" width="1200" height="300">
  <defs>
    <!-- Gradient Background -->
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0a0a0a"/>
      <stop offset="50%" stop-color="#111111"/>
      <stop offset="100%" stop-color="#050505"/>
    </linearGradient>

    <!-- Glow Effect -->
    <radialGradient id="glow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#ffffff" stop-opacity="0.15"/>
      <stop offset="100%" stop-color="#ffffff" stop-opacity="0"/>
    </radialGradient>

    <!-- Text Gradient -->
    <linearGradient id="textGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#ffffff"/>
      <stop offset="50%" stop-color="#888888"/>
      <stop offset="100%" stop-color="#ffffff"/>
    </linearGradient>

    <!-- Line Gradient -->
    <linearGradient id="lineGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#ffffff" stop-opacity="0"/>
      <stop offset="50%" stop-color="#ffffff" stop-opacity="0.8"/>
      <stop offset="100%" stop-color="#ffffff" stop-opacity="0"/>
    </linearGradient>
  </defs>

  <!-- Background -->
  <rect width="1200" height="300" fill="url(#bg)"/>

  <!-- Glow Circle -->
  <ellipse cx="600" cy="150" rx="400" ry="120" fill="url(#glow)"/>

  <!-- Grid Pattern -->
  <g stroke="#ffffff" stroke-opacity="0.04" stroke-width="1">
    <line x1="0" y1="50" x2="1200" y2="50"/>
    <line x1="0" y1="100" x2="1200" y2="100"/>
    <line x1="0" y1="150" x2="1200" y2="150"/>
    <line x1="0" y1="200" x2="1200" y2="200"/>
    <line x1="0" y1="250" x2="1200" y2="250"/>
    <line x1="200" y1="0" x2="200" y2="300"/>
    <line x1="400" y1="0" x2="400" y2="300"/>
    <line x1="600" y1="0" x2="600" y2="300"/>
    <line x1="800" y1="0" x2="800" y2="300"/>
    <line x1="1000" y1="0" x2="1000" y2="300"/>
  </g>

  <!-- Top Decorative Line -->
  <line x1="0" y1="20" x2="1200" y2="20" stroke="url(#lineGrad)" stroke-width="1"/>

  <!-- Corner Decorations -->
  <path d="M 30 30 L 30 60 M 30 30 L 60 30" stroke="#ffffff" stroke-opacity="0.5" stroke-width="2" fill="none"/>
  <path d="M 1170 30 L 1170 60 M 1170 30 L 1140 30" stroke="#ffffff" stroke-opacity="0.5" stroke-width="2" fill="none"/>
  <path d="M 30 270 L 30 240 M 30 270 L 60 270" stroke="#ffffff" stroke-opacity="0.5" stroke-width="2" fill="none"/>
  <path d="M 1170 270 L 1170 240 M 1170 270 L 1140 270" stroke="#ffffff" stroke-opacity="0.5" stroke-width="2" fill="none"/>

  <!-- Small dots -->
  <circle cx="600" cy="60" r="2" fill="#ffffff" fill-opacity="0.6"/>
  <circle cx="600" cy="240" r="2" fill="#ffffff" fill-opacity="0.6"/>

  <!-- Main Title -->
  <text x="600" y="155" 
        font-family="'Segoe UI', 'Helvetica Neue', Arial, sans-serif" 
        font-size="90" 
        font-weight="200" 
        letter-spacing="20" 
        fill="url(#textGrad)" 
        text-anchor="middle" 
        dominant-baseline="middle">
    VORSI666
  </text>

  <!-- Subtitle -->
  <text x="600" y="205" 
        font-family="'Segoe UI', 'Helvetica Neue', Arial, sans-serif" 
        font-size="14" 
        font-weight="300" 
        letter-spacing="8" 
        fill="#888888" 
        text-anchor="middle">
    DEVELOPER · CREATOR · BUILDER
  </text>

  <!-- Underline -->
  <line x1="450" y1="225" x2="750" y2="225" stroke="url(#lineGrad)" stroke-width="1"/>

  <!-- Bottom Decorative Line -->
  <line x1="0" y1="280" x2="1200" y2="280" stroke="url(#lineGrad)" stroke-width="1"/>
</svg>
