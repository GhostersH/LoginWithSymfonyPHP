﻿# LoginWithSymfonyPHP
1. Instalar symfony mediante el link https://symfony.com/download (recomendacion descargar scoop) https://scoop.sh facilita mucho la instalacion de synffony si tienes error con el archivo descargable que brinda el framework.
2. Para crear el login se recomienda descargar XAMPP https://www.apachefriends.org/es/index.html, si tienes conocimientos de PHP.INI hazlo manualmente.
3. Descargar composer https://getcomposer.org, esto sirve para poder subir el servidor localmente.
4. Crea un proyecto synony desde el CLI, NO EJECUTAR COMO ADMINISTRADOR EL CLI ESE TE REDIRECCIONA A LA CARPETA DE SYSTEM32, AHI NO PODRAS SUBIR EL SERVIDOR POR QUE LA SEGURIDAD DE WINDOWS NO TE LO PERMITE.
5. Usar los comandos para generar el login. https://symfony.com/doc/5.2/security/form_login_setup.html.
6. LA MATORIA DE CODIGO SE TE GENERA AUTIMATICAMENTE.
7. Usar el comenado de php bin/console d:d:c para generar automaticamente la base de datos en PHPMYADMIN
8. UTILIZA php bin/console security:hash-password PARA HASHEAR TU CONTRASENIA.
9. Una vez generada la base de datos y la contrasena hash entra a phpmyadmin, dale click a la base de datos que se genero automaticamente desde el comando e inserta tus datos.
10. LISTO YA TENDRIAS TU CUENTA AUTENTICADA DE SYNFONY!
