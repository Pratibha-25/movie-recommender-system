# 🎬 Movie Recommender System (Content-Based)

## 📌 Overview
This project implements a **Content-Based Movie Recommender System** that suggests movies based on their similarity to a given movie. The system utilizes **TF-IDF (Term Frequency-Inverse Document Frequency)** and **cosine similarity** to find and recommend movies with similar descriptions.

## 🚀 Features
- 📌 **Content-Based Filtering** using movie descriptions.
- 🏆 **TF-IDF Vectorization** to analyze textual data.
- ⚡ **Cosine Similarity Calculation** for recommendation ranking.
- 📊 **Movie Metadata Analysis** using pandas and scikit-learn.
- 🌐 **Web Interface (Optional)** for user-friendly movie search.

## 🛠️ Technologies Used
- **Python** (Backend processing)
- **pandas** (Data handling)
- **scikit-learn** (TF-IDF and cosine similarity)
- **Streamlit** (Web app framework)
- 
## 📂 Dataset
We use the **TMDB 5000 Movies Dataset**, which includes:
- `tmdb_5000_movies.csv`: Contains movie metadata (title, genres, overview, etc.).
- `tmdb_5000_credits.csv`: Contains actor and crew information.

The datasets are merged using the `id` column to enrich movie metadata.

## 🔧 Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/movie-recommender-system.git
   cd movie-recommender-system
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the script to generate recommendations:
   ```bash
   python recommend.py
   ```

## 📌 Data Processing
- **Load Data**: `pandas` is used to read movie and credits datasets.
- **Merge Data**: The movies and credits datasets are combined using `id`.
- **Text Processing**: Movie overviews a

## 📌 Running the Streamlit Web App
To start the **Movie Recommender System**, run:
```bash
streamlit run app.py
```

## 📌 Usage
1. Select a movie from the dropdown menu.
2. Click the **Recommend** button.
3. The system will display **5 similar movies**.

## 📜 License
This project is licensed under the **MIT License**.

---
💡 **Author**: [Your Name](https://github.com/yourusername)  
🌟 Star this repository if you found it useful!
