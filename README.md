# Flask API Assignment

## Objective

Create a Flask application with an `/api` route that returns data in JSON format. The data is stored in a backend file and is read and returned as a response when the route is accessed.

---

## Project Structure

```text
flask-api-assignment/
│
├── app.py
├── data.json
├── requirements.txt
└── .gitignore
```

---

## Technologies Used

* Python 3
* Flask

---

## Setup Instructions

### 1. Clone the Repository

```bash
git clone <repository-url>
cd flask-api-assignment
```

### 2. Create a Virtual Environment

```bash
python3 -m venv venv
```

### 3. Activate the Virtual Environment

Linux/macOS:

```bash
source venv/bin/activate
```

Windows:

```cmd
venv\Scripts\activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the Application

```bash
python app.py
```

The application will start at:

```text
http://127.0.0.1:5000
```

---

## API Endpoint

### GET /api

Returns the contents of the `data.json` file as a JSON response.

Example Response:

```json
[
    {
        "id": 1,
        "name": "Pawan",
        "role": "Student"
    },
    {
        "id": 2,
        "name": "John",
        "role": "Developer"
    }
]
```

---

## Features

* Flask web application
* REST API endpoint (`/api`)
* Reads data from a backend JSON file
* Returns data in JSON format using Flask's `jsonify()`
* Simple and lightweight implementation

---

## Author

Pawan Kalyan
