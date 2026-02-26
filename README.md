# Flor Geométrica en Blender 

## Descripción
Este proyecto genera una flor geométrica utilizando Python en Blender.
Se compone de:
- 1 círculo central
- 12 círculos distribuidos uniformemente alrededor

## Parámetros utilizados
- Radio: 3
- Paso angular: 30°
- Total de círculos periféricos: 12
- Vértices por círculo: 64

## Procedimiento
1. Se limpia la escena.
2. Se define el radio y el paso angular.
3. Se crea el círculo central.
4. Se usa un ciclo while para generar los círculos alrededor.
5. Se convierten coordenadas polares a cartesianas usando:
   x = r * cos(θ)
   y = r * sin(θ)

## Resultado
![WhatsApp Image 2026-02-25 at 20 10 52](https://github.com/user-attachments/assets/7d357036-4eb8-43ca-9b03-944997eb6dbb)

