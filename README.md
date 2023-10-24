# DataCamp Project

## Netflix Movie Duration Analysis

Netflix, founded in 1997 as a DVD rental service, has evolved into the world's leading entertainment and media company. As of January 2021, it boasts over 200 million subscribers. With its vast library of movies and series, it presents an exciting opportunity to explore trends in the entertainment industry.

### Introduction

This project aims to analyze the duration of movies on Netflix and determine if there is a trend of decreasing movie lengths over time. Our friend provided data showing the average movie durations for the years 2011 to 2020, which we'll investigate. The provided average movie durations are as follows: 103, 101, 99, 100, 100, 95, 95, 96, 93, and 90 minutes, respectively.

### Data Handling

#### Loading Data into a Dictionary

To begin our analysis, we created a Python dictionary containing movie years and their respective durations.

```python
## Create the years and durations lists
years = [2011, 2012, 2013, 2014, 2015, 2016, 2017, 2018, 2019, 2020]
durations = [103, 101, 99, 100, 100, 95, 95, 96, 93, 90]

## Create a dictionary with the two lists
movie_dict = {
    "years": years,
    "durations": durations
}
```

#### Creating a DataFrame

We then converted the dictionary into a Pandas DataFrame for further analysis.

#### Visual Inspection

A visual inspection of the data was carried out through a line plot, demonstrating the average movie duration trends over the specified years.

### Data Exploration

#### Loading the Full Dataset

To explore the trend in greater detail, we obtained the original dataset, which includes information on various movies and TV shows on Netflix.

#### Filtering for Movies

We filtered the dataset to focus exclusively on movies, ignoring TV shows. A new DataFrame, `netflix_movies_col_subset`, was created, containing information about movie titles, countries, genres, release years, and durations.

#### Scatter Plot

To visualize the data, a scatter plot was generated, with release years on the x-axis and movie durations on the y-axis.

### Genre Analysis

To delve deeper into the shorter movie durations, we identified that genres such as "Children," "Documentaries," and "Stand-Up" often have shorter movies. These genres were highlighted in different colors on the scatter plot, providing insights into the potential influence of genre on movie duration trends.

### Conclusion

The analysis has allowed us to explore trends in Netflix movie durations, highlighting the influence of genres on shorter movie lengths. This project provides a foundation for further investigation into the entertainment industry and movie trends over time.

### Next Steps

Further data analysis could include statistical tests to confirm the observed trends and explore the impact of other factors on movie durations, such as genre, country of origin, or viewer preferences.

