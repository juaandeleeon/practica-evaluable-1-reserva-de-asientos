# Simulador de Reservas de Asientos para un Avión
## Descripción y Objetivo del Programa
### El objetivo de este proyecto es desarrollar un simulador de reservas de asientos para un avión en Python. El programa permitirá a los usuarios reservar, cancelar, y visualizar asientos disponibles. Se utilizará una matriz bidimensional para representar la disposición de los asientos en el avión, manejando las operaciones de reserva y cancelación en tiempo real.
## Organización del Código
### El código estará organizado en módulos para facilitar la legibilidad, reutilización y mantenimiento:
### Inicialización del avión: Este módulo definirá la configuración del avión, estableciendo una matriz que represente los asientos.
### Reserva de asientos: Aquí se gestionará la lógica para reservar asientos, comprobando la disponibilidad según las preferencias del usuario (ventana, pasillo).
### Cancelación de reservas: Este módulo permitirá a los usuarios cancelar sus reservas, actualizando el estado de los asientos.
### Visualización del mapa de asientos: Se mostrará un mapa actualizado del avión, con los asientos ocupados y libres.
### Gestión de excepciones: Este módulo controlará errores, como intentos de reservar asientos inexistentes o cancelaciones inválidas.
## Abordaje de cada Parte
### Inicialización: Crear una matriz que represente la disposición de asientos (por fila y columna).
### Reserva y Cancelación: Implementar funciones que modifiquen el estado de los asientos en la matriz.
### Visualización: Representar el mapa de asientos, indicando claramente los ocupados y disponibles.
### Gestión de errores: Controlar entradas inválidas y condiciones que puedan causar fallos.
## Retos
### Uno de los principales desafíos será la optimización de la selección de asientos basados en preferencias del usuario (ventana o pasillo). Además, la representación visual del mapa del avión puede requerir una actualización constante de la matriz. También se debe garantizar un manejo robusto de excepciones para prevenir errores.
## Librerias a utilizar
### NumPy, para la gestión eficiente de matrices.
### Posiblemente matplotlib, para la visualización gráfica opcional del avión.
## referencias y bibliografia
### Documentación de NumPy: https://numpy.org/doc/.
