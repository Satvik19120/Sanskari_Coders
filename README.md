To set up the project locally, follow these steps:

Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/medsync.git
Navigate to the project directory:

bash
Copy code
cd medsync
Create and activate a virtual environment:

bash
Copy code
python -m venv venv
source venv/bin/activate  # For Linux/macOS
venv\Scripts\activate  # For Windows
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Set up the database:

Ensure you have a SQLite or PostgreSQL database configured.
Run the following to initialize the database:
bash
Copy code
flask db init
flask db migrate
flask db upgrade
Run the Flask app:

bash
Copy code
flask run
Visit http://127.0.0.1:5000/ in your browser to access the application.
