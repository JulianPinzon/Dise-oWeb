# Dise-oWeb


Para el despliegue local del proyecto tenemos que:

1) Utlilizando la herramienta para almacenamiento de repositorios en la nube
   GitHub, descargamos el programa e instalamos el programa para manejo del codigo .git 
   en el interprete de comandos de windows CMD (https://git-scm.com/download/win) 
   
2) Despues con el link del repositorio (ya creado) ingresamos la linea de comando
   git clone (link de repositorio git) para clonar el repositorio en el directorio actual
   
3) Con el comando git add . añadimos los archivos al repositorio local 

4) Con el comando git commit -m "(mensaje)" realizamos una confirmacion de los cambios hechos 
   en el repositorio local, para asi mediante un mensaje establacer los cambios hechos hasta dicha confirmacion
   -commit
  
5) Finalmente con el comando git push -u origin master realizamos una sincronizacion con el repositorio en la nube
   para asi cargar los archivos del repositorio local al repositorio en la nube Git Hub
