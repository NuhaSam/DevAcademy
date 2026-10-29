# DevAcademy | Laravel Landing Page

A simple, fast, and fully responsive landing page for a Laravel development academy. This project demonstrates backend integration with a dynamic database seeder and factory setup, combined with a clean and minimalistic front-end design.

## 🚀 Features
- **Dynamic Content:** Courses are fetched dynamically from the database using Laravel Blade templates.
- **Robust Backend:** Pre-configured with a custom `CourseSeeder` and `CourseFactory` for immediate testing.
- **Fast & Minimalist UI:** Styled efficiently using a classless CSS framework combined with CSS Grid for a fully responsive layout.
- **Modern Tech Stack:** Powered by Laravel, Vite, and PHP.

## 🛠️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/NuhaSam/DevAcademy.git

   ```

2. **Install dependencies:**
   ```bash
   composer install
   npm install
   ```

3. **Environment Setup:**
   - Copy `.env.example` to `.env`
   - Configure your database settings inside `.env`
   - Generate app key:
     ```bash
     php artisan key:generate
     ```

4. **Database & Seeding:**
   ```bash
   php artisan migrate --seed --class=CourseSeeder
   ```

5. **Run the Application:**
   - Compile assets: `npm run dev` or `npm run build`
   - Start local server: `php artisan serve`
