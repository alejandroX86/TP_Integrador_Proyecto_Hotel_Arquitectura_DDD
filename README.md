Proyecto Hotel: Arquitectura DDD
Descripción
Este proyecto es una aplicación de gestión de un hotel utilizando la arquitectura DDD (Domain-Driven Design). El proyecto incluye un menú de clientes y reservas, y soporta múltiples tipos de bases de datos: en memoria, MySQL, y MongoDB.

Profesor: Daniel Alejandro Fernandez
Integrantes del Proyecto
Julia Avalos
Leonardo Caceres
Eduardo Arizza
Gonzalo Arizza
Omar Bazar


Requisitos
.NET Core 3.1 o superior
MySQL Server
MongoDB
Estructura del Proyecto
El proyecto está dividido en las siguientes capas:

Presentación
Aplicación
Dominio
Persistencia de Datos
Instrucciones de Instalación y Ejecución
Clonar el Repositorio
bash

Configurar Base de Datos
Dependiendo de la base de datos que desees utilizar, sigue los pasos de configuración correspondientes.

MySQL
Crear una base de datos en MySQL:
sql
Copiar código
CREATE DATABASE hotel_db;
Configurar la cadena de conexión en el archivo de configuración de la aplicación.
MongoDB
Asegúrate de que MongoDB esté corriendo en tu máquina local o en un servidor accesible.
Configurar la cadena de conexión en el archivo de configuración de la aplicación.
Compilar y Ejecutar
bash
Copiar código
dotnet build
dotnet run --project Presentacion
Uso del Menú
Menú Principal
Al iniciar la aplicación, verás el menú principal con las siguientes opciones:

Base de Datos en Memoria
Base de Datos en MySQL
Base de Datos en MongoDB
Ir a Menú Clientes
Ir a Menú Reservas
Salir
Selecciona el tipo de base de datos con el que deseas trabajar antes de proceder a los menús de clientes o reservas.

Menú Clientes
Una vez seleccionada la base de datos, puedes acceder al menú de clientes seleccionando la opción 4 en el menú principal.

En el menú de clientes, verás las siguientes opciones:

Ingresar nuevo cliente
Listar clientes
Borrar cliente
Salir
Ingresar Nuevo Cliente
Selecciona la opción 1.
Ingresa el nombre del cliente.
Ingresa el email del cliente.
Ingresa la clave del cliente.
Ingresa la fecha de nacimiento del cliente en formato YYYY-MM-DD.
Listar Clientes
Selecciona la opción 2 para ver una lista de todos los clientes registrados.
Borrar Cliente
Selecciona la opción 3.
Ingresa el ID del cliente a borrar.
Menú Reservas
Para acceder al menú de reservas, selecciona la opción 5 en el menú principal.

En el menú de reservas, verás las siguientes opciones:

Crear nueva reserva
Listar reservas
Borrar reserva
Salir
Crear Nueva Reserva
Selecciona la opción 1.
Ingresa el ID del cliente.
Ingresa la fecha de inicio de la reserva en formato YYYY-MM-DD.
Ingresa la fecha de fin de la reserva en formato YYYY-MM-DD.
Selecciona el estado de la reserva: 1 (Disponible), 2 (Reservada), 3 (Cancelada).
Listar Reservas
Selecciona la opción 2 para ver una lista de todas las reservas registradas.
Borrar Reserva
Selecciona la opción 3.
Ingresa el ID de la reserva a borrar.
