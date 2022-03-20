# postgresql-centos7
Con la configuración actual, este playbook sirve para VMs de vagrant.

Deberás de editar el archivo vars.yml con los credenciales que quieras para el usuario de la base de datos.

El usuario que se crea en los servidores de bases de datos tiene tanto nombre como contraseña: postgres.

# importar datos a la base de datos
Con el playbook importar.yml podrás importar un archivo .sql en el servidor de base de datos PostgreSQL que elijas.
