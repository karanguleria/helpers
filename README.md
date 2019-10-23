# helpers
It includes the helper functions needed

# Usage
require __DIR__.'/vendor/autoload.php';

use Helpers\Helpers;
$helpers = new Helpers();
$cars = array("Volvo", "BMW", "Toyota");
$helpers->pr($cars);
