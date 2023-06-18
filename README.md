# Food Donor Management System

[![Python](https://img.shields.io/badge/Python-3.9-blue.svg)](https://www.python.org/)
[![Django](https://img.shields.io/badge/Django-3.2-green.svg)](https://www.djangoproject.com/)
[![HTML](https://img.shields.io/badge/HTML-5-orange.svg)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS-3-blue.svg)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![MongoDB](https://img.shields.io/badge/MongoDB-4.4-green.svg)](https://www.mongodb.com/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-2.2-blueviolet.svg)](https://tailwindcss.com/)

The Food Donor Management System is a web-based application aimed at reducing food waste by connecting food donors with potential buyers. The platform allows users to register as food donors, list food items for sale, and enables buyers to browse and purchase available food items.

## Features

- Food Donation: Users can register as food donors and list their surplus food items for sale.
- Food Purchase: Buyers can browse the available food listings and purchase the desired items.
- Platform Independence: The application is designed to be platform independent, allowing users to access it from any web browser on their preferred device.
- User Management: The system provides user registration, login, and authentication functionalities to maintain user profiles and ensure secure transactions.
- Notifications: Users receive notifications for successful purchases, order updates, and other relevant information.
- Search and Filters: Buyers can search for specific food items or apply filters based on categories, location, and other criteria.
- Reviews and Ratings: Users can provide feedback and rate the food items and the overall donation experience.

## Technologies Used

- Python and Django: The backend of the application is developed using Python programming language and the Django web framework.
- HTML, CSS, and JavaScript: The frontend of the application is built using standard web technologies for creating a user-friendly and interactive interface.
- MongoDB: The database management system used to store user data, food listings, and transaction information.
- Tailwind CSS: The Tailwind CSS framework is used for responsive and mobile-friendly design components.


## Technologies Used

- Python and Django: The backend of the application is developed using Python programming language and the Django web framework.
- HTML, CSS, and JavaScript: The frontend of the application is built using standard web technologies for creating a user-friendly and interactive interface.
- MongoDB: The database management system used to store user data, food listings, and transaction information.
- Tailwind CSS: The Tailwind CSS framework is used for responsive and mobile-friendly design components.

## Installation and Usage

To run the Food Donor Management System locally, follow these steps:

1. Clone the repository: `git clone https://github.com/NagiPragalathan/food-donar-management-system.git`
2. Navigate to the project directory: `cd food-donar-management-system`
3. Create a virtual environment: `python -m venv env`
4. Activate the virtual environment:
   - On Windows: `.\env\Scripts\activate`
   - On macOS and Linux: `source env/bin/activate`
5. Install the required dependencies: `pip install -r requirements.txt`
6. Set up the MongoDB database:
   - Install MongoDB if you haven't already: [MongoDB Installation Guide](https://docs.mongodb.com/manual/installation/)
   - Start the MongoDB service: `mongod`
7. Modify the database configuration in the `settings.py` file to match your MongoDB connection details.
8. Run database migrations: `python manage.py migrate`
9. Start the development server: `python manage.py runserver`
10. Access the application in your web browser at `http://localhost:8000`

Note: Make sure you have Python, Django, and MongoDB installed on your machine before proceeding with the installation.

## Contributing

Contributions to the Food Donor Management System are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
