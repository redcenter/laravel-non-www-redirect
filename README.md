# Laravel non-WWW Redirect

Simple package to redirect non-www domains to www in your Laravel application.

# Install
##### Install with composer
```
$ composer require redcenter/laravel-non-www-redirect
```

# Adding middleware
Add the middleware class to your Kernel.php in App\Http:
```
    protected $middlewareGroups = [
        'web' => [
            ...
            LaravelNonWwwRedirectMiddleware::class,
            ...
        ],
    ];
```

## Questions?
You can contact me through my website: redcenter.nl

##### Good bye!

Check out the documentation on Bitbucket for all details!

https://bitbucket.org/redcenter/laravel-non-www-redirect
