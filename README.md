# Resultados

## La aplicación debe cumplir con los siguientes puntos que actualmente estan fallando: (

*   Tener un encabezado, color rojo, donde esté el nombre de la aplicación
*   En el encabezado, el título de la aplicación debe ser un link para mandar al usuario al índice
*   El índice debe mostrar:
    *  Una nota por fila
    *  Las notas ordenadas de más reciente a más antigua
    *  La fecha y hora de creación en la parte superior derecha de cada nota
    *  La hora de creación debe ser la hora local
    *  Un campo para buscar por título:
       * Encontrará las notas que contengan lo buscado en cualquier parte del título.
       * Si hay multiples palabras buscadas, debe buscar que todas las palabras esten presentes en el título, sin importar su orden.
       * Debe poder buscar caracteres especiales también ($, _, \, *, %)
*  Al hacer clic en cada nota, debe enviar a la vista completa de la nota, donde:
    *  se debe mostrar el cuerpo de la nota,
    *  respetando saltos de línea en caso de tenerlos,
    *  con un ícono indicado para borrar la nota,
    *  y otro para editarla.
*  Debe haber un botón de Nueva nota en el índice, también color rojo, que envíe al usuario a la interfaz de creación de notas.
Al crear o editar una nota:
    *  Si el titulo o el cuerpo de la nota estan vacios, no debe guardarse la nota.
    *  Si el titulo y el cuerpo tienen contenido, debe poder crearse la nota.
    *  El cuerpo de la nota debe permitir saltos de línea
    *  Si el cuerpo de la nota es muy grande, se debe ajustar automaticamente para mostrar todo el contenido.
    *  Despues de guardar la nota, se debe redireccionar al usuario a la vista completa de la nota recien guardada.
