<!-- Principio del widget de globo de Calendly -->
<link href="https://assets.calendly.com/assets/external/widget.css" rel="stylesheet">
<script src="https://assets.calendly.com/assets/external/widget.js" type="text/javascript" async></script>
<script type="text/javascript">window.onload = function() { Calendly.initBadgeWidget({ url: 'https://calendly.com/youthmtoquenzipa/com', text: 'Let\'s Talk', color: '#0069ff', textColor: '#ffffff', branding: true }); }</script>
<!-- Final del widget de globo de Calendly -->


<style>
  @import url('https://fonts.googleapis.com/css2?family=Courier+Prime&display=swap');
 
    body {
    margin: 0;
    padding: 0;
    font-family: "Courier Prime", monospace;
    background-color: #fdfdfe;
    }

    h5 {
    font-size: 25px;
    font-weight: bold; 
    color: #553c9a;
    border-right: 4px solid #000;
    white-space: pre-line;
    overflow: hidden;
    margin: 0;
    font-family: "Courier Prime", monospace;
    }

  h4 {
    font-size: 30px;
    font-weight: bold;
    color: #553c9a;
    border-right: 4px solid #000;
    white-space: pre-line;
    overflow: hidden;
    margin: 0;
    font-family: "Courier Prime", monospace;
    }

  h1 {
    font-size: 30px;
    font-weight: bold; 
    color: #553c9a;
    border-right: 4px solid #000;
    white-space: pre-line;
    overflow: hidden;
    margin: 0;
    font-family: "Courier Prime", monospace;
    }

  @keyframes cursor {
    0%, 100% { border-color: transparent; }
    50% { border-color: #000; }
  }

  #myCarousel .carousel-inner .carousel-item img {
    width: 100%;
    height: auto;
    border-radius: 10px;
  }
</style>

# Youth Ministry Collaborators

{bdg-primary}`Partnership`

<div id="myCarousel" class="carousel slide" data-ride="carousel">
  <!-- Indicadores -->
  <ol class="carousel-indicators">
    <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
    <li data-target="#myCarousel" data-slide-to="1"></li>
    <li data-target="#myCarousel" data-slide-to="2"></li>
  </ol>

  <!-- Slides -->
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="https://i.ibb.co/n1BVKLr/4.jpg" alt="Imagen 1" class="d-block">
    </div>
    <div class="carousel-item">
      <img src="https://i.ibb.co/R0DdkvW/7.jpg" alt="Imagen 2" class="d-block">
    </div>
    <div class="carousel-item">
      <img src="https://i.ibb.co/19Qb9Qz/6.jpg" alt="Imagen 3" class="d-block">
    </div>
  </div>

  <!-- Controles -->
  <a class="carousel-control-prev" href="#myCarousel" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Anterior</span>
  </a>
  <a class="carousel-control-next" href="#myCarousel" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Siguiente</span>
  </a>
</div>

<script>
  require(['jquery', 'bootstrap'], function($) {
    $(document).ready(function() {
      $('#myCarousel').carousel();
    });
  });
</script>
    
---   

<h4 id="typing-effect-1"></h4>  
<br>

Aquí están, nuestros talentosos miembros del equipo, quienes nutren la chispa de la juventud y el ámbito universitario con su dedicación y creatividad.

```{epigraph}
La verdadera medida de cualquier sociedad es cómo trata a aquellos que son más vulnerables

-- Mahatma Gandhi
```


<script>
  const texts = [
    "Collaborators"
  ];

  texts.forEach((text, index) => {
    let indexCounter = 0;
    const typingElement = document.getElementById(`typing-effect-${index + 1}`);

    function typeText() {
      if (indexCounter < text.length) {
        typingElement.textContent += text.charAt(indexCounter);
        indexCounter++;
        setTimeout(typeText, 90);
      }
    }

    typeText();
  });
</script>