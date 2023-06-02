# **Capítulo 2: Flujo de trabajo básico**

Crear una rama: Antes de comenzar a trabajar en una nueva función o corrección de errores, se crea una nueva rama utilizando el comando git branch nombre_rama. Por ejemplo, git branch feature_x crea una nueva rama llamada "feature_x".

Cambiar a la rama: Para comenzar a trabajar en la nueva rama, se cambia a ella utilizando el comando git checkout nombre_rama. Por ejemplo, git checkout feature_x cambia a la rama "feature_x".

Realizar cambios y confirmar: En la nueva rama, se realizan los cambios necesarios en los archivos del proyecto. Una vez que se han realizado los cambios, se confirman (commit) utilizando el comando git commit -m "Mensaje descriptivo". El mensaje debe ser informativo y explicar los cambios realizados.

Fusionar cambios: Una vez que los cambios se han confirmado en la rama, es posible que desees fusionarlos con la rama principal del proyecto (por lo general, llamada "master" o "main"). Para hacerlo, primero, cambias a la rama principal utilizando git checkout nombre_rama_principal y luego utilizas el comando git merge nombre_rama para fusionar los cambios de la rama en la rama principal.

Resolver conflictos: En algunos casos, puede haber conflictos durante la fusión debido a cambios conflictivos en las mismas líneas de código. Git te notificará sobre estos conflictos y tendrás que resolverlos manualmente. Una vez resueltos, se agregan los archivos modificados y se confirma nuevamente.

Eliminar ramas: Después de fusionar los cambios de una rama en la rama principal y confirmarlos, puedes eliminar la rama utilizando el comando git branch -d nombre_rama.