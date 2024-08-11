# Netology-Project
Developed on Laravel 10 in conjunction with livewire, using the moonshine admin panel

### Requirements
* **php >= 8.1**
* **composer > 2**
* **mySQL >= 5.6.0**

### Installation
 * Run the command in the terminal: **composer create-project anna-stupina38/cinema**
 * Create a mySQL database on your local or remote server and edit the **.env** file in the project root directory, assigning values ​​to the constants, where:<br />
**APP_URL:** your domain<br />
**DB_HOST:** mySQL server address<br />
**DB_PORT:** connection port<br />
**DB_DATABASE:** database name<br />
**DB_USERNAME:** username to connect to the database<br />
**DB_PASSWORD:** password to connect to the database<br />


### Run migrations
 * **php artisan migrate**

### Creating an administrator
* **php artisan moonshine:user**

### Resources
* **The admin panel resources are located in the folder:** App\MoonShine\Resources
* **Route to enter the admin panel:** /lk
