<p align="center"><img src="/art/logo.svg" alt="Logo Laravel Breeze"></p>

<p align="center">
    <a href="https://packagist.org/packages/laravel/breeze">
        <img src="https://img.shields.io/packagist/dt/laravel/breeze" alt="Total Downloads">
    </a>
    <a href="https://packagist.org/packages/laravel/breeze">
        <img src="https://img.shields.io/packagist/v/laravel/breeze" alt="Latest Stable Version">
    </a>
    <a href="https://packagist.org/packages/laravel/breeze">
        <img src="https://img.shields.io/packagist/l/laravel/breeze" alt="License">
    </a>
</p>

## Introduction

Breeze provides a minimal and simple starting point for building a Laravel application with authentication. Styled with Tailwind, Breeze publishes authentication controllers and views to your application that can be easily customized based on your own application's needs.

Laravel Breeze is powered by Blade and Tailwind. If you're looking for a more robust Laravel starter kit that includes two factor authentication, Livewire / Inertia support, and more, check out [Laravel Jetstream](https://jetstream.laravel.com).

Getting started couldn't be easier:

```bash
laravel new my-app

cd my-app

composer require laravel/breeze --dev

php artisan breeze:install
```