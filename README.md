# Module Stubs

## Introduction

When creating a new model, controller, component they are all generated from stubs. This repository replaced the default stubs with customised versions. Mainly dropping docblocks from classes.
    
To replace the default stubs with the ones contained within this package open config/modules.php 

>If you don't have this file ensure you're published laravel-modules config file with this command php artisan vendor:publish --provider="Nwidart\Modules\LaravelModulesServiceProvider"

Find:

```php
'path' => base_path() . '/vendor/nwidart/laravel-modules/src/Commands/stubs',
```

Replace with

```php
'path' => base_path() . '/vendor/laravel-modules-com/module-stubs/src/stubs',
```
