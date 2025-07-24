# Rasanusa - Indonesian Food Ordering Website

**Rasanusa** is a Laravel-based web application for ordering authentic Indonesian cuisine. It allows users to browse a variety of traditional dishes from across Indonesia, add them to a cart, place orders, and manage their purchase history — all from an intuitive and responsive interface.

## Features

- User authentication & registration
- Add to cart & place orders
- Menu browsing by category or search
- Integrated Xendit payment gateway
- Order history & transaction tracking
- Admin dashboard powered by Filament
- Real-time interactivity with Laravel Livewire

## Tech Stack

| Layer        | Technology             |
|--------------|------------------------|
| Backend      | Laravel 10             |
| Frontend     | Blade, Livewire        |
| Styling      | Bootstrap              |
| Admin Panel  | Filament               |
| Payment      | Xendit                 |
| Database     | MySQL                  |

---

## Screenshots (Optional)

[COMING SOON]

---

## Installation

```bash
# Clone the repository
git clone https://github.com/haemuucia/rasanusa.git
cd rasanusa

# Install PHP dependencies
composer install

# Install JavaScript dependencies
npm install && npm run dev

# Copy .env and configure your environment
cp .env.example .env

# Generate application key
php artisan key:generate

# Set up your database
php artisan migrate --seed

# Run the application
php artisan serve