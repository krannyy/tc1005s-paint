# tc1005s-paint

Juego Paint de freegames, modificado para la evidencia de TC1005S (Actividad 1).

Owner del repositorio: Jaime Samuel García Manzano (krannyy). Fork: Angel Barush (thenewbaru).

## Contenido
- `paint.py`: el juego.
- `README.md`: este archivo.

## Cómo correrlo
```
pip install freegames
python3 paint.py
```
Teclas de color: `K` negro, `W` blanco, `G` verde, `B` azul, `R` rojo, `Y` amarillo.
Teclas de figura: `l` línea, `s` cuadrado, `c` círculo, `r` rectángulo, `t` triángulo. `u` deshace.
Se hace clic en dos puntos para dibujar la figura.

## Cambios
| Cambio | Autor |
|---|---|
| Imports explícitos en lugar de `import *` | Samuel |
| Color nuevo: amarillo (tecla `Y`) | Samuel |
| Círculo (tecla `c`) | Samuel |
| Se restaura el círculo que se perdió al hacer merge | Samuel |
| Rectángulo (tecla `r`) | Barush |
| Triángulo (tecla `t`) | Barush |
