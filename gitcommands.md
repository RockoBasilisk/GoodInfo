**Configurar nombre de usuario e email para firmar los commits y guardar las credenciales de acceso:**
```bash
$ git config --global user.email "example@gmail.com"
```
```bash
$ git config --global user.name "UserName"
```
```bash
$ git config --global credential.helper "store"
```
****
**Iniciar un nuevo repositorio:**
```bash
$ git init
```
**Mostrar el estado del directorio de trabajo:**
```bash
$ git status
```
**Añadir archivos o modificaciones al área de ensayo:**
```bash
$ git add <archivo o directorio>
```
**Crear un commit con un mensaje o descripción del cambio:**
```bash
$ git commit -m "Mensaje del commit"
```
**Ver el historial de commits del repositorio en la rama actual:**
```bash
$ git log
```
**Modificar el mensaje de un commit:**
```bash
$ git commit -m "Nuevo mensaje del commit" --amend
```
**Agregar repositorio remoto:**
```bash
$ git remote add origin <url>
```
****
**Crear nueva rama a partir de la activa**
```bash
$ git branch "nombre"
```
**Ver ramas presentes en el repositorio y la rama activa:**
```bash
$ git branch
```
**Establecer una rama del repositorio como la rama activa:**
```bash
$ git checkout <nombre de la rama>
```
**Renombrar la rama activa:**
```bash
$ git branch -m <nuevo nombre>
```
**Renombrar una rama por su nombre:**
```bash
$ git branch -m <nombre de la rama> <nuevo nombre>
```
**Eliminar una rama:**
```bash
$ git branch -d <nombre de la rama>
```
****
**Enviar cambios al repositorio remoto:**
```bash
$ git push -u origin <nombre de la rama>
```