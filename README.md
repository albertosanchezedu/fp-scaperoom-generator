# 🎮 Escape Room Generator · FP

Generador de escape rooms educativos gamificados para **Moodle**, **EducaMadrid** y **EVEX Extremadura**.

## ¿Qué hace?

Pega el contenido de cualquier tema de tus apuntes, elige el número de salas y obtén el prompt perfecto para que Claude genere en minutos un **escape room interactivo completo**: puzzles drag & drop, preguntas de elección múltiple, códigos cifrados con cifrado César, sala de castigo con vidas y temporizador, y **calificación automática en Moodle** vía cuestionario AIKEN.

## ¿Qué obtienes?

- `escape_room.html` — escape room listo para subir a Moodle como Archivo
- `cuestionario.txt` — preguntas en formato AIKEN para importar al banco de preguntas
- Guía paso a paso para instalarlo en Moodle

## Características

- 3, 4 o 5 salas configurables (~15-30 min de juego en equipo)
- Mecánicas reales: 2 vidas, temporizador 30 min, -5 min por fallo, sala de castigo
- Códigos falsos en respuestas incorrectas para evitar que se copien
- Bases de datos manipuladas en cada sala para obligar a usar los apuntes
- Los alumnos juegan en equipo — cada uno completa el cuestionario individualmente
- Compatible con **Moodle**, **EducaMadrid** y **EVEX Extremadura**
- Paleta de identidad docente FP: · Fira Sans · CC BY-NC 4.0

## Uso

1. Abre el generador en Claude
2. Rellena el módulo, pega el contenido del tema y elige el número de salas
3. Copia el prompt generado y pégalo en [claude.ai](https://claude.ai)
4. Claude genera el plan de salas — revisas, ajustas y le pides los archivos
5. Sube `escape_room.html` a Moodle como **Archivo** (Apariencia → Abrir)
6. Importa `cuestionario.txt` al banco de preguntas en formato **AIKEN**

## Flujo en clase

Los alumnos forman equipos y juegan el escape room juntos en una pantalla, anotando los códigos de cada sala. Después, **cada alumno individualmente** va al cuestionario de Moodle, introduce los códigos y responde las preguntas de conceptos. La nota va directa al calificador sin corrección manual.

---

*Creado por Alberto Sánchez Cabanillas — Docente FP Comercio y Marketing · [LinkedIn](https://www.linkedin.com/in/albertosanchezcabanillas/) · Curso 2025-2026*
