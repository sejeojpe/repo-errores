# Recuperación de errores

**Error simulado:**
- Eliminé accidentalmente el archivo errores.sh y confirmé el cambio.

**Comandos usados para recuperar:**
- git reflog
- git checkout HEAD@{1} -- errores.sh

**Aprendizaje:**
- Aprendí que usando git reflog puedo ver el historial completo de los movimientos recientes en Git.
- Con git checkout puedo recuperar archivos individuales de estados anteriores sin tener que rehacer todo el proyecto.
