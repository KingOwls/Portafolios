#PROYECTO DE PROTAFOLIOS

Analisis de peticiones y ajustes para la Pagina web

En lo ideal se pensaba utilizar React en el sentido de avanze y logro pero seria demasiado dificil por lo que preferiblemente no se usara en esta ocasion, en vez se usara exclusivamente HTML y CSS

Para este caso se diseñara lo siguiente queriendolo especificar en palabras.

Presentacion de Perfil: Mucho gusto, Jorge Osorio.
Desarollador de Videojuegos, estudiante de ingenieria de sistemas e infomatica, Desarrollador Junior.

Graduado de un seminario, estudiante de la UPB seccional bucaramanga, interesado en el desarollo de videojuegos desde joven, he querido plasmar mis ideas mas alla de simplemente hacer un codigo ya que incluso, los videojuegos como un nuevo arte dentro de las disciplinas.

Soy una persona creativa, alguien que piensa fuera de las normativas o leyes, escritor de medio tiempo y tambien lo que algunos consideran un filosofo interesado en entender las conductas humanas

Objetivos profesionales

Objetuvos a corto plazo:

Entre mis objetivos cercanos es buscar una compañia centrada en el desarollo de videojuegos y vender los inicios de mis ideas, entre ellas Symphony of Justice y de alli trabajar completamente enfocado en ello.

Objetuvos a medio plazo:

Deseando hacerme de un nombre o un titulo dentro de la industria seguir avanzando y creando mas conceptos e ideas los cuales puedan aportar a la industria, tanto mecanicamente, como en fundamento, centrandome en temas que usualmente no son tratados.

De alli generar un respeto entre los ideales y ampliar la vision, aunque sea de forma minima haga preguntas dentro de las personas que jueguen aquellas creaciones mias, intentando dar una pizca de duda en el interior de todos

Objetuvos a largo plazo:

Mi idea despues de tener un gran renombre y volverme una persona respetada es hacer una fundacion y una compañia, la fundacion esta centrada en chico con problemas psicologico centrado en la duda de su futuro, depresion, anciedad y demas temas los cuales en varias oportunidad no se les da el valor que merecen. al igual que muhcos jovenes que no pueden tener la oportunidad de estudiar por problemas economicos.

La compañia que deseo crear se enfoca mas en el desarrollo de videojuegos queriendo apoyar a estudios indie o incluso personas las cuales desean darle vida a sus proyectos, pero sea por orientacion, dificultades economicas y demas no pueden tener la oportunidad de crear y dar luz a sus invenciones.

Mision, Vision y valores

Misión: Define tu propósito profesional. Esta es una declaración que refleja por qué haces lo que haces y qué impacto quieres tener en tu entorno.

Visión: Describe tu aspiración a largo plazo. Aquí puedes detallar cómo imaginas tu carrera y cómo deseas influir en tu industria o comunidad.

Valores: Lista los valores que son importantes para ti y que guían tu toma de decisiones profesionales (e.g., integridad, innovación, colaboración, responsabilidad).

Certificaciones

Cur. Creacion de Videojuegos hecho por la UPB 2021

Servicios:

Los servicios que proveo son enfocado en Documentacion, conceptualizacion, proyectos y demas enfocado en la industria de los videojuegos, analisis y diseño de requerimientos, enfoque de actividades y desarollador de logica de videojuegos.

Proyectos

Exorcista judicii
Hijutsu No Shitsuji
Ultimo suspiro de los No muertos
Symphonia Iustitiae
Gastronomia Corrupta

Datos de contacto:

Correo personal
Correo Institucional
Numero de telefono
Whatsapp
Linkedin
Git

Ahora teniendo en cuenta todos los puntos se va a dar una descripcion de lo que desea dentro de cada uno de ellos y su justificacion.

Presentacion de Perfil: En este caso se buscara algo con un toque sombrio y gamer, lo ideal seria un diseño Pixel art presentando diferentes Conceptos, al igual que un perfil algo mas personal.

https://www.davidshaver.net/index.html

