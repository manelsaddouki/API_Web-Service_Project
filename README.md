# Rest-API 

## Link to my Report & Presentation: 
My report is accessible at [https://www.overleaf.com/read/fgskfpqgfshb#cc3fdf](https://www.overleaf.com/read/fgskfpqgfshb#cc3fdf).

My Presentation is accessible at [https://www.overleaf.com/read/skwkdhsxnktq#f17396](https://www.overleaf.com/read/skwkdhsxnktq#f17396).

N.B: PDF versions are available in this repository. 

## Introduction: 
This project is part of the Web Service class, focusing on the assigned theme of 'Politics.' The objective is to design and implement an API centered around a political topic.

For my project, I chose to develop an API that manages funds allocated by countries to address specific issues such as the effects of war, responses to natural disasters, or limiting the impacts of climate change.

As part of this project, I have created a prototype for the front end. Now, we have a user-friendly interface that facilitates interaction with the API. The live version of my web service is accessible at [https://lossanddamagefunds.onrender.com/](https://lossanddamagefunds.onrender.com/) (Deployment is currently suspended for security purposes). 

The development process involved various libraries and tools:

- **For the backend and development:** Python served as the primary programming language, supported by several libraries such as Flask, Flask-Smorest, Migrate (from Flask-Migrate), JWTManager (Flask-JWT), Secrets, Passlib.hash, SQLAlchemy (from Flask-SQLAlchemy), Flask.Views, and Schemas. For testing, Insomnia and Postman were employed. Plus, Swagger was employed for documentation and other APIs have been integrated.
- **For the frontend and deployment:** HTML, CSS, and JavaScript were the languages used. Gunicorn was the library of choice for server deployment. Render, ElephantSQL, and pgAdmin4 (PostgreSQL) were tools implemented for deployment and production database manipulation.
