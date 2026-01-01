<p align="center">
  <svg width="480" height="160" viewBox="0 0 480 160" xmlns="http://www.w3.org/2000/svg">

    <!-- Glow effect -->
    <defs>
      <filter id="glow">
        <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
        <feMerge>
          <feMergeNode in="coloredBlur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
    </defs>

    <!-- Snake border -->
    <rect
      x="8"
      y="8"
      rx="20"
      ry="20"
      width="464"
      height="144"
      fill="none"
      stroke="white"
      stroke-width="3"
      stroke-dasharray="70 380"
      filter="url(#glow)"
    >
      <animate
        attributeName="stroke-dashoffset"
        from="0"
        to="-450"
        dur="2.2s"
        repeatCount="indefinite"
      />
    </rect>

    <!-- Content -->
    <text x="240" y="75"
          text-anchor="middle"
          fill="white"
          font-size="22"
          font-family="Arial, Helvetica, sans-serif"
          font-weight="bold">
      Sahil Kumar Gupta
    </text>

    <text x="240" y="105"
          text-anchor="middle"
          fill="#cbd5f5"
          font-size="15"
          font-family="Arial, Helvetica, sans-serif">
      DevOps • Docker • Kubernetes • Jenkins
    </text>

  </svg>
</p>
