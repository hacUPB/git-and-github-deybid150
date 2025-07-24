Creación de un repositorio local
Un repositorio local es un espacio en tu computadora donde Git controla los cambios de tus archivos. Para crear uno:

Abre la consola y ubícate en la carpeta de tu proyecto.

Inicializa Git con el comando:

csharp
Copiar
Editar
git init
Configura tu nombre y correo (solo la primera vez):

arduino
Copiar
Editar
git config --global user.name "Tu Nombre"
git config --global user.email "tuemail@example.com"
Agrega los archivos al área de preparación:

csharp
Copiar
Editar
git add .
Crea el primer commit con un mensaje descriptivo:

sql
Copiar
Editar
git commit -m "Primer commit"
