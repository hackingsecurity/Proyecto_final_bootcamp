# Comandos Git Básicos en CMD

| Nº | Acción                           | Comando Git en CMD                                           | Descripción breve                                     |
|----|----------------------------------|---------------------------------------------------------------|--------------------------------------------------------|
| 1  | Configurar nombre y correo       | `git config --global user.name "Tu Nombre"`<br>`git config --global user.email "correo@ejemplo.com"` | Se usa una sola vez. Configura tu identidad.          |
| 2  | Clonar un repositorio            | `git clone https://github.com/usuario/repositorio.git`        | Copia el repositorio de GitHub a tu PC.               |
| 3  | Ver estado del repositorio       | `git status`                                                  | Muestra archivos modificados, nuevos, etc.            |
| 4  | Añadir todos los cambios         | `git add .`                                                   | Prepara todos los cambios para el commit.             |
| 5  | Añadir un archivo específico     | `git add archivo.txt`                                         | Prepara solo ese archivo para el commit.              |
| 6  | Hacer un commit                  | `git commit -m "Mensaje claro"`                               | Guarda los cambios en tu repositorio local.           |
| 7  | Subir cambios al remoto          | `git push`                                                    | Sube los commits al repositorio en GitHub.            |
| 8  | Traer cambios del remoto         | `git pull`                                                    | Descarga cambios nuevos desde GitHub.                 |
| 9  | Ver historial de commits         | `git log`                                                     | Lista todos los commits realizados.                   |
| 10 | Crear una nueva rama             | `git checkout -b nombre-rama`                                 | Crea y se mueve a una rama nueva.                     |
| 11 | Eliminar un archivo del repo     | `git rm archivo.txt`<br>`git commit -m "Eliminar archivo"`    | Elimina un archivo del repositorio y lo guarda.       |
