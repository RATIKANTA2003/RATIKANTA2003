## 🎬 Movie Recommendation System

The **Movie Recommendation System** is an AI-based project that suggests movies similar to the ones a user likes.
It uses **content-based filtering** with **TF-IDF Vectorization** and **Cosine Similarity** to find the closest matches between movies based on features like:

* Title
* Genres
* Overview (description)
* Keywords
* Cast and Crew

### 🧠 Technologies Used

* **Python**
* **Pandas** & **NumPy** for data handling
* **Scikit-learn** for machine learning (TF-IDF & Cosine Similarity)
* **Streamlit / Flask** *(optional)* for front-end interface
* **Jupyter Notebook** for model building and testing

### ⚙️ Features

* Search for a movie and get similar movie recommendations instantly
* Uses large movie datasets (like TMDB or IMDB)
* Clean and efficient code for better performance
* Scalable — easy to improve with collaborative filtering or deep learning in the future

### 📊 Future Improvements

* Add **user-based collaborative filtering**
* Build a **web app interface** with Streamlit
* Integrate **movie posters and trailers** using TMDB API
* Deploy online using **Render / Hugging Face Spaces / GitHub Pages**

### 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/RatikantaPati/movies_recommendater.git
   ```
2. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the script:

   ```bash
   python main.py
   ```
4. Enter a movie name and get recommendations!

💡 *This project was created to explore real-world AI applications in entertainment using machine learning and NLP.*
