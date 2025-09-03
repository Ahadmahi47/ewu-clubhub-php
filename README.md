# EWU ClubHub — PHP + MySQL (XAMPP)

A simple club and event management system for East West University.

## Features
- Auth (Register/Login)
- Clubs CRUD (Admin)
- Membership requests + approvals (Admin/Officer)
- Events CRUD (Admin/Officer)
- Event registrations

## Quickstart (Windows + XAMPP)
1. Copy `ewu-clubhub-php/` to `C:\xampp\htdocs\`
2. Start Apache & MySQL in XAMPP
3. Create DB `ewu_clubhub` in phpMyAdmin and Import `database/ewu_clubhub.sql`
   - Or hit `http://localhost/ewu-clubhub-php/seed_admin.php` once
4. Open `http://localhost/ewu-clubhub-php/`
5. Admin: admin@ewu.edu / admin123

## Tech
PHP 8, MySQL (MariaDB), MySQLi (prepared statements), Bootstrap 5
