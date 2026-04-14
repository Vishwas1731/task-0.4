# task-0.4
# 🚀 Flask REST API for User Management

## 📌 Project Overview

This project is a simple **REST API built using Flask** that performs CRUD (Create, Read, Update, Delete) operations on user data.
It demonstrates the fundamentals of backend API development using Python.

---

## 🎯 Objective

* Build a RESTful API using Flask
* Implement CRUD operations
* Understand API request/response handling
* Learn how to test APIs using Postman or Curl

---

## 🛠️ Tech Stack

* **Language:** Python
* **Framework:** Flask
* **Tools:** Postman / Curl / Google Colab

---

## 📂 Project Structure

```
flask-user-api/
│── app.py          # Main Flask application
│── README.md       # Project documentation
```

---

## ⚙️ Installation & Setup

### 🔹 1. Clone the Repository

```
git clone https://github.com/your-username/flask-user-api.git
cd flask-user-api
```

### 🔹 2. Install Dependencies

```
pip install flask
```

### 🔹 3. Run the Application

```
python app.py
```

### 🔹 4. Open in Browser

```
http://127.0.0.1:5000/users
```

---

## 📌 API Endpoints

### ✅ 1. Get All Users

* **Method:** GET
* **URL:** `/users`

---

### ✅ 2. Get Single User

* **Method:** GET
* **URL:** `/users/<id>`

---

### ✅ 3. Add User

* **Method:** POST
* **URL:** `/users`
* **Body (JSON):**

```
{
  "name": "John",
  "age": 25
}
```

---

### ✅ 4. Update User

* **Method:** PUT
* **URL:** `/users/<id>`
* **Body (JSON):**

```
{
  "name": "Updated Name",
  "age": 30
}
```

---

### ✅ 5. Delete User

* **Method:** DELETE
* **URL:** `/users/<id>`

---

## 🧪 Testing the API

### 🔹 Using Curl

**GET**

```
curl http://127.0.0.1:5000/users
```

**POST**

```
curl -X POST http://127.0.0.1:5000/users \
-H "Content-Type: application/json" \
-d '{"name":"Alice","age":22}'
```

**PUT**

```
curl -X PUT http://127.0.0.1:5000/users/1 \
-H "Content-Type: application/json" \
-d '{"name":"Updated","age":23}'
```

**DELETE**

```
curl -X DELETE http://127.0.0.1:5000/users/1
```

---

## 📊 Features

* RESTful API design
* CRUD operations
* JSON-based communication
* In-memory data storage
* Easy to extend and modify

---

## 🚧 Limitations

* Data is not persistent (stored in memory)
* No authentication or security
* Suitable only for learning/demo purposes

---

## 🔮 Future Enhancements

* Integrate database (SQLite / MongoDB)
* Add authentication (JWT)
* Deploy on cloud (Render / AWS)
* Add input validation and error handling
* Build frontend UI

---

## 🎓 Learning Outcomes

* Understanding REST API concepts
* Hands-on experience with Flask
* API testing using Postman and Curl
* Backend development basics

---


