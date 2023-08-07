# Ecommerce Python Project

This is an Ecommerce Python project that allows users to become buyers or sellers, with the option to add and delete products. Additionally, it includes a chat tool that enables buyers to communicate with the admin and sellers.

# Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- Credits


# Introduction

The Ecommerce Python project is designed to provide a platform for users to engage in buying and selling products. Users can register as buyers or sellers and then manage their products accordingly. The project incorporates a chat tool that enables buyers to communicate with both the admin and sellers, facilitating smooth transactions.

# Features

- User registration and authentication
- User roles as buyers or sellers
- Buyers can view and purchase products
- Sellers can add, update, and delete their products
- Chat functionality for buyers to interact with the admin and sellers
- Secure and responsive web interface
- Database storage for products, user information, and chat messages

# Requirements

Before running the project, make sure you have the following requirements installed:

- Python (>= 3.6)
- Django

# Installation

1. Clone the repository to your local machine:

```bash
git clone https://github.com/Dera4L/Puddle
```

2. Navigate to the project directory:

```bash
cd ecommerce-python-project
```

3. Create a virtual environment (optional but recommended):

```bash
python -m venv venv
```

4. Activate the virtual environment:

   - On Windows:

   ```bash
   venv\Scripts\activate
   ```

   - On macOS and Linux:

   ```bash
   source venv/bin/activate
   ```

5. Install the required dependencies:

```bash
pip install -r requirements.txt
```

6. Configure the database:

   - Open `config.py` and set your database configuration.

7. Initialize the database:

```bash
python manage.py db init
python manage.py db migrate
python manage.py db upgrade
```

# Usage

1. Run the application:

```bash
cd puddle
python manage.py runserver
```

2. Open your web browser and go to `http://localhost:8000`.

3. Buyers can browse and purchase products, and also initiate chats with the admin and sellers.

4. Sellers can add new products, update existing ones, and delete products as needed.

#Credit
- All credits to @Freecodecamp
- Credit also goes to @Mremmalex my tutor
