# laravel_notes
Development Notes for Laravel Framework

## Project Creation

* In CLI: laravel new {project name}
* Scaffold Authentication in CLI: php artisan make:auth
* To create migration in CLI: php artisan make:migration create_{table}_table --create={table}
  * See Migrations https://laravel.com/docs/5.6/migrations.
  * Build database in CLI: php artisan migrate
* Make a model in CLI: php artisan make:model --factory {Factory Name}
  * See Factories: https://laravel.com/docs/5.6/database-testing#writing-factories
  * See Models: https://laravel.com/docs/5.6/eloquent
* Make Seeder in CLI: php artisan make:seeder {table}TableSeeder
  * See Seeders https://laravel.com/docs/5.6/seeding#writing-seeders.
* Push seeds to DB in CLI: php artisan migrate:fresh --seed
* Begin routing
 * Routing: https://laravel.com/docs/5.6/routing.
* Begin writing UI.
 * Blades: https://laravel.com/docs/5.6/blade
