
                -  ¿Qué comando utilizaste en el paso 11? ¿Por qué?  Comando: git reset —hard HEAD~1
                Para moverme al commit hijo descartando con hard para descartar el working copy
                -  ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
                Comando: git reflog
                Para ver el id de los commits
                Comando: git reset —hard 6bc2e3e
                Para moverme al commit anterior descartando los cambios 
                -  El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?  
                No, ya que HEAD tiene acceso a todos los commits
                -  El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
                Si, el archivo existe en commits de lineas diferentes y al mergear da un conflicto que tenemos que resolver 
                editando el archivo para elegir el contenido que queremos para el nuevo commit 
                -  El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?  
                No, porque están en la misma linea de commits. Así que lo que ha hecho es moverse head y master al commit 
                de la rama styled y actualizar los cambios en el archivo git-nuestro.md
                -  ¿Qué comando o comandos utilizaste en el paso 25?  Comando: git graph
                -  El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?  Si porque Head tiene acceso ya que están en la misma linea. 
                Pero así queda constancia mediante la creación de un nuevo commit
                -  ¿Qué comando o comandos utilizaste en el paso 27?
                git reset HEAD~1
                -  ¿Qué comando o comandos utilizaste en el paso 28?  
                git checkout — git-nuestro.md
                -  ¿Qué comando o comandos utilizaste en el paso 29?  
                git branch -D title
                -  ¿Qué comando o comandos utilizaste en el paso 30?  git reflog
                git reset —hard 1c0123b2
                -  ¿Qué comando o comandos usaste en el paso 32?  
                git reset —hard a8dc507
                -  ¿Qué comando o comandos usaste en el punto 33?  git reflog
                git reset —hard f5ac22c

# Jose Luis Tovar Cifuentes
# Práctica 1 GIT
