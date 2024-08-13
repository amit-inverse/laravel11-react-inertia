```
composer create-project laravel/laravel laravel11-react-inertia
```

```
composer require laravel/breeze --dev
php artisan breeze:install
    - react
    - dark
    - default
```

```
serve terminal  -- php artisan serve
vite terminal   -- npm run dev
tinker terminal -- php artisan tinker
artisan terminal
```

```
php artisan make:model Project -fm
php artisan make:model Task -fm
... ... ...
php artisan migrate --seed
php artisan migrate:refresh --seed
```

```
\App\Models\Project::count()
\App\Models\Task::count()
\App\Models\Task::query()->paginate(5)->all()
```

```
php artisan make:controller ProjectController --model=Project --requests --resource
php artisan make:controller TaskController --model=Task --requests --resource
php artisan make:controller UserController --model=User --requests --resource
```

```
php artisan route:list
```

```
php artisan make:resource ProjectResouce
php artisan make:resource TaskResouce
```

```
php artisan make:resource UserResource
```

```
npm install @heroicons/react -S
```
