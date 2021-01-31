<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel attempts to take the pain out of development by easing common tasks used in the majority of web projects, such as:

## Todos
    - [ php artisan make:model Todo -m](Membuat model beserta miggrationnnya).
    - [ php artisan make:controller TodosController](Membuat Controller Todo).
    - [ php artisan make:seeder TodosTableSeeder](Membuat Seeder Todo).
        -php artisan db:seed


## Blog - Post
- [ php artisan make:model Post -m](Membuat model Post beserta miggrationnnya).
- [ php artisan make:model Category -m](Membuat model Category beserta miggrationnnya).
- [php artisan make:controller PostsController -r](Membuat controller Post beserta resourcenya).
## Blog - Categories
- [ php artisan make:controller CategoriesController -r](Membuat Controller Categories beserta resourcenya).
- [Menambah notifikasi](https://github.com/CodeSeven/toastr).
## Pindah semua data ke branch blog
- [mulai dari  031 Displaying Categories in form]
-[php artisan migrate:refresh](merollback database migration)
-[php artisan make:seeder UsersTableSeeder](Membuat UsersTableSeeder)
-[php artisan migrate:refresh --seed](Merefresh sekaligus mensending data yang dibuat pada UserTableSeeder)

## Blog - Tags
- [ php artisan make:model Tag -m](Membuat model Tag beserta migrationnya).
- [ php artisan make:migration create_post_tag_table](Membuat migration vipot,  relasi antara tags dan post).
    - php artisan migrate

- [ php artisan make:controller TagsController -r](Membuat Controller Tag beserta resourcenya).

## Blog - Profile
- [ php artisan make:model Profile -m](Membuat model Profile beserta migrationnya).
- [ php artisan migrate:refresh --seed](Merollback migration serta data seedernya).