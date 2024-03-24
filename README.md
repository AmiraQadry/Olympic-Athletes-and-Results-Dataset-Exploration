# Olympic Athletes and Results Dataset Exploration

## Overview
This dataset [120 years of Olympic history: athletes and results](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results/data) provides information about athletes' demographics and their performance in various Olympic games over the past 120 years. It includes details such as age, height, weight, sex, team, and the medals won by athletes. The dataset allows for exploration of trends, patterns, and insights into the world of Olympic sports.

## Dataset Information
- **ID**: Unique identifier for each athlete
- **Name**: Athlete's name
- **Sex**: Gender of the athlete (M or F)
- **Age**: Age of the athlete
- **Height**: Height of the athlete in centimeters
- **Weight**: Weight of the athlete in kilograms
- **Team**: Team name
- **NOC**: National Olympic Committee 3-letter code
- **Games**: Year and season of the Olympic games
- **Year**: Year of the Olympic games
- **Medal**: Medal won by the athlete (Gold, Silver, Bronze, or NA if no medal won)

## Exploratory Data Analysis (EDA)

### Data Cleaning
- Checked for missing values and handled them by filling with mean values or dropping rows/columns.
- Removed duplicate entries to ensure data integrity.

### Insights
1. **Demographics**: Most athletes fall within the age range of 20-30 years, with a fairly normal distribution of height and weight among athletes.
2. **Gender Distribution**: There are more male athletes compared to female athletes participating in the Olympics.
3. **Top Countries**: The USA, Soviet Union, and Germany have consistently had the highest number of athletes across different Olympic games.
4. **Trends Over Time**: The number of athletes participating in the Olympics has varied over the years, indicating changing levels of participation and interest.
5. **Height and Weight Relationship**: There is a positive correlation between height and weight among athletes, indicating that taller athletes tend to have higher weights.
6. **Popular Sports**: Athletics, swimming, and rowing emerge as the most popular sports, attracting a significant number of athletes.
7. **Age Distribution Across Sports**: Different sports attract athletes of varying age groups, suggesting diverse participation across different sports.
8. **Gender Distribution Across Sports**: Some sports show a balanced distribution of male and female athletes, while others are more skewed towards one gender.
9. **Medal Distribution**: The distribution of medals (gold, silver, bronze) among athletes is relatively balanced, with each category constituting roughly one-third of the total medals awarded.
10. **Geographical Distribution of Medals**: The choropleth map provides a visual representation of the number of medals won by each country, showing variations in medal counts across different nations.

## Visualizations
- Histograms showing the distribution of age, height, and weight among athletes.
- Bar charts illustrating the gender distribution of athletes, top countries with the highest number of athletes, and the number of athletes over the years.
- Box plots showcasing the distribution of age across different sports.
- Bar charts displaying the distribution of athletes by sport and gender.
- Pie chart representing the percentage of each medal awarded at the Olympics.
- Choropleth map indicating the geographical distribution of medals won by each country.

## Conclusion
The exploration of the Olympic athletes and results dataset provides valuable insights into the demographics, participation trends, and performance achievements in Olympic sports over the years. The dataset serves as a rich resource for further analysis and research in the field of sports analytics and Olympic studies.
