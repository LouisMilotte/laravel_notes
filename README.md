# laravel_notes
Development Notes for Laravel Framework

##Project Creation
*In CLI: laravel new {project name}
*Scaffold Authentication in CLI: php artisan make:auth
*To create migration in CLI: php artisan make:migration create_{table}_table --create={table}
  *See Migrations for writing a migration.
  *Build database in CLI: php artisan migrate
*Make a model in CLI: php artisan make:model --factory {Factory Name}
  *See Factories and Models for writing classes
*Make Seeder in CLI: php artisan make:seeder {table}TableSeeder
  *See Seeders for writing Seeders.
*Push seeds to DB in CLI: php artisan migrate:fresh --seed
*Begin routing, see Routing for how.
*Begin writing UI.
