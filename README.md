1. Clone the project from https://github.com/Romanf5/directory-tree.git.

2. Configure Virtual Host (if needed). Configuration recommendations https://symfony.com/doc/3.4/setup/web_server_configuration.html

3. Install the composer (if needed). https://getcomposer.org/

4. Install all dependencies with the "composer install" command.

5. Make the necessary settins for accessing the database and the SMTP server in file: app/config/parameters.yml. As a test SMTP server, you can use the mailtrap.io service. During registration, the user will receive a notification about successful registration at the specified e-mail.

6. Create a database with the command: php bin/console doctrine:database:create.

7. Create tables in the database using the command: php bin/console doctrine:schema:update --force.
