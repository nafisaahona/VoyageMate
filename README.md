# Voyage Mate

Simple Laravel + Inertia.js project for managing trips, destinations, itineraries, and reviews.

## Requirements

- PHP 8.1+
- Composer
- Node.js 16+
- npm or pnpm

## Quick start

1. Install PHP dependencies:

   composer install

2. Copy environment and generate app key:

   cp .env.example .env
   php artisan key:generate

3. Install JS dependencies and build assets:

   npm install
   npm run dev

4. Run database migrations and seeders:

   php artisan migrate --seed

5. Run the app (built-in server):

   php artisan serve

6. Run tests:

   ./vendor/bin/phpunit

## Notes

- This repository was pushed from a local copy — confirm/update `.env` values (DB, mail, etc.) before deploying.
- Adjust Node build commands if you use `pnpm` or a different package manager.

## Contributing

PRs are welcome — open an issue first to discuss larger changes.

## License

MIT
