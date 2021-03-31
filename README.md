# Main commands
git init --------------------------------------- Iniciar repositorio

git checkout <rama> ---------------------------- Cambiar de rama

git branch <rama> ------------------------------ Crear rama(-m renombrar)

git add <archivo> ------------------------------ Agregar archivo a stage area

git commit -m <mensaje> ------------------------ Agregar desde stage area a repositorio (--amend para corregir el commit anterior)

git status ------------------------------------- Ver el estado de los archivos

git log ---------------------------------------- Registro de los commits de la rama

git log --graph --all -------------------------- Registro grafico de todas las ramas

git remote add <nombre_rama_remota> <url> ------ Agregar repositorio remoto

git pull <nombre_rama_remota> <url> ------------ Sincronizar desde repositorio remoto (-allow-unrelated-histories cuando no tienen commits en común)

git push <nombre_rama_remota> <url> ------------ Subir a repositorio remoto

git merge <nombre_rama> ------------------------ Unir otra rama a la rama actual

git tag <nombre> ------------------------------- Etiiqueta para identificar algo, como versiones

git reflog ------------------------------------- Últimos cambios con ID

git reset --<tipo> <ID> ------------------------ Devuelve al punto ID(--hard borra los cambios sin commit, --soft mantiene los cambios sin comit)
	
git remote -v ---------------------------------- Listar repositorios remotos

git remote add <nombre> <url> ------------------ Agregar repositorio remoto


## Train register

	* commit 62bbe01b478686c6499f53cd9be25a35ba5ce553 (master)
	| Author: Cristian Chitiva <cychitivav@unal.edu.co>
	| Date:   Tue Mar 16 21:31:57 2021 -0500
	| 
	|     add tags command
	|   
	*   commit c106ebbbf3b0eb5644f6ce3dbc06262a326956b2 (tag: v1, origin/master)
	|\  Merge: fbd1399 16cf155
	| | Author: Cristian Chitiva <cychitivav@unal.edu.co>
	| | Date:   Tue Mar 16 21:29:31 2021 -0500
	| | 
	| |     Merge branch 'login'
	| | 
	| * commit 16cf155884ecdcb54690d36d3d236bba1cb101da (github/login, login)
	| | Author: Cristian Chitiva <cychitivav@unal.edu.co>
	| | Date:   Tue Mar 16 20:44:25 2021 -0500
	| | 
	| |     Remove test folder from gitignore
	| | 
	* | commit fbd13993d80224a5e62ae35e2a9fdfa4185309c0
	| | Author: Cristian Chitiva <30636259+cychitivav@users.noreply.github.com>
	| | Date:   Tue Mar 16 21:11:24 2021 -0500
	| | 
	| |     Create README
	| | 
	* | commit 6f828aa1e726385c3c02598606dfb379185683f9
	| | Author: Cristian Chitiva <cychitivav@unal.edu.co>
	| | Date:   Tue Mar 16 20:57:38 2021 -0500
	| | 
	| |     Latex de documentacion agregado a la rama principal
	| | 
	* | commit ab4433c27e5473d460e8b8105bef95a42adb5bf3
	| | Author: Cristian Chitiva <cychitivav@unal.edu.co>
	| | Date:   Tue Mar 16 19:41:54 2021 -0500
	| | 
	| |     add init.jar
	| |   
	| | * commit c389dd4ec6b6b650764ba9f6bdf773a2497f329b (HEAD -> test, origin/test)
	| | | Author: Cristian Chitiva <cychitivav@unal.edu.co>
	| | | Date:   Tue Mar 16 21:25:39 2021 -0500
	| | | 
	| | |     Add remote commands
	| | | 
	| | * commit 5ddde37b84e17d0c80034af33eccddecda4acb77
	| |/  Author: Cristian Chitiva <cychitivav@unal.edu.co>
	| |   Date:   Tue Mar 16 20:50:48 2021 -0500
	| |   
	| |       Agregué los comandos de git
	| | 
	| * commit 8dbc885a99bfdac7a242ca4c6c6507da0a3c5c11
	| | Author: Cristian Chitiva <cychitivav@unal.edu.co>
	| | Date:   Tue Mar 16 20:10:01 2021 -0500
	| | 
	| |     He agregado un auth y login
	| | 
	| * commit 5b02848644afda8fe5121a0197395e0c18b48d26
	|/  Author: Cristian Chitiva <cychitivav@unal.edu.co>
	|   Date:   Tue Mar 16 19:41:54 2021 -0500
	|   
	|       He agregado un gitignore
	| 
	* commit a3c58cbb8aef5eda4ab99adc7cf62f3a1ef89040
	| Author: Cristian Chitiva <cychitivav@unal.edu.co>
	| Date:   Tue Mar 16 19:34:22 2021 -0500
	| 
	|     El archivo index.html ahora tiene código html
	| 
	* commit de428a503601d4d2a4096007cf940f234b8d5171
	  Author: Cristian Chitiva <cychitivav@unal.edu.co>
	  Date:   Tue Mar 16 19:27:33 2021 -0500
	  
	      Mi primer commit
	(END)
