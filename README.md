# Personalized Book Recommender

## Project Overview
The primary objective of this project is to develop a **book recommendation system** that provides personalized book suggestions based on users' preferences and interests. The system analyzes historical book data to suggest relevant books that align closely with the user's reading habits.

### Key Features:
- Personalized book recommendations
- Cosine similarity algorithm to find similarity between books
- Interactive web application created using **Streamlit** for real-time recommendations
- Model saved using **Pickle** for easy deployment

## Dataset
The book dataset used in this project is obtained from **Kaggle**. This dataset contains information about various books, including their titles, authors, genres, and user ratings. The data is analyzed and processed using Python libraries such as **pandas** and **numpy**.

- **Link to the Dataset**: [DataSet](https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset)

## Project Details
### Technologies Used:
- **Python**: The main programming language used for analysis and modeling.
- **pandas**: For data manipulation and cleaning.
- **cosine similarity**: Used to calculate the similarity between books.
- **pickle**: For saving the trained model.
- **Streamlit**: For building an interactive web application that allows users to input book details and receive personalized recommendations.

### Workflow:
1. **Data Analysis**: The dataset is first cleaned and processed using pandas. The relevant features such as book title, author, and genre are extracted for recommendation.
2. **Modeling**: Cosine similarity is applied to measure the similarity between books based on the features.
3. **Web Application**: A user-friendly interface is created using Streamlit, where users can input book details, and the app will provide personalized recommendations based on the user's input.
4. **Deployment**: The trained recommendation model is saved using pickle for easy deployment and future use.

## Instructions to Run the Project Locally
### Step 1: Clone the Repository
Clone this repository to your local machine using the following command:
```bash
git clone https://github.com/jaswanthaitha21/Book_Recommendation_System.git
