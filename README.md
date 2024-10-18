School Recommender System for Persons with Disabilities in Kenya
Overview

This project provides a recommender system designed to help users discover schools in Kenya that cater to persons with disabilities (PWDs). The system aims to enhance access to relevant education facilities by leveraging data on schools’ accessibility, services, and resources specifically for PWDs.

The project collects and processes data on schools across Kenya, highlighting key information about their support for various disabilities, including physical, sensory, cognitive, and other special needs.
Features

    School Search: Users can search for schools based on location, types of disabilities supported, and educational level (primary, secondary, etc.).
    Recommendation Engine: A personalized recommendation system that suggests schools based on user preferences and needs.
    Accessibility Filters: Filters to find schools that provide accessibility features such as ramps, braille materials, special education teachers, etc.
    Data Visualization: Visualizes the geographical distribution of schools that support PWDs.
    Detailed School Information: Provides detailed information on each school, including contact details, type of services provided, and special accommodations.

Technologies Used

    Programming Language: Python
    Machine Learning Framework: Scikit-learn
    Web Framework: Flask
    Database: PostgreSQL/MySQL
    Geospatial Data: Google Maps API
    Frontend: HTML, CSS, JavaScript
    Visualization: Matplotlib, Seaborn, Plotly
    Deployment: Docker

How It Works

    Data Collection: The dataset consists of schools in Kenya, sourced from Ministry of Education data and other relevant institutions, with details on the accessibility features and services for persons with disabilities.
    Preprocessing: The data undergoes cleaning and preprocessing, including handling missing values, standardizing formats, and applying geospatial data for mapping school locations.
    Recommendation Algorithm: The system uses a content-based filtering algorithm to match user needs (input by the user) with schools that offer suitable services and infrastructure.
    Web Application: The frontend allows users to input their preferences and disabilities, which the backend processes to recommend suitable schools.
    Visualization: The system generates maps and charts to display the distribution and concentration of schools across different regions of Kenya.

Installation

  Clone the repository:

    bash

    git clone https://github.com/username/pwd-school-recommender.git
    cd pwd-school-recommender

Install the required dependencies:

    bash

    pip install -r requirements.txt

Set up the database:

  Create and configure the database (PostgreSQL/MySQL)
  Apply migrations if applicable:

    bash

    python manage.py migrate

Obtain API keys for geospatial data (e.g., Google Maps API):

  Set up environment variables or config files for API keys.

Run the application:

    bash

    python manage.py runserver

Usage

  Visit the web application interface.
  Enter the location and specific needs (e.g., physical, sensory, cognitive disabilities).
  Get a list of recommended schools that match your criteria.
  Explore detailed school profiles and their accessibility features.

Data Sources

  Ministry of Education, Kenya
  Kenya Institute of Special Education (KISE)
  Google Maps for location data

Contributing

Contributions are welcome! Please feel free to open an issue or submit a pull request for any improvements or additional features.
To contribute:

  Fork the repository.
  Create a new branch for your feature:

    bash

    git checkout -b feature-name

Commit your changes:

    bash

    git commit -m "Added feature"

Push the branch:

    bash

    git push origin feature-name

  Open a pull request.

License

This project is licensed under the MIT License - see the LICENSE file for details.
Contact

For any inquiries or feedback, feel free to reach out at:

  Email: mutioesther@gmail.coom
  GitHub: EMutio7
