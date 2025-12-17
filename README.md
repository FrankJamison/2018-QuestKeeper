# QuestKeeper Character Tracker

QuestKeeper is a web-based Dungeons & Dragons 5e character manager, originally created for the 2018 UC Davis WEB515 course: Creating Web Applications with AJAX.

## Features
- Create, edit, and manage D&D 5e characters
- Store character stats, backgrounds, classes, races, and more
- User registration and authentication
- AJAX-powered character data retrieval and updates
- Responsive design with HTML, CSS, JavaScript, and PHP
- MySQL database backend

## Project Structure
- `index.php` — Main entry point
- `members/` — Character management and user pages
- `includes/` — PHP includes for logic and configuration
- `js/` — JavaScript for AJAX and UI logic
- `css/` — Stylesheets
- `images/` — Project images
- `questkeeper.sql` — MySQL database schema and sample data

## Setup
1. Import `questkeeper.sql` into your MySQL database (use utf8mb4 charset).
2. Configure your database connection in the PHP includes (see `constants.inc.php`).
3. Place the project files in your web server's root directory (e.g., XAMPP `htdocs`).
4. Access the site in your browser (e.g., `http://localhost/2018-QuestKeeper`).

## Requirements
- PHP 5.6+
- MySQL 5.6+
- Web server (Apache recommended)
- Modern browser

## Credits
Created by Frank Jamison for UC Davis WEB515 (2018).

---
*This project was an academic exercise and is provided as-is for learning and demonstration purposes.*
