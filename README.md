# ContentHub CMS

Modern CMS and REST API platform built with Symfony 6, EasyAdmin and MySQL.

## Overview

ContentHub CMS is a modern content management system developed with Symfony 6.
The application allows administrators to manage blog articles, categories, comments, media uploads and API resources through a secure and scalable architecture.

This project was developed as part of an advanced backend learning process focused on Symfony ecosystem, REST API development and enterprise web application architecture.

---

## Main Features

### Authentication & Security

* Secure user authentication
* Role and permission management
* Protected administration area

### Content Management

* Create, edit and delete blog articles
* Category management
* Dynamic content administration
* Image upload and media management

### REST API

* RESTful API endpoints
* JSON responses
* API testing with Postman
* CRUD operations through API controllers

### Administration

* Modern admin dashboard using EasyAdmin
* Entity management
* Optimized backend workflow

### Additional Features

* Comment system
* Doctrine ORM relationships
* DataFixtures for test data
* Event Listeners implementation
* Responsive UI with Bootstrap 5

---

## Technologies Used

* PHP 8
* Symfony 6
* Doctrine ORM
* MySQL
* Twig
* EasyAdmin
* Bootstrap 5
* REST API
* DataFixtures
* Event Listeners
* Git & GitHub

---

## Learning Objectives

This project allowed me to strengthen my skills in:

* Symfony architecture
* MVC design pattern
* REST API development
* Doctrine entity relationships
* Backend administration
* Secure authentication systems
* Clean backend development practices

---

## Installation

Clone the repository:

```bash
git clone https://github.com/wince-webdev/ContentHub-CMS.git
```

Install dependencies:

```bash
composer install
npm install
```

Configure environment variables:

```bash
cp .env .env.local
```

Run database migrations:

```bash
php bin/console doctrine:migrations:migrate
```

Load fixtures:

```bash
php bin/console doctrine:fixtures:load
```

Start the development server:

```bash
symfony server:start
```

---

## Project Status

Project completed and continuously improved for backend practice and API architecture learning.

---

## Author

**Winceslas ADJIHANOU**
Full Stack PHP Developer — Symfony & Laravel
