## Installation
You can clone this repository OR download the .zip file.

After extracting, you need to run composer to install the dependencies and generate the autoload.

Navigate to the project folder using the command prompt/terminal and execute:

composer install

Then just wait for the process to finish.

## Configuration
All configuration files and application files are located inside the src folder.

The database and URL configurations can be found in the file src/Config.php.

It is important to correctly configure the BASE_DIR constant:

``
const BASE_DIR = '/ProjectFolder/public';
``

## Usage
You should access the public folder of the project.

It is recommended to create a specific alias on the server that points directly to the public folder.



## MODEL
```php
<?php
namespace src\models;
use \core\Model;

class Usuario extends Model {

}
```