# 🎓 PhD Task Manager – Laravel Project

This is a Laravel-based web application designed to help PhD students effectively manage their academic workflow. The system provides tools for organizing research materials, tracking upcoming academic events, managing research ideas, and logging teaching or administrative duties.

## 🚀 Features

- 📚 **Resource Manager**: Upload and organize PDF documents (e.g., research papers, thesis references).
- 📅 **Upcoming Events Tracker**: Track conferences, seminars, workshops, and deadlines.
- 💡 **Idea Box**: Store and manage research ideas with tags and status.
- 🧑‍🏫 **Teaching & Duty Log**: Record academic responsibilities such as lectures (TP, TD), exam supervision, and vacations.

## 🛠️ Built With

- [Laravel](https://laravel.com/) – PHP web framework
- [Tailwind CSS](https://tailwindcss.com/) – Utility-first CSS framework
- [MySQL / SQLite] – Relational database
- [Blade](https://laravel.com/docs/blade) – Laravel templating engine

## ⚙️ Installation

```bash
git clone https://github.com/Gasbiachraf/AcademicTaskManager.git
cd AcademicTaskManager
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
