# Nail Master Service Project

This project was created to provide a platform for nail masters and customers to connect and schedule nail services. It allows nail masters to create their profiles, list their services and prices, and manage their schedule. Customers can search for nail masters, view their profiles, and book appointments for nail services.

#### Check it out!
[Nail Master Service deployed to Render!](https://nail-master-service.onrender.com)

## Setup and Local Installation

### To set up and run the project locally, follow these steps:

#### 1.  Clone the repository:

```python
git clone https://github.com/OleksandrYanchuk/py-nail-master-service.git
```
#### 2. Create a virtual environment:
```python
python -m venv venv
```
#### 3. Activate the virtual environment:
   
##### - For Windows:
```python
venv\Scripts\activate
```
##### -	For macOS and Linux:
```python
source venv/bin/activate
```
#### 4. Install the project dependencies:
```python
pip install -r requirements.txt
```
#### 5. Apply database migrations:
```python
python manage.py migrate
```
#### 6. Create a superuser to access the admin panel:
```python
python manage.py createsuperuser
```
#### 7. Start the development server:
```python
python manage.py runserver
```
#### 8. Open your web browser and go to http://localhost:8000 to access the application.

## Setting up Environment Variables

The Nail Master Service project uses environment variables to store sensitive information and configuration settings. To set up the required environment variables, follow these steps:

#### 1. Rename a file name `.env_sample` to `.env` in the project root directory.

#### 2. Make sure to replace `your_secret_key_value_here` with your actual secret key.

## Created users in fixture:

masters: Test_master, Test_master3, Test_master4, Test_master6, Test_master7, Test_master8

customers: test_customer, test_customer2, test_customer3, test_customer4, test_customer5, test_customer6, test_customer8

### IMPORTANT: pass for all users: `b8396313`
