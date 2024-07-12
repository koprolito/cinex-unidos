CinexUnidos

Descripción:
  Este proyecto se hace con la finalidad de dar cumplimiento a lo pautado 
  en el plan de evaluación en la materia "Programación Orientada a la Web" en la Universidad
  Católica Andrés Bello en el segundo semestre del período académico 2023-2024. El taller en cuestión
  simula el comportamiento de una aplicación web de un cine para el apartado del cliente, entiendase
  la visualización de los cines, de las funciones del cine, las películas en proyección y la
  reservación de asientos.

Instrucciones de uso:
  1. Descargue el archivo index.html
  2. Una vez descargado, abra este archivo en el navegador de su preferencia.
  3. Lo primero que verá al abrir el archivo será una interfaz con un encabezado 
     de segundo nivel que dice "Cines:" y tres contenedores que contienen una imagen y un 
     encabezado de tercer nivel respectivamente. Cada uno de estos contenedores es seleccionable,
     y a su vez la selección de uno de estos desplegará un contenido diferente. Seleccione uno de estos contenedores.
  4. Al haber seleccionado uno de los contenedores, todo lo mencionado anteriormente dejará de mostrarse y 
     se deben desplegar a continuación un encabezado de segundo nivel que dice "Salas:" y, al menos, un
     contenedor con un encabezado de tercer nivel. Seleccione uno de estos contenedores.
  5. Al haber seleccionado uno de los contenedores, todo lo mencionado anteriormente dejará de mostrarse y 
     se deben desplegar a continuación un encabezado de segundo nivel que dice "Funciones:" y, al menos, un
     contenedor con una imagen y un encabezado de tercer nivel. Seleccione uno de estos contenedores.
  6. Al haber seleccionado uno de los contenedores, todo lo mencionado anteriormente dejará de mostrarse y 
     se deben desplegar a continuación elementos de tipo encabezado de tercer nivel,contenedores, una tabla con contenido 
     seleccionable (asientos) y tres botones. 
      6.1 Para ciertos elementos en esta parte deben ocurrir lo siguiente:
            - Asientos: como se debe indicar en la interfaz, cada color de cada asiento simboliza algo diferente. 
            Para los asientos de color azul (asientos disponibles), estos son asientos que puede seleccionar
            para ser procesados más adelante. Para los asientos de color rojo (asientos ocupados), estos no son
            seleccionables. Para los asientos de color verde (asiento seleccionado) simboliza 
            que ha seleccionado uno o más asiento.
            - Botones:
               - Botón "Soporte": desplegará un contenedor "chat" el cual le permitirá contactar con el "soporte" del cine.
                 Más adelante se desarrolla cómo proceder con este chat.
               - Botón "Aceptar": sirve para procesar los asientos seleccionados. Si no ha seleccionado ningún asiento, se
                 le alerta al usuario de ello. Más adelante se desarrolla cómo proceder ante este botón
               - Botón "Voler": Lo devolverá a la interfaz que se mostró antes de la actual.
         6.1.1 Seleccione uno o más asientos y luego presione el botón "Aceptar". Al haber hecho esto, se mostrará
               una interfaz detallando los datos procesados en todas sus selecciones hasta el momento incluyendo los asientos 
               y dos botones: un botón "Confirmar" y un botón "Cancelar". Seleccione el boton "Confirmar" y, al hacerlo, se mostrará
               el resumen de todos los datos procesados hasta ese momento y un botón "Volver al menú" que, si lo selecciona,
               lo devolverá a la primera interfaz que visualizó al entrar a la página.
         6.1.2 Si selecciona el botón "Soporte", desplegará un contenedor "chat" el cual le permitirá contactar con el 
               "soporte" del cine. Lo primero que le pedirá para poder hacer esto es su nombre, escriba su nombre y presione
               la tecla "Enter" en su teclado.
               6.1.2.1 Al seleccionarlo, ya estará en el chat esperando a que lo contacte el soporte. Debido a la versión
                       actual del proyecto y a su simpleza, para poder interactuar con el soporte debe abrir en el navegador 
                       el archivo "empleado.html".
               6.1.2.2 Al hacerlo, debe desplegarse primero un campo de entrada
                       donde debe colocar el nombre de un empleado ficticio. Coloque dicho nombre y presione la tecla 
                       "Enter en su teclado".
               6.1.2.3 Al hacerlo se mostrará una interfaz donde se le indican los clientes que 
                       están conectados en ese momento. Seleccione el cliente que tiene el mismo nombre que había ingresado
                       anteriormente y, al hacerlo, se desplegará un chat con dicho cliente donde podrá interactuar
                       con el enviando mensajes como empleado.
