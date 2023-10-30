# Commit
Con este comando se guarda todos los cambios realizados en el proyecto o minisistema que se este trabajando, con una breve explicación de lo que se ha realizado de parte del usuario. El o los commit no se podrán sobreescribir. Se puede recordar los cambios a los que se les hizo commit en una fecha posterior o revertir a esa fecha(_"git checkout"_).

# Rama
Rama es el directorio principal del proyecto, o miniproyecto que se este trabajando.

Dentro del mismo se puede:
* Ver rama -> `git branch`; `git branch -a`
* Cambiar rama-> `git checkout NOMBRE RAMA`
* Crear rama -> `git branch NOMBRE NUEVA RAMA`
* Mover a rama -> `git checkout -b NUEVA RAMA`
* Renombrar rama -> `git branch -m NOMBRE ANTERIOR RAMA NOMBRE NUEVO RAMA`
* Eliminar rama -> `git branch -d RAMA A ELIMINAR`
* Comparar ramas -> `git diff PRIMERA RAMA..SEGUNDA RAMA`

# Merge

Se utiliza para unir o fusionar uno o mas ramas dentro de la rama que tienes activa, a continuación avanzará la rama al resultado de la fusión(unión).

# Rebase

Se utiliza para integrar cambios de una rama a otra. Es una de las formas de combinar cambios en Git junto con git merge. Sin embargo, a diferencia de git merge, que crea un nuevo commit de fusión para combinar las ramas, git rebase reescribe el historial de la rama que se está fusionando.
