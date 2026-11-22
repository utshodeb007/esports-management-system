# 🎮 Esports Management System

A PHP and MySQL-based web application designed to manage esports tournaments, games, teams, players, matches, and sponsors through a centralized platform.

## 📌 Project Overview

The **Esports Management System** is a web-based project developed to organize and manage esports tournament-related information. It provides dedicated pages for managing games, tournaments, teams, players, matches, and sponsors.

The system uses PHP for backend development and MySQL for database management.

## ✨ Features

- 🎮 Game Management
- 🏆 Tournament Management
- 👥 Team Management
- 🎯 Player Management
- ⚔️ Match Management
- 📊 Match Details and Results
- 🤝 Sponsor Management
- 🗄️ MySQL Database Integration
- 🌐 Dynamic PHP-based Web Pages

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| PHP | Backend Development |
| MySQL | Database Management |
| HTML | Web Page Structure |
| CSS | Styling and Design |
| XAMPP | Local Development Server |
| VS Code | Code Editor |
| Git & GitHub | Version Control |

## 📂 Project Structure

```text
esports-management-system/
│
├── css/
│   └── style.css
│
├── db_connect.example.php
├── db_connect.php
├── esports_management.sql
│
├── header.php
├── footer.php
├── index.php
│
├── games/
│
├── matches.php
├── match_details.php
│
├── players.php
├── player_details.php
│
├── teams.php
├── team_details.php
│
├── tournaments.php
├── tournament_details.php
│
├── sponsors.php
└── sponsor_details.php
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/utshodeb007/esports-management-system.git
```

### 2. Move Project to XAMPP

Copy the project folder into:

```text
xampp/htdocs/
```

### 3. Start XAMPP

Start the following services:

- Apache
- MySQL

### 4. Create Database

1. Open phpMyAdmin.
2. Create a database named `esports_tournament`.
3. Import the `esports_management.sql` file.

### 5. Configure Database Connection

Copy `db_connect.example.php` and rename the copy to `db_connect.php`.

Update the database credentials according to your local XAMPP configuration.

### 6. Run the Project

Open your browser and visit:

```text
http://localhost/esports_01/
```

## 🗄️ Database Tables

The project includes the following database tables:

- `games`
- `tournaments`
- `teams`
- `players`
- `sponsors`
- `matches`
- `match_results`

## 🔒 Security

- Local database credentials are excluded from Git tracking.
- `.gitignore` is used to prevent unnecessary and sensitive files from being uploaded.
- A sample database configuration file is provided.

## 🚀 Future Improvements

- Admin Authentication System
- Tournament Registration
- Advanced Match Scheduling
- Team Performance Statistics
- Improved Dashboard
- Responsive UI Enhancements

## 👨‍💻 Developer

**Utsho Kumar Deb**

Computer Science and Engineering (CSE)

Northern University Bangladesh

## 📜 License

This project is created for educational and learning purposes.

---

⭐ If you find this project interesting, consider giving it a star on GitHub!
