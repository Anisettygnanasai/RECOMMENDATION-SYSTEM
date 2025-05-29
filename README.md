# RECOMMENDATION-SYSTEM

COMPANY: CODTECH IT SOLUTIONS

NAME: ANISETTY GNANA SAI

INTERN ID: CT04DN782

DOMAIN: MACHINE LEARNING

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH

##
The provided files collectively build a simple yet effective anime recommendation system with a user-friendly interface and core logic powered by collaborative filtering using the SVD algorithm from the Surprise library. The project includes the backend logic in Python (using Flask), a styled HTML frontend, and a CSS design for a visually appealing experience.

Backend Overview
The heart of the recommendation system lies in the Python script that uses the Flask web framework to handle user interactions and generate recommendations. It starts with a small dataset containing user ratings for popular anime titles, including genres like Action, Isekai, Fantasy, and more. This data is used to train a collaborative filtering model using the Singular Value Decomposition (SVD) algorithm, which is effective for matrix factorization-based recommendations.

When a user submits their ID and preferred genre via a form, the application filters out anime from the chosen genre that the user hasn’t rated yet. These “unseen” anime are then evaluated using the trained model, and the top five with the highest predicted ratings are recommended back to the user.

In addition, there is a fallback mechanism that ensures genre-specific anime suggestions are available even without a dynamic database, making the system functional and robust with limited data.

Frontend Overview
The index.html file provides a clean and interactive user interface. It includes:

An input box for the user to enter their ID.

A dropdown menu to select their favorite genre.

A button to submit the form and generate recommendations.

Once the form is submitted, the results appear below, displaying the top recommendations in a card layout with anime titles and predicted ratings. This dynamic HTML rendering is powered by Jinja2 templating, a part of Flask.

Styling and Visual Design
The CSS files  contribute to the aesthetic appeal of the application. The background features a high-resolution anime-themed wallpaper, adding an immersive and thematic look. Containers are semi-transparent with a soft black tint, white text, and rounded borders to ensure readability. Inputs and buttons are styled with modern UI elements—rounded corners, vibrant green buttons, and soft shadows give it a polished appearance.

Recommendation cards are clean and centered, each displaying one anime suggestion along with the estimated rating. The overall design balances functionality with a visually engaging anime-fan-friendly interface.

Conclusion
This project demonstrates a foundational implementation of a recommendation system that combines data science and web development skills. It leverages machine learning (SVD model), Flask for server-side handling, and HTML/CSS for frontend design. Though the dataset is minimal and hardcoded, the structure allows easy scaling by plugging in real-world data sources like MyAnimeList or user-generated content. It’s a perfect prototype for anyone starting in the domain of personalized recommendation systems with a focus on anime or similar entertainment domains

##

#OUTPUT:
