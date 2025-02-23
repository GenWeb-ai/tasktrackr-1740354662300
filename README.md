```markdown
# Todo App

This is a simple Todo application with a frontend built using vanilla JavaScript and a backend using Flask.

## Setup & Installation Guide

### Prerequisites

- Node.js and npm (for frontend)
- Python 3 and pip (for backend)

### Frontend Setup

1. Navigate to the `frontend` directory:
   ```bash
   cd frontend
   ```

2. Open `index.html` in your browser to view the app.

### Backend Setup

1. Navigate to the `backend` directory:
   ```bash
   cd backend
   ```

2. Create a virtual environment:
   ```bash
   python3 -m venv venv
   ```

3. Activate the virtual environment:

   - On Windows:
     ```bash
     venv\Scripts\activate
     ```

   - On macOS and Linux:
     ```bash
     source venv/bin/activate
     ```

4. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

5. Run the Flask app:
   ```bash
   python app.py
   ```

6. The backend server will be running on `http://127.0.0.1:5000`.

### Usage

- Open the frontend in your browser.
- Use the input field to add new todos.
- Click "Add" to add the todo to the list.
- Click "Remove" to delete a todo from the list.

### Note

This is a simple implementation and does not persist data. Refreshing the page will reset the todo list.
```

