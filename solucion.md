Ejercicio 2

juan-@DESKTOP-Q2B2HAH UCRT64 /d/Curso DAM/PracticasGit/biblioteca (main)
$ git log --oneline --graph --all
*   29d06fd (HEAD -> main) Fusionar gestion de usuarios
|\
| * f199584 (feature/gestion-usuarios) Añadir contraseña ficticia a la ficha
| * b1ac1c9 Añadir email a la ficha del usuario
| * 5999867 Crear ficha inicial del usuario
* |   8808df5 Fusionar gestion de libros
|\ \
| |/
|/|
| * df75ae3 (feature/gestion-libros) añadir ISBN a la ficha del libro
| * 12e5c17 Añadir autor a la ficha del libro
| * 84ab59c Crear ficha inicial del libro
|/
* 9b6253c Añadir notas iniciales de la biblioteca
* 89f2407 (origin/master) Ampliar descripción del proyecto en README
* 588adce Añadir README inicial
* 8e8cebc Creado el proyecto con Hello y el readme, ahora si porque me equivoque al crear Hello
* 0fa57de Creado el proyecto con hello y el readme



Ejercicio 3

juan-@DESKTOP-Q2B2HAH UCRT64 /d/Curso DAM/PracticasGit/conflictos-git (main)
$ git --no-pager log --oneline --graph --all
*   cab3983 (HEAD -> main) Resolver conflicto en mensaje
|\
| * 24a1fa0 (feature/despedida) Modificar mensaje en rama despedida
* |   8a5a7cc Fusionar rama saludo
|\ \
| |/
|/|
| * 7342aa2 (feature/saludo) modificar mensaje en rama saludo
|/
* 2808c40 Crear mensaje inicial


Ejercicio 4

juan-@DESKTOP-Q2B2HAH UCRT64 /d/Curso DAM/PracticasGit/tienda-online (main)
$ git --no-pager log --oneline --graph --decorate --all
*   7a43de3 (HEAD -> main, tag: v1.0.1) Publicar version 1.0
|\
* \   a912ee3 Fusionar hotfix de precio en main
|\ \
| | | *   33a0de3 (develop) Fusionar hotfix de precio en develop
| | | |\
| | |_|/
| |/| |
| * | | 6b79f90 (hotfix/error-precio) Corregir error de precio
|/ / /
| | *   d82d6ea integrar release 1.0 en develop
| | |\
| | |/
| |/|
| * | 84f68b8 (tag: v1.0, release/1.0) Preparar version 1.0
| |/
| * b657c9f Fusionar carrito de compra en develop
|/|
| * 8612535 (feature/carrito-compra) Añadir auriculares al carrito
| * 42e532e Crear lista inicial de articulos del carrito, que me confundi antes
| * 1b1f320 Crear funcionalidad inicial del carrito
| * 630e75c Crear funcionalidad inicial del carrito
|/
* 2e1df28 Crear README inicial