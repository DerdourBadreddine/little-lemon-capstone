
# Restaurant Reservation Management Web App
This web application is built using Django and MySQL database server , and is designed to help restaurants efficiently manage reservations. With this app, restaurant owners and staff can easily keep track of reservations, manage table assignments, and provide excellent customer service.

## Features

- __Reservation Booking__: Customers can easily make reservations through the web interface, specifying the date, time, party size, and any special requests.
- __Table Management__: Restaurant staff can assign and manage tables for reservations, ensuring an efficient seating arrangement.
- __Customer Information__: Keep track of customer details, preferences, and contact information to provide personalized service.

- __Staff Dashboard__: A user-friendly dashboard for restaurant staff to view and manage reservations, tables, and customer information.

- __User Authentication__: Secure login and authentication system to protect customer and staff information.
- __Customizable Settings__: Configure various settings such as restaurant hours, table layouts, and reservation policies.
- __Mobile-Friendly__: The web app is responsive and works well on both desktop and mobile devices.

## Prerequisites

- __Python__: You need to have Python 3.x installed. You can download it from python.org.

- __Pipenv__ : Pipenv is used to manage dependencies. If you don't have it installed, you can do so with pip:

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


