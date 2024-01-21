## Comandos Git CLI
### Comandos de configuración general
****
**Establecer de forma global el email público de Github:**
```bash
git config --global user.email "example@gmail.com"
```
**Establecer de forma global el email privado de Github:**
```bash
git config --global user.email "<12345678>+<github_user>@users.noreply.github.com"
```
**Establecer de forma global el nombre de usuario de Github:**
```bash
git config --global user.name  "nombre de usuario"
```
**Activar guardado de las credenciales de acceso:**
```bash
git config --global credential.helper "store"
```
**Establecer el nombre de la rama principal:**
```bash
git config --global init.defaultBranch <nombre de la rama>
```
**Generar credenciales SSH para acceso:**
```bash
ssh-keygen -t ed25519 -C "example@gmail.com"
```


### Comandos de git para gestionar repositorios:
****
**Iniciar un nuevo repositorio:**
```bash
git init
```
**Mostrar el estado del directorio de trabajo:**
```bash
git status
```
**Añadir archivos o modificaciones al área de ensayo:**
```bash
git add <archivo o directorio>
```
****
