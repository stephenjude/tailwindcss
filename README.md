# Laravel 7.0+ Frontend preset for Tailwind CSS

A Laravel front-end scaffolding preset for [Tailwind CSS](https://tailwindcss.com) - a Utility-First CSS Framework for Rapid UI Development.


# Usage
add this line into **composer.json** on your laravel project
```
...

"repositories": [
    {
        "type": "vcs",
        "url": "https://github.com/yaelahan/tailwindcss"
    }
],
...
```

and then run 

> composer require laravel-frontend-presets/tailwindcss:dev-alternate-universe --dev


to install tailwindcss with auth scalfolding run
> php artisan ui tailwindcss-auth

OR

you can just install tailwindcss wihtout auth scalfolding
> php artisan ui tailwindcss
