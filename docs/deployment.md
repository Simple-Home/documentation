# Installation
* Download the Simple Home Project to your web server (/var/www/)
* git clone https://github.com/Simple-Home/Simple-Home.git
* cd into the LAR_v4_Simple_Home_Server-master
* Run the command: composer install
* Run the command: npm install
* Create a database in MySQL
* add folovin lines to your Cron tab:
  
    ```batch
    * * * * * cd /var/www/dev.steelants.cz/vasek/simple-home-v4/ && php artisan schedule:run >> /dev/null 2>&1
    ```

    ```batch
    * 1 * * * cd /var/www/dev.steelants.cz/vasek/simple-home-v4/ && php artisan queue:work --stop-when-empty >> /dev/null 2>&1
    ```

* Visit your webservers URL and proceed with setup