https://hugo.fyi/#

Referencia de lo que se busca pero limitado al no tener Videos ni presentaciones, por lo cual se buscara de algun Link o algo similar que pueda presentar estos conceptos

Objetivos profesionales: En este caso se habla mas de Ambito Gamer, centrado en cosas externos como pueden ser, la ingenieria, conceptualizacion, planteamiento de requerimientos, etc.
Tambein sacando adelante las ideas o conceptos de menor escala, dandoles como un Componente (Por eso, React) que explique mas a profundidad lo que se quiere, en su defecnto se buscara hacer conexion de hipervinculos entre los mismos proyectos, un git general y uno que se conecte entre ellos(Ver si es posible).

Mision, Vision y valores, Esto explicado con imagenes y animaciones al igual que una estetica mas relagada

Certificaciones: La unica que se posee que es de introduccion a desarrollo de videojuegos (Buscar el poster)

Servicios: Explicar mis servicios y mis capacidades en el ambito profesional y de la misma manera profundizar un poco mas en todos estos proyectos.

Proyectos: Estos se trataran resaltando los de campus y se va a mostrar aquel que se hizo en la universidad, aunque es preferible darle un vistazo simple, por demas hablar desde los conceptos y llevarlos con una estetica que atraiga.

Exorcista judicii
Hijutsu No Shitsuji
Ultimo suspiro de los No muertos
Symphonia Iustitiae
Gastronomia Corrupta

Se quiere vender mas la idea de que tengo gran potencial y lo unico que me limita es el equipo que pueda apoyar las grandes ideas que pueden llegar a presentarse como proyectos textuales.

Datos de contacto
En este caso ese basa en buscar hacer lo mismo que hizo pola, en el sentido de buscar metodos de contacto, diseño y presentacion, intentando atraer a las personas por como se puede hacer, al igual que buscar hacer que mi instagram llenarlo de info de personajes y creaciones.

Mas adelante se especificara como se hara cada uno de ellos teniendo que cada Proyecto tenga un diseño que atraiga por su idea.

El portafolio debe ser oscuro pero no aterrador enfocado en las ideas de las sombras y lo que se quiere buscar es dar miendo que aun asuste no pudeas dejar de verlo.

```<!DOCTYPE html>
<html>
<head>
<style>
body {
  margin: 0;
  padding: 0;
  background-color: #f0f0f0;
}

.container {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100vh;
}

.title {
  font-size: 3em;
  margin-bottom: 20px;
  cursor: pointer;
}

.crow {
  position: absolute;
  width: 100px;
  height: 100px;
  background-image: url("crow.jpg"); /* Replace with your crow image */
  background-size: contain;
  background-repeat: no-repeat;
  opacity: 0;
  transition: all 0.3s ease-in-out;
}

.crow.show {
  opacity: 1;
}

.crow.flying {
  animation: fly 2s linear infinite;
}

@keyframes fly {
  0% {
    transform: translateX(0) translateY(0);
  }
  50% {
    transform: translateX(20px) translateY(-10px);
  }
  100% {
    transform: translateX(0) translateY(0);
  }
}
</style>
</head>
<body>
<div class="container">
  <h1 class="title" data-target="title1">Title 1</h1>
  <h1 class="title" data-target="title2">Title 2</h1>
  <h1 class="title" data-target="title3">Title 3</h1>
  <div class="crow" id="crow"></div>
</div>
<script>
const titles = document.querySelectorAll('.title');
const crow = document.getElementById('crow');

titles.forEach(title => {
  title.addEventListener('click', () => {
    const target = title.dataset.target;
    crow.style.left = `${title.offsetLeft + (title.offsetWidth / 2) - (crow.offsetWidth / 2)}px`;
    crow.style.top = `${title.offsetTop - crow.offsetHeight}px`;
    crow.classList.add('show', 'flying');
    setTimeout(() => {
      crow.classList.remove('flying');
      setTimeout(() => {
        crow.classList.remove('show');
      }, 3000);
    }, 5000);
  });
});
</script>
</body>
</html>```