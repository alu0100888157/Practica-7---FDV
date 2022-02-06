# Practica-7---FDV
Cámara con seguimiento al personaje A. Se debe configurar el seguimiento hacia adelante. Esta cámara es la que debe tener la máxima prioridad.
Cámara con seguimiento al personaje B. Debe configurarse una zona de seguimiento del personaje B más amplia que la de A.
Cámara que hace el seguimiento de ambos personajes.
Crear una zona de confinamiento de A que abarque toda la escena.
Se debe crear una zona de confinamiento de la cámara B que abarque una parte de la escena.
Añadir un objeto que genere una vibración en la cámara cuando A choca con el
Seleccionar un conjunto de teclas que permitan hacer el cambio de la cámara de los personajes a la cámara que sigue al grupo. (Habilitar/Deshabilitar el gameobject de la cámara virtual)


Como se puede observar al principio pruebo las tres cámaras cambiándolo con los botones 1 (jugador),2(enemigo),3(ambos), también se puede ver cómo vibra la cámara y eso es que el objeto puerta, tiene un evento de vibración y al tocar al jugador vibra
Se comprueba que por el confiner del jugador la cámara no va más a la izquierda del escenario
En el segundo vídeo se ve cómo la cámara 2 tiene una zona de seguimiento más amplia y a la vez un confiner diferente porque al final si cambiamos a la cámara 1, esta se quedó más atrás
Por último se comprueba con la cámara 3 que no tiene confiner, cómo es atravesar ambos confiner (tanto del jugador como del enemigo).

![](https://github.com/alu0100888157/Practica-7---FDV/blob/master/Assets/VIDEOS/practica%207-1-%2505d.gif)
![](https://github.com/alu0100888157/Practica-7---FDV/blob/master/Assets/VIDEOS/practica7-2-%2505d.gif)
![](https://github.com/alu0100888157/Practica-7---FDV/blob/master/Assets/VIDEOS/Practica%207-3-%2505d.gif)
