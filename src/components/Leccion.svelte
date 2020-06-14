<script>
  import * as data from '../../data/leccion1.json'
</script>

<div class="Leccion">
  
  <div>
    <h3> <!--Leccion Numero -->
      Leccion {@html data.numero}
    </h3> 
    <p> <!--Leccion Fecha-->
      <em>
        {@html data.fecha}
      </em>
    </p> 
    <h2> <!--Leccion Titulo-->
      {@html data.titulo}
    </h2> 
    <h4> <!--Leccion Subtitulo-->
      {@html data.subtitulo}
    </h4> 
    
    <p> <!--Nota Introduccion -->
     {@html data.notaIntro}
    </p>
  </div>

  <div class="Pregunta"> <!--Empieza Pregunta -->
    <!-- <h3>Subtitulo</h3> Subtitulo  -->
    <h4>1. {@html data.preguntas[0].pregunta}</h4> <!--Pregunta -->
    <p><strong>{@html data.preguntas[0].citas[0]}</strong></p> <!--Texto 1 {-->
    <p>
      {@html data.preguntas[0].textos[0]}
    </p>
    <p><strong>{@html data.preguntas[0].citas[1]}</strong></p> <!--Texto 2-->
    <p>
      {@html data.preguntas[0].textos[1]}
    </p>
    <p><strong>{@html data.preguntas[0].citas[2]}</strong></p> <!--Texto 3-->
    <p>
      {@html data.preguntas[0].textos[2]}
    </p>
    <p><strong>Nota</strong></p> <!--Nota -->
    <p>
      {@html data.preguntas[0].nota}
    </p>
  </div> <!-- Fin Pregunta -->
  
  <div class="Pregunta"> <!--Empieza Pregunta -->
    <!-- <h3>Subtitulo</h3> Subtitulo  -->
    <h4>2. {@html data.preguntas[1].pregunta}</h4> <!--Pregunta -->
    <p><strong>{@html data.preguntas[1].citas[0]}</strong></p> <!--Texto 1 {-->
    <p>
      {@html data.preguntas[1].textos[0]}
    </p>
    <p><strong>{@html data.preguntas[1].citas[1]}</strong></p> <!--Texto 2-->
    <p>
      {@html data.preguntas[1].textos[1]}
    </p>
    <p><strong>{@html data.preguntas[1].citas[2]}</strong></p> <!--Texto 3-->
    <p>
      {@html data.preguntas[1].textos[2]}
    </p>
    <p><strong>Nota</strong></p> <!--Nota -->
    <p>
      {@html data.preguntas[1].nota}
    </p>
  </div> <!-- Fin Pregunta -->

</div>