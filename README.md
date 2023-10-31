# Restaurant Reservation Management Web App

This web application is built using Django and MySQL database server , and is designed to help restaurants efficiently manage reservations. With this app, restaurant owners and staff can easily keep track of reservations, manage table assignments, and provide excellent customer service.

## Features

- **Reservation Booking**: Customers can easily make reservations through the web interface, specifying the date, time, party size, and any special requests.
- **Table Management**: Restaurant staff can assign and manage tables for reservations, ensuring an efficient seating arrangement.
- **Customer Information**: Keep track of customer details, preferences, and contact information to provide personalized service.

- **Staff Dashboard**: A user-friendly dashboard for restaurant staff to view and manage reservations, tables, and customer information.

- **User Authentication**: Secure login and authentication system to protect customer and staff information.
- **Customizable Settings**: Configure various settings such as restaurant hours, table layouts, and reservation policies.
- **Mobile-Friendly**: The web app is responsive and works well on both desktop and mobile devices.

## Prerequisites

- **Python**: You need to have Python 3.x installed. You can download it from python.org.

- **Pipenv** : Pipenv is used to manage dependencies. If you don't have it installed, you can do so with pip:

```bash
  pip install pipenv
```

- Create a virtual environment and install project dependencies:

```bash
  pipenv install
```

- Activate the virtual environment:

```bash
  pipenv shell
```

- Apply database migrations:

```bash
  python manage.py migrate
```

- finally , you can run it on the local server by:

```bash
  python manage.py runserver
```
