# Flask E-Commerce Store

A simple E-Commerce web application built using Flask, HTML, CSS, JavaScript, and SQLite.

## Features

- User Registration
- User Login
- Product Listing
- Product Search
- Add to Cart
- Shopping Cart
- Checkout Page
- Order Confirmation Page
- Responsive Design

## Technologies Used

- Python
- Flask
- HTML
- CSS
- JavaScript
- SQLite
- Docker

## Project Structure

flask-ecommerce-store/
│
├── app.py
├── requirements.txt
├── Dockerfile
├── static/
│ ├── style.css
│ └── images/
│
└── templates/
├── index.html
├── login.html
├── register.html
├── cart.html
└── checkout.html

## Run Locally

1. Clone Repository

```bash
git clone https://github.com/gsanjana10/flask-ecommerce-store.git
```

2. Install Dependencies

```bash
pip install -r requirements.txt
```

3. Run Application

```bash
python app.py
```

4. Open Browser

```text
http://127.0.0.1:5000
```

## Docker Commands

Build Image

```bash
docker build -t flask-ecommerce-store .
```

Run Container

```bash
docker run -p 5000:5000 flask-ecommerce-store
```

## Future Enhancements

- Product Categories
- Order History
- User Profile
- Admin Dashboard

## Author
Gampala Sanjana
