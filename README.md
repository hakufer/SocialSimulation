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
# Ejercicio 2: Torneo de Rock, Paper, Scissors, Lizard, Spock

Este programa extiende las reglas clásicas de Piedra, Papel o Tijera, añadiendo dos nuevas opciones: **Lizard** y **Spock**, lo que crea un juego más variado y emocionante. Este torneo simula múltiples rondas entre varios jugadores, determinando el ganador según los puntajes acumulados.

---

## Descripción del Programa

### Objetivo

Simular un torneo de múltiples rondas en el que los jugadores seleccionan estrategias aleatorias entre las cinco opciones: `Rock`, `Paper`, `Scissors`, `Lizard`, `Spock`. El programa evalúa los enfrentamientos entre pares y actualiza los puntajes en función de las reglas del juego.

### Funcionalidades principales

1. **Definir estrategias y reglas del juego**:
   - Estrategias disponibles: `Rock`, `Paper`, `Scissors`, `Lizard`, `Spock`.
   - Las reglas de victoria están definidas mediante un diccionario (`payoff`) que evalúa todas las combinaciones posibles:
     - `Rock` aplasta a `Scissors` y aplasta a `Lizard`, pero pierde contra `Paper` y `Spock`.
     - `Paper` cubre a `Rock` y desautoriza a `Spock`, pero pierde contra `Scissors` y `Lizard`.
     - `Scissors` corta `Paper` y decapita a `Lizard`, pero pierde contra `Rock` y `Spock`.
     - `Lizard` envenena `Spock` y come `Paper`, pero pierde contra `Rock` y `Scissors`.
     - `Spock` rompe `Scissors` y vaporiza `Rock`, pero pierde contra `Paper` y `Lizard`.

2. **Definir a los jugadores**:
   - Los participantes incluyen: `Jim`, `Jane`, `Peter`, `Zoe`, `Sam`, `Alice`, `Bob`, `Charlie`, `Dana` y `Eve`.
   - Cada jugador tiene un puntaje inicial de 0 y selecciona estrategias de forma aleatoria durante cada enfrentamiento.

3. **Simulación del Torneo**:
   - El torneo consta de 5 rondas, donde los jugadores se enfrentan en todos los pares posibles en cada ronda.
   - Los puntajes se actualizan dinámicamente en función de los resultados de cada enfrentamiento.

4. **Determinación del Ganador**:
   - Al final de las rondas, se identifica al jugador con el puntaje más alto como ganador.
   - Si hay un empate, todos los jugadores líderes comparten la victoria.

---
