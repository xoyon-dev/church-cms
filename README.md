![Company Logo](public/images/CROW.svg)
# Church CMS Project

## 🙏 Welcome

Welcome to the official CMS project for our church! This Laravel-based web application aims to keep our church members informed about services, events, sermons, and small groups.

## 📋 Project Description

**Objective:** To inform current church members about the church itself, its events, sermons, and small groups.

**Primary Audience:** Church members.

### Content Features
- ✅ Full church name
- 📍 Temple address
- 📅 Available services and events with their schedules
- 📖 Statement of faith or church doctrine (mission, vision, or values)
- 🎧 Resources such as sermons and Bible studies
- 📞 Contact information

### Functionality
- 📝 Contact form for prayer requests, questions, or comments
- ✋ Form to confirm participation in events

### Design
- 🎨 Modern and minimalist design
- 🎨 Church colors:
    - `#d6a21e` - Yellow
    - `#895301` - Brown

## 🚀 Development Setup

### Prerequisites
- PHP >= 8.1
- Composer
- Node.js & npm
- MySQL/PostgreSQL/SQLite

### Installation

1. **Clone the repository:**
```bash
git clone https://github.com/your-username/iglesia-website.git
cd iglesia-website
```
2. **Install PHP dependencies:**
```bash
composer install
```
3. **Install Node.js dependencies:**
```
npm install
```
4. **Environment setup:**
```
cp .env.example .env
php artisan key:generate
```
5. **Configure database: Edit .env file with your database credentials:**
```  
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=iglesia_website
DB_USERNAME=your_username
DB_PASSWORD=your_password
```
6. **Run migrations:**
```
php artisan migrate
```
7. **Seed database:**
```
php artisan db:seed
```
8. **Build assets:**
```
npm run dev
```
9. **Start development server:**
```
composer run dev
```
Visit http://localhost:8000 to see the application.

## 🤝 How to Contribute
We welcome contributions from our community! 
### Getting Started
1. **Fork the repository**
2. **Create a feature branch**
```
git checkout -b feature/nueva-funcionalidad
```
3. **Make your changes**
4. **Commit your changes**
```
git commit -m "Add: nueva funcionalidad para eventos"
```
5. **Push to your fork**
```
git push origin feature/nueva-funcionalidad
```
6. **Create a Pull Request**

### Contribution Guidelines
- 📝 Write clear, descriptive commit messages 
- 🧪 Add tests for new functionality 
- 📚 Update documentation when needed 
- 🎨 Follow the existing code style 
- 🔍 Ensure your code passes all tests

### Code Style
- Use meaningful variable and function name
- Keep functions small and focused

### Testing
```
# Run PHP tests
php artisan test

# Run PHP tests
npm run test
```
## 👥 Team
- Miguel 

## 📞 Support
If you encounter any issues or have questions, please:

- Create an issue on GitHub
- Contact the development team
- Check the documentation

## 📄 License
This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments
Thank God, you to all contributors and church members who support this project.

**Made with ❤️ for our Rey de reyes church community in Totonicapán**
