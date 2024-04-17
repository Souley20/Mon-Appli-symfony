Mon-Appli-symfony
========================

The Mon-Appli-symfony is a reference application created
how to develop applications using [Symfony Best Practices][1].

You can also discover these practices in [the official Symfony Book][5].

Requirements
------------

 * PHP 8.3 or higher ;
 * PHP PDO-SQLite extension enabled ;
 * and the [usual Symfony application requirements][2].

Installation
------------

There are 2 different ways to install this project depending on your needs:

**Option 1.**: [Download Symfony CLI] and use the symfony binary installed
on your computer to run this command:

```bash
symfony new --My-Appli-symfony 
```

**Option 2.** [Download Composer][6] and use the composer binary installed
on your computer to run these commands:

```bash
# you can create a new project based on the Symfony Demo project...
composer create-project symfony/skeleton:"^5.4" my_project_directory

# ...or you can clone the code repository and install its dependencies
git clone https://github.com/symfony/Mon-Appli-symfony.git my_project
cd my_project/
composer install
```

Usage
-----

There's no need to configure anything before launching the application.
There are 2 different ways to run this application, depending on your needs:

**Option 1.**: [Download Symfony CLI][4] and run this command:

```bash
cd my_project/
symfony server:start -d
```

Then access the application in your browser at the given URL( http://127.0.0.1:8000 by default).

**Option 2.** Use a web server like replit.dev or Apache to run the application
(read the documentation about [configuring a web server for Symfony][3]).

On your local machine, you can run this command to use the built-in PHP web server:

```bash
cd my_project/
php -S localhost:8000 -t public/
```

Tests
-----

Execute this command to run tests:

```bash
cd my_project_name/
php bin/console server:run
```
[1]: https://symfony.com/doc/current/best_practices.html
[2]: https://symfony.com/doc/current/setup.html#technical-requirements
[3]: https://symfony.com/doc/current/setup/web_server_configuration.html
[4]: https://symfony.com/download
[5]: https://symfony.com/book
[6]: https://getcomposer.org/
