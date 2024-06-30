# Laravel Strict

The skeleton application for the Laravel framework with built-in strict typing, enhanced code quality tools, and safety features.

## Features

-   **Git Hooks Pre-commit Setup**

    -   Utilize Husky to enforce code quality checks with [Laravel Pint](https://laravel.com/docs/11.x/pint), [PHPStan](https://phpstan.org/), [Rector](https://getrector.com/), and [PestPHP](https://pestphp.com/) during pre-commit.

-   **GitHub Actions Integration**

    -   Automated workflows for continuous integration, running Laravel Pint, and PHPStan on every push and pull request.

-   **Eloquent Strict Mode**

    -   Enforce strict mode in Eloquent ORM for improved data integrity and error detection. [Learn More](https://laravel-news.com/shouldbestrict)

-   **Prevent Destructive Commands**
    -   Safeguard the application by preventing the execution of destructive commands in production environments. [Learn More](https://laravel-news.com/prevent-destructive-commands-from-running-in-laravel-11)

## Installation

Clone the Repository

```bash
git clone https://github.com/PyaeSoneAungRgn/laravel-strict.git
```

Setup Husky

```
npm install
```
