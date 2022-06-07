# Parte practica del examen del tercer trimestre de sistemas informáticos 
### Hecho por Joan Pérez Susidko


Primero logeamos en docker desde powershell

![image](https://user-images.githubusercontent.com/101748401/172464019-54a51521-449c-4a65-b146-5c8847781325.png)

He creado una carpeta docker con el dockerfile y el archivo .war del proyecto

![image](https://user-images.githubusercontent.com/101748401/172464184-08c0a4d4-1410-487e-9fe4-bdf6a54dc201.png)

Creo un dockerfile 

![image](https://user-images.githubusercontent.com/101748401/172464364-524800e7-d123-4f07-a267-30e65d511e71.png)

Creo una imagen con docker image build -t gymapp . 

![image](https://user-images.githubusercontent.com/101748401/172464493-d844ef56-7b36-4d1e-9329-638426e42343.png)



Me da un error y a partir de aquí no puedo avanzar, pero esto serían los siguientes pasos:

#### SOLUCIÓN:
*Cambiar a contenedores de windows, en switch to windows containers*


Después de la imagen, creo un tag con gymapp:. gymapp:gymappimage

Luego haría un push de la imagen al repositorio de DockerHub con el comando: docker push joanperezs/gymappimage

Finalmente tendriamos desplegada la imagen en el repositorio de DockerHub









