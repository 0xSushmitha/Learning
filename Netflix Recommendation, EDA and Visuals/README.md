# 🔴 Netflix Recommendation System with Exploratory Data Analysis and Visuals 🥤🍿

## Datasets
This project utilizes three datasets, which you can find in this Kaggle link: [Netflix Recommendation and EDA Data](https://www.kaggle.com/karan842/netflix-recommendation-and-eda/data).

## 🔵 About the Project
This recommendation system project is based on datasets from **Netflix**, **IMDb**, and **Books**. Netflix is one of the most popular platforms for streaming movies and TV shows globally. According to Wikipedia, Netflix's net worth was USD 2.761 billion in 2020.

<img src='screenshots/netfllix.jpg' height='400px'></img>

The project also explores how many movies and shows on Netflix are inspired by books 📚. We utilize two IMDb datasets: one for **IMDb ratings** and the other for **IMDb movies**.

Visualizations in this project are created using Matplotlib, Seaborn, WordCloud, and Plotly. The project employs **Natural Language Processing (NLP)** techniques, as all datasets consist of text data, to create the **Netflix Recommendation System**.

For building the recommendation system, I implemented two techniques: **TF-IDF (Term Frequency-Inverse Document Frequency)**, which performed well, and **CountVectorizer** along with **Cosine Similarity** for improved accuracy.

## 🟢 Approach
The approach follows a classical machine learning method. First, I imported all the necessary Python libraries and loaded the Netflix dataset for initial visualization. Next, I loaded the two IMDb datasets (ratings and movies) and began exploring the collected data through visualization, data cleaning, and creating subsets for better analysis. Additionally, I showcased content using **WordCloud**.

## 🟡 Recommendation System
The main goal of this project is to create a recommendation system. Since our data is text-based, I utilized **NLP** concepts. I tested the recommendation system on popular Netflix shows and movies such as **F.R.I.E.N.D.S.**, **PEAKY BLINDERS**, **NARCOS**, and **3 IDIOTS**.

## 🟣 Issues Encountered
While plotting some visuals using the **Plotly** library, I encountered issues where the visuals were not visible in the GitHub notebook. Here are the visuals generated:

Output of code line 98 in the notebook file:
<img src='screenshots/Screenshot (12).png' height='300px' width='500px'></img>

Output of code line 136 in the notebook file:
<img src='screenshots/Screenshot (14).png' height='300px' width='auto'></img>

## 🟠 Thank You
Thank you for your time! Corrections and suggestions are always welcome. 😉