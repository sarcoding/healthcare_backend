##Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/sarcoding/healthcare_backend.git
   cd healthcare_backend
   ```
2. **Create and activate a virtual environment**
  
3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
  
    ```
4. **Set up PostgreSQL**
   Create a PostgreSQL database and update the `.env` file (i have not pushed my .env file in the repository):
    ```bash
    SECRET_KEY=
    DEBUG=
    DB_NAME=
    DB_USER=
    DB_PASSWORD=
    DB_HOST=localhost
    DB_PORT=5432
    ```
5. **Apply database migrations**

    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```

6. **Run the development server**

    ```bash
    
    python manage.py runserver
    ```

7. **Access the API**
   
  Visit: http://127.0.0.1:8000/


