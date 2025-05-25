# 💼 Job Board for Internships

A mini job listing and internship application portal built using **HTML**, **CSS**, **SQL**, and **PHP**. This project allows users to view internship opportunities and apply, while an admin can manage job listings.

---

## 🚀 Demo

[🌐 Live Preview Link (if hosted)](https://your-live-link.com)

![Job Board Screenshot](screenshots/homepage.png)

---

## 🧰 Tech Stack

- **Frontend:** HTML5, CSS3
- **Backend:** PHP (Core PHP, no framework)
- **Database:** MySQL
- **Server:** XAMPP / WAMP / Localhost

---

## 📌 Features

### 👤 User Side
- View internship/job listings
- Apply for internships via application form
- Basic responsive design

### 🔐 Admin Side
- Admin login
- Post new job opportunities
- Edit or delete existing job posts
- View applicant list

---

## 🗃️ Database Structure

### `jobs` table
| Field       | Type          |
|-------------|---------------|
| id          | INT (PK)      |
| title       | VARCHAR(100)  |
| company     | VARCHAR(100)  |
| location    | VARCHAR(100)  |
| description | TEXT          |
| date_posted | DATE          |

### `applicants` table
| Field       | Type          |
|-------------|---------------|
| id          | INT (PK)      |
| job_id      | INT (FK)      |
| name        | VARCHAR(100)  |
| email       | VARCHAR(100)  |
| resume      | TEXT          |

### `admin` table
| Field       | Type         |
|-------------|--------------|
| id          | INT (PK)     |
| username    | VARCHAR(50)  |
| password    | VARCHAR(255) |

---

## 🛠️ How to Run the Project Locally

1. **Install XAMPP or WAMP**
   - [Download XAMPP](https://www.apachefriends.org/index.html)

2. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/job-board
