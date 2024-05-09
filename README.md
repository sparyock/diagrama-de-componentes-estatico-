# diagrama-de-componentes-estatico-
# Sistema de Gestión de Biblioteca

@startuml


package "Sistema de Gestión de Biblioteca" {
    [Cliente]
    
    [Interfaz]
    
    [Controlador]
    
    [Base de Datos]   
}

[Cliente] --> [Interfaz]

[Interfaz] --> [Controlador]

[Controlador] --> [Base de Datos]

@enduml

# Explicacion del diagrama:
El diagrama de componentes del Sistema de Gestión de Biblioteca representa la estructura interna del sistema, mostrando los principales componentes y sus relaciones. Este diagrama es estático y proporciona una visión general de cómo están organizados los diferentes elementos del sistema.

Cliente: Representa los usuarios que interactúan con el sistema de gestión de la biblioteca.
Interfaz: La interfaz de usuario a través de la cual los clientes interactúan con el sistema.
Controlador: La lógica que procesa las solicitudes de la interfaz y coordina las acciones del sistema.
Base de Datos: Almacena la información sobre libros, usuarios, préstamos, etc.


![yeison](https://github.com/sparyock/diagrama-de-componentes-estatico-/assets/55572135/5d7b9c0d-6fad-46b0-8d27-a2557f284e5d)
