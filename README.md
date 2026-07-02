# 3DwithEase V2

> **Advanced E-commerce Platform for 3D Products**

An enhanced version of the 3DwithEase e-commerce platform, built with Laravel 12 to provide a seamless shopping experience for 3D models, designs, and digital assets.

---

## 🎯 Overview

3DwithEase V2 is a modern e-commerce platform specifically designed for the 3D product market. This version represents a significant improvement over its predecessor, featuring better performance, enhanced user experience, and robust architecture.

---

## ✨ Key Features

- 🛒 **Complete E-commerce Solution** - Full shopping cart, checkout, and payment processing
- 🎨 **3D Product Showcase** - Optimized display and preview of 3D models
- 👥 **User Management** - Customer accounts, profiles, and order history
- 💳 **Secure Transactions** - Integrated payment processing and order management
- 📦 **Product Management** - Admin dashboard for inventory and catalog management
- 🔐 **Authentication & Authorization** - Secure user authentication and role-based access
- 🗄️ **Database-driven** - Scalable database architecture with migrations
- ⚡ **Real-time Features** - Queue processing for background jobs
- 📱 **Responsive Design** - Mobile-friendly interface

---

## 🛠️ Tech Stack

- **Backend**: [Laravel 12](https://laravel.com) - Modern PHP framework
- **Frontend**: [Vite](https://vitejs.dev) - Next-generation build tool
- **Language**: PHP 8.2+
- **Testing**: PHPUnit, Mockery
- **Code Quality**: Laravel Pint for code formatting
- **Development**: Laravel Sail for containerized development

---

## 📋 Requirements

- PHP 8.2 or higher
- Composer
- Node.js & npm
- Database (MySQL, PostgreSQL, SQLite, etc.)

---

## 🚀 Quick Start

### 1. Clone the Repository
```bash
git clone https://github.com/MegIv/3DwithEase_V2.git
cd 3DwithEase_V2
```

### 2. Install Dependencies
```bash
composer install
npm install
```

### 3. Environment Setup
```bash
cp .env.example .env
php artisan key:generate
```

### 4. Database Setup
```bash
php artisan migrate
```

### 5. Build Assets
```bash
npm run build
```

### 6. Start Development Server
```bash
php artisan serve
```

The application will be available at `http://localhost:8000`

---

## 🧑‍💻 Development

### Running the Full Development Environment
```bash
composer run dev
```

This command runs:
- Laravel development server
- Queue listener
- Log viewer (Pail)
- Vite build watcher

All processes run concurrently for seamless development.

### Running Tests
```bash
composer test
```

Tests are configured in `phpunit.xml`

### Code Formatting
```bash
./vendor/bin/pint
```

---

## 📁 Project Structure

```
3DwithEase_V2/
├── app/              # Application code (Controllers, Models, etc.)
├── bootstrap/        # Framework bootstrap
├── config/           # Configuration files
├── database/         # Migrations, seeders, and factories
├── public/           # Public assets and entry point
├── resources/        # Views, CSS, and JavaScript
├── routes/           # Route definitions
├── storage/          # Logs, uploads, and cache
├── tests/            # Test files
├── artisan           # Artisan CLI
├── composer.json     # PHP dependencies
├── package.json      # JavaScript dependencies
└── vite.config.js    # Vite configuration
```

---

## 🔄 Available Commands

| Command | Description |
|---------|-------------|
| `composer setup` | Complete project setup (install, env, migrate, build) |
| `composer dev` | Start development environment with all services |
| `composer test` | Run PHPUnit tests |
| `php artisan migrate` | Run database migrations |
| `php artisan tinker` | Interactive PHP shell for the application |
| `php artisan queue:listen` | Listen for queued jobs |
| `npm run build` | Build production assets |
| `npm run dev` | Start Vite dev server |

---

## 🗄️ Database

This project uses Laravel migrations for database management. Supported databases:
- MySQL
- PostgreSQL  
- SQLite
- SQL Server

Configure your database in `.env`:
```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=3dwithease
DB_USERNAME=root
DB_PASSWORD=
```

---

## 🧪 Testing

The project includes PHPUnit for automated testing:

```bash
# Run all tests
composer test

# Run tests with coverage
php artisan test --coverage
```

---

## 📝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

Please ensure your code passes all tests and follows Laravel best practices.

---

## 🔒 Security

For security vulnerabilities, please email the maintainer privately rather than using the issue tracker.

---

## 📄 License

This project is open-source software licensed under the [MIT License](https://opensource.org/licenses/MIT).

---

## 👤 Author

**MegIv**
- GitHub: [@MegIv](https://github.com/MegIv)

---

## 🤝 Support

For issues, feature requests, or questions:
- [Open an Issue](https://github.com/MegIv/3DwithEase_V2/issues)
- [Start a Discussion](https://github.com/MegIv/3DwithEase_V2/discussions)

---

## 📚 Learn More

- [Laravel Documentation](https://laravel.com/docs)
- [Vite Documentation](https://vitejs.dev)
- [Composer Documentation](https://getcomposer.org/doc)

---

**Made with ❤️ by MegIv**