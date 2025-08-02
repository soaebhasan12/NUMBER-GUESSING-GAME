# 🎮 Django Number Guessing Game

  

A classic number guessing game brought to life as a dynamic web application using the Django framework. This project challenges players to guess a secret number within a set number of attempts, offering two distinct difficulty levels for varying challenges.

## ✨ Features

  - **🏠 Homepage**: A simple and welcoming landing page to start the game.
  - **🕹️ Difficulty Levels**: Players can choose between:
      - **Easy Mode**: Guess a number between 1 and 100 in 10 attempts.
      - **Hard Mode**: Guess a number between 1 and 100 in just 5 attempts.
  - **💡 Dynamic Feedback**: Instant hints guide the player, indicating if their guess is "Too High" or "Too Low."
  - **🎉 Game Over States**: Clear win/loss screens congratulate the player or reveal the correct number.
  - **🔄 Play Again**: A seamless option to restart the game and try again.

-----

## 📸 Screenshots

Here's a sneak peek into the game's interface:

# 🎯Game Preview
 ![Home Page](Num_Gue_Game\game_screenshots\home.png)
 ![Level Selection Page](Num_Gue_Game\game_screenshots\stage.png)
 ![Easy level Page](Num_Gue_Game\game_screenshots\easy_level.png)
 ![Hard level Page](Num_Gue_Game\game_screenshots\hard_level.png)

-----

## 🛠️ Tech Stack

  - **Backend**: **Django**
  - **Frontend**: **HTML5**, **CSS3**
  - **Database**: **SQLite3** (default)
  - **Programming Language**: **Python**

-----

## 🚀 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

Make sure you have **Python** and **pip** installed on your system.

### Installation

1.  **Clone the repository:**

    ```sh
    git clone https://github.com/your-username/number-guessing-game.git
    cd number-guessing-game
    ```

2.  **Create and activate a virtual environment:**

      - On Windows:
        ```sh
        python -m venv venv
        .\venv\Scripts\activate
        ```
      - On macOS/Linux:
        ```sh
        python3 -m venv venv
        source venv/bin/activate
        ```

3.  **Install the required dependencies:**
    *(Ensure you have a `requirements.txt` file in your project root)*

    ```sh
    pip install -r requirements.txt
    ```

4.  **Apply database migrations:**

    ```sh
    python manage.py migrate
    ```

5.  **Run the development server:**

    ```sh
    python manage.py runserver
    ```

6.  **Access the application:**
    Open your web browser and navigate to `http://127.0.0.1:8000/`.

-----

## 🧧 Usage

1.  From the **Home Page**, click **"Play Game"**.
2.  Select either the **Easy** or **Hard** difficulty level.
3.  Enter your guess in the input field and submit.
4.  Use the feedback to make your next guess.
5.  Continue until you win or run out of attempts\!

-----

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

-----

## 📜 License

Distributed under the MIT License. See `LICENSE.txt` for more information.

-----

## 📬 Contact

Soaeb Hasan - [@LinkedIn](www.linkedin.com/in/shoaib-ahmad-789827360)

Project Link: [https://github.com/soaebhasan12/number-guessing-game](https://github.com/soaebhasan12/number-guessing-game)