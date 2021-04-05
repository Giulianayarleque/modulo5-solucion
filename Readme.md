Asignación de codificación del módulo 5
Curso de Coursera: HTML, CSS y Javascript para desarrolladores web

¡Última tarea y listo!

Tiempo para completar: unos 30 minutos.

¡Haga preguntas en Debates si se queda atascado! Todos estamos aprendiendo, y atravesar el problema y luego despegarnos (incluso con la ayuda de alguien) puede ser una experiencia de aprendizaje muy valiosa.

Resumen: En esta tarea, vamos a divertirnos un poco con nuestra aplicación web de restaurante construida. La página principal de nuestra aplicación web contiene 3 mosaicos en los que se puede hacer clic: Menú, Especiales y Mapa. Si hace clic en el mosaico de Especiales, se lo llevará a una página de una sola categoría donde se mostrarán todos los elementos del menú que pertenecen a la categoría del menú de Especiales. Su tarea en esta tarea es modificar este comportamiento de modo que cuando el usuario haga clic en el mosaico de Especiales, la aplicación web lleve al usuario a una página de menú aleatoria de una sola categoría, que enumere los elementos del menú en la categoría, ya sea "Almuerzo", "Cena "," Sushi ", etc. ¡De esa manera, cualquier categoría aleatoria puede convertirse en Especiales! ¡Qué divertido! (¡no! :-) )

Para lograr esto, necesitamos cambiar el fragmento HTML de inicio y, además de extraerlo dinámicamente del servidor, también insertar una categoría aleatoria short_nameen la llamada de función del siguiente código. Anteriormente, el código para enviar al usuario a la categoría "Especiales" era este:

< Un  href = " # " onclick =" $ dc.loadMenuItems ( 'SP'); " >
Para esta asignación, cambiamos esta línea para prepararla para que una categoría aleatoria short_namesea ​​esta:

< Un  href = " # " onclick =" $ dc.loadMenuItems ({{}} randomCategoryShortName); " >
Esto es lo que necesitará para completar la tarea:

(Si aún no lo ha hecho) Cree una cuenta de GitHub.com y un repositorio que utilizará para esta clase.

(Si aún no lo ha hecho) Siga las instrucciones del video de configuración de desarrollo (comienzo del módulo 1) sobre cómo crear un repositorio y configurarlo de manera que pueda alojar y ver sus páginas web terminadas en las páginas de GitHub, es decir, GitHub.io nombre de dominio. Deberá proporcionar esa URL para su revisión por pares.

Cree una carpeta en su repositorio que servirá como carpeta contenedor para su solución a esta tarea. Puedes llamarlo como quieras. Por ejemplo, module5-solutiono mod5_solution, etc.

Deberá descargar los archivos de inicio para este proyecto y copiarlos en la carpeta contenedora de la solución (por ejemplo, en 'module5-solution'). Dado que las asignaciones y el código de inicio se actualizan de vez en cuando, no asuma que ya tiene la última versión en su sistema. La mejor manera de asegurarse de que está trabajando con el código de inicio más reciente es 'git clone' el fullstack-course4repositorio en un nuevo directorio O, si ya ha hecho 'git clone' anteriormente, simplemente puede abrir su símbolo del sistema ( cmd en Windows o Terminal en Mac), navegue hasta la carpeta donde fullstack-course4se clonó previamente el repositorio y haga: git pull

Esto actualizará su repositorio local con los cambios que se hayan realizado desde la última actualización.

Como recordatorio, la URL completa del repositorio es: https://github.com/jhu-ep-coursera/fullstack-course4

Una vez que actualice su repositorio, copiar todo el contenido de la fullstack-course4/assignments/assignment5/assignment5-solution-startercarpeta en la carpeta de soluciones de envase recién creado para esta tarea, por ejemplo, module5-solution.

Una vez hecho esto, estará listo para comenzar a codificar la solución.

NOTA: el código proporcionado no se ejecutará. Depende de usted seguir las instrucciones para que se ejecute.

NO se le permite cambiar el home-snippet.htmlarchivo. Cualquier ajuste al valor de la randomCategoryShortNamepropiedad debe realizarse en código Javascript.

Hay 4-5 pasos bastante simples para implementar la funcionalidad requerida.

Abra el js/script.jsarchivo.
Busque TODO: STEP 0 y siga las instrucciones hasta que haya terminado con TODO: STEP 4.

Si ha visto las conferencias, el código le resultará muy familiar.

Una vez que haya terminado, verifique que la funcionalidad deseada esté funcionando correctamente. Use Browser Sync o implemente su solución en las páginas de GitHub.
Cargue la página de inicio en el navegador.
Haga clic en el mosaico de Especiales. Debería aparecer una categoría de una sola página con una lista de elementos de menú para alguna categoría.
Haga clic en el logotipo del restaurante para volver a la página de inicio.
Vuelva a hacer clic en el mosaico de Especiales. Lo más probable es que se muestre una página de categoría de una sola página diferente.

Repita esto varias veces para asegurarse de que la mayoría de las veces vea una página de una sola categoría diferente.

¡Eso es todo!
