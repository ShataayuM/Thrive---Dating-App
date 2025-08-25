# Thrive / Mystery Mode - A Personality-First Dating App

Thrive is a unique dating application designed to foster genuine connections by prioritizing personality over appearance. In a world of swipe-left, swipe-right culture, Thrive's "Mystery Mode" encourages users to engage in meaningful conversation first. Profiles, including photos, are only revealed after both users mutually agree, ensuring that the initial spark is based on who you are, not just what you look like.

<!-- Make sure your logo.png is in the static folder -->

## ✨ Core Features

* **User Authentication:** Secure user registration and login system to manage profiles and conversations.
* **In-Depth Questionnaire:** A dynamic, multi-step questionnaire with randomized questions to build a unique personality profile for each user.
* **Real-Time Mystery Chat:** A fully-featured, real-time chat powered by WebSockets. Users are represented by default avatars, and their names are hidden.
* **Multimedia Messaging:** Users can send text, emojis, photos, and voice messages.
* **"Is Typing..." Indicator:** See when your match is actively typing a response.
* **Mutual Consent Reveal:** Instead of an automatic reveal, profiles and photos are only un-blurred after both users click the "Ready to Reveal?" button, putting control in the users' hands.
* **Match History:** Users can view and revisit conversations with their past matches.
* **Profile Management:** Users can add a bio and upload a profile picture.

## 🛠️ Technology Stack

* **Backend:** Python with Flask & Flask-SocketIO
* **Database:** SQLAlchemy with SQLite
* **User Management:** Flask-Login & Flask-Bcrypt
* **Frontend:** HTML5, CSS3, Vanilla JavaScript
* **Real-Time Engine:** Socket.IO
* **Audio/Visuals:** HTML5 Canvas for animations, HTML5 Audio

## 🚀 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

* Python 3.x
* Git

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/ShataayuM/Thrive---Dating-App.git](https://github.com/ShataayuM/Thrive---Dating-App.git)
    cd Thrive---Dating-App
    ```

2.  **Create and activate a virtual environment:**
    * On Windows:
        ```bash
        python -m venv venv
        .\venv\Scripts\activate
        ```
    * On macOS/Linux:
        ```bash
        python3 -m venv venv
        source venv/bin/activate
        ```

3.  **Install the required packages:**
    ```bash
    pip install -r requirements.txt
    ```
    *(Note: You will need to create a `requirements.txt` file. See the section below.)*

4.  **Run the application:**
    ```bash
    python app.py
    ```
    The application will be running at `http://127.0.0.1:5000`.

## 📝 How to Create `requirements.txt`

Before you push your code to GitHub, you need to create a file that lists all the Python packages your project needs. In your terminal (with the `venv` activated), run this command:

```bash
pip freeze > requirements.txt
