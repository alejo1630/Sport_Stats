# Olympic Data Analysis

Data analysis of information from the summer and winter Olympic games over the years. UC Davis SQL Specialization Final Project

## 🔰 What is it about?

In this SQL project, we delve into the rich dataset of Olympic sports, examining the correlation between countries and their performance across various sports in both summer and winter games. Additionally, we explore the distribution of medals by gender and age, shedding light on the patterns and trends within these demographics. The findings of this project could be of keen interest to various stakeholders, including sports federations, national Olympic committees, and even potential sponsors. Understanding which sports resonate more strongly with different demographics and regions can inform strategic decisions regarding athlete development, resource allocation, and sponsorship investments. Thus, the audience for this project ranges from sports enthusiasts and analysts to marketing professionals seeking insights into the dynamics of Olympic sports participation and performance.

<img src = "https://raw.githubusercontent.com/alejo1630/Sport_Stats/main/ERD.png" width = "700">

### Main Questions
1. **Medal Distribution**: How does the distribution of medals across different sports vary between summer and winter Olympic games?
2. **Age and gender performance**: What are the age and gender demographics of athletes who tend to win the most medals, and does this vary by sport?
3. **Countries performance**:Are there any notable trends or correlations between a country's overall medal count and its performance in specific sports, both in summer and winter games?
4. **Correlation between age and performance**: Is there a correlation between the age of athletes and their performance in different sports?
2. **Gender disparity in sports participation**: Despite the overall gender ratio of athletes being 3:1, are there specific sports or countries where the gender gap is narrower or wider?
3. **Long-term trends in Olympic performance**: How has the performance of countries in the Olympics evolved over time? Are there any noticeable trends in terms of the rise or decline of certain nations in specific sports or across seasons?

### Hypotesis
`Certain countries may exhibit a consistent dominance in specific sports across both summer and winter Olympic games. For example, countries with a strong tradition in winter sports may perform exceptionally well in disciplines like skiing or ice hockey during the Winter Olympics.`

### Approach
To prove or disprove the hypotheses, I will initially focus on several key features from the provided SQL database. Firstly, I will examine the 'Country' or 'NOC' (National Olympic Committee) column to analyze the distribution of medals by country across different sports and Olympic seasons. This will help me identify any patterns of dominance or specialization. Next, I will explore the 'Sport' column to investigate the relationship between specific sports and the countries' performance. This will involve examining which countries excel in which sports and whether these trends differ between summer and winter games. Additionally, I will delve into the 'Age' and 'Sex' columns to assess any correlations between athlete demographics and medal counts, using metrics such as average age of medalists or gender distribution of medals. Lastly, I will employ metrics like correlation coefficients

## 💠 Insights

### Key Points
In my analysis of the Olympics dataset spanning various years, several intriguing patterns and statistics have emerged, shedding light on the diverse dynamics of the games across different seasons and countries.

Firstly, it's evident that the Summer Olympics attract significantly more athletes than their Winter counterpart, with a ratio of 6:1. Moreover, there's a notable gender skew, with male athletes outnumbering female athletes by a ratio of 3:1 across both seasons.

Age-wise, the spectrum of participants ranges widely, from the youngest at 10 years in Gymnastics for the Summer Olympics to 11 years in Figure Skating for the Winter Games. Conversely, the oldest competitors clock in at 97 years for the Summer Olympics (in Art Competitions) and 58 years for the Winter Olympics (in Curling).

Interestingly, statistical analysis reveals that male athletes tend to be older, taller, and heavier compared to their female counterparts, regardless of the season.

When it comes to national representation, the United States, Great Britain, and France boast the highest number of athletes in the Summer Olympics, while the Winter Olympics see dominance from the United States, Canada, and Italy.

Geographically, most Winter Olympic athletes hail from the northern hemisphere, though outliers like Argentina, Australia, and New Zealand also participate actively.

In terms of medal tallies, the top three countries in the Summer Olympics are the USA, Russia, and Germany. Meanwhile, in the Winter Olympics, Russia leads the pack, followed closely by the USA and Germany.

An intriguing metric emerges when examining the ratio of total medals to total athletes per country. While Russia, the USA, and Germany maintain their dominance in the Summer Olympics, the Winter Games witness an unexpected shift, with Russia, India, and Finland boasting the most efficient medal-per-athlete ratios. India's prowess in winter sports, particularly Alpinism, stands out, while Finland's strength lies in traditional winter disciplines like Ice Hockey, Ski Jumping, and Cross Country Skiing.

Finally, the top three countries in terms of gold medals reflect their prowess in specific sports. In the Summer Olympics, the USA dominates in Swimming, Germany excels in Rowing, and Russia shines in Gymnastics. Meanwhile, in the Winter Olympics, Canada, Russia, and the USA dominate the podium in Ice Hockey.

During the Summer Olympics, the United States saw remarkable peaks in medal performance in 1904, 1932, and 1984. The 1904 Olympics were held in St. Louis, USA, where American athletes showcased their dominance across various sports. In 1932, Los Angeles, USA, hosted the Olympics, providing American athletes with a home advantage, resulting in a significant medal haul. The peak in 1984 coincides with the Los Angeles Olympics, where Team USA's success was celebrated on home soil, further fueling the nation's sporting pride. Russia's notable peak in medal performance during the Summer Olympics occurred in 1980, when Moscow, Russia, hosted the Games. The strong showing by Soviet athletes on home turf contributed to a memorable Olympic Games for the nation. Germany's exceptional performances in the Summer Olympics, particularly in 1936 and 1972, were highlighted during the Berlin Olympics and the Munich Olympics, respectively, where German athletes excelled in front of their home audiences, showcasing the nation's athletic prowess on the world stage.

### Hypotesis Analysis
The hypothesis that certain countries maintain a consistent dominance in specific sports across both the Summer and Winter Olympics is indeed supported by the data analysis conducted. This pattern highlights the deep-rooted traditions and strengths that certain nations possess in particular athletic endeavors.

One of the most prominent examples of this phenomenon is evident in the realm of winter sports. Countries with a rich heritage and infrastructure in winter sports, such as Finland, Canada, and Russia, consistently excel in disciplines like Ice Hockey, Ski Jumping, and Cross Country Skiing. This dominance extends across multiple editions of the Winter Olympics, showcasing the enduring prowess of these nations in these specialized events.

Similarly, in the Summer Olympics, we observe certain countries consistently leading the medal tables in specific sports. The United States, for instance, has historically been dominant in Swimming, while Germany has showcased remarkable strength in Rowing. Russia's stronghold in Gymnastics further exemplifies this trend.

This consistency in performance can be attributed to various factors, including robust training programs, cultural emphasis on certain sports, and investment in infrastructure. For countries with a strong tradition in winter sports, the availability of suitable terrain and facilities plays a crucial role in nurturing talent and fostering excellence.

Furthermore, the specialization of athletes and coaches in particular sports over generations contributes to the sustained success of these nations. By focusing resources and efforts on disciplines where they have a competitive advantage, countries can maintain their position at the forefront of Olympic competition.

Overall, the data analysis supports the hypothesis that certain countries exhibit a consistent dominance in specific sports across both the Summer and Winter Olympics. This trend underscores the enduring legacy of athletic excellence and the profound impact of cultural heritage and investment in sports development.
