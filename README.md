# Effective Integration of Generative AI Into Programming Learning Environments

## Project Overview
The goal of this project is to design and implement a learning portal integrated with Generative AI capabilities. The portal empowers learners by providing self-paced education, interactive assignments, and AI-driven assistance. It includes:
- Learning videos
- Assignments
- Resources
- Practice and graded assignments
- Programming quizzes

## Technologies Used
- **Vue.js** – Frontend framework
- **Flask** – Backend framework
- **SQLite** – Database
- **npm** – Package manager for frontend dependencies
- **Gemini-1.5-Flash** – AI model for interactive learning assistance

## Instructions to Use the Vue.js and Flask Web Application

### Prerequisites
Before starting, ensure you have the following installed:
- [Node.js](https://nodejs.org/) (includes npm)
- [Python](https://www.python.org/downloads/)
- [Git](https://git-scm.com/)
- [Virtualenv](https://pypi.org/project/virtualenv/) (optional but recommended)

### 1. Clone the Repository
Clone the repository from GitHub to your local machine:
```bash
git clone <your-repo-url>
cd <your-repo-directory>
```

### 2. Set Up the Backend (Flask)
#### Create a Virtual Environment
Navigate to the backend directory and create a virtual environment:
```bash
cd backend
python -m venv venv
```
Activate the virtual environment:
- **Windows:**
  ```bash
  venv\Scripts\activate
  ```
- **macOS/Linux:**
  ```bash
  source venv/bin/activate
  ```

#### Install Dependencies
Install the required Python packages:
```bash
pip install -r requirements.txt
```

#### Configure Environment Variables
Create a `.env` file in the `backend` directory and add necessary environment variables:
```bash
API_KEY=your_api_key_here
```

#### Run the Flask Application
Start the Flask server:
```bash
flask run
```
The backend server should now be running at `http://127.0.0.1:5000`.

### 3. Set Up the Frontend (Vue.js)
Navigate to the frontend directory:
```bash
cd ../frontend
```

#### Install Dependencies
Install the required Node.js packages:
```bash
npm install
```

#### Run the Vue.js Application
Start the Vue.js development server:
```bash
npm run serve
```
The frontend server should now be running at `http://localhost:8080`.

### 4. Access the Application
Open your web browser and navigate to `http://localhost:8080` to access the learning portal.

