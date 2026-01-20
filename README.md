Preguntas de reflexión: 
1. Sirve para crear un repositorio. La carpeta ocula que se crea para rastrar los cambios es ".git"
2. git config --list
3. Porque es importante para la seguridad y la limpieza, evita que subas información por error al repositorio que es publico y evita llenar el proyecto de basura que genera tu ordenador.
4. Se encuentra en el Staging Area y se utiliza el comando git status 
5. Los archivos cambian físicamente. Git "quita" los archivos que no pertenecen a la rama a la que vas "pone" los que si pertenecen.
6. La principal ventaja es el aislamiento, te permite probar cosas nuevas o arreglar fallos e un "entorno seguro", sin romper la versión principal del proyecto.
7.El nombre que se le asigna por defecto es origin

8.Usaria el git remote -v 
9. He utilizado git fetch y git status
10. La diferencia es que git fetch solo descarga datos que yo pueda ver que hay de nuevo y git pull hace dos cosas a la vez: descarga los cambios y los mezcla inmediatamente en mis archivos locales para actualizarlos
11. 
git remote add origin [URL]: Me costó entender que este comando no sube archivos, sino que simplemente sirve para "presentar" mi carpeta local al servidor de GitHub y que se reconozcan.

git checkout -b [rama]: Al principio es confuso porque hace dos cosas a la vez: crea una rama nueva y te cambia a ella. Ver cómo los archivos de mi carpeta aparecen y desaparecen según la rama me pareció extraño.

git pull vs git fetch: Es difícil entender que uno solo descarga la información y el otro además la mezcla con mi trabajo, lo que puede causar conflictos si no tengo cuidado.