# AWS SDK for PHP

Pulling in the code via a shell command in the modman file isn't optimal, but "good enough" :)
Since the autoloader is registered with the prepend parameter you can simple require_once the file like this:
 
```
require_once 'lib/AwsSdk/autoload.php';
```