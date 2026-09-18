<div align="center" style="background: #000; padding: 20px; border-radius: 8px; overflow: hidden; height: 180px;">
  <!-- Perspective container for 3D crawl -->
  <div style="
    perspective: 300px;
    vertical-align: middle;
    height: 100%;
    width: 100%;
    position: relative;
  ">
    <style>
      @keyframes starWarsCrawl {
        0% {
          top: 150px;
          transform: rotateX(25deg) translateY(0);
          opacity: 1;
        }
        100% {
          top: -200px;
          transform: rotateX(25deg) translateY(-150px) scale(0.6);
          opacity: 0;
        }
      }
      .crawl-text {
        position: absolute;
        width: 80%;
        left: 10%;
        color: #FFE81F; /* Classic Star Wars Yellow */
        font-family: 'Arial Black', Gadget, sans-serif;
        text-align: center;
        animation: starWarsCrawl 12s linear infinite;
        text-transform: uppercase;
        line-height: 1.6;
        font-weight: bold;
      }
    </style>

    <div class="crawl-text">
      <p style="font-size: 14px; margin: 0 0 10px 0;">Episode 2026</p>
      <h3 style="font-size: 18px; margin: 0 0 15px 0; color: #FFE81F;">THE HARSH PATEL CHRONICLES</h3>
      <p style="font-size: 12px; margin: 0;">It is a period of open source development. Striking from their home terminals, AI engineers have won their first victory against legacy workflows...</p>
    </div>
  </div>
</div>
