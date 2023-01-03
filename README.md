
# Laravel 9 Vue 3 Inertia Template

A template to start using Inertia.js with Laravel, Vue.js and Tailwindcss!


## Tech Stack

**Client:** Vue 3, TailwindCSS

**Server:** Laravel 9

**Adapter:** Inertia
<div>
<img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="150" alt="Laravel Logo">
<img src="https://www.phpro.be/uploads/media/170x/01/441-vue.js%404x.png?v=2-0?62b3251db82aa489a7ee194a74cc6fb1" width="150" alt="Vue Js Logo">
<img src="https://tailwindcss.com/_next/static/media/tailwindcss-logotype-white.e0b2bd6155fa0bed8e24ff6b28f4a911.svg" width="150" alt="Tailwind Logo">
</div>



## Screenshots

![App Screenshot](https://i.imgur.com/crfNajo.png)

![App Screenshot](https://i.imgur.com/JFSoCJP.png)

![App Screenshot](https://i.imgur.com/UA4g8Xo.png)
## Installation

Install my-project with npm

```bash
  npm install my-project
  cd my-project
```
Start by cloning the repo

```bash
 git clone https://github.com/hareeshn22/Laravel-9-Vue-3-Inertia-Tailwind

```
Copy the environment file 
```bash
 cp .env.example .env
 ```
Install php dependencies
```bash
 composer install
 ```
Generate the encryption key for Laravel
```bash
 php artisan key:generate
 ```
Install node dependencies
```bash
npm install
 ```
And now... start building something amazing!
    
## Usage/Examples

Create or Edit Vue Pages like this!
```vue
<script setup>
import AuthLayout from "@/Layouts/AuthLayout.vue";
import { Head } from "@inertiajs/inertia-vue3";
</script>

<template>
  <Head title="Team" />

  <AuthLayout>
    <template #header>
      <div class="mx-auto max-w-7xl py-6 px-4 sm:px-6 lg:px-8">
        <h1 class="text-3xl font-bold tracking-tight text-gray-900">Team</h1>
      </div>
    </template>

    <div class="py-12">
      <div class="max-w-7xl mx-auto sm:px-6 lg:px-8">
        <div class="bg-white overflow-hidden shadow-sm sm:rounded-lg">
          <div class="p-6 text-gray-900">You're in Team Page!</div>
        </div>
      </div>
    </div>

    <div class="mx-auto max-w-7xl py-6 sm:px-6 lg:px-8">
      <!-- Replace with your content -->
      <div class="px-4 py-6 sm:px-0">
        <div class="h-96 rounded-lg border-4 border-dashed border-gray-200" />
      </div>
      <!-- /End replace -->
    </div>
  </AuthLayout>
</template>

```




## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

You may also try the [Laravel Bootcamp](https://bootcamp.laravel.com), where you will be guided through building a modern Laravel application from scratch.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains over 2000 video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.


## License

The template is licensed under the [MIT license](https://opensource.org/licenses/MIT).
