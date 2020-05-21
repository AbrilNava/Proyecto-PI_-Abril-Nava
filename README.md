# Proyecto PI_ Abril Nava

Se trata de un proyecto multidisciplinario puesto que se hace uso de la programación, imagen y sonido. 
Cabe mencionar que está basado en el primer proyecto entregado en el parcial 1, a continuación se explica la naturaleza del proyecto y sus diferencias con el anterior…
Se usan 2 programas, Pure Data y Processing: en Processing se carga un modelo 3D con distintas luces de colores direccionales que responden a los datos que se introducen en un parche de Pure Data, en dicho parche se implementan algunas funciones tales como:
Key, detecta la nota que estamos tocando; Select, deja pasar la señal de un valor, la señal llega al Bang y si esa señal es cierta, reproduce un tono, también esa señal la envía a 3 parámetros de la función Note out; el primero de esos 3 parámetros es la nota MIDI que reproduce esa nota (o la identifica), el segundo es la velocidad a la que se presiona la tecla, y el tercero es el canal en el que se reproduce la nota.
El bang envía una señal a un mensaje y ese mensaje se almacena en una casilla de número, este valor envía algún parámetro al programa de processing donde se modifican los colores y la posición de la luz. 

Se diferencia del primero en la cuestión de que ahora tiene sonido (con todo lo que implica haberlo implementado), se hizo una especie de teclado con notas MIDI que interactúan con el objeto 3D cargado en processing.


En cuanto a su perspectiva artística, está sustentado en el uso de la luz como representación de cambio (en el rostro del modelo), pueden ser cambios del ánimo, del pensamiento o cualquier cambio que el espectador pueda captar ya que de hecho actualmente nos encontramos en una etapa de cambio grande para nuestra sociedad. 
El uso de la música también, a manera de cómo influye o manipula nuestros estados de ánimo, ya que como podrá notar al cambiar alguna nota también cambia el color y la luz en el rostro del modelo. 
