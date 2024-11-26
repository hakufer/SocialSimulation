# SocialSimulation

# Ejercicio 1: Torneo de Piedra, Papel o Tijera

Este programa simula un torneo de **Piedra, Papel o Tijera** entre varios jugadores. Cada enfrentamiento sigue las reglas estándar del juego, y los puntajes se acumulan para determinar al ganador final. El programa incluye una simulación que genera resultados dinámicos dependiendo de las estrategias seleccionadas aleatoriamente por los jugadores.

---

## Descripción del Programa

### Objetivo

El objetivo del programa es simular múltiples rondas de enfrentamientos de Piedra, Papel o Tijera entre varios jugadores. Los resultados se calculan de acuerdo con las reglas del juego y se lleva un seguimiento de los puntajes para determinar al ganador o posibles empates al final del torneo.

### Funcionalidades principales

1. **Definir estrategias y reglas del juego**:
   - Estrategias disponibles: `Rock`, `Paper`, `Scissors`.
   - Las reglas de victoria están definidas mediante un diccionario (`payoff`) que evalúa cada combinación posible:
     - `Rock` gana a `Scissors`, pero pierde contra `Paper`.
     - `Paper` gana a `Rock`, pero pierde contra `Scissors`.
     - `Scissors` gana a `Paper`, pero pierde contra `Rock`.

2. **Definir a los jugadores**:
   - Los jugadores son definidos en una lista con sus respectivos nombres, puntajes iniciales y estrategias (que se seleccionan aleatoriamente durante el juego).

3. **Simulación del Torneo**:
   - El torneo consta de un número de rondas predefinido (en este caso, 5).
   - Cada ronda implica múltiples enfrentamientos entre pares de jugadores. Los puntajes se actualizan dinámicamente en función de los resultados.

4. **Determinación del ganador**:
   - Al final de las rondas, se determina el jugador con el puntaje más alto. Si hay empate, se declara empate entre los jugadores líderes.

---
