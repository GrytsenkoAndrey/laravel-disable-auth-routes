# laravel-disable-auth-routes
How to disable one or more Auth routes

## 1. Use parameters

You can pass parameters to the route **routes/web.php**

```
Auth::routes(['register' => false]);
```

or multiple of them

```
Auth::routes([
    'register' => false,
    'reset' => false,
    'verify' => false
]);
```
