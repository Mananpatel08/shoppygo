# ShoppyGo

ShoppyGO is a dynamic e-commerce web application built with Django.  
It solves the limitations of static websites by allowing products to be managed dynamically through the Django admin panel.

The platform enables administrators to add, update, and remove products in real-time without modifying the source code. It also supports category-based product organization and basic customer support functionality.

### Features

- Dynamic product management via Django Admin
- Add, update, and delete products
- Category-wise product listing
- User management through admin panel
- Responsive UI using Bootstrap
- Customer support section

### Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

### Project Purpose

This project was built while learning Django to understand:

- Django models and admin panel
- User authentication system
- Shopping cart functionality
- Payment integration
- Dynamic content rendering
- Template inheritance
- CRUD operations
- Basic e-commerce architecture

### Future Improvements

- Filtering and sorting functionality
- Order management
- Deployment to production server

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/Mananpatel08/shoppygo.git
   ```
2. Create a virtual environment
   ```sh
   cd shoppygo
   python -m venv venv
   ```
3. Activate the virtual environment
   ```sh
   source venv/bin/activate
   ```
4. Install the dependencies
   ```sh
   pip install -r requirements.txt
   ```
5. Run the server
   ```sh
   python manage.py migrate
   python manage.py runserver
   ```
