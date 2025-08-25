# RepositorioTuluanto
# App: Tuluánto

Aplicación móvil estilo red social que centraliza información sobre seguridad, movilidad y convivencia ciudadana en Tuluá.

## Reglas de Colaboración

Para el desarrollo de **Tuluánto** nuestro equipo seguirá el flujo de trabajo **GitHub Flow**, ya que se adapta bien a proyectos pequeños con despliegues continuos y colaborativos.  

### Flujo de Ramas
1. **Rama principal (`main`)**  
   - Contendrá siempre el código estable y en producción.  
   - No se permiten cambios directos; todos deben pasar por Pull Requests.  

2. **Ramas de funcionalidad o corrección**  
   - Cada nueva tarea (funcionalidad, mejora o bugfix) se desarrollará en una rama independiente creada a partir de `main`.  
   - El nombre de la rama debe indicar su propósito, por ejemplo:  
     - `feature/estadisticas`  
     - `feature/mapa-rutas`  
     - `fix/error-login`  

3. **Pull Requests (PRs)**  
   - Una vez finalizada la tarea en su rama, se abrirá un PR hacia `main`.  
   - Al menos un miembro del equipo deberá revisar y aprobar el PR antes de fusionarlo.  
   - El historial de commits debe ser claro y, de ser necesario, se usará squash para mantenerlo limpio.  

4. **Integración**  
   - Tras la aprobación, la rama se fusionará en `main`.  
   - Las ramas que ya fueron fusionadas deben eliminarse para mantener el repositorio ordenado. 
