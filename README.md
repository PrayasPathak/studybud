# Study Bud Application
Studybud is an online web application facilitating users to create, join, update and delete rooms. It is similar to discord but relatively simple. It uses session based authentication.

User can perform the following tasks:

- Create room (Host room)
- View available rooms
- Join room
- Delete Room
- View Recent activities
- Browse Topic
- Communicate with each other
- Register
- Login
- Update account information

## Run the project

Follow the following steps to run the project successfully:

### 1. Create a virtual environment:

`python -m venv env`

### 2. Activate the virtual envrironment:

> On Windows: venv\scripts\activate

> on Linux/Max: source venv/Scripts/activate

### 3. Install Necessary packages

`pip install -r requirements.txt`

### 4. Run migrations

`python manage.py migrate`

### 5. Run project

`python manage.py runserver`
