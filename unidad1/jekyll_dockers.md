# Desplegando el tema de Jekyll "minima" utilizando dockers

## Indice:

[Paso 1](#paso-1)

[Paso 2](#paso-2)

[Paso 3](#paso-3)

[Paso 4](#paso-4)

[Paso 5](#paso-5)

## Paso 1:

  El primer paso es **traer la imagen**, que usaremos para crear nuestro sitio en jekyll con el comando:
    
```
docker run -it --rm -v "$PWD:$HOME/repositorios/blog" jekyll/jekyll jekyll
```

![Paso 1](img/dockers1.png)

## Paso 2:

  El siguinete paso sera **montar el fichero donde estara nuestro blog** con es siguiente comando:
  
```
docker run -it --rm -v "$PWD:$HOME/repositorios/blog" jekyll/jekyll jekyll new blog
```

![Paso 2](img/dockers2.png)

## Paso 3:

  Despues  

![Paso 3](img/dockers4.png)

## Paso 4:

  Luego editaremos los ficheros:
+ **about.markdown**
+ **index.html**

![Paso 4.1](/imagenes/jekyll7.png)

![Paso 4.2](/imagenes/jekyll8.png)

## Paso 5:

  Despues crearemos una nueva '*page*' llamada **informacion** en forma de fichero markdown igual que el **about** y el **index**.

![Paso 5](/imagenes/jekyll9.png)
