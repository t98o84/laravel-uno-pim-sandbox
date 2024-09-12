# Laravel UnoPim Sandbox

## Installation
1. Clone the repository
2. Run `cp .env.example .env`
3. Run `./vendor/bin/sail up -d`

[//]: # (4. Run `./vendor/bin/sail artisan migrate`)
5. Run `./vendor/bin/sail artisan unopim:install`
6. Run `./vendor/bin/sail artisan queue:work`
7. Visit `http://localhost` in your browser
