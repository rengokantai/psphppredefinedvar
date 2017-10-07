# psphppredefinedvar
## 2. Introduction
### 4 List of All PHP Predefined Variables
```
$GLOBALS
$_SERVER
$_GET
$_POST
$_FILES
$_REQUEST
$_SESSION
$_ENV
$_COOKIE
$php_errormsg
$HTTP_RAW_POST_DATA
$http_response_header
$argc
$argv
```


## 3. $_ENV
### 3 Demo - Enable Environmant Variables
```
vim /etc/php5/apache2/php.ini
service apache2 restart
```
```
print_r($_ENV['APACHE_RUN_USER']);
```

[diff between $ENV and getenv](https://stackoverflow.com/questions/8798294/getenv-vs-env-in-php)

### 5 $_SERVER : Demo - Root Directory of Given Web Site
```
$_SERVER['DOCUMENT_ROOT']
```

### 6 $_SERVER : Demo - Server IP Address
```
$_SERVER['SERVER_ADDR']
```

### 7 $_SERVER : Demo - Server IP Address
```
$_SERVER['REMOTE_ADDR']
```


### 8 $_SERVER : Demo - Host Name
```
$_SERVER['HTTP_HOST']
```

### 9 $_SERVER : Demo - User Agent Information
```
$_SERVER['HTTP_USER_AGENT']
```
### 10 $_SERVER : Demo - Time Script Was Requested
```
$time = $_SERVER['REQUEST_TIME'];
print date('YmdHis',$time);
```
