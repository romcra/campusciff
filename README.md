#  Ejercicio 2.3
## 1
- **git clone campusciff** Comando para clonar el repositorio remoto "campusciff" en el local

# Ejercicio 2.4
## 1
- **touch privado.txt** Comando para crear el archivo privado.txt

## 2
- **mkdir privada** Comando para crear la carpeta privada

## 3
- Hay que tener en cuenta que los directorios vacíos no se  tienen en cuenta por Git:

**mv privado.txt privada** Movemos el archivo a la carpeta para que no este vacia y de esta forma pueda ser reconocida con git status también la carpeta, y no solo el archivo. Ignoramos el archivo y la carpeta a la vez usando el comando **privada >.gitignore**

# Ejercicio 2.5
## 1
**touch 1.txt**

**git add 1.txt**

**git commit -m "añado fichero 1.txt al repositorio local"**

## 2
**git tag -a v0.1 3e7a893 m "añado etiqueta v0.1"**

## 3
**git push origin master** Subo los cambios al repositorio remoto

# Ejercicio 2.6
## 1
**git branch v0.2** Comando para crear una rama local v0.2 y posicionarnos en ella

**git push origin v0.2** Comando para crear la rama remota v0.2

## 2
**git checkout v0.2** Comando para posicionar el HEAD en la rama v0.2

## 3
**touch 2.txt** Comando para crear el fichero 2.txt

## 4
**git add 2.txt**

**git commit -m "añado archivo 2.txt al repositorio local en la rama v0.2"**

**git push origin v0.2** Comando para subir cambios en la rama v0.2 al repositorio remoto

# Ejercicio 2.7
## 1
**git checkout master**

## 2
**git merge v0.2**

# Ejercicio 2.8
## 1
**echo Hola>>1.txt** Comando para escribir Hola en 1.txt

**git add 1.txt**

**git commit -m "escribo Hola en 1.txt"** Añado cambios de 1.txt en el repositorio local

## 2
**checkout v0.2** Comando para posicionarse en la rama local v0.2

**echo Adios>>1.txt** Comando para escribir Hola en 1.txt

**git add 1.txt**

**git commit -m "escribo Adios en 1.txt"** Añado cambios de 1.txt en el repositorio local

## 3
**git checkout master**

**git merge v0.2**

![Mergedfallido](https://github.com/romcra/campusciff/blob/master/Capturas/foto.png)

## 4

**git branch --merged**
**git branch --no-merge**

![Mergedfallido](https://github.com/romcra/campusciff/blob/master/Capturas/foto 1.png)
## 5

**vim 1.txt**
![Mergedfallido](https://github.com/romcra/campusciff/blob/master/Capturas/foto 2.png)

**git add 1.txt**

**git commit -m "cambios en el fichero 1.txt"

# Ejercicio 2.9

## 1
**git tag v0.2** Comando para crear la etiqueta v0.2

## 2
**git list** Podemos ver todas las etiquetas con sus comitts

![Etiquetas commits](https://github.com/romcra/campusciff/blob/master/Capturas/foto 3.png)

## 3

**git branch -d v0.2** Comando para borrar la rama v0.2

# Ejercicio 2.10

## 1
![Foto usuario](https://github.com/romcra/campusciff/blob/master/Capturas/foto 4.png)
## 2
![doble factor de autentificación en vuestra
cuenta de GitHub](https://github.com/romcra/campusciff/blob/master/Capturas/foto a.png)
## 3
![Clave plúbica](https://github.com/romcra/campusciff/blob/master/Capturas/foto 6.png)

# Ejercicio 2.11

He hecho todos los pasos como se puede comprobar en GitHub

# Ejercicio 2.12

| Nombre | GitHub |
| ------ | ------ |
| Alfonso Peña | [Alfonso Peña](https://github.com/alfonsops) |
| Borja Moreno | [Borja Moreno](https://github.com/bmpozo)
| Juan Jose | [Juan Jose](https://github.com/jjdiazl)
| Ramon Márquez | [Ramon Márquez](https://github.com/marquezjr)
| Carlos Saiz | [Carlos Saiz](https://github.com/Carsaiz)
| Francisco Rivas | [Francisco Rivas](https://github.com/jrivax)
| Marcos Cortina  |[Marcos Cortina](https://github.com/marcoscortina)

# Ejercicio 2.13

He hecho todos los pasos como se puede comprobar en GitHub

# Ejercicio 2.14

He hecho todos los pasos como se puede comprobar en GitHub

# Ejercicio 2.15

He hecho todos los pasos como se puede comprobar en GitHub

# Ejecicio 2.16

**git clone git@github.com:campusciff-romcra/campusciff-romcra.github.io.git**

**mv idex.html > campusciff-romcra.github.io**

**mv index.html > campusciff-romcra.github.io/index.html**

**cd campusciff-romcra.github.io**

**git add index.html**

**git commit -m "subo archivo index.html"**

**git push origin master**

# Ejercicio 2.17

- Realizo el fork al repositorio campusciff-marquezjr.github.io, lo clono en un
directorio local utilizando el comando **git clone git@github.com:romcra/
campusciff-marquezjr.github.io.git**

- Creo y me cambio a una nueva rama llamada *rama* utilizando el comando **git -b checkout rama**

- Realizo cambios en el fichero index.html **echo Rodrigo Marcos>>index.html**

- Subo los camios al repositorio local **git add idex.html** **git commit -m"cambios en index.html**

- Subo los cambios al repositorio remoto **git push origin rama**

- Realizo el pull request
![Pull request]https://github.com/romcra/campusciff/blob/master/Capturas/imagen.png)

- Realizo lo mismo para el repositorio campusciff-alfonsops.github.io y hago la pull request.
![Pull request]https://github.com/romcra/campusciff/blob/master/Capturas/imagen2.png)
