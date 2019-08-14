# php-fileStreamer

php-fileStreamer is a php class that helps you to stream your file via php server & control the flow,

# How to use:
```
include "FileStreamer.php";

$filePath = "path of the your file here";
$config = [

];

$stream = new FileStreamer($filePath, $config);
$stream->start();

```
I hope that will help some one.