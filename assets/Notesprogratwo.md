# Notas de clases de PROGRA II  
## Aether / MeganHolic (Nombre de mi repositorio)

-apuntes de las clases paso a paso  

# Class I : Git  


## Primer programa en Java
 - 461  cd ..  
 - 462  ls -la
 - 463  cd prjGit
 - 464  ls -la
 - 465  code . : para abrir mi repositorio
 - 466  touch Hi.java Sumar.java  : para crear documentos con touch  
 - 467  ls
 - 468  rm Hi.java Sumar.java  : elimine aca los dos documentos porque tenia repetidos  
 - 469  cd ..
 - 470  cd prjGithub : fui a mi repositorio a crear las nuevas clases  
 - 471  touch Hi.java Suma.java  : cree los nuevos documentos  
 - 472  cd Hi.java  
 - 473  code Hi.java  : para ingresar a mi archivo para editar  
 - 474  history : para ver mis lineas de codigo  

## Mi programa de Hello World
```java

public class Hi{

    public static void main(String[] args) {
        System.out.println("Hi MeganHolic, welcome to Java programming!");
        System.out.println("Hi MeganHolic, welcome to Java programming!");
        System.out.println("Im thunder ");
        System.out.println("Im thunder ");
    }
}
```
## Mi programa de Suma en Java  

- 480  clear
- 481  code Suma.java
- 482  javac Suma.java
- 483  java Suma
- 484  java Suma
- 485  java Suma
- 486  history+
- 487  history
- $ pwd
- /c/MeganHolic/progra_two/prjGithub

```java
public class Suma{

    public static void main(String[] args) {
        int num1 = 7;
        int num2 = 770;
        int sum = num1 + num2;
        System.out.println("la suma de dos numeros " + num1 + " y " + num2 + " es: " + sum);
    }
}

```

# Class II : github
## Comandos Linux  

 - 441  ls -ña  
 - 442  ls -la  
 - 443  pwd : ubicacion de mi directorio o repositorio  
 - 444  pwd
 - 445  cd c:/ ir a una ruta con cd  
 - 446  ls -la para enlistar con archivos protegidos o ocultas
 - 447  cd MeganHolic/
 - 448  ls -la  
 - 449  wsl  llamar a la maquina virtual
 - 450  exit
 - 451  java Mate. con tab puedo ver los documentos con las caracteristicas  
 - 452  java Mate.java
 - 453  java Mate.java  
 - 454  java Mate.java
 - 455  git status
 - 456  exit
 - 457  touch readme.md
 - 458  echo "#Class II : github" >> readme.md
 - 459  code readme.md  
 - 460  history >> readme.md  

## Como contectar el repositorio con git  
480  git remote -v
 - 481  git remote set-url origin https://github.com/aerher/Prueba-Repositorio.git  : conectamos el repositorio al destinatario para guardar los siguientes git pull  
 - 482  git push -u origin main  
 - 483  git status  
 - 484  .gitignore
 - 485  code .gitignore
 - 486  git rm --cached *.class   : eliminamos los documentos que esten de mas en nuestro proyecto y validando el gitingnore
 - 487  git rm --cached *.md
 - 488  git status
 - 489  git add.   : agrego los nuevos cambios  
 - 490  git add .
 - 491  git commit -m "Eliminando los archivos del gitignore" : comento lo que realice
 - 492  git push  : subo a mi nube de Github con los cambios realizados  
 - 493  history


  ## Git comand  
  ### comandos base  
  - git clone : voy a traer un repositorio de la nube a mi maquina con su URL
  
  1 vez  
  - git init : para primera vez para darme noticias sobre mi repositorio o iniciar mi proyecto  
  - gitignore : para no registrar documentos privados
  Repetitivamente / cada dia  

  - git status :  el estado de mi repositorio
  - git add . : para agregar todo
  - git add xxx/ . : es para agregar o quitar cambios  
  - git comit -m "(podemos poner mensaje aqui para su cambio guardado)" : nombre que voy a guardar mi archivo
  
  para subir los cambios de la organizacion  
  - git push : enviar todo a mi nube de GitHub
  
  - ls -a para llamar a todos los documentos sin restrinciones  
  - cat : es para revisar documentos que esten guardados o destinados a llevar autoguardado.
  - .md : para crear documentos de texto
## Actividad 13/04  
- git log -d--decorate --oneline : es para saber cuando mcomit he hecho sobre mi proyecto y ver cambios y modificaciones  
- congit <"name ">  : es para darte una etiqueta a un commit que sea importante de todos los commit que he realizado  