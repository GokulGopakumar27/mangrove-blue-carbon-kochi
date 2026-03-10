## 🌎 Mangrove Blue Carbon Cycle

<p align="center">

<svg width="800" height="300" viewBox="0 0 800 300" xmlns="http://www.w3.org/2000/svg">

<style>
.mangrove { fill:#2e8b57; }
.soil { fill:#8d6e63; }
.text { font-size:14px; font-family:Arial; }
.co2 { fill:#555; font-size:14px; }
.arrow { stroke:#333; stroke-width:2; marker-end:url(#arrowhead); }

.float {
  animation: float 3s ease-in-out infinite;
}

@keyframes float {
  0% { transform: translateY(0px); }
  50% { transform: translateY(-5px); }
  100% { transform: translateY(0px); }
}
</style>

<defs>
<marker id="arrowhead" markerWidth="10" markerHeight="7"
refX="10" refY="3.5" orient="auto">
<polygon points="0 0, 10 3.5, 0 7"/>
</marker>
</defs>

<!-- Sky CO2 -->
<text x="350" y="40" class="co2 float">Atmospheric CO₂</text>

<!-- Arrow Down -->
<line class="arrow" x1="400" y1="50" x2="400" y2="100"/>

<!-- Mangrove -->
<rect x="350" y="100" width="100" height="80" class="mangrove"/>
<text x="360" y="150" class="text" fill="white">Mangroves</text>

<!-- Arrow to soil -->
<line class="arrow" x1="400" y1="180" x2="400" y2="230"/>

<!-- Soil -->
<rect x="330" y="230" width="140" height="50" class="soil"/>
<text x="350" y="260" class="text" fill="white">Soil Carbon Storage</text>

</svg>

</p>
