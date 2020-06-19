# PHP-CURL-HTTP-CLASS


$url = "https://api.github.com/user";

$http = new CurlHttp();

echo $http->get($url);

print_r($http->getStatusCode());
