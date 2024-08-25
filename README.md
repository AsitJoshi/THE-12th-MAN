
# Football Player Recognition and Analysis

## Project Overview

The Football Information Web Application is designed to be a comprehensive platform for football enthusiasts, coaches, and analysts. The web application provides detailed information about football leagues, clubs, rules, formations, and player statistics. It features a search function for retrieving player data and includes an advanced player identification system using photographs.

## Features

- **Current Leagues**: Information about popular ongoing football leagues globally, such as the Premier League, La Liga, Indian Super League, and the Champions League.
- **Clubs and Leagues**: Details about which clubs are in which league, how teams qualify for the Champions League, and the geographical distribution of leagues.
- **Players Identification**: A player recognition system that identifies players based on their photographs and provides detailed information about them.
- **Player Stats**: Detailed statistics on searched players, including their club, nationality, age, and career statistics.
- **Rules and Formations**: Information about football rules (e.g., the offside rule), commonly used formations, and popular player positions to enhance understanding of the game.

## Technology Stack

- **Backend**: Flask (Python Framework)
- **Database**: MySQL
- **Frontend**: HTML, CSS, JavaScript
- **Image Recognition**: Integrated player identification system using image processing techniques

## Setup and Installation

### Prerequisites

- Python 3.x
- MySQL
- Flask
- Required Python packages (listed in `requirements.txt`)

### Installation Steps

1. **Clone the Repository**

   ```bash
   git clone https://github.com/DS-Parihar/football-info-web-app.git
   cd football-info-web-app
   ```

2. **Create and Activate a Virtual Environment**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Set Up the MySQL Database**

   - Create a MySQL database and import the initial dataset.
   - Update the database configuration in `config.py`.

5. **Run Migrations**

   If using Flask-Migrate, run:

   ```bash
   flask db upgrade
   ```

6. **Start the Flask Application**

   ```bash
   flask run
   ```

7. **Access the Application**

   Open your web browser and go to `http://127.0.0.1:5000/`.

## Usage

- **Home Page**: Upload a photograph to identify a player and view detailed information about them.
- **Leagues**: View ongoing leagues, clubs within those leagues, and league qualifications.
- **Players Stats**: Search for players and view their statistics and details.
- **Rules and Formations**: Learn about football rules, formations, and player positions.

## Contributing

We welcome contributions to improve the project. To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any questions or suggestions, please contact [Deependra Singh Parihar](mailto:deependrasinghparihar3@gmail.com).

---

Thank you for using the Football Information Web Application! Enjoy exploring the world of football.

```
