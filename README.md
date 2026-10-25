# Golazo English

Juego en castellano, estilo Ultimate Team, para practicar inglés: verbo *to be*, países, continentes, idiomas y nacionalidades. Cada respuesta correcta es un gol, se ganan fechas, se abren sobres de jugadores y se arma la plantilla.

Web: https://ericlsg-19.github.io/golazo/

## Archivos
- `index.html`: el juego completo.
- `firestore.rules`: reglas de seguridad de la base de datos (se pegan en Firebase → Firestore → Reglas).

## Cuentas y nube (Firebase, proyecto `golazo-33a4b`)
- Cada chico entra con **usuario + PIN de 6 números**. No se piden emails: por dentro se usa `usuario@golazo-english.app`.
- El progreso se guarda en `players/{uid}` y también en el navegador.
- También se puede jugar sin cuenta (el progreso queda solo en ese aparato).
- El usuario **`eric`** es el administrador: en Ajustes → Modo profe carga unidades nuevas (`config/units`) y ve los informes de todos los jugadores.
- Si un chico se olvida el PIN, se puede borrar su usuario en Firebase → Authentication y crear otro; antes conviene que guarde su código en Ajustes → Copia de seguridad.
