# Star-Wars-Survey

While waiting for [Star Wars: The Force Awakens](https://en.wikipedia.org/wiki/Star_Wars:_The_Force_Awakens) to come out, the team at FiveThirtyEight became interested in answering some questions about Star Wars fans. In particular, they wondered: does the rest of America realize that “The Empire Strikes Back” is clearly the best of the bunch?

The team needed to collect data addressing this question. To do this, they surveyed Star Wars fans using the online tool SurveyMonkey. They received 835 total responses.

For this project, I will be cleaning and exploring the [data set](https://github.com/fivethirtyeight/data/blob/master/star-wars-survey/StarWars.csv) in Jupyter notebook.

The data has several columns, including:

    RespondentID - An anonymized ID for the respondent (person taking the survey)
    Gender - The respondent's gender
    Age - The respondent's age
    Household Income - The respondent's income
    Education - The respondent's education level
    Location (Census Region) - The respondent's location
    Have you seen any of the 6 films in the Star Wars franchise? - Has a Yes or No response
    Do you consider yourself to be a fan of the Star Wars film franchise? - Has a Yes or No response

There are several other columns containing answers to questions about the Star Wars movies. For some questions, the respondent had to check one or more boxes. This type of data is difficult to represent in columnar format. As a result, this data set needs a lot of cleaning.

This dataset is mainly about the story [America’s Favorite ‘Star Wars’ Movies (And Least Favorite Characters).](https://fivethirtyeight.com/features/americas-favorite-star-wars-movies-and-least-favorite-characters/)

The main dependencies used in this project are pandas,numpy and matplolib.

