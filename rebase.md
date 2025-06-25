# Limpieza de commits con git rebase -i

Usé el comando: git rebase -i HEAD~3

- Cambié el primer commit a `reword` para mejorar el mensaje.
- Usé `squash` en los otros dos para fusionarlos en un solo commit.
- Escribí un nuevo mensaje más claro para describir los cambios al README.

Finalmente, ejecuté: git push --force para actualizar el historial en el repositorio remoto.
