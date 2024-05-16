# DungeonExplorer
Enunciado del Juego de Exploración de Mazmorras
Objetivo del Ejercicio
Desarrollar un juego de exploración de mazmorras en Java que utilice los cuatro pilares de la programación orientada a objetos: encapsulación, herencia, polimorfismo y abstracción. El juego debe incluir clases, interfaces y la interacción entre diferentes tipos de objetos en la mazmorra.

Descripción del Juego
El jugador debe explorar una mazmorra compuesta de diferentes tipos de salas. Cada sala puede estar vacía, contener un tesoro o albergar un enemigo. El jugador debe navegar por estas salas, recoger objetos y enfrentarse a enemigos, todo mientras intenta mantenerse con vida.

Reglas del Juego
El jugador comienza con un nombre y una cantidad inicial de puntos de vida.
El jugador puede moverse a través de varias salas en la mazmorra.
Las salas pueden ser de tres tipos: vacía, con tesoro o con enemigo.
El jugador puede recoger tesoros que se añaden a su inventario.
El jugador puede recibir daño de los enemigos y perder puntos de vida.
El juego termina cuando el jugador ha explorado todas las salas o ha perdido todos sus puntos de vida.
Requisitos Técnicos
Interfaces y Abstracción: Define interfaces para las salas y los objetos interactuables en el juego.
Encapsulación: Utiliza atributos privados y métodos públicos para manejar el estado del jugador y de las salas.
Herencia: Crea clases concretas que implementen las interfaces definidas para representar diferentes tipos de salas.
Polimorfismo: Usa referencias de las interfaces para manejar los diferentes tipos de salas y objetos en el juego.
Especificaciones Detalladas
Paso 1: Crear las interfaces básicas

Define una interfaz Room para representar una sala en la mazmorra.
Define una interfaz GameObject para representar objetos interactuables en la mazmorra.
Paso 2: Crear la clase Player

Define una clase Player que encapsule los datos y comportamientos del jugador.
La clase debe incluir atributos como name, health, e inventory.
Proporciona métodos para que el jugador pueda recibir daño, recoger objetos y mostrar su estado actual.
Paso 3: Crear clases concretas de Room

Crea una clase EmptyRoom que represente una sala vacía.
Crea una clase TreasureRoom que represente una sala con un tesoro.
Crea una clase EnemyRoom que represente una sala con un enemigo.
Paso 4: Crear la clase principal del juego

Define una clase principal que inicialice el jugador y una serie de salas.
Implementa un bucle que permita al jugador moverse por las salas.
Maneja las interacciones del jugador con las salas y los objetos.

Para tomar en cuenta:
- Asegúrate de manejar adecuadamente las interacciones entre el jugador y los diferentes tipos de salas.
- Considera agregar más salas y enemigos para hacer el juego más interesante.
- Puedes implementar características adicionales como la posibilidad de que el jugador use objetos del inventario.
