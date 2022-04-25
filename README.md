# Instalacion de docker en Alpine
### Tendremos que entrar en la pagina principal de alpine y descargar la alpine virtual

![i1](https://user-images.githubusercontent.com/91874537/165064696-86fc648f-1aed-4b03-a503-783b7abeb9a9.PNG)

### Abrimos el oracle y creamos una nueva maquina virtual

![3](https://user-images.githubusercontent.com/91874537/165064845-24b450e2-3aa3-4d63-9363-9742ee816239.PNG)

### Ponemos el tamaño de memoria

![4](https://user-images.githubusercontent.com/91874537/165064885-38665bef-43e8-4d36-bdb4-8a8e6d628ae9.PNG)

### Ponemos la capacidad del disco duro

![5](https://user-images.githubusercontent.com/91874537/165064936-f73094ca-7a4e-4000-bae2-0eb581a3fe29.PNG)

### Y ya tendriamos en oracle añadido alpine

![6](https://user-images.githubusercontent.com/91874537/165065226-41ac1f72-5229-4c5f-bfaf-d6247c6fdb00.PNG)

### Ahora tendremos que ajustarlo

#### Quitamos el audio ya que no lo usaremos

![q1](https://user-images.githubusercontent.com/91874537/165065742-44ead213-9e70-4b59-82e8-470a9d6b6464.PNG)

#### Añadiremos el alphine al disco que aparecera como vacio

![q2](https://user-images.githubusercontent.com/91874537/165065965-f5a6a8b3-00ff-45e3-afac-fb46cd553ca6.PNG)

#### Entramos como root y ejecutamos el setup-alpine

![q3](https://user-images.githubusercontent.com/91874537/165066281-ef88073e-366d-432f-a5ca-c9912dadfca5.PNG)

#### Ponemos la distribucion del teclado
es y luego especificamos es-cat
#### entramos como node1 
le damos 3 veces a enter para que nos lo ponga por defecto

#### Ponemos de donde somos

![q4](https://user-images.githubusercontent.com/91874537/165067103-2a35ee8c-7fe3-417c-bb18-69001e38b33c.PNG)

y la subcategoría

volvemos a darle enter para que nos ponga valores por defecto

#### selecionamos el disco 

![q5](https://user-images.githubusercontent.com/91874537/165067435-280d8afa-118a-4074-8d4f-98749a1a7aed.PNG)

#### y entamos sys y le damos a y
#### se descarga y nos pide reiniciar

### Cambiamos la red

![q6](https://user-images.githubusercontent.com/91874537/165067861-1c3b8329-4c3f-4726-a629-5aaebb8053cd.PNG)

### vamos al sistema y deselecionamos 2 casillas

![q7](https://user-images.githubusercontent.com/91874537/165068150-e1b7f371-8197-4a7e-9100-0f49691068d2.PNG)

### ejecutamos el siguiente comando vi /etc/ssh/sshd_config 
dentro vamso a la linea 23 que la modificamos a yes

#### restablecemos el sshd
y pedimos la ip

### Abrimos el git bash y nos metemos a la ip 

![q8](https://user-images.githubusercontent.com/91874537/165068994-1fd79fbe-0ea0-480d-a206-8b025eeefca0.PNG)

### Ejecutamos el siguiente comando y quitamos los hashtac

![q9](https://user-images.githubusercontent.com/91874537/165069218-8c30b8c6-d0b0-4d72-b176-1fa9e9662174.PNG)

### Ejecutamos el apk add docker y se descargara

![q10](https://user-images.githubusercontent.com/91874537/165069703-b1b59577-8303-4640-bfbe-2add6e778a1d.PNG)
