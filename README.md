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

1. Crear una carpeta llamada Proyecto1, en C:/.

2. En la carpeta Proyecto1:

   a) Crear una carpeta llamada  chrome.
   
   b) Crear una carpeta llamada default.
   
   c)Crear un archivo  llamado application.ini  con lo siguiente:
              

                        [App]
                              Vendor=Silvia
                        Name=Proyecto1
                        Version=1.0
                        BuildID=20100901
                        ID=sdelgado@itcr.ac.cr
                        
                        [Gecko]
                        MinVersion=1.8
                        MaxVersion=16.*
                        
                        
   d)Crear un archivo  chrome.manifest con lo siguiente:
   
                       manifest chrome/chrome.manifest
                       
                       
 3.  En la carpeta  default :

   a)Crear una carpeta preferences  y en esta crear un archivo prefs.js con lo siguiente:
   
                       pref("toolkit.defaultChromeURI", "chrome://Proyecto1/content/main.xul");
           
           
4.En la carpeta chrome:

  a)Crear  una carpeta content .
  
  b)Crear un archivo chrome.manifest con lo siguiente: 
   
                       content Proyecto1 content/
                 
5. En la carpeta content:

  a) Descargar en esta carpeta la compilador de coffeescript y  la librería d3.js.
  
  b) Copiar a esta carpeta los archivos main.xul ,main.coffee y reveal.js que se adjuntan.
 

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

                
                
Limitaciones observadas y posibles mejoras 
------------------------------------------

Limitaciones:

   1.
   
Mejoras:

   1.
   
   
 by Silvia Delgado y Aaron Ruiz