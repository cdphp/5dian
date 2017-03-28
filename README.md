# README


* Ruby version
    - 2.3.3
* Rails version
    - 5.0.2
* Docker >= 17.03
* Docker-compose

* Database creation
    - postgres
* Database initialization
    - `docker-compose run web /bin/bash`
    - `psql -h db -U postgres` password `postgres`
    - 
    ```sql
        CREATE DATABASE udian_development ENCODING 'UTF8';
        CREATE DATABASE udian_production ENCODING 'UTF8';
        CREATE DATABASE udian_test ENCODING 'UTF8';
        GRANT ALL ON DATABASE udian_development TO postgres;
        GRANT ALL ON DATABASE udian_production TO postgres;
        GRANT ALL ON DATABASE udian_test TO postgres;
    ```

* ...
