# mysql

1 *Mettre dans le dossier essentiel et recrée un dossier [libs] et mettre tout ces dossier dedans*

2 *Allez dans le dossier esplugin_mysql et importe le fichier ``esplugin_mysql.sql``dans la base de donné*

3 *Start les ressource dans le server.cfg* ``mysql-async``, `` esplugin_mysql``, ``cron``, ``async``, ``instance``,

4 *Mettez cet ligne* set mysql_connection_string "server=localhost;database=nom de la database mysql;userid=root;password=*"

**Voila votre serveur est connecté a mysql**
