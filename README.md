# PFC 2014 - Un nuevo flujo de trabajo para el desarrollo de aplicaciones web

El código aquí presente es parte de un proyecto de final de carrera dónde se analiza un nuevo flujo de trabajo para desarrollar aplicaciones web.

El objetivo del mismo es demostrar como se puede incorporar la definición de la arquitectura de un sistema al código de la propia aplicación, consiguiendo desarrollar un nuevo flujo de trabajo dónde los desarrolladores puedan levantar un entorno de trabajo virtualizado rápidamente.

A partir de este repositorio, instalando los prerequisitos y siguiendo las instrucciones de ejecución, cualquier persona podrá crear una máquina virtual Ubuntu 12.04 LTS, configurarla, e instalar Drupal en la misma, la cual será inmediatamente accesible una vez concluido el proceso.

## Prerequisitos

* git http://git-scm.com/book/en/v2/Getting-Started-Installing-Git
* VirtualBox https://www.virtualbox.org/wiki/Downloads
* Vagrant https://www.vagrantup.com/downloads.html
* Ansible http://docs.ansible.com/intro_installation.html

## Demostración

Instalar los prerrequisitos.

Clonar el repositorio:

    git clone git@github.com:pfc2014/pfc.git

Entrar en el directorio y ejecuta 'vagrant up':

    cd pfc && vagrant up

Vagrant descargará y creará una máquina virtual, invocando a su vez a Ansible para aprovisionar el sistema.

Una vez termine el proceso nuestra aplicación debe estar disponible en la dirección:

http://192.168.33.30

