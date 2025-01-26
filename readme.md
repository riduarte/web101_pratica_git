#Practica de git

**- ¿Qué comando utilizaste en el paso 11? ¿Por qué?**

He usado el comando `git reset --hard HEAD~1` para deshacer el ultimo commit y perder lo que habia en el working copy, dejandotodo como estaba antes de este commit.

**- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**

He usado el comando `Ref log` para poder ver los commits y sus identificadores. Seleccione el identificador del commit que iba a rehacer y luego ejecute `git reset --hard identificador` para mover el puntero head al commit.

**- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**

No ha ocurrido ningun conflicto, por que la rama styled estaba por arriba de main y no causan conflictos.

**- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**

Si hubo conflictos, por que los cambios de los archivos no eran 
compatibles.

**- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**

No causo conflictos, hizo un fast-forward y los cambios en la rama styled fueron añadidos sin conflictos.

**- ¿Qué comando o comandos utilizaste en el paso 25?**

He utilizado el comando `git log --graph`

**- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**

Si podria haber sido fast foward por que en la rama title esta por encima de main y main podria haber absorbido a title sin conflictos. 

**- ¿Qué comando o comandos utilizaste en el paso 27?**

He usado el comando `git reset HEAD~1` que mantiene el working copy.

**- ¿Qué comando o comandos utilizaste en el paso 28?**

Use el comando `notepad archivo` para abrir de nuevo el archivo y borrar el titulo, al guardo ya los cambios no se toman en cuenta y mi repositorio esta al dia.

**- ¿Qué comando o comandos utilizaste en el paso 29?**

Use el comando `git branch -D Rama`

**- ¿Qué comando o comandos utilizaste en el paso 30?**

He usado el comando `reflog` para ver el identificador del commit donde habia hecho el merge y use el comando `git reset --hard identificador` para rehacer los cambios borrados.

**- ¿Qué comando o comandos usaste en el paso 32?**

He usado `reflog` para ver el identificador del primer commit y use el comando 
`git checkout identificador`

**- ¿Qué comando o comandos usaste en el punto 33?**

He usado `reflog` para ver el identificador del ultimo commit y use el comando 
`git checkout identificador`
