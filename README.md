# SocialSimulation

# Ejercicio 1: Torneo de Piedra, Papel o Tijera

Este programa simula un torneo de **Piedra, Papel o Tijera** entre cuatro jugadores. Cada enfrentamiento sigue las reglas estándar del juego, y los puntajes se acumulan para determinar al ganador final. En este ejemplo, el torneo culminó con **Jane** como ganadora.

---

## Descripción del Programa

El programa realiza las siguientes acciones principales:

1. **Definir estrategias y reglas de juego**:
   - Estrategias disponibles: `Rock`, `Paper`, `Scissors`.
   - Las reglas de victoria están definidas mediante un diccionario (`payoff`) que indica el resultado de cada combinación posible.

2. **Definir a los jugadores**:
   - Los participantes del torneo son: `Jim`, `Jane`, `Peter` y `Zoe`.
   - Cada jugador tiene un puntaje inicial de 0 y selecciona estrategias aleatorias en cada enfrentamiento.

3. **Simulación del Torneo**:
   - El torneo consta de 5 rondas.
   - En cada ronda, los jugadores se enfrentan en pares. El ganador de cada enfrentamiento obtiene 1 punto y el perdedor 0. En caso de empate, ambos reciben 0 puntos.
   - Los puntajes se actualizan dinámicamente y se muestran al final de cada ronda.

4. **Resultados Finales**:
   - Al finalizar las rondas, se determina el jugador con el mayor puntaje acumulado como ganador. Si hay un empate en el puntaje más alto, todos los jugadores empatados comparten la victoria. En este caso, la ganadora fue Jane con 7 puntos

---
