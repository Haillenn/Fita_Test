# Fita_Test

**Fita_Test** is a web-based multiple-choice testing application built with Laravel. This project provides a platform for users to create and participate in online quizzes with automatic grading and performance tracking.

---

## 🚀 Features

- **User Authentication**: Register, login, and role-based access control.  
- **Quiz Management**: Admins can create and manage quizzes and questions.  
- **Exam Participation**: Users can take assigned quizzes easily.  
- **Automatic Grading**: Instant scoring after quiz submission.  
- **Results and Statistics**: View performance reports and exam analytics.

---

## 🛠️ Installation

### Requirements

- PHP >= 7.3  
- Composer  
- MySQL or MariaDB  
- Node.js and npm

### Steps

#### 1. Clone the repository

```bash
git clone https://github.com/Haillenn/Fita_Test.git
cd Fita_Test
```

#### 2. Install PHP dependencies

```bash
composer install
```

#### 3. Install JavaScript dependencies

```bash
npm install
npm run dev
```

#### 4. Environment Configuration

Copy the `.env.example` file to `.env`:

```bash
cp .env.example .env
```

Update your `.env` file with database credentials and other configuration values as needed.

#### 5. Generate application key

```bash
php artisan key:generate
```

#### 6. Run database migrations

```bash
php artisan migrate
```

#### 7. Start the development server

```bash
php artisan serve
```

Then open your browser and go to:  
[http://localhost:8000](http://localhost:8000)

---

## 📁 Project Structure

```
app/               # Application logic, including controllers and models
resources/views/   # Blade template views
routes/web.php     # Defines application routes
public/            # Public assets and entry point for the web server
```

---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork this repository.  
2. Create a new branch:

```bash
git checkout -b feature/YourFeature
```

3. Commit your changes:

```bash
git commit -m "Add new feature"
```

4. Push the branch:

```bash
git push origin feature/YourFeature
```

5. Open a Pull Request.

---
