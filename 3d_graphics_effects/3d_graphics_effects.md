!SLIDE transition=scrollUp

# 3d, gráficos e efeitos #

!SLIDE bullets incremental

# HTML + JavaScript + CSS = #

* <strike>3d</strike>
* <strike>Imagens vetoriais</strike>
* <strike>Renderização complexa</strike>

!SLIDE bullets

# HTML5: soluções #

* SVG
* Canvas
* WebGL
* CSS 3d



!SLIDE

# SVG #

!SLIDE bullets

# Scalable Vector Graphics #

## "Linguagem de marcação para descrever gráficos e imagens bidimensionais, e uma coleção de interfaces scripts para gráficos" ##

!SLIDE

    @@@html
    <svg id="svg" height="400" width="640"
         xmlns="http://www.w3.org/2000/svg">
      <circle id="circle" cx="150" cy="150"
              r="250" fill="#880000" />
    </svg>

!SLIDE

<div class="svg">
  <svg id="svg" height="400" width="640" xmlns="http://www.w3.org/2000/svg">
  <circle id="circle" cx="150" cy="150" r="250" fill="#880000" />
  </svg>
</div>





!SLIDE

# Canvas #

!SLIDE

# Canvas #

## _"Resolution-dependent bitmap canvas which can be used for rendering graphs, game graphics, or other visual images on the fly."_ ##

!SLIDE

# Canvas #

## Área retangular em que se pode fazer desenhos com JavaScript ##

!SLIDE

    @@@html
    <canvas width="640" height="480"></canvas>

!SLIDE

<div class='canvas'>
  <canvas width="640" height="480"></canvas>
</div>

!SLIDE

    @@@javascript
    var canvas = document.getElementById("canvas");
    var context = b_canvas.getContext("2d");
    b_context.fillRect(50, 100, 200, 100);

!SLIDE

<div class='canvas'>
  <canvas id="first" width="640" height="480"></canvas>
</div>
<script>
  var canvas = document.getElementById("first");
  var context = canvas.getContext("2d");
  context.fillRect(50, 100, 200, 100);
</script>

!SLIDE

    @@@javascript
    var gradient = context.createRadialGradient(
      300, 250, 500, 100, 600, 150
    );
    gradient.addColorStop(0, "#FF3333");
    gradient.addColorStop(1, "#333333");
    context.fillStyle = gradient;
    context.fillRect(25, 25, 590, 430);

!SLIDE

<div class='canvas'>
  <canvas id="second" width="640" height="480"></canvas>
</div>
<script>
  var canvas = document.getElementById("second");
  var context = canvas.getContext("2d");
  var gradient = context.createRadialGradient(
    300, 250, 500, 100, 600, 150
  );
  gradient.addColorStop(0, "#FF3333");
  gradient.addColorStop(1, "#333333");
  context.fillStyle = gradient;
  context.fillRect(25, 25, 590, 430);
</script>

!SLIDE bullets

# Outras formas de renderização #

* linhas
* pontos
* texto
* imagens
* ...

!SLIDE bullets

# Demos #

* [gradientes em canvas interativo](http://html5demos.com/canvas-grad)
* [canvas & vídeo](http://html5demos.com/video-canvas)




!SLIDE

# WebGL #

!SLIDE

# WebGL #
## Web-based Graphics Library ##

!SLIDE bullets

# WebGL #

## Gráficos 3d interativos, manuseados via APIs e DOM com JavaScript ##

!SLIDE bullets

# Exemplos #

* [The Navigator](https://mozillademos.org/demos/flight-of-the-navigator/demo.html)
* [No Comply](https://mozillademos.org/demos/nocomply/demo.html)
* [GlobeTweeter](https://mozillademos.org/demos/globetweeter/demo.html)
