<p id="top" align="center">
  <a href="https://music-club.mrsoni.in" target="_blank">
    <img src="static/admin/folder/images/logo-music-club.png" alt="Logo" width="300" height="100">
  </a>
</p>

<h1 align="center" class="dotted">
    <a href="https://music-club.mrsoni.in" target="_blank">Music Club eCommerce</a>
</h1>

<br>

<p align="center">
  
<img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=for-the-badge" />
<img src="https://img.shields.io/badge/Django-092E20?logo=django&logoColor=white&style=for-the-badge" />
<img src="https://img.shields.io/badge/Razorpay-0C2451?logo=Razorpay&logoColor=white&style=for-the-badge" />
<img src="https://img.shields.io/badge/SQL%20Server-CC2927?logo=microsoft-sql-server&logoColor=white&style=for-the-badge" />
<img src="https://img.shields.io/badge/Html5-E34F26?logo=html5&logoColor=white&style=for-the-badge" />
<img src="https://img.shields.io/badge/Css3-1572B6?logo=css3&logoColor=white&style=for-the-badge" />
<img src="https://img.shields.io/badge/Bootstrap-563D7C?logo=bootstrap&logoColor=white&style=for-the-badge" />
<img src="https://img.shields.io/badge/Github-181717?logo=github&logoColor=white&style=for-the-badge" />
<img src="https://img.shields.io/badge/AI--Powered-Image%20Search-purple?style=for-the-badge" />
<a href="https://github.com/PrathmeshSoni">
  <img src="https://custom-icons-badges.vercel.app/github/visitors/?username=Ecommerce">
</a>
</p>


This Django-built Music Instruments E-commerce system facilitates product addition and integrates Razorpay for seamless payments.

# Live Demo 👇:

<a href="https://music-club.mrsoni.in" target="_blank">music-club.mrsoni.in</a>

<br>

## Table Of Contents :

* [About the Project](#About-The-Project)
* [Technologies Used](#technologies-used)
* [Features](#Features)
* [Getting Started](#Getting-Started)
  * [Prerequisites](#Prerequisites)
  * [Installation](#installation)
* [Credentials](#Default-Credentials)
* [Screenshots, Demo Video](#Screenshots)
* [Connect Me](#Connect-with-me-at)


## About The Project

![Screen Shot](/static/admin/folder/images/pretty-snap-25-09-2023.png)

This project is a full-stack Music Instruments E-commerce website developed using Python and the Django framework. It incorporates essential features for an online store, including user authentication, a shopping cart, and integration with the Razorpay payment gateway.


## Technologies Used

- Full Stack: Python, Django, HTML, CSS, Bootstrap
- Database: MySQL
- Payment Gateway: Razorpay


## Features

- User Authentication: Secure login and registration for a personalized shopping experience.
- Shopping Cart: Efficient cart management for adding, updating, and removing products.
- Razorpay Integration: Seamless payment transactions through the Razorpay payment gateway.
- **AI-Based Product Search (Image Upload):**
  - Users can upload an image of a musical instrument.
  - AI analyzes the image and predicts the instrument category.
  - Relevant products from the database are displayed automatically based on the predicted category.


## AI-Based Product Search (Image Upload)

This feature enhances the shopping experience by allowing users to search for products using images instead of text.

### How It Works

1. The user uploads an image of a musical instrument (e.g., guitar, piano, drum).
2. The image is sent to the backend API.
3. An AI/ML model processes the image and predicts the instrument category.
4. The predicted category is matched against the product categories stored in the database.
5. All related products are fetched and displayed to the user in real time.

### Supported Instrument Categories

- Guitar
- Piano
- Keyboard
- Drum
- Tabla
- Flute
- Sitar
- Violin

### Benefits

- Faster and smarter product discovery
- No need to know exact product names
- Ideal for beginners who recognize instruments visually


### Preview At 👇:

<a href="https://music-club.mrsoni.in/user/classify-image/" target="_blank">music-club.mrsoni.in/user/classify-image/</a>


## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

Install Python 3.7 or above

* <a href="https://python.org/downloads/" target="_blank">Python</a>
 
### Installation

> 👉 **Step 1** - Download the code from the GH repository (using `GIT`):
```bash
git clone https://github.com/Spark0914724/ecommerce-music.git
```

<br />

> 👉 **Step 2** - Create virtual environment:
```
python -m venv .venv
```

<br />

> 👉 **Step 3** - Activating the environment:

on Windows:
```bash
.venv\Scripts\activate.bat
```
on Mac OS / Linux:
```bash
source .venv\Scripts\activate
```

<br />

> 👉 **Step 4** - Installing dependencies:

```bash
pip install -r requirements.txt
```

<br />

> 👉 **Step 5** - You can now run the development server:

```bash
python manage.py runserver
```

Visit [`http://127.0.0.1:8000`](http://localhost:8000) in your browser. The app should be up & running.

<br />

> 👉 **Step 6** - Go `config.py` Not Necessary:


Go to the `config.py` file on the Ecommerce folder (`/music_club/config.py`) setting all requirements after "=". 

```
# For sending email to users during registration or password recovery
email = ''
password = ''

# For integrating with the Razorpay payment gateway.
razorpay_key_id = ''
razorpay_key_secret = ''
```

<br />

> 👉 **Step 7** - Integrate the Razorpay payment gateway for transactions.

Documentation: <a href="https://razorpay.com/docs/payments/server-integration/python/install/" target="_blank">Razorpay Integration</a>

**IMPORTANT**: Make sure your Razorpay account is running in `TEST Mode` and Use the Test token provided by Razorpay:

<br />

## Default Credentials

- **User Credentials:**
  - URL: http://127.0.0.1:8000/
  - Username: user
  - Password: user@123

- **Admin Credentials:**
  - URLS:
    - Admin Panel: http://127.0.0.1:8000/admin/
    - Django Admin Panel: http://127.0.0.1:8000/admin_side/
  - Username: admin
  - Password: admin@123


## Screenshots

Visit our <a href="https://private-app.mrsoni.in/view/113" target="_blank"> Screenshots Page </a> for a visual walkthrough of the Music Club E-Commerce Website.

<br />

The repository is a starting point for most of my professional projects; for this, I'm using it as a part of my portfolio, feel free to use it wherever you want. I'll be happy if you provide any feedback code improvements or suggestions.


## Connect with me at

<p align='center'>
  <a href="https://www.linkedin.com/in/PrathmeshSoni/" target="_blank">
    <img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</p>

<p align='center'>
  📫 How to reach me: <a href='mailto:connect.prathmeshsoni@gmail.com'>connect.prathmeshsoni@gmail.com</a>
</p>


## All Set :)

<p style="float:left;" align="left">
  <a href="#top">Back To Top</a>
</p>

