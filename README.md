# Wheelify - Vehicle Listing Platform

![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)

Wheelify is a Django-based web application for listing and browsing vehicles. The platform allows users to create accounts, list vehicles for sale, browse listings, and save their favorite vehicles.

## Features

- 🔐 User Authentication (Register, Login, Logout)
- 🚗 Create and manage vehicle listings
- ❤️ Save favorite listings
- 🔍 Advanced filtering for vehicle searches
- 📱 Responsive design with Bootstrap 4
- 📱 Media file handling for vehicle images

## Prerequisites

- Python 3.8+
- pip (Python package installer)
- Virtual Environment (recommended)

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/wheelify.git
   cd wheelify
   ```

2. **Create and activate a virtual environment**
   ```bash
   # Windows
   python -m venv venv
   .\venv\Scripts\activate
   
   # macOS/Linux
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install dependencies**
   ```bash
   cd src
   pip install -r requirements.txt
   ```

4. **Apply migrations**
   ```bash
   python manage.py migrate
   ```

5. **Create a superuser (admin)**
   ```bash
   python manage.py createsuperuser
   ```

6. **Run the development server**
   ```bash
   python manage.py runserver
   ```

7. **Access the application**
   - Website: http://127.0.0.1:8000/
   - Admin Panel: http://127.0.0.1:8000/admin/

## Project Structure

```
django_app/
├── src/                    # Main project directory
│   ├── automax/            # Project settings and configurations
│   ├── main/               # Main application
│   │   ├── migrations/     # Database migrations
│   │   ├── static/         # Static files (CSS, JS, images)
│   │   ├── templates/      # HTML templates
│   │   ├── admin.py        # Admin configurations
│   │   ├── apps.py         # App configurations
│   │   ├── models.py       # Database models
│   │   ├── urls.py         # URL routing
│   │   └── views.py        # View functions
│   ├── users/              # User management app
│   ├── manage.py           # Django management script
│   └── requirements.txt    # Project dependencies
├── venv/                   # Virtual environment
└── README.md               # This file
```

## Environment Variables

Create a `.env` file in the `src` directory with the following variables:

```
DEBUG=True
SECRET_KEY=your-secret-key-here
```

## Dependencies

- Django 5.2.7
- django-crispy-forms
- django-crispy-bootstrap4
- django-localflavor
- django-filter
- python-dotenv

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Built with [Django](https://www.djangoproject.com/)
- Styled with [Bootstrap 4](https://getbootstrap.com/)
- Icons from [Font Awesome](https://fontawesome.com/)

---

<div align="center">
  <p>Made with ❤️ by Akshay Kumar</p>
  <p>🚀 Happy Coding!</p>
</div>
