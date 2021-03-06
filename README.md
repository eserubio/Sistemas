# Simulación Examen 2ª evaluación Sistemas Operativos.

### Día xx/xx/xxxx		Tiempo: x horas

Pasos previos antes de empezar
------------------------------

* Configure su usuario de Git

```bash
	git config --global user.name "????"
	git config --global user.email "????"
```

* Haga un [fork](https://github.com/IGZJavierPerez/Sistemas/fork) del repositorio


* Clone el fork de su repositorio. Para ello vaya a su cuenta de GitHub y copie la URL del repositorio y ejecute:

```bash
	git clone URL_del_repositorio
```

* Vaya a su repositorio

```bash
	cd sistemas
```

* Compruebe que todo es correcto:

```bash
	git status
```

* Dígale al profesor que ya ha terminado para que compruebe que todo es correcto y desconecte la red.


Enunciado
---------

1º Cree un script (script1) que dada una cadena de texto AÑADA esa cadena al archivo "~/usuarios".



2º Si la cadena de texto ya existiera en el archivo "~/usuarios" no se añadiría y daría un mensaje de aviso. Si la cadena tuviera caracteres que no formen parte del alfabeto inglés no se añadirá y se advertirá.





3º Cree un script (script2) que cree un directorio "buzones" y dentro de este un subdirectorio con el nombre de cada usuario. Dentro del directorio de cada usuario cree otros dos subdirectorios llamados "in" y "out". Si los directorios a crear ya existiesen no dará error ni aviso.





4º Cree un script (script3) que reciba un nombre de usuario -el remitente- otro nombre de usuario -el destinatario- y una cadena de texto -el mensaje- y cree un archivo en la carpeta de "out" del remitente con el nombre del destinatario y que contenga el mensaje.






5º Si el remitente o el destinatario no existen se advertirá. Si el archivo a crear ya existiera se añadirá el nuevo mensaje.




6º (2 puntos) Cree un script (script4) que mueva todos los archivos que estén en las carpetas "out" de los remitentes a las carpetas "in" de los destinatarios. El nombre del archivo debe cambiar para que tenga el nombre del remitente.



7º Puede ser que al hacer el proceso anterior, algún usuario tenga mensajes en su carpeta "in" y que al mover los archivos reemplacen los archivos existentes. Haga que cuando ocurra esto los archivos en vez de moverse se añadan al original.



8º (2 puntos) Cree un script (script5) que reciba un usuario y que muestre los mensajes que tenga pendientes de procesar en su carpeta "in". El formato de salida será:

usuario:mensaje

Después de mostrar los mensajes el script borrará los archivos de la carpeta "in".
Si el usuario no existe o no tiene archivos en su carpeta "in" se advertirá.


Para entregar
-------------

* Ejecute el siguiente comando para comprobar que está en la rama correcta y ver los ficheros que han cambiado:

```bash
	git status
```

* Prepare los cambios para que se añadan al repositorio local:

```bash
	git add *
	git commit -m "completed exam" -a
```

* Compruebe que no tiene más cambios que incluir:

```bash
	git status
```

* Dígale al profesor que va a entregar el examen.

* Conecte la red y ejecute el siguiente comando:

```bash
	git push
```

* Abandone el aula en silencio.
