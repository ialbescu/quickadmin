## Requirements
* Laravel `^5.2` - Because of changed routing middleware and unsupported package `illuminate/html`

### Laravel 5.1.11 users info!
To use Quickadmin with Laravel Laravel 5.1.11 use branch `0.4.x`

## Quick Admin installation

###Please note: QuickAdmin requires fresh Laravel installation

1. Clone this repo.
2. Configure your .env file with correct database information
3. Run `composer install`
4. Run `php artisan quickadmin:install` and fill the required information.
5. Run `php artisan key:generate` to generate key.
5. Access QuickAdmin panel by visiting `http://yourdomain/admin`.
