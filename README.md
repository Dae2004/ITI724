# Workshop 01

## ¿Cómo sobrevivir en bash?

A continuación se explican comandos.

- `pwd`   : Imprime el directorio de trabajo.
- `ls`    : Muestra el contenido del directorio.
- `cd`    : Permite cambiar el directorio.
- `touch` : Crear un archivo.
- `clear` : Limpia la consola.
- `file`  : Describe un archivo.

## Introducción a Markdown (.md)

Formato utilizado para combinar texto plano junto con diseños sencillos.

- `#`  : Se utiliza para representar un título nivel 1.
- `##` : Se utiliza para representar un título nivel 2.

Se puede utilizar la tilde invertida para insertr código en línea, así:

```java

public class Main {
    public static void main(String args[]){
        System.out.println("Hola Mundo");
    }
}

``` 

## Insertar imagen

!["Tux"](/home/dae/Documents/ITI724/images/tux.png)

## Implementando PKI con SSH

Generar claves (Ya sea RSA o ED25519) y relacionar estas en GitHub.

- `ssh-keygen -t ed25519` : Genera claves ssh.

Luego, copiamos la clave pública y creamos una clave SSH en github, usando esta misma.

