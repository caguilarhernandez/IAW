# Desplegando el tema de Jekyll "minima"

## Indice:

[Introduccion](#introduccion)

[Paso 1](#paso-1)

[Paso 2](#paso-2)

[Paso 3](#paso-3)

[Paso 4](#paso-4)

[Paso 5](#paso-5)

[Paso 6](#paso-6)

[Paso 7](#paso-7)

## Introduccion:

  Esto sera un ejemplo de como ejecuto los **pasos necesarios** para desplegar el tema de Jekyll "*minima*" en GitHub Pages. En esta practica *ya esta configurado*, tanto la red, como los pasos anteriores a crear el sitio 
  jekyll:

1. Instalar las gemas.
1. Crear un nuevo repositorio
1. Conectarlo al repositorio remoto.

## Paso 1:

  El primer paso es crear el sitio jefyll, para lo que necesitaremos usar el comando:  
    
```
jekyll new myblog2
```

![Paso 1](/imagenes/jekyll3.png)

## Paso 2:

  El siguinete paso sera comprobar que funciona el sitio jekyll, arrancandolo localmente usando el comando:
  
```
jekyll serve --host 10.0.16.201 --port 3000
```

![Paso 2](/imagenes/jekyll13.png)

## Paso 3:

  Despues conectaremos el repositorio remoto al visual studio code a traves de *ssh* y editaremos el **_config.yml** 

![Paso 3](/imagenes/jekyll12.png)

## Paso 4:

  Luego editaremos los ficheros:
+ **about.markdown**
+ **index.html**

![Paso 4.1](/imagenes/jekyll7.png)

![Paso 4.2](/imagenes/jekyll8.png)

## Paso 5:

  Despues crearemos una nueva '*page*' llamada **informacion** en forma de fichero markdown igual que el **about** y el **index**.

![Paso 5](/imagenes/jekyll9.png)

## Paso 6:

  Tambien creo los 3 posts dentro de la carpeta *_posts*:
+ **2023-11-14-aviso-importante.markdown**.
+ **2023-11-14-credenciales.markdown**.
+ **2023-11-14-bienvenidos.markdown**.

![Paso 6](/imagenes/jekyll10.png)

## Paso 7:

  Por ultimo abres el sitio jekyll desde *github pages* y compruebas que todos los cambios han sido realizados.

![Paso 7](/imagenes/jekyll11.png)
