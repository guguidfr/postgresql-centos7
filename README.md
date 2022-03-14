# postgresql-centos7
Con la configuración actual, este playbook sirve para VMs de vagrant.
Deberás de editar el archivo vars.yml con los credenciales que quieras para el usuario de la base de datos.
El usuario que se crea en los servidores de bases de datos tiene tanto nombre como contraseña: postgres.
# importar datos a la base de datos
En la rama importar-script-SQL encontrarás un playbook para crear una base de datos en los servidores. 
Edita los campos necesarios para que el playbook funcione. 
También hay un .sql de ejemplo. Quita los comentarios, y escribe lo que quieras.
