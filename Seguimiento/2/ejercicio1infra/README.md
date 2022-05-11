### Seguimiento 2

El proposito del ejercicio es la recuperacion de la contraseña root y del ejercicio anterior de las carpetas añadir otras nuevas y utilizar el comando mv para mover los nuevos archivos.

1. Recuperar la contraseña root

- Oprimir una tecla para detener el arranque
- Presionar la tecla "e"

![1](https://user-images.githubusercontent.com/90016164/167905068-f737067a-da28-47cc-b654-1e914e61ae49.PNG)

- Se busca la línea linux "rhgb quiet" y se reemplazar la sentencia  por "rd break"
- Presionar Ctrl + x


![2](https://user-images.githubusercontent.com/90016164/167905739-2c060b7f-99f6-4082-81fc-c9e9e1d5778a.PNG)

![3](https://user-images.githubusercontent.com/90016164/167905731-fdb1d661-8c77-4a1a-ac65-f4068b0d0877.PNG)

![4](https://user-images.githubusercontent.com/90016164/167905736-5da303a0-0ca1-46aa-80f5-018f98136206.PNG)

- Se usa el comando "mount" para cambiar la contraseña del root mount -o rw, remount /sysroot/ y ya siguiente el comando mount chroot/sysroot/ passwd y por ultimo el comando touch /.autorelabel - Exit x2.


![6](https://user-images.githubusercontent.com/90016164/167906796-85ca10e2-bf2e-455b-8418-db758fd37b42.PNG)

![8](https://user-images.githubusercontent.com/90016164/167906799-a5565223-3e7e-48c9-b6fb-883db6083364.PNG)

![10](https://user-images.githubusercontent.com/90016164/167906791-3b5ddc5a-6097-4c97-9410-a590fa50d5c3.PNG)

![11](https://user-images.githubusercontent.com/90016164/167906793-29909c46-9724-45ac-92ff-eca95a73036a.PNG)

![12](https://user-images.githubusercontent.com/90016164/167906795-f1c37319-3f73-420b-8638-7621b669af87.PNG)

1. De los archivos ya creados se realiza el uso del comando mv para el ejercicio propuesto.

- Se observa el arbol de directorios.

![1](https://user-images.githubusercontent.com/90016164/167907571-72a16a7b-4fc8-4c33-8c5b-cd29bfc47a98.PNG)

- Movemos los nuevos directorios para establecer la jerarquia de las carpetas.

![2](https://user-images.githubusercontent.com/90016164/167908399-de5372be-314d-4c74-a8cb-4850bd4d99ea.PNG)

![3](https://user-images.githubusercontent.com/90016164/167908393-7e269559-1fef-4cd2-844c-2d38b81ec699.PNG)

![4](https://user-images.githubusercontent.com/90016164/167908396-81eabaac-2781-4ed5-a623-2f9f00d7ce5e.PNG)

- Y ahora movemos los archivos para realizar el intercambio cumpliendo con la jerarqui de los directorios.

![8](https://user-images.githubusercontent.com/90016164/167909384-7074f3aa-298e-4b71-8a08-a755e83541eb.PNG)

![9](https://user-images.githubusercontent.com/90016164/167909387-0127e4b8-cefe-486f-bc7c-cb09f91da84e.PNG)

![10](https://user-images.githubusercontent.com/90016164/167909372-2964152b-f95c-4a3a-aaab-e96d9d5172d8.PNG)

![11](https://user-images.githubusercontent.com/90016164/167909378-4ed27bd1-e1dc-4301-89e6-dba395ba0f54.PNG)

![12](https://user-images.githubusercontent.com/90016164/167909380-334ff892-9ac4-42a5-a643-b2b31d0f2a65.PNG)

- Se completa el ejercicio y se ejecuta el comando tree para comprobar el resultado.

![18](https://user-images.githubusercontent.com/90016164/167909678-34929010-30ec-4231-a005-ab533f9f8c83.PNG)



