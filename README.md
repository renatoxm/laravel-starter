# Laravel 11 Starter Project

Laravel 11 Starter project

## Stack

[![Laravel](https://img.shields.io/badge/laravel-%23FF2D20.svg?style=for-the-badge&logo=laravel&logoColor=white)](https://laravel.com/docs/11.x)
[![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)
[![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)
[![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)

## Features

- [x] 📏 [ESLint — To find and fix problems in your code](https://eslint.org/)
- [x] 💖 [Prettier — Code Formatter for consistent style](https://prettier.io/)
- [x] 🐶 [Husky — For running scripts before committing](https://typicode.github.io/husky/)
- [x] 🚓 [Commitlint — To make sure your commit messages follow the convention](https://commitlint.js.org/)
- [x] 🚫 [lint-staged — Run ESLint and Prettier against staged Git files](https://github.com/lint-staged/lint-staged)
- [x] 🗲 [Pretty-quick - Runs prettier on git changed files](https://github.com/prettier/pretty-quick)
- [x] 🔍 [Laravel IDE Helper - Generates helper files that enable your IDE to provide accurate autocompletion](https://github.com/barryvdh/laravel-ide-helper)
- [x] 🍺 [Laravel Pint - An opinionated PHP code style fixer for minimalists](https://laravel.com/docs/11.x/pint)
- [x] ⚗️ [PHP Stan and Larastan - finding errors in your php code](https://github.com/larastan/larastan)
- [x] 😸 Github CI/CD workflow - Enforcing code formatting on pull requests
- [x] 🤖 [Dependabot - automating the dependency update process](https://docs.github.com/en/code-security/getting-started/dependabot-quickstart-guide)
- [x] ⌨️ .vscode settings - Auto formating options

## Instalation

- Clone the repo
- Run composer install & npm install commands
- Run migrations

```sh
composer i
npm i
artisan migrate
```

## Commands

- [Laravel IDE Helper](#laravel-ide-helper)
- [Commitzen](#commitzen)
- [PHP Stan](#php-stan)
- [Laravel Pint](#laravel-pint)

### Laravel IDE Helper

Re-generate the docs yourself

```sh
sail artisan ide-helper:generate
```

Automatic PHPDocs for models

```sh
sail artisan ide-helper:models
```

### Commitzen

Using commitzen instead of git commit -m "something"

```sh
git cz
```

### PHP Stan

Run PHP Stan

```sh
composer analyse
```

### Laravel Pint

Format Laravel code

```sh
composer format
```

## License

This project is licensed under the MIT license, Copyright (c) 2023 Renato Nabinger. For more information see the [LICENSE](LICENSE.md) file.
