# Primer-proyecto-LearHistology
Este va a ser mi primera app publicada en la playstore, como tal no voy a hacer público el código, sin embargo voy a ir subiendo su progreso en imágenes hasta que finalmente este publicada.

La idea de la app es estar orientada a estudiantes de medicina, particularmente de la materia de histología, cuando fui alumno me hizo falta tener a mano las imágenes para consultarlas a la hora del estudio ya sea con el microscopio en mano o cuando iba en viaje al examen, por eso, la aplicación está orientada a mostrar todas las imágenes microscópicas de cada órgano del cuerpo humano, ordenadas por categoría y de una manera amigable al usuario.

Para eso y como primer proyecto me baso sobre todo en el navigation component de Android, con un solo activity estoy almacenando varios fragmentos y entre ellos se van informando sobre que mostrar en la pantalla siguiente para de esa manera reutilizar los fragmentos y ahorrar recursos. 
Con la pantalla de inicio se adjuntan los distintos sistemas del cuerpo de manera amigable y siguiendo los lineamientos de material design, en lugar de utilizar botones tradicionales decidí utilizar material cardViews con botones e imágenes, les agregué el parámetro de elevation para que en la interfaz tuvieran la sombra que es tan estética.

Una vez elegida la categoría se lleva a otra subcategoría donde el usuario elige el órgano que quiere inspeccionar, y allí dependiendo siempre de que botón se presione se reutiliza el fragmento para mostrar la información y las imágenes. Para la información utilizo un ExpandableTextView, el cual logre gracias a la librería 
'com.ms-square:expandableTextView:0.1.4', debajo incluiré próximamente un Image Slider con todas las imágenes y los zooms para cada órgano correspondiente, es decir, para el estómago una imagen x2, x4, x8 de manera que se puedan dilucidar todos los componentes celulares del órgano.

Sumado a lo previo me gustaría agregar que la aplicación va a contar con un Material Navigation Drawer, para así poder elegir el idioma entre inglés y español y para también poder cambiar entre modo oscuro y modo luminoso a gusto del usuario, así también como un botón de compartir y un intent para referirlo a la página de calificaciones de Playstore. Además, la idea es que la app contenga un Search Bar para así poder navegar de manera más fluida entre los distintos órganos en caso de ser necesario. Me gustaría comentar que a la fecha de creación de este README la aplicación solo lleva solo 4 días de desarrollo invirtiendo aproximadamente 3-4 horas por día, con lo que mi plazo aproximado de finalización es de un mes.
