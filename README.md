# YDrive Google Drive Proxy
I hate video proxy script that encrypted with IonCube, so I made this, you can use it for another project.

Give me a star if you like this !

## Requirements
PHP 7+

## Usage

Include the `core.php`
```php
include "core.php";
```
Demo script
```php
include("core.php");
// Init
$s = new YDrive();
// set new ID
$s->setID($_GET["id"] ?? "");
// set Resolution
$s->setResolution($_GET["m"]  ?? "");
// download Link 
$s->setDownload($_GET["alt"]  ?? "");
// Start Stream
$s->stream();
```
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

Sorry for bad README documentation

## License
[Apache](https://www.apache.org/licenses/LICENSE-2.0)
