# 🐾 FurryFriend Care - Pet Care Website

A comprehensive pet care service website built with PHP and MySQL that allows users to book appointments for their pets and administrators to manage bookings and user accounts.

## 🌟 Features

### 🏠 Frontend Features
- **Responsive Design**: Mobile-friendly interface built with Bootstrap
- **Service Information**: Detailed information about pet care services
- **Appointment Booking**: Easy-to-use booking system for pet care appointments
- **User Authentication**: Secure login and registration system
- **Contact Information**: Business hours, contact details, and location
- **Service Pricing**: Transparent pricing for various pet care services
- **About Page**: Information about the pet care center
- **Blog Section**: Pet care tips and articles

### 🔧 Admin Dashboard
- **User Management**: View, add, and update user accounts
- **Appointment Management**: View, update, and manage pet appointments
- **Dashboard Analytics**: Overview of total users and appointments
- **Secure Admin Login**: Protected admin area

### 👤 User Dashboard
- **Personal Dashboard**: User-specific appointment management
- **Appointment Booking**: Book new appointments
- **Appointment History**: View past and upcoming appointments
- **Profile Management**: Update personal details

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript, Bootstrap 4
- **Backend**: PHP 7.4+
- **Database**: MySQL/MariaDB
- **Server**: Apache (XAMPP)
- **Libraries**: 
  - Font Awesome (Icons)
  - Owl Carousel (Sliders)
  - Tempus Dominus (Date Picker)
  - jQuery

## 📋 Prerequisites

Before running this project, make sure you have:

- [XAMPP](https://www.apachefriends.org/index.html) (Apache, MySQL, PHP)
- Web browser (Chrome, Firefox, Safari, etc.)
- Text editor or IDE (VS Code, Sublime Text, etc.)

## 🚀 Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/furryriend-care.git
cd furryriend-care
```

### 2. Setup XAMPP
1. Download and install XAMPP
2. Start Apache and MySQL services from XAMPP Control Panel

### 3. Database Setup
1. Open phpMyAdmin (http://localhost/phpmyadmin)
2. Create a new database named `pet-care`
3. Import the database backup:
   - Click on the `pet-care` database
   - Go to the **Import** tab
   - Choose the `pet-care-database-backup.sql` file
   - Click **Go** to import

### 4. File Setup
1. Copy the project folder to `C:\xampp\htdocs\`
2. Update database connection settings in `conn.php` if needed:
   ```php
   $servername = "localhost";
   $username = "root";
   $password = "";
   $dbname = "pet-care";
   ```

### 5. Access the Website
- **Frontend**: http://localhost/pet-care/
- **Admin Login**: http://localhost/pet-care/admin_login.php
- **User Login**: http://localhost/pet-care/user_login.php

## 🔐 Default Login Credentials

### Admin Access
- **Username**: admin
- **Password**: admin

### User Access
Users need to register through the registration page or can be added by admin.

## 📁 Project Structure

```
pet-care/
├── 📄 index.php              # Homepage
├── 📄 about.php              # About page
├── 📄 service.php            # Services page
├── 📄 price.php              # Pricing page
├── 📄 booking.php            # Appointment booking
├── 📄 contact.php            # Contact page
├── 📄 blog.php               # Blog page
├── 📄 register.php           # User registration
├── 📄 user_login.php         # User login
├── 📄 admin_login.php        # Admin login
├── 📄 conn.php               # Database connection
├── 📄 footer.php             # Footer component
├── 📄 thank-you.html         # Thank you page
├── 🗃️ pet-care-database-backup.sql # Database backup
├── 📁 assets/                # CSS, JS, Images, Fonts
├── 📁 backend/
│   ├── 📁 admin/            # Admin dashboard files
│   └── 📁 user/             # User dashboard files
├── 📁 css/                  # Custom stylesheets
├── 📁 js/                   # Custom JavaScript
├── 📁 img/                  # Images
└── 📁 lib/                  # External libraries
```

## 🎯 Usage

### For Users:
1. Register a new account or login with existing credentials
2. Navigate to the booking page
3. Fill in pet details and select appointment date/time
4. Submit the appointment request
5. View appointment status in the user dashboard

### For Admins:
1. Login with admin credentials
2. Access the admin dashboard
3. Manage user accounts and appointments
4. View analytics and reports

## 🔧 Configuration

### Database Configuration
Update the database connection in `conn.php` and `backend/admin/conn.php`:

```php
$servername = "localhost";
$username = "your_db_username";
$password = "your_db_password";
$dbname = "pet-care";
```

### Email Configuration
To enable email notifications, update the email settings in the respective PHP files.

## 🤝 Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 Database Schema

The database includes the following main tables:
- `admin_login` - Admin authentication
- `appointment_table` - Pet appointment bookings
- `login_table` - User authentication and profiles

## 🐛 Known Issues

- Email notifications are not fully implemented
- Some responsive design improvements needed for mobile devices
- Form validation could be enhanced

## 🔮 Future Enhancements

- [ ] Email notification system
- [ ] Online payment integration
- [ ] Pet medical records management
- [ ] Calendar view for appointments
- [ ] SMS notifications
- [ ] Multi-language support
- [ ] Dark mode theme


## 👥 Authors

- **Jeet Kayasth** 

## 🙏 Acknowledgments

- Bootstrap team for the responsive framework
- Font Awesome for the icons
- XAMPP team for the development environment
- Pet care industry for inspiration



---
⭐ **Star this repository** if you found it helpful!