# Book Paulina

## Inicio :dog:

Esto es una guia para poder aprender los comandos basicos para manerar archivos en la terminal y los comandos basicos de Git.

### Comandos para moverse en la terminal

#### Ver los archivos y carpetas donde te encuentras

```
ls
```

#### Moverse entre carpetas

```
cd <Nombre de la carpeta>

Ejemplo

cd Proyectos
```
#### Regresar a una carpeta anterior

```
cd ..
```

#### Crear una carpeta

```
mkdir <Nombre de la carpeta>

Ejemplo

mkdir carpeta1
```

#### Eliminar una carpeta1

```
rm -rf <Nombre de la carpeta>

Ejemplo

rm -rf Proyectos
```

### Comandos de Git

#### 1er camino, clonar un proyecto existente
Si lo que quieres es clonar un proyecto existente en tu computadora el comando sería

```
git clone <URL>

Ejemplo del proyecto actual

git clone https://github.com/paucoro/book.git
```
La URL del proyecto la puedes encontrar dentro del proyecto en Github, al inicio viene un botón verde
que dice Clone or Download, al dar click te abrira un input con la URL en donde tu solo tendras que copiar su contenido.

Al momento de ingresar el comando y dar **Enter** se descargara el proyecto en tu computadora.

Para poder ingresar a la carpeta puedes ejecutar el comando **cd book**, donde **book** es un ejemplo del
nombre de la carpeta.  

#### Subir cambios a mi proyecto de Github

Existen tres pasos para poder subir cambios a mi proyecto de Git.

1. git add ( agregar archivos a mi commit )
2. git commmit -m "" ( nombrar el commit, que hicimos )
3. git push ( subir cambios a mi proyecto en Git )

#### Agregar archivos a tu commit

##### Agregar un archivo

```
git add <archivo>

Ejemplo

git add README.md
```

##### Agregar todos los archivos

```
git add .
```

#### Crear commit

```
git commit -m "Aquí va los cambios que hice"
```

#### Subir mis cambios

```
git push
```

Algunas veces Git no te dejara subir cambios ya que alguien mas subío cambios y necesitas estar actualizado y bajar cambios para ello.

El comando para bajar los cambios existentes es

```
git pull
```
