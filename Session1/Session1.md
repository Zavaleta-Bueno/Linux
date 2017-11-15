# Seccion 1




## History of Linux

The history of Linux began in 1991 with the commencement of a personal project by Finnish student Linus Torvalds to create a new free operating system kernel. Since then, the resulting Linux kernel has been marked by constant growth throughout its history. Since the initial release of its source code in 1991, it has grown from a small number of C files under a license prohibiting commercial distribution to the 4.2.3 version in 2015 with more than 18 million lines of source code under the GNU General Public License v2.




## Commands

We can make use of the following commands to see the BIOS information:


``` bash
	biosdecode	
```


And we want to be more specific :

``` bash
	dmidecode	
```

Comando para mostrar el contenido de un archivo:

Usamos el comando:

``` bash
	cat	
```
Podemos observar el contenido de los archivos planos.

Ahora si queremos observar las primeras _n_ lineas utilizamos:

``` bash
	head  -n nombre_archivo	
```

Y si queremos ver las _n_ ultimas lineas utilizamos:


``` bash
	tail -n nombre_archivo 			
```

Ver los detalles de archivos 

Antes de pasar de lleno a los detalles de los archivos, tenemos primero que listarlos

``` bash
	ls 			
```
Este comando nos listara todos los **_archivos visibles_** presentes en el directorio.

``` bash
	ls 	-a		
```



## Tipos de Archivos en Linux

By default Unix have only 3 types of files:


**Regular files**:

* Directory files

* Special files(This category is having 5 sub types in it.)






## Installing some programs


In order to install the program we can use dnf:

DNF is a software package manager that installs, updates, and removes packages on RPM-based Linux distributions. It automatically computes dependencies and determines the actions required to install packages. DNF also makes it easier to maintain groups of machines, eliminating the need to manually update each one using rpm. Introduced in Fedora 18, it has been the default package manager since Fedora 22.

DNF or Dandified yum is the next generation version of yum. It roughly maintains CLI compatibility with yum and defines a strict API for extensions and plugins. Plugins can modify or extend features of DNF or provide additional CLI commands on top of those mentioned below. If you know the name of such a command (including commands mentioned bellow), you may find/install the package which provides it using the appropriate virtual provide in the form of dnf-command(**< alias >**) where **< alias >** is the name of the command; e.g. dnf-command(repoquery) for a repoquery command (the same applies to specifying dependencies of packages that require a particular command).




<p align="center">
  <img src="https://raw.githubusercontent.com/Zavaleta-Bueno/Linux/gh-pages/imagenes/lain-1.gif">
  <center><b> No seas como yuri y programa </b></center> 
</p>
