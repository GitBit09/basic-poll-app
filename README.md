# Django Polling App

This is a basic yet fully functional polling (voting) app built with Django.  
Users can register, log in, view available polls, vote on choices, and see poll results.

---

## Features

- User registration and authentication (login/logout)
- Display list of polls (questions)
- Poll detail page with choices to vote for
- Real-time display of voting results
- Admin interface to add/manage polls and choices
- Responsive and clean UI styled with Bootstrap 5

---

## Project Structure

- `accounts/` — user authentication app (register, login, logout)
- `home/` — polling app (questions, choices, voting, results)
- `templates/` — shared base layout (Bootstrap-based)
- `myenv/` — Python virtual environment (excluded from Git)
- `db.sqlite3` — SQLite database file

---

## Setup and Run

### Prerequisites

- Python 3.13+
- Django 5.2.5+
- Virtual environment recommended

### Installation

1. Clone the repo:
git clone https://github.com/GitBit09/basic-poll-app.git
cd basic-poll-app

text

2. Create and activate virtual environment:
python -m venv myenv
myenv\Scripts\activate # Windows
source myenv/bin/activate # macOS/Linux

text

3. Install dependencies:
pip install -r requirements.txt

text

4. Run migrations:
python manage.py migrate

text

5. Create a superuser for admin:
python manage.py createsuperuser

text

6. Run the development server:
python manage.py runserver

text

7. Open [http://127.0.0.1:8000/](http://127.0.0.1:8000/) in your browser.

---

## Usage

- Register a new user or log in.
- View available polls on the home page.
- Click on a poll to vote.
- View poll results after voting.
- Admin users can add polls and choices at `/admin/`.

---

## Styling

- Uses Bootstrap 5 for responsive and clean UI.
- Shared base template for consistent layout and navigation.

---

## License

This project is open source and free to use.

---

## Contact

For any questions or support, please contact GitBit09 on GitHub.

---

Thank you for checking out this Django polling app! Feel free to customize and expand according to your needs.
