<div style="display: flex; justify-content: center; align-items: center;">
  
  <!-- Círculo de Progreso (Estado de la Carrera Universitaria) -->
  <div style="margin-right: 20px;">
    <svg width="150" height="150" viewBox="0 0 36 36" class="circular-chart">
      <path class="circle-bg"
        d="M18 2.0845
        a 15.9155 15.9155 0 0 1 0 31.831
        a 15.9155 15.9155 0 0 1 0 -31.831" />
      
      <path class="circle"
        stroke-dasharray="50, 100" 
        d="M18 2.0845
        a 15.9155 15.9155 0 0 1 0 31.831
        a 15.9155 15.9155 0 0 1 0 -31.831" />
      
      <text x="18" y="20.35" class="percentage" font-size="0.5em" fill="#000" text-anchor="middle">50%</text>
    </svg>
  </div>

  <!-- Most Used Languages -->
  <div>
    ![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=FedericoKesselman&layout=compact&theme=radical)
  </div>

</div>

<!-- Estilos del círculo de progreso -->
<style>
  .circular-chart {
    max-width: 100%;
    max-height: 250px;
    display: block;
    margin: 0 auto;
  }

  .circle-bg {
    fill: none;
    stroke: #eee;
    stroke-width: 3.8;
  }

  .circle {
    fill: none;
    stroke-width: 2.8;
    stroke-linecap: round;
    stroke: #4caf50;
    stroke-dasharray: 50, 100;
    animation: progress 1s ease-out forwards;
  }

  @keyframes progress {
    0% {
      stroke-dasharray: 0 100;
    }
  }

  .percentage {
    font-size: 0.5em;
    font-weight: bold;
  }
</style>