# Wine Store Laravel / GraphQL Example

## Setting up the Laravel PHP Project

The first step to create a Laravel project is to run the following command in a terminal:

```shell
composer create-project --prefer-dist laravel/laravel winestore
```

I added a new project on GitHub and called it Wine Store, I then added all the project files to the repo

```shell
git init
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/charlpcronje/winestore.git
git push -u origin main
```

## Creating the Wine Store Model

_Creating the Model and the Migration Script_

```shell
# make sure you run it from the winestore directory
php artisan make:model Wine -m
```

This command will create the `Wine` model and, thanks to the `-m` flag, a migration script for database persistence.#   l u m i n . w i n e s t o r e . e x a m p l e  
 