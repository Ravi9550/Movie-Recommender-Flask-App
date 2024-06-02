#                                                                                    Movie Recommender Flask App

A Web based Movie Recommender System consisting of movies 5000 TMDB movies dataset from Kaggle. 
The recommender System uses Machine Learning and Natural Language processing to suggestions for similar films they might enjoy.




## Screenshots 
![01](https://github.com/Ravi9550/Movie-Recommender-Flask-app/assets/107767414/4079a549-fcc2-44ac-a799-8452e1e7a8f6)
![02](https://github.com/Ravi9550/Movie-Recommender-Flask-app/assets/107767414/7a791044-81fb-44b1-8ea2-7b15295fe564)
![03](https://github.com/Ravi9550/Movie-Recommender-Flask-app/assets/107767414/2656c0fc-880f-4563-9f82-0718eaab6357)
![04](https://github.com/Ravi9550/Movie-Recommender-Flask-app/assets/107767414/be1f8566-d170-4cf2-8d0e-ecd5e0fdd9f3)




## Features
1. Search for movies from a predefined list.

2. Get movie recommendations based on similarity.


3. Display detailed movie information in a modal.


4. Store the last searched movie for convenience.


## Prerequisites
Python 3.7 or higher

Flask

Pandas

Requests


## Installation
1. **Clone the repository :**
   
```bash
git clone https://github.com/Ravi9550/Movie-Recommender-Flask-app.git
cd Movie-Recommender-Flask-app
```
2. **Create a virtual environment: (Recommended not necessary)**
```bash
python -m venv virtual_env_name
virtual_env_name\Scripts\activate
```
3. **Install the required packages:**
```bash
pip install -r requirements.txt
```
4. Ensure you have the necessary data files (movies.pkl and similarity.pkl) in the project directory


## Project Structure 
```bash
Movie-Recommender-Flask-app/
|
├── templates/
│   ├── home.html
│   ├── movie_detail.html
│   ├── cast_detail.html
│
├── static/
│   ├── style.css
│   └── images/
│
├── models.py
├── database.py
├── app.py
├── movies.pkl
├── similarity.pkl
├── requirements.txt
└── README.md

```

## Deployment

To deploy this project run

```bash
python app.py
```

Go to address 127.0.0.1:5000 to see the website

## Technology Used

**Front-End:** Html , Css , Bootstrap

**Backend:** Flask

**Libraries:**  Sci-kit learn , Numpy , Pandas , Nltk

**Contributions :**
Contributions are welcome! Please feel free to submit issues and pull requests to enhance the application.

