After clone this repository.

Clone the source repository.
* `git clone <repo> investandearn`

Run command to start containers
* `docker-compose up -d`

After do this (and if this not happen), open a new terminal to start
the services to have a running project

* `docker exec -it invest-and-earn /bin/bash`
    * `service apache2 start`
    * `service mysql start`
    * `cd /var/www/investandearn`
    * `composer update`
    
