# iMBD Movie Rating Project

# Web Page Overview:
![image](https://github.com/MirAb-77/Codsoft-Projects/assets/169236743/23f9647f-8e27-4aec-bf8b-6c8acd811302)


# 🎬 Project: IMDB Movie Rating Prediction

![IMDB](https://upload.wikimedia.org/wikipedia/commons/6/69/IMDB_Logo_2016.svg)

## 🌟 About the Project:

Welcome to the "IMDB Movie Rating Prediction" project! Our mission is to leverage data analytics and machine learning to predict movie ratings. By examining various features of movies such as genre, duration, and key personnel (directors and actors), we aim to create a model that can accurately forecast a movie's IMDB rating. This project not only enhances our understanding of what makes a movie successful but also aids producers, directors, and film enthusiasts in making informed decisions.

## 📁 About the Dataset:

Our dataset is a goldmine of movie information, capturing a wide range of attributes that can influence a movie's rating. Here’s an overview of the dataset's structure:

| Column     | Description                                      |
|------------|--------------------------------------------------|
| **Name**   | Title of the movie 🎬                              |
| **Year**   | Year of release 📅                                |
| **Duration** | Duration of the movie ⏱                          |
| **Genre**  | Genre(s) of the movie 🎭                          |
| **Rating** | IMDB rating ⭐                                    |
| **Votes**  | Number of votes 🗳️                               |
| **Director** | Name of the director 🎥                          |
| **Actor 1** | Name of the lead actor/actress 🎭                  |
| **Actor 2** | Name of the supporting actor/actress 🎭           |
| **Actor 3** | Name of another supporting actor/actress 🎭      |

### Dataset Snapshot:

```plaintext
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 15509 entries, 0 to 15508
Data columns (total 10 columns):
 #   Column    Non-Null Count  Dtype  
---  ------    --------------  -----  
 0   Name      15509 non-null  object 
 1   Year      14981 non-null  object 
 2   Duration  7240 non-null   object 
 3   Genre     13632 non-null  object 
 4   Rating    7919 non-null   float64
 5   Votes     7920 non-null   object 
 6   Director  14984 non-null  object 
 7   Actor 1   13892 non-null  object 
 8   Actor 2   13125 non-null  object 
 9   Actor 3   12365 non-null  object 
dtypes: float64(1), object(9)
memory usage: 1.2+ MB
```

## 🎯 Project Objectives:

Our cinematic journey is driven by these core objectives:

- **Data Exploration**: Dive deep into the dataset to uncover hidden patterns and trends within the movie industry.
- **Feature Engineering**: Transform raw data into meaningful features that can be used to train our predictive model.
- **Predictive Modeling**: Develop and fine-tune machine learning models to accurately predict movie ratings based on various attributes.
- **Insight Generation**: Extract actionable insights that can help filmmakers and producers understand what factors contribute to higher ratings.

Embark on this exciting voyage with us as we explore the world of cinema through the lens of data science! 🎥📊🚀

