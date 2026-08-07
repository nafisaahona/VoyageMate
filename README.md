# Voyage Mate

Simple Laravel + Inertia.js project for managing trips, destinations, itineraries, and reviews.

## About

Voyage Mate provides a Laravel backend with an Inertia.js + React (TypeScript) frontend to help users create and manage trips. It includes user authentication (with two-factor support), CRUD for trips, destinations, itinerary items, and reviews, plus seeders and tests for local development.

## Features

- User registration, login, email verification, and two-factor authentication
- CRUD: Trips, Destinations, Itinerary Items, Reviews
- Database seeders and model factories for generating sample data
- Inertia + React TypeScript frontend components and layouts
- PHPUnit tests and GitHub Actions workflows for linting/tests

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
