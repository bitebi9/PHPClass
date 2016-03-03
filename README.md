Bitebi9 API PHP Class
===========

PHP wrapper for [Bitebi9.com](https://www.bitebi9.com/) for use with the [Bitebi9.com API](https://www.bitebi9.com/pages/api). Simple abstraction layer on top of existing API interfaces, and automatic JSON decoding on response.

Pull requests accepted and encouraged. :)

### Usage

First, sign up for an account at [Bitebi9.com](https://www.bitebi9.com/) and request an API key under Account > Settings

Download and include the Bitebi9API.php class:

~~~
require_once 'path/to/Bitebi9API.php';
~~~

Instantiate the class and set your API key and API Secret.

~~~
$apiKeys = array('key' => 'API_KEY_HERE', 'secret' => 'API_SECRET_HERE');

$api = new \Bitebi9\Bitebi9API($apiKeys);
