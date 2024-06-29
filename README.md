### Identification of Fake Instagram Accounts

This project is dedicated to detecting and distinguishing fake Instagram accounts using advanced machine learning techniques, specifically leveraging the Support Vector Machine (SVM) model. The initiative involves developing a robust web framework with Flask for backend operations and designing an intuitive frontend using HTML and CSS.

#### Abstract

The detection of fake Instagram accounts plays a pivotal role in maintaining the platform's integrity and user trust. This study employs machine learning methodologies, specifically SVM, to effectively identify deceptive profiles amidst genuine ones.

#### Features

- **SVM Classifier:** Utilized as a supervised learning algorithm for precise classification of accounts as either genuine or deceptive.
- **Web Framework:** Developed using Flask for seamless backend integration.
- **Frontend Design:** Implemented with HTML and CSS to provide an engaging user interface.

#### Requirements

To successfully deploy and run this project, ensure you have the following prerequisites:

- Python 3.x
- Flask
- Scikit-learn
- Pandas
- NumPy
- HTML and CSS

#### Installation

To get started, follow these straightforward installation steps:

1. Clone the project repository:

   ```
   git clone https://github.com/yourusername/fake-instagram-detection.git
   cd fake-instagram-detection
   ```

2. Set up a virtual environment to manage dependencies:

   ```
   python3 -m venv venv
   source venv/Scripts/activate  
   ```

3. Install necessary Python packages specified in `requirements.txt`:

   ```
   pip install -r requirements.txt
   ```

#### Usage

To utilize the application effectively:

1. Prepare your dataset:
   - Ensure your training dataset (`train.csv`) is placed within the `templates` directory.

2. Launch the Flask application:

   ```
   python app.py
   ```

3. Access the web application through your preferred web browser:

   - Navigate to [http://127.0.0.1:5000](http://127.0.0.1:5000) to interact with the deployed application.

#### Project Structure

- **app.py:** Main Flask application file where SVM model training and web server integration occur.
- **static/:** Directory housing static files such as CSS stylesheets and images.
- **templates/:** Directory containing HTML templates, including where the `train.csv` dataset is expected for model training.
- **requirements.txt:** List of essential Python packages required for seamless project operation.

This project offers a structured approach to combatting fake Instagram accounts using cutting-edge machine learning techniques, empowering developers to implement both backend functionality with Flask and frontend design using HTML and CSS effectively.
