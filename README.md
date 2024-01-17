# Cafe Review App

This is a simple Flask web application that allows users to add and review cafes. Users can provide information about the cafe's name, location on Google Maps, opening and closing times, and rate the coffee, wifi strength, and power socket availability.

## Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.x
- Flask
- Flask Bootstrap
- Flask WTF
- (other dependencies)

## Getting Started

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/cafe-review-app.git
    cd cafe-review-app
    ```

2. Install the dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Set up the application:

    ```bash
    export FLASK_APP=app.py
    export FLASK_ENV=development
    ```

4. Run the application:

    ```bash
    flask run
    ```

The application should now be running at [http://localhost:5000](http://localhost:5000).

## Usage

1. Access the home page:

    [http://localhost:5000](http://localhost:5000)

2. Add a new cafe:

    - Navigate to [http://localhost:5000/add](http://localhost:5000/add)
    - Fill out the cafe details form and click "Submit"

3. View cafes:

    - Navigate to [http://localhost:5000/cafes](http://localhost:5000/cafes)
    - See a list of cafes and their details.

## Note

Feel free to make changes according to your needs.
