**Fita_Test**
Fita_Test is a web-based multiple-choice testing application built with Laravel. This project provides a platform for users to create and participate in online quizzes with automatic grading and performance tracking.

🚀 Features
User Authentication: Register, login, and role-based access control.

Quiz Management: Admins can create and manage quizzes and questions.

Exam Participation: Users can take assigned quizzes easily.

Automatic Grading: Instant scoring after quiz submission.

Results and Statistics: View performance reports and exam analytics.

🛠️ Installation
Requirements
PHP >= 7.3
Composer
MySQL or MariaDB
Node.js and npm

Steps
1. Clone the repository
git clone https://github.com/Haillenn/Fita_Test.git
cd Fita_Test

2. Install PHP dependencies
composer install

3.Install JavaScript dependencies
npm install
npm run dev

4.Environment Configuration
Copy the .env.example file to .env:
cp .env.example .env

5. Start the development server
php artisan serve

📁 Project Structure
app/: Application logic, including controllers and models.

resources/views/: Blade template views.

routes/web.php: Defines application routes.

public/: Public assets and the entry point for the web server.

🤝 Contributing
Contributions are welcome! To contribute:

Fork this repository.

Create a new branch: git checkout -b feature/YourFeature

Commit your changes: git commit -m 'Add new feature'

Push the branch: git push origin feature/YourFeature

Open a Pull Request.

