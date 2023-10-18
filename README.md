# TaskMasterPro

TaskMasterPro is a Django-based Task Management App.

## Getting Started

Follow these steps to set up and run TaskMasterPro locally:

```bash
# Prerequisites
- [Python](https://www.python.org/downloads/) (3.6 or higher)
- [pip](https://pip.pypa.io/en/stable/installation/)

# Clone the Repository
git clone https://github.com/AshishGavit/TaskManagerPro.git
cd TaskMasterPro

# Create a Virtual Environment (Optional but Recommended)
python -m venv env

# Activate the Virtual Environment (Optional)
# On Windows:
.\env\Scripts\activate
# On macOS and Linux:
source env/bin/activate

# Install Dependencies
pip install -r requirements.txt

# Apply Migrations
python manage.py migrate

# Create Superuser (Optional)
python manage.py createsuperuser

# Run the Development Server
python manage.py runserver

# Access the Application
# Open your web browser and go to http://127.0.0.1:8000/

# Admin Panel
# To access the admin panel, go to http://127.0.0.1:8000/admin/ and log in with the superuser credentials.

## Usage

- Create tasks with titles, descriptions, due dates, and priority levels.
- Organize tasks into categories and add tags for easy organization.
- Track task progress and mark tasks as completed.
