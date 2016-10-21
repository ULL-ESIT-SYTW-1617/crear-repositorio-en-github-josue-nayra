# Práctica 4. Sistemas y Tecnologías Web

## Nueva funcionalidad para el paquete NPM: plugins (IAAS)

El objetivo de esta práctica es extender el package NodeJS publicado en npm con una nueva funcionalidad que permita que los usuarios con conocimientos de NodeJS puedan extender la conducta del ejecutable para que este realice el despliegue en plataformas distintas de las ya consideradas.

En esta práctica sólo se pide desarrollar el plugin para iaas.ull.es




### Pasos a seguir para la utilización del plugin

1- Descargar el paquete inicial: *gitbook-start*
    ``` $ npm install -g gitbook-start-josue-nayra ```

2- Crear el libro mediante el comando:
    ``` $ gitbook-start -d <directorio> --autor <autor> --name <nombre_libro> --url <url_repo>```

Se construye la estructura inicial por *gitbook-start* la jerarquía de directorios conteniendo los scripts y ficheros markdown para el libro

3- Colocarse en la carpeta que contiene el libro.

4- Instalar las dependencias necesarias mediante el comando:
    ``` $ npm install ```

5- Instalar el plugin *gitbook-start-iaas-ull-es-josue-nayra* para el despliegue en iaas.
    ``` $ npm install --save gitbook-start-iaas-ull-es-josue-nayra ```

6- Es necesario tener el repositorio remoto actualizado, para ello se dispone de una tarea en el gulp: ***gulp push***.

7- Ejecutar el plugin:
    ``` $ gitbook-start --deploy iaas-ull-es --IP <ip> --path <ruta_maquina> --usuarioremoto <usuario_maquina>  ```


### Tareas Gulp


* push
  


* instalar_recursos
* deploy


### Enlaces

- [Campus virtual](https://campusvirtual.ull.es/1617/course/view.php?id=1175)

- [Descripción de la práctica](https://casianorodriguezleon.gitbooks.io/ull-esit-1617/content/practicas/practicaplugin.html)

- [Publicación del paquete en npm](https://www.npmjs.com/package/gitbook-start-josue-nayra)

- [Repositorio en Github.com](https://github.com/ULL-ESIT-SYTW-1617/nueva-funcionalidad-para-el-paquete-npm-plugins-josue-nayra)



### Referencias

- [Tutorial para publicar paquetes nodejs](https://casianorodriguezleon.gitbooks.io/ull-esit-1617/content/apuntes/nodejspackages.html)

- [Gulp](https://casianorodriguezleon.gitbooks.io/ull-esit-1617/content/apuntes/gulp/)

- [Uso de templates](https://www.npmjs.com/package/ejs)

- [Fyle System de Nodejs para el manejo de archivos](https://casianorodriguezleon.gitbooks.io/ull-esit-1617/content/apuntes/fs.html)

- [Construyendo package.json](https://docs.npmjs.com/files/package.json)



### Integrantes

- Josué Toledo Castro
    [Github personal](www.github.com/JosueTC94)
- María Nayra Rodríguez Pérez
    [Github personal](www.github.com/alu0100406122)