# 📚 Bev-Book_Recom - Smart Book Recommendation System

<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" alt="Flask"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white" alt="Scikit-learn"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3"/>
</div>

<br>

<div align="center">
  <img src="https://github.com/bevinsamraj/Book_Recommendation_System/blog/main/Web_Book_Home.png" alt="Bev-Book_Recom Home Interface - Top 50 Books" width="700"/>
  <p><em>Discover your next favorite book with AI-powered recommendations and curated top picks</em></p>
</div>

## 🎮 Usage

**Home Page** · Browse top 50 curated books with ratings and covers  
**Recommendation Engine** · Enter a book title to get personalized suggestions

<div align="center">
  <img src="https://github.com/bevinsamraj/Book_Recommendation_System/blog/main/Web_Book_Recommend.png" alt="Bev-Book_Recom Recommendation Interface" width="700"/>
  <p><em>Smart recommendation engine with modern search interface</em></p>
</div>

<br>

## ✨ Features

🎯 **Smart Recommendations** · Get personalized book suggestions based on your reading preferences  
📊 **Top 50 Curated Books** · Explore the most popular and highly-rated books from our database  
🔍 **Collaborative Filtering** · Advanced ML algorithm that finds books similar to your favorites  
📈 **Popularity-Based System** · Discover trending books based on community ratings and votes  
🎨 **Modern Dark UI** · Sleek, responsive interface with smooth animations and glass-morphism design  
⚡ **Fast Performance** · Optimized recommendation engine with pre-computed similarity matrices

## 🛠️ Tech Stack

**Python** · Core programming language and backend logic  
**Flask** · Lightweight web application framework  
**Pandas & NumPy** · Data manipulation and numerical analysis  
**Scikit-learn** · Machine learning algorithms and cosine similarity  
**Joblib** · Model serialization and efficient data storage  
**HTML5/CSS3** · Modern responsive frontend with animations  
**JavaScript** · Interactive UI elements and smooth user experience  

## 🚀 Quick Start

**Prerequisites**
```
Python 3.7+ · pip package manager
```

**Installation**
```bash
# Clone the repository
git clone https://github.com/bevinsamraj/Book-Recommendation-System.git
cd Book-Recommendation-System

# Install dependencies
pip install flask pandas scikit-learn numpy joblib

# Run the application
python app.py
```

Open your browser and navigate to `http://localhost:5000`

## 📁 Project Structure

```
Book-Recommendation-System/
│
├── app.py                           # Main Flask application
├── Book_Recommendation_System.ipynb # Jupyter notebook with model development  
├── popular.pkl                      # Popular books data (joblib format)
├── pt.pkl                          # Pivot table for collaborative filtering
├── books.pkl                       # Books metadata
├── similarity_scores.pkl           # Pre-computed similarity matrix
├── books.csv                       # Raw books dataset
├── users.csv                       # User data
├── ratings.csv                     # Book ratings data
├── templates/
│   ├── index.html                  # Home page template
│   └── recommend.html              # Recommendation page template
├── static/                         # CSS, JS, and image assets
├── requirements.txt                # Python dependencies
└── README.md                       # Project documentation
```

## 🔧 How It Works

**Data Processing** · Merges books, users, and ratings datasets · Filters users with 200+ ratings and books with 50+ reviews · Handles data cleaning and duplicate removal

**Popularity-Based Recommender** · Calculates average ratings and vote counts · Filters books with minimum 250 ratings · Ranks by average rating for reliable recommendations

**Collaborative Filtering** · Creates user-item matrix using pivot tables · Computes cosine similarity between books · Finds books similar to user's input using nearest neighbors

**Real-time Recommendations** · Takes book title as input · Processes through trained similarity matrix · Returns top 4 most similar books with metadata

## 🎯 Algorithm Details

The system uses **Two Recommendation Approaches**

**Popularity-Based** · Simple ranking by average rating and vote count · Great for new users without rating history · Provides globally popular recommendations

**Collaborative Filtering** · Cosine similarity on user-item interaction matrix · Memory-based approach using k-nearest neighbors · Personalized recommendations based on user behavior patterns

## 📊 Dataset

**Source** · Book Crossing Dataset  
**Books** · 270,000+ book records  
**Users** · 278,000+ registered users  
**Ratings** · 1.1M+ book ratings (scale 1-10)  
**Features** · Book titles, authors, publication years, ISBNs, cover images  

## 🎮 Usage

### Home Page - Top 50 Books
1. **Browse Popular Books** · View curated list of top-rated books
2. **Book Details** · See book covers, authors, ratings, and vote counts
3. **Visual Cards** · Modern card-based layout with hover effects

### Recommendation Page
1. **Enter Book Title** · Type the name of a book you enjoyed
2. **Get Suggestions** · Click "Discover" to receive personalized recommendations
3. **Explore Results** · Browse similar books with covers and author information
4. **Try Suggestions** · Use popular search tags for quick discovery

<div align="center">
  <img src="recommend_screenshot.png" alt="Bev-Book_Recom Recommendation Interface" width="700"/>
  <p><em>Smart recommendation engine with modern search interface</em></p>
</div>

## 🔮 Future Enhancements

- [ ] **User Profiles** · Personal accounts with reading history and preferences
- [ ] **Advanced ML Models** · Deep learning approaches like neural collaborative filtering
- [ ] **Content-Based Filtering** · Recommendations based on book genres, themes, and descriptions
- [ ] **Hybrid Approach** · Combine multiple recommendation techniques
- [ ] **Real-time Reviews** · User-generated reviews and rating system
- [ ] **Mobile App** · React Native or Flutter mobile application
- [ ] **Social Features** · Friend recommendations and reading groups
- [ ] **API Integration** · Connect with Goodreads, Amazon, or Google Books APIs

## 📈 Model Performance

**Accuracy** · High precision in finding similar books based on user preferences  
**Coverage** · Recommends from 50+ popular books with sufficient rating data  
**Diversity** · Balanced recommendations across different genres and authors  
**Scalability** · Pre-computed similarity matrix ensures fast response times  

## 🎨 UI/UX Features

**Modern Design** · Dark theme with gradient backgrounds and glass-morphism effects  
**Responsive Layout** · Works seamlessly on desktop, tablet, and mobile devices  
**Smooth Animations** · CSS transitions and JavaScript interactions for engaging UX  
**Accessibility** · Proper contrast ratios and semantic HTML structure  
**Performance** · Optimized images with lazy loading and error handling  

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

**CampusX** · for the comprehensive [original tutorial](https://www.youtube.com/watch?v=1YoD0fg3_EM&t=5947s) that served as the foundation for this project 
**Book-Crossing Dataset** · Community-contributed book rating data  

## 📬 Contact

**Bevin Samraj** · bevinsamraj.work@gmail.com

**GitHub** · [https://github.com/bevinsamraj](https://github.com/bevinsamraj)  
**LinkedIn** · [https://www.linkedin.com/in/bevin-samraj-s-52991b249](https://www.linkedin.com/in/bevin-samraj-s-52991b249)

Project Link: [https://github.com/bevinsamraj/](https://github.com/bevinsamraj/)
---

<div align="center">
  <p>⭐ Star this repo if you found it helpful!</p>
  <p>Made with ❤️ and lots of 📚</p>
</div>﻿# Book_Recommendation_System
