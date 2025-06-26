
# 📦 Product Recommendation System using Django, TF-IDF & Cosine Similarity

A web-based product recommendation system built using Python, Django framework, and machine learning techniques like TF-IDF vectorization and Cosine Similarity. The system helps users search and discover similar products from an e-commerce dataset based on product descriptions, with optional filters for price and rating.

---

## 📊 Features

- User authentication (Signup, Login, Logout)
- Product search with name, price, and rating filters
- Product recommendations based on text similarity
- Add new products to the dataset via a form
- Clean, responsive Bootstrap 5 front-end interface
- Clickable email and LinkedIn icons in a fixed footer

---

## 🛠️ Tech Stack

- **Python 3.x**
- **Django 5.x**
- **Pandas**
- **Scikit-learn**
- **Bootstrap 5**
- **Bootstrap Icons**
- **CSV** for product data storage
- **SQLite** for authentication data

---

## 🚀 Local Setup Instructions

Follow these steps to run the project on your system:

### 1️⃣ Clone the repository:

```bash
git clone https://github.com/abhaysariyal/product-recommendation-system.git
cd product-recommendation-system
````

### 2️⃣ Create a virtual environment:

```bash
python -m venv venv
```

### 3️⃣ Activate the virtual environment:

* On **Windows**:

```bash
venv\Scripts\activate
```

* On **Mac/Linux**:

```bash
source venv/bin/activate
```

### 4️⃣ Install dependencies:

```bash
pip install -r requirements.txt
```

*(If no `requirements.txt`, install manually:)*

```bash
pip install django pandas scikit-learn
```

### 5️⃣ Apply database migrations:

```bash
python manage.py makemigrations
python manage.py migrate
```

### 6️⃣ Run the development server:

```bash
python manage.py runserver
```

### 7️⃣ Open your browser:

```url
http://127.0.0.1:8000/
```

Use the system and test product recommendations!

---

## 📂 Project Structure

```
├── manage.py
├── projectname/
│   ├── settings.py
│   ├── urls.py
│   └── ...
├── appname/
│   ├── views.py
│   ├── templates/
│   ├── static/
│   └── ...
├── data/
│   └── cleaned_product_data.csv
├── static/
│   └── css/
│       └── styles.css
├── requirements.txt
├── .gitignore
└── README.md
```

---

## 📧 Contact

* 📧 Email: [abhaysariyal143@gmail.com](mailto:abhaysariyal143@gmail.com)
* 🔗 LinkedIn: [Abhay Sariyal](https://www.linkedin.com/in/abhay-sariyal-b544ab2b8/)

---
