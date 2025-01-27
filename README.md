# sre-challenge-repo
 Flask App: Hello World
# Flask App: Hello World

## Project Title and Description

**Flask App: Hello World**  
This repository contains a minimal Flask application that displays "Hello, World!" when accessed. It's a simple starting point for anyone learning Flask.

---

## Getting Started

### Prerequisites
To set up and run this application, ensure you have the following installed:

- Python 3.8 or later
- pip (Python package manager)

### Installation Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/Pablovindas42/<your-repo-name>.git
   cd <your-repo-name>
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install Flask:
   ```bash
   pip install flask
   ```

4. Create a `app.py` file with the following content:
   ```python
   from flask import Flask

   app = Flask(__name__)

   @app.route("/")
   def hello_world():
       return "Hello, World!"

   if __name__ == "__main__":
       app.run(debug=True)
   ```

5. Run the Flask application:
   ```bash
   python app.py
   ```

6. Open your browser and go to [http://127.0.0.1:5000](http://127.0.0.1:5000) to view the app.

---

## Usage Examples

### Example: Hello, World!
Visit the homepage to see the message "Hello, World!" displayed on the screen.

---

## Features

- Minimal Flask app structure for beginners
- Displays "Hello, World!" as a response to HTTP requests

---

## Contributing

We welcome contributions! To contribute:

1. Fork the repository.
2. Clone the forked repository to your local machine:
   ```bash
   git clone https://github.com/<your-username>/<your-forked-repo>.git
   ```
3. Create a new branch for your feature:
   ```bash
   git checkout -b feature/your-feature-name
   ```
4. Make your changes and commit them:
   ```bash
   git add .
   git commit -m "Add: Description of your feature"
   ```
5. Push your branch to GitHub:
   ```bash
   git push origin feature/your-feature-name
   ```
6. Open a Pull Request in the original repository.

---

## Author

Pablo de Jesús Vindas Rodríguez
Nueva línea de prueba
