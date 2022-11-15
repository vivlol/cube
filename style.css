html, body {
	height: 100%;
  overflow: hidden;
}

body {
  background: rgb(100, 10, 15);
	background:
		radial-gradient(circle, rgba(155, 255, 255, .3), transparent)
	,	linear-gradient(rgba(155, 255, 255, .5) 1px, transparent 1px)
	,	linear-gradient(90deg, rgba(155, 255, 255, .5) 1px, transparent 1px)
	,	linear-gradient(rgba(155, 255, 255, .3) 1px, transparent 1px)
	,	linear-gradient(90deg, rgba(255, 255, 255, .3) 1px, transparent 1px)
	,		rgb(100, 10, 150);
  	box-shadow:
    inset 0 0 10em rgba(0, 0, 0, .5)
  	, 0 0 1em rgba(0, 0, 0, .8);
  font-family: Raleway, sans-serif;
  font-weight: 100;
}

.container {
  perspective: 1000px;
  perspective-origin: 50% 50%;
  width: 80%;
  margin: 0 auto;
  padding: 15%;
 }

.animate {
  animation: spinningH 6s infinite linear;
}

.cube {
  $s: 360px;
  
  position: relative;
  margin: 0 auto;
  height: $s;
  width: $s;
  transition: transform 2s linear;
  transform-style: preserve-3d;
  transform: translateX($s/2);
  
  & > .face {
    position: absolute;
    height: $s;
    width: $s;
    background-color: rgba(255,255,255,.6);
    border: 0;
    resize: none;
    color: #000;
    text-align: left;
    font-variant-ligatures: normal;
    text-rendering: optimizeLegibility;
  }
  .face:nth-child(1) {
    transform: translateZ($s/2);
  }
  .face:nth-child(2) {
    transform: rotateY(90deg) translateZ($s/2);
  }
  .face:nth-child(3) {
    transform: rotateY(180deg) translateZ($s/2);
  }
  .face:nth-child(4) {
    transform: rotateY(-90deg) translateZ($s/2);
  }
  .face:nth-child(5) {
    transform: rotateX(-90deg) translateZ($s/2) rotate(180deg);
  }
  .face:nth-child(6) {
    transform: rotateX(90deg) translateZ($s/2);
  }
}
