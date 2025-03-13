# XyloShop - E-Commerce Shopping App

XyloShop is a feature-rich e-commerce application designed to provide users with a seamless shopping experience. Built with modern technologies, XyloShop ensures fast, secure, and efficient online shopping.

## Features

- 🛍️ **User-Friendly Interface**: Simple and intuitive design for easy navigation.
- 🔍 **Product Search & Filters**: Find products quickly with advanced search and filtering options.
- 🛒 **Cart & Wishlist**: Save favorite products and checkout effortlessly.
- 💳 **Secure Payments**: Multiple payment gateways for safe transactions.
- 🚀 **Fast & Scalable**: Optimized for high performance and smooth browsing.
- 📦 **Order Tracking**: Real-time order status updates.
- 🔐 **Secure Authentication**: User accounts with strong security measures.

## Getting Started

### 1. Installation

To set up XyloShop, install the required dependencies:

```bash
pip install flask flask_sqlalchemy
```

### 2. Running the App

```bash
python app.py
```

## Basic Shopping App Example

A simple Flask-based backend for XyloShop:

```python
from flask import Flask, render_template, request, jsonify

app = Flask(__name__)

products = [
    {"id": 1, "name": "Smartphone", "price": 499},
    {"id": 2, "name": "Laptop", "price": 999},
    {"id": 3, "name": "Headphones", "price": 199}
]

@app.route("/")
def home():
    return render_template("index.html", products=products)

if __name__ == "__main__":
    app.run(debug=True)
```

### Frontend (index.html)

```html
<!DOCTYPE html>
<html>
<head>
    <title>XyloShop</title>
</head>
<body>
    <h1>Welcome to XyloShop</h1>
    <ul>
        {% for product in products %}
        <li>{{ product.name }} - ${{ product.price }}</li>
        {% endfor %}
    </ul>
</body>
</html>
```

## API Endpoints

### 🔹 `GET /products`
**Description**: Fetches a list of available products.

**Response:**
```json
[
  {"id": 1, "name": "Smartphone", "price": 499},
  {"id": 2, "name": "Laptop", "price": 999}
]
```

## Team Credits
- **CEO & Lead Developer**: Harshit
- **Developer**: Ekansh Prajapati
- **Video & Content Editor**: Chitransh
- **AI Research & Consultant**: Ritoshree Saha

## License
MIT License

# E-CommerceWebsite
 A mobile responsive sample of E-Commerce Website using HTML, CSS, JavaScript and API's
 
 
 
### Home page
![1](https://user-images.githubusercontent.com/17312616/65086776-b1beb080-d9d0-11e9-9983-143d61ed8fdc.png)



### Content Description page
![2](https://user-images.githubusercontent.com/17312616/65086777-b1beb080-d9d0-11e9-9e2b-af3b7210bdf3.png)



### Ordered List page
![3](https://user-images.githubusercontent.com/17312616/65086778-b2574700-d9d0-11e9-9377-8e4886f582a8.png)



### Order confirm page
![4](https://user-images.githubusercontent.com/17312616/65086779-b2efdd80-d9d0-11e9-95d5-4b1a48eafe04.png)



## Contact
For support or inquiries, email us at **support@xyloshop.com** or visit [Xylo](https://xylotech.in).
