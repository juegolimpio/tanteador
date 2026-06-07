# Tanteador

Aplicación web para llevar el marcador en clases de Educación Física. Permite registrar puntos en partidos de Voleibol y Básquetbol en tiempo real, desde cualquier celular y sin necesidad de instalación.

🔗 **[Acceder a la app](https://juegolimpio.github.io/tanteador/)**

---

## Funcionalidades

### Voleibol
- Tanteador de puntos con indicador visual del equipo que tiene el saque
- Configuración previa del partido: puntos para ganar el set, diferencia mínima y sets para ganar el partido
- Botones rápidos de configuración (10, 15, 21 y 25 puntos) y campo libre para cualquier valor
- Detección automática del fin de set y del partido según la configuración elegida
- Historial de sets jugados con parciales
- Alerta visual cuando el marcador está cerca del punto de set

### Básquetbol
- Tanteador simple con botones +1, +2 y +3 por equipo
- Sin lógica de cuartos ni tiempos oficiales: adaptado a los tiempos reales de clase

### Cronómetro
- Independiente del tanteador: reiniciar el marcador no afecta el cronómetro y viceversa
- Botones de inicio, pausa y reinicio
- Presets rápidos: 5, 8, 10 y 15 minutos
- Campo manual para ingresar cualquier duración

### General
- Botón Deshacer para corregir puntos mal anotados
- Botón Reiniciar partido
- Guardado automático del estado completo: si se cierra el celular o se recarga la página, el partido se recupera exactamente donde estaba
- Nombres de equipos editables directamente en el marcador

## Tecnologías

- HTML, CSS y JavaScript
- Sin dependencias de servidor ni base de datos
- Desplegada en GitHub Pages
- Persistencia local mediante localStorage

## Estado del proyecto

En uso activo en clases de Educación Física en educación media (DGES – DGETP UTU, Uruguay).

---

## Declaración de autoría e integridad académica

Esta aplicación fue conceptualizada, diseñada y dirigida por **Diego González**, docente de Educación Física en educación media (DGES – DGETP UTU, Uruguay).

El desarrollo técnico fue realizado mediante co-creación con el modelo de inteligencia artificial generativa **Claude** (Anthropic), utilizado como herramienta de asistencia para programación, depuración y estructuración del código fuente.

Las decisiones pedagógicas, funcionales y de diseño de la experiencia de usuario son de autoría exclusiva del autor humano. La dirección del proyecto, la definición de requisitos y la validación en contexto real de uso corresponden íntegramente a Diego González.

Esta declaración se realiza en concordancia con los principios de honestidad intelectual, transparencia en el uso de tecnologías emergentes y las buenas prácticas vigentes en el ámbito educativo.

> *"El foco de este proyecto no radica en la programación tradicional desde cero, sino en la capacidad de resolver de manera concreta y eficiente una necesidad real de la práctica docente."*
