

<h1 align="center">
  Lumen phpunit Test
</h1>

<h3 align="center">
    Project made for study purposes and understand how PHPUnit and TDD works.
</h3> 



:bulb: Quick Start

```
composer install
```
<br>

:bulb: CRUD 
```
$router->get('/users','UserController@getUsers');
$router->post('/users','UserController@postUser');
$router->get('/users/{id}','UserController@getUser');
$router->put('/users/{id}','UserController@putUser');
$router->delete('/users/{id}','UserController@deleteUser');
```

```
vendor/bin/phpunit --testdox
```




