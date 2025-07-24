**conceptos basicos**

Crear un repositorio local con Git:

1. Abre la terminal y ve al directorio de tu proyecto.
2. Inicializa el repositorio:
   git init

3. Configura tu nombre y correo (solo la primera vez):
   git config --global user.name "Tu Nombre"
   git config --global user.email "tuemail@ejemplo.com"

4. Agrega archivos al repositorio:
   git add .

5. Crea un commit:
   git commit -m "Primer commit"


Crear un repositorio remoto en GitHub y conectarlo:

1. Crea un repositorio nuevo en GitHub sin README.

2. Copia la URL del repositorio.

3. En tu terminal, dentro del proyecto local:
   git remote add origin https://github.com/usuario/repositorio.git

4. Sube los archivos:
   git push -u origin main
   (o usa 'master' si es tu rama)

5. Para subir cambios nuevos:
   git add .
   git commit -m "mensaje"
   git push|

