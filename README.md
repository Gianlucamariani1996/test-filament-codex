# Testing codex

* Prompt: 
    ```
    this is a new filament 3 project, i would like to add a Product resource with two fields: 
    name and images where images are handled with Spatie Media Library plugin
    ```
* mergiata la modifica proposta, e' necessario comunque eseguire i comandi:
    - `composer update`
    - `php artisan vendor:publish --provider="Spatie\MediaLibrary\MediaLibraryServiceProvider" --tag="medialibrary-migrations"`
    - `php artisan migrate`
