# php-apache-phpmyadmin-mariadb-setup

### make sure to remove .gitignore from empty folders first
### run docker-compose up
### Then go into the container using docker exec -it yiitraining-php-apache bash
### enable rewrite using a2enmod rewrite
### restart apache2 service using service apache2 reload. the container will quit rerun docker-compose up and go in the container again
### uncomment the comented part in apacheconf/sites-available/bigCompaEmployees
### enable your websites using a2ensite bigCompaEmployees.testingapp
### restart apache using service apache2 reload
### website is accessible now