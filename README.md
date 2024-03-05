# TDD + API

## Features

- CRUD operations for managing resources
- Features Tests

## Prerequisites

Before you begin, ensure you have met the following requirements:
- Git installed on your local machine.
- Docker installed on your local machine.
- Docker Compose installed on your local machine.

## Installation

1. Clone the repository:
   ```bash
   git clone git@github.com:caiostarke/tdd-laravel.git

2. cd the project:
   ```bash
   cd [project-name]

3. Start the Docker containers using Laravel Sail:
   ```bash
   ./vendor/bin/sail up -d

4. Install PHP dependencies:
   ```bash
   ./vendor/bin/sail composer install

5. Generate application key:
   ```bash
   ./vendor/bin/sail artisan key:generate

6. Run database migrations and seeders:
   ```bash
   ./vendor/bin/sail artisan migrate --seed
