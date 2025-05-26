# Inscription-Registration

# 🧾 Form Validation with Dynamic Asterisk

This is a responsive registration form built with **HTML**, **Bootstrap 5**, and enhanced with **JavaScript** and **PHP (PDO)** for real-time validation and secure user insertion into a **MySQL database**.

## 🚀 Features

- Responsive form layout using Bootstrap 5.
- Real-time input validation using the `input` event.
- A red asterisk appears next to required fields if empty.
- Clean and organized HTML and CSS structure.
- Dynamically scalable to work with multiple inputs.

## 🧩 Technologies Used

- HTML5
- CSS3
- Bootstrap 5
- JavaScript (Vanilla)
- PHP 8+
- MySQL
- PDO (PHP Data Objects)


### 🔴 Frontend (index.html + JavaScript)
- Each required input field is monitored by JavaScript.
- When a field is empty, a red asterisk appears next to its label.
- Once the user starts typing, the red asterisk disappears automatically.

### 🟢 Backend (insert.php)
- PHP script collects submitted form data via POST.
- Uses PDO and prepared statements to prevent SQL injection.
- Validates fields before inserting into a MySQL database.

