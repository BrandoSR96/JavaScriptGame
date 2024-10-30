# JavaScriptGame

# Juego de Jugadores

Este proyecto es un simple simulador de juego donde los jugadores pueden curarse mutuamente y atacar usando flechas. Está implementado en JavaScript y permite ver cómo se manejan los puntos de vida (PV) y los puntos de energía (SP) de cada jugador.

## Tabla de Contenidos
- [Descripción](#descripción)
- [Uso](#uso)
- [Funciones Principales](#funciones-principales)
- [Ejemplo de Uso](#ejemplo-de-uso)

## Descripción

El juego cuenta con una clase `Jugador` que permite crear objetos de jugador con un nombre, puntos de vida y puntos de energía. Los jugadores pueden curarse entre sí y atacar con flechas, lo que afecta sus puntos de vida.

## Uso

Para utilizar el código, simplemente puedes copiarlo y pegarlo en un entorno de JavaScript, como un navegador web o Node.js. 

### Instalación

1. Clona este repositorio:
   ```bash
   git clone <URL_DEL_REPOSITORIO>
2. Navega al directorio del proyecto:
   cd NOMBRE_DEL_REPOSITORIO
3. Abre el archivo en tu editor de texto
   ejm: code . (Comando para abir editor de texto: Visual estudio code)
   
### Funciones Principales
curar(jugadorObjetivo): Permite al jugador curar a otro jugador, incrementando su puntos de vida (PV) si tiene suficientes puntos de energía (SP).
tirarFlecha(jugadorObjetivo): Permite al jugador atacar a otro jugador, reduciendo sus puntos de vida (PV). Si los puntos de vida del jugador objetivo llegan a 0, se indica que el jugador ha muerto.
estado(jugadorObjetivo): Muestra el estado actual del jugador y del jugador objetivo en la consola.

   
