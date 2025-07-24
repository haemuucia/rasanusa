# [ON GOING PROJECT] Rasanusa - Indonesian Food Ordering Website

Did you know that many local Indonesian dishes are still difficult to discover and access online, especially for people outside their region? While global food apps focus mostly on popular fast food or mainstream restaurants, **thousands of authentic Indonesian meals from small, local sellers remain underrepresented and underserved**. **Rasanusa** aims to **digitally connect local food vendors and traditional Indonesian cuisine with a wider audience** through a seamless and accessible food ordering platform. By empowering users to easily browse, order, and pay for diverse regional dishes, we’re helping preserve culinary heritage while boosting small food businesses across the archipelago. **Rasanusa** is a Laravel-based web application for ordering authentic Indonesian cuisine. It allows users to browse a variety of traditional dishes from across Indonesia, add them to a cart, place orders, and manage their purchase history.

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

## Screenshots

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
