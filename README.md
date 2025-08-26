# 🐶 Dog Breed App

A Laravel + Inertia.js (Vue 3) application that allows users to browse dog breeds, like/unlike them (with a max of 3 likes), and view other users' liked dogs.

---

## 🚀 Features

- ✅ User Authentication (Laravel Breeze)
- 📸 Browse dog breeds with images
- ❤️ Like/unlike dog breeds (limit of 3 likes per user)
- 👥 View other users and their liked dogs
- ⚡ Built with Laravel, Vue 3, Inertia.js, Tailwind CSS
- 🗃️ Eloquent many-to-many relationship for liked dogs

---

## 🛠 Requirements

- PHP 8.1+
- Composer
- Node.js (v16+)
- NPM or Yarn
- MySQL/PostgreSQL/SQLite
- Laravel 10+

---

## 📦 Installation (Local Setup)


```bash
git clone git@github.com:iannavs1991/dog-breed-app.git
cd dog-breed-app
```

composer install

cp .env.example .env

DB_DATABASE=dog_breed_app
DB_USERNAME=root
DB_PASSWORD=your_password

php artisan key:generate


php artisan migrate
php artisan db:seed


npm install


npm run dev


php artisan serve

