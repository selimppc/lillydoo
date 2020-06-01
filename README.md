Symfony 3.4
========================

Install symfony 3.4.x 

    $ composer create-project symfony/framework-standard-edition lilly "3.4.*"
    
Sqlite path:

    in parameters.yml:
    database_path: '%kernel.project_dir%/var/data/data.sqlite'

Database Create:

    $ php bin/console doctrine:database:create
    
Schema Create:

    $ php bin/console doctrine:schema:create        
    

Run application

    $ php bin/console server:run
        
AddressBook URL :

    $ http://127.0.0.1:8000/addressbook/
    
Author:

    Selim Reza
    selimppc@gmail.com
    8801831803255
