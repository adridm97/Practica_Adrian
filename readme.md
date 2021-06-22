1. ¿Que comando utilizaste en el paso 11? ¿Por Que?

Comando: git reset --hard HEAD~1
Utilizo este comando ya que se realiza el proceso en una sola instrucción y tenemos claro a que va a afectar.

2. ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

Comando1: git reflog    para ver todo el listado de commits y poder situarme en el anterior
comando2: git reset --hard 6436812 con este comando vuelvo al commit anterior que habia deshecho.

3. El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

No, está todo correcto debido a que sólo se modifican los cambios del archivo desde una de las ramas y por lo cual no hay conflicto.

4. El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

Si que hay conflicto debido a que intentamos hacer un merge de un archivo modificado desde otro archivo que también está modificado en las mismas líneas y entonces da error.

5. El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?

No causa conflicto ya que lo que ha hecho ha sido coger los cambios que había en styled y aplicarlos en su archivo y como el de master no se había modificado en nungún momento no ha dado conflicto.

6. ¿Qué comando o comandos utilizaste en el paso 25?

git log --graph --decorate --pretty=oneline

7. El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?



8. ¿Qué comando o comandos utilizaste en el paso 27?

git reset HEAD~1

9. ¿Qué comando o comandos utilizaste en el paso 28?

git restore git-nuestro.md

10. ¿Qué comando o comandos utilizaste en el paso 29?

git branch -D title

11. ¿Qué comando o comandos utilizaste en el paso 30?

git reset 936eddf

12. ¿Qué comando o comandos utilizaste en el paso 32?
git reset --hard 5aa8103
13. ¿Qué comando o comandos utilizaste en el paso 33?
git reset --hard 936eddf
