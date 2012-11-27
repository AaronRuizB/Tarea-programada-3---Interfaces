Proyecto3 - Interfaces Gráficas
=============================

 Editor de presentaciones HTML5
--------------------------------

Introducción
--------------


El presente trabajo tiene como objetivo que los estudiantes se familiaricen con los conceptos
relacionados con Bootstrap, en nuestro caso, con editores de HTML para usuarios finales. 

Para el trabajo, es necesario investigar e implementar una aplicación web que permita abrir, 
guardar y crear una presentación, tomando en cuenta las librerías utilizadas en clase para su desarrollo, 
esto con la Tecnología mencionada anteriormente (Bootstrap).

 
 
Algunas librerías  investigadas
-------------------------------

1. Filefuntions.js:
-------------

   * Contiene las funciones relacionadas con los ficheros, es decir, abir, guardar y crear presentación.

2. style.css:
-----------
 
   * Permite usar temas para el manual de ayuda.
   * Se implementa de manera iterativa la forma, color y tamaño de las diapositivas creadas por defecto.

3. impress.js:
--------------

 *  Utiliza las últimas tecnologías soportadas por los navegadores, de modo que las presentaciones requieren ser visualizadas en las últimas versiones de los navegadores modernos, como Google Chrome, Firefox, Opera o Safari.
 *  Inspirada en Prezi pero que utiliza solamente CSS3, Javascript y HTML.

4. Editor de HTML.htm:
----------------------

*  Se crea el código para ulitizar los componentes necesarios en la interfaz


 
Contenido a Desplegar
----------------------

 Se debe crear un editor de presentaciones en html5, el
 cual debe ser capaz de cargar un archivo y visualizarlo como una presentación HTML5.
 
 Se le mostrará al usuario una interfaz amigable, con tooltips para su mayor entendimiento, 
 además, se le brindará un manual de usuario, indicando los pasos necesarios para utilizar la 
 aplicación web. 
 
 Se espera mostrar una presentación pre-cargada al inicio, lo cual es de ayuda intuitiva para el usuario,
 además, se le brinda la facilidad de poder editar la diapositiva de modo que vaya viendo los cambios realizados.
 
 

Estructura de los datos
------------------------

              <presentation>
                 <slide>
                   <title titulo="Titulo de la diapositiva 1"</title>
                   <h1 info="Descripción de la diapositiva 1"></h1>
                 </slide> 
                 <slide>
                   <title titulo="Titulo de la diapositiva 2"</title>
                   <h1 info="Descripción de la diapositiva 2.1"></h1>
                   <h1 info="Descripción de la diapositiva 2.2"></h1>
                 </slide>
                 
              </presentation>
                
Forma de compilación, ejecución y utilización de la aplicación
---------------------------------------------------------------

1. Crear una carpeta llamada Proyecto3, en C:/

2. En la carpeta Proyecto3:

   a) Crear una carpeta llamada  source.
   
   b) Pegar dentro los archivos encontrados en el github como proeyecto 3 - interfaces gráficas
   enlace: https://github.com/aaruiz89/Tarea-programada-3---Interfaces
   
   c)Ejecutar el Adobe Air,
   Adobe Air cuenta con la herramienta adl que permite probar la correcta ejecución de las aplicaciones. 
   Esta herramienta se puede ejecutar desde el directorio en donde se instaló el SDK de Adobe Air,
   por ejemplo: C:/AdobeAirSDK. Por tanto la ejecución se puede realizar de la siguiente
   forma (desde el directorio tinyhtmleditor\source):
   
   d) Ejecutar Adobe Air con el siguiente comando en consola:  C:\AdobeAirSDK\bin\adl application.xml
   
   Luego abrir el "Editor de html" y empezar la aplicación.
              

 

Ejemplo de Datos
------------------
  
             <presentation>
                   <slide>
                     <title titulo="Interfaces Gráficas"</title>
                     <h1 info="Curso electivo del TEC"></h1>
                   </slide> 
                   <slide>
                     <title titulo="Contenidos"</title>
                     <h1 info="Diseño de Interfaces"></h1>
                     <h1 info="Programacion en Coffeescript"></h1>
                   </slide>
                   <slide>
                     <title titulo="Evaluaciones"</title>
                     <h1 info="Examenes y Proyectos"></h1>
                   </slide>
                   <slide>
                     <title titulo="Sitio web del Curso"</title>
                     <h1 info="http://www.arcux.com/cursos/course/view.php?id=9"></h1>
                   </slide>
                </presentation>

Además, se utilizán datos de pre-llenado, para facilitarle al usuario la ulitización de la apliacción, con el mínimo
esfuerzo. Para esto, se le brindará la siguiente estructura en pantala:


<!--Aqui van las diapositivas-->
<!--________________________________________________-->
    <div class="slide" id="slide3">
      <section class="middle">
         <hgroup>
           <h2>
             TITULO
           </h2>
         </hgroup>
         <p> CONTENIDO</p>
         <img src= -URL DE LA IMAGEN-></img>
      </section>
    </div>

                
                
Limitaciones observadas y posibles mejoras 
------------------------------------------

Limitaciones:

   1.Se tuvieron limitaciones con el Adobe Air, ya que no se logró empaquetar en un .air
   
Mejoras:

   1. Se creó el manual de usuario en el sitio web
   2. Se modificó el tema de la aplicación
   3. Se crearon botones con tooltips, para guiar al ususario, en vez de botones no visibles dentro de un manú
   4. Se implementó un archivo style.css, en donde se definieron los tipos y colores de las diapositivas.
   5. Se aprendió sobre bootstrap, dentro de las mejoras, la herramienta cuenta como parte, ya que contienen 
      suficiente documentación en internet, además de al dada por el Profesor en el curso de Interfaces Gráficas.

   
   
 by Silvia Delgado y Aaron Ruiz