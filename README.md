# laphpperfoptimization

## 1. Optimization Basics
### 3 General optimization techniques and tools
```
$_SERVER['REQUEST_TIME_FLOAT'] //The unix timestamp of start of the request with microsecond precision.
```

Some techniques:
- Add expires headers.
- In effect, its giving your users a local cache of pieces of content of your site.
The fastest content to serve is the content that doesnot even need to be served.


### 4 The path from your server to their browser

##### The HTTP request cycle


DNS to request to response to render



## 2. PHP and Xdebug
### 2 Xdebug: Stack traces
For example cakePHP
```
localhost:8765/pages/stack
```
### 3 Xdebug: Function traces
```
localhost:8765/pages/function
```

## 6. Haedware Up and Out
### 1 From one single server to service servers
Web server - Handles serving PHP-driven content
Database server - Handles database engine and queries
