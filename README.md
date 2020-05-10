# Cercas y Alambrados Chavez
Desarrollo de software de gestión de servicios y relación con los clientes.

# Descripción
El objetivo e impacto principal de este proyecto, se verá reperentado en el área de atención a clientes y gestión de servicios, esto debido a que a través de este software los administradores del negocio podrán generar cotizaciones de una forma más rápida y automatizada, la respuesta al cliente será en un corto periodo de tiempo, al igual que la información de los materiales que se requerirán para llevar a cabo la solicitud del cliente.

# Justificación
La empresa Cercas y Alambrados Chavez no cuenta con una solución de software que le permita controlar los procesos que son realizados dentro del negocio en donde ofrecen los productos y servicios de construcción.

# Objetivo
El objetivo del presente proyecto es impulsar a la micro empresa “Cercas y Alambrados Chavez”, el cuál manifiesta interés de involucrarse en el mercado de los sistemas informáticos como parte de su estrategia de ventas e inclusión de sus productos en una solución de software para generar un crecimiento en el negocio.

# Solución
El negocio pretende contar con el detalle de productos con los que cuenta en inventario de su sucursal, y poder realizar las  cotizaciones de las necesidades de los clientes. Se espera que el software en desarrollo,  mejore el proceso de cotización de los productos que ofrecen.

Cabe mencionar que, actualmente el negocio no cuenta con ningún servicio digital que le permita llevar a cabo la función que espera obtener a través de este sistema.

# Arquitectura
El Modelo-Vista-Controlador (MVC) es un patrón arquitectónico que separa una aplicación en tres componentes lógicos principales: el modelo , la vista y el controlador. Cada uno de estos componentes está diseñado para manejar aspectos de desarrollo específicos de una aplicación. MVC es uno de los marcos de desarrollo web estándar de la industria más utilizados para crear proyectos escalables y extensibles.

# Tabla de Contenidos (ToC)
- [Cercas y Alambrados Chavez](#cercas-y-alambrados-chavez)
- [Descripción](#descripci-n)
- [Justificación](#justificaci-n)
- [Objetivo](#objetivo)
- [Solución](#soluci-n)
- [Arquitectura](#arquitectura)
- [Tabla de Contenidos (ToC)](#tabla-de-contenidos--toc-)
- [Requerimientos](#requerimientos)
- [Instalación](#instalaci-n)
- [Configuración](#configuraci-n)
- [Uso](#uso)

# Requerimientos
Sistema operativo: Windows XP, Vista, 7, 8, 10 ó los equivalentes Windows Server (2003, 2008, 2012 y 2016)
Memoria RAM: mínimo 512 MB
Ratón o similar
Conexión a Internet para navegador Web
Versión Java: 7 o posterior

# Instalación
En primer lugar clonar el repositorio en nuestro servidor:

git clone https://github.com/FrancoFlo/CercasAlambradosChavez
Definir URL base en application/config/config.php

Una vez instalada la aplicación, podemos llevar a cabo pruebas del funcionamiento del software. Éstas pueden ser pruebas manuales, en las que llevamos a cabo la ejecucion de la aplicación.

Debemos realizar un ejercicio de cotización con el método con el que lleva a cabo la actividad antes de usar el sistema de cotización, esto servira para asegurar que el sistema funciona de forma esperada.

Si has seguido los pasos correctamente, se habrá generado la instalación del sistema. Si has tenido problemas durante la instalación, vamos a asegurarnos de que disponemos de las últimas versiones de Java, y de la versión que es recomendable de Windows.

# Configuración
Configuración de los requerimientos
  Asegurar que se cuenta con la versión de Windows
  Asegurar que se cuenta con la versión de Java
  Contar con la memoria RAM determinado en los requerimientos
  Asegurar que se cuenta con conexión a internet.
  
Archivos de Configuración
  > .gitconfig
  
# Uso
Después de completar el proceso de instalación del software, el usuario ("operador") tendrá habilitadas las funciones de visualización y elaboración de cotizaciones, por ejemplo:

  Registrar a un nuevo cliente para poder generar cotización de servicio
  Llenar formulario de datos
  Formulario de datos (Nombre, Empresa, Direccion, Telefono, Mail)
  Registro de datos en BD
  Almacenar información de clientes en la base de datos del sistema.
  El sistema deberá asignar un identificador a la cotización que se realice para las solicitudes de los clientes.
  Acceso a Interfaz para generar calculos de cotización
 
Los niveles de acceso a los que tiene permiso el usuario que será determinado como administrador, podrá hacer uso de las siguientes funciones, adicional a que tiene habilitados todas las funciones para el usuario de tipo "operador":

 Modificar el cátalogo de productos
 Modificar el cátalogo de servicios
 Edición de los costos establecidos en las cotizaciones.
 Aprobación de cotizaciones generadas por otros usuarios.
 Agregar productos o servicios al sistema
 Cancelación de registros de clientes
 Cancelación de cotizaciones.

# Contribución
Para que otros desarrolladores de software puedan contribuir en la mejora, modificación, actualización o ampliación del alcance del sistema, deben respetar la estructura del software, trabajando con el mismo esquema establecido.

Se debe llevar a cabo la clonación del repositorio, asegurando que esta sincrinizado todo el repositorio desde la raiz, para tener visibilidad a todos los archivos contenidos.

Una vez realizada la propuesta de modificaciones, se debe realizar un pull request para que el administrador del repositorio pueda analizar las contribuciones de los usuarios.

Una vez aprobado el pullrequest, se realiza el merge para incluir los cambios en la última versión del repositorio


  
