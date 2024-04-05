# QuickNote
Welcome to QuickNote – your personal note-taking app designed to simplify the way you capture, organize, and access your thoughts. Whether you're brainstorming ideas, jotting down reminders, or outlining your next big project, QuickNote provides a seamless platform to streamline your note-taking process.


## Features

- Users can register and log in to the application securely to access personalized features.
  
- Create new notes.

- Delete notes.

## Getting Started

To get started with QuickNote Pro, follow these steps:

1. **Clone the repository**:
   ```bash
   https://github.com/MohdMaaz19/My_Notes_App.git
   ```

2. **Create a virtual environment**:
   ```bash
   python -m venv venv
   ```

3. **Activate the virtual environment**:
   ```bash
   Activate the virtual environment (on Windows)
    venv\Scripts\activate

   Activate the virtual environment (on macOS or Linux)
    source venv/bin/activate
   ```
   
4. **Navigate to the project directory**:
   ```bash
   cd backend
   ```

5. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

6. **Run the app**:
   ```bash
   python manage.py migrate
   python manage.py runserver
   ```

7. **For the frontend, Navigate to project directory**:
   ```
   cd frontend
   ```

8. **Install dependencies**:
   ```bash
   npm install
   ```

9. **Run the app**:
   ```bash
   npm run dev
   ```
10. **Backend Endpoints**:
   ```bash
      /api/user/register/ -> Register new user
      /api/token/ -> Get access and refresh token
      /api/token/refresh/ -> Get a new access token)
   ```
## Please run the front and backend simultaneously for the jwt token to be passed onto the frontend

