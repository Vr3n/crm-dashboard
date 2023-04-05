## CRM Application

This is a web-based CRM (Customer Relationship Management) application built using Django, HTMX, and Tailwindcss. It provides a suite of features for managing customer relationships, inventory, lead management, purchase and sales billing, as well as data analysis with an accessible dashboard.

### Features

- Inventory System: Manage product inventory with ease, including adding and removing products, updating quantities, and viewing inventory levels.

- Lead Management: Keep track of leads and opportunities, including the ability to add and update leads, track progress, and set reminders.

- Purchase and Sales Billing: Create and manage invoices for purchases and sales, including adding products, setting prices, and generating invoices.

- Excel and CSV Exports: Export data in Excel or CSV format for easy analysis or integration with other tools.

- Data Analysis with Accessible Dashboard: Analyze your sales and customer data with a customizable dashboard that provides insights into key metrics such as sales revenue, customer acquisition, and product performance.

### Installation

To run the CRM application on your local machine, follow these steps:

1. Clone the repository: git clone https://github.com/Vr3n/crm-dashboard.git
2. Create a virtual environment and activate it: python -m venv env and source env/bin/activate
3. Install the requirements: pip install -r requirements.txt
4. Set up the database: python manage.py migrate
5. Create a superuser: python manage.py createsuperuser
6. Run the server: python manage.py runserver

### Credits

The CRM application was created by [Viren Patel](https://virenspatel.com) and is licensed under the MIT License. It was built using the following technologies:

- Django
- HTMX
- Tailwindcss
