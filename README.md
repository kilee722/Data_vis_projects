# Project Title

EDA and Report of Crime Rate Vancouver 2003-2017

### Intro

Vancouver has been named one of the most liveable city in the world for many years. One of the reasons why Vancouver is a highly desirable place to live is probably low local crime rates. However, the overall crime rate in Vancouver is higher than the national average by 26%, and this has become a major concern of Vancouver city council. Although the government of the city of Vancouver are spending millions of dollars, high crime rates in some areas such as Downtown Eastside or Main Street region are still not under control. what makes the crime rate of Vancouver higher than the other Canadian cities? Where should the government budget and resources be spent on to lower the crime rate? In this report, I am introducing major findings and solutions from my analytic studies on crime rate of Vancouver in an effort to answer these questions.

A dataset of 530652 observations on crime incidents between January 2003 and July 2017 is used. The sample also contained variables including type of crime, year, month, day, hour, and minute of when the reported crime activity happened, hundred block as generalized location of the report crime activity, neighbourhood where the crime occurred, x and y for coordinate values projected in UTM Zone 10, and latitude and longitude coordinate values. I found that the crime rate in Vancouver is decreasing and theft types of crimes play a major role in overall crime rate of the city. I also found that theft types of crimes make up a large proportion of total crime number among the top eight most dangerous neighbourhoods in Vancouver whereas break and enter crimes has a larger proportion of total crime incidents in other neighbourhoods.

### Prerequisites

R
All used packages are pre-loaded.


Graph 1

![image](https://user-images.githubusercontent.com/55430338/77514050-506e1300-6e33-11ea-9598-7f4dd5e70826.png)

Anlysis 
Initially, my primary interest laid in a long-term trend of the city’s crime rate and I also wanted to know what is the most frequent type of crime. By looking at total number of crime activities and annual number of each crime type between 2003 and 2017, I wanted to see if any crime type has a similar trend as the total crime trend. As seen in the graphs above, we can clearly see that the annual crime rate swings alike the movement of total crime rate over years. In contrast, the total crime rate trend without theft type crimes steadily decreases over time and a similar tendency is seen in the other types of crimes excluding theft. As over 55% of crimes activities is theft classified crime, this is not surprising. The total crime rate drastically declines from 2003 until 2010, but it starts to increase after 2013. We can see that the total crime rate is reacting strongly to the theft crime trend, and this tells that theft is the most impactable factor. This information suggests that preventing theft crimes is a vital to bring down crime rate of Vancouver. On the other hand, the graph informs that other types of crime such as break and enter, vehicle collision, homicide and mischief have been successfully reduced over time.


Graph 2

![image](https://user-images.githubusercontent.com/55430338/77514108-71366880-6e33-11ea-83dc-79f14428d6e8.png)

Analysis
For my sending finding, I wanted to focus on the most recurrent type of crime in each neighbourhood. However, there were 25 neighbourhoods in the dataset, and it was too many for effective graphical analysis. To deal with having too many data in my graph, I combined neighbourhoods and grouped into two based on total crime number of neighbourhood: Safe community and Unsafe community. Safe community consists of the top eight highest crime rates neighbourhoods and the rest grouped as unsafe community. The left of the graph shows that break and enter type crime is more likely to happen among safe communities as it is 25% out of total crime activities. On the contrary, the percentage of theft crime is 64.3% in unsafe neighbourhoods, and it is significantly higher by 11.6% than the theft crime rate of safe neighbourhoods. This is particularly remarkable finding as we can employ different strategic moves to each neighbourhood such as increase number of patrols as it can prevent theft crimes in dangerous neighbourhoods and install more security systems against burglary in safer neighbourhoods.

Although I did not discuss in depth in this report, there were several other findings from this study. First, I found that case of theft of bicycle increases during summer and drops in winter. Second, break and enter commercial crime has a specific pattern in hour and minute graphs, which tells that such type of crime is highly likely to be organized crime as majority of incidents occured at particular time period. Lastly, homicide and vehicle collision with fatality do not share trend with other type of crime at any time and place, thus such types of crime happen rather unintentionally.

## Summary

Explain how to run the automated tests for this system

In summary, based on my analysis, we see that theft crime is the most significant factor in crime rate of Vancouver. Furthere analysis found that while crime rate of the city is slightly decreasing overall, the increasing of theft crime activities from 2013 is the leading cause of failure of reducing the crime rate further down. It also found that other than theft type crimes, the city has been successfully reducing crime rate. In addition, I also discovered that more dangerous neighbourhoods have a higher percentage of theft crime while less dangerous communities tend to have higher proportion of break and enter type crimes. I believe this report provides some valuable insights to our crime policy council members such as suppressing theft crimes is the key to control Vancouver’s crime rate and taking advantage of using different crime prevention strategies for each neighbourhood to reduce number of crime incidents. Hopefully with this information, our crime policy makers can further decrease the crime rate and make the city safer.

Further analysis can be done if I have more information on certain variables. For example, it would be helpful to know average income of neighbourhood and number of police officers stationed. It would also be helpful to know age of criminals and victims to better predict criminal behavior.

For further information, reach me at klee1@seattleu.edu.
The raw data is obtained from https://www.kaggle.com/wosaku/crime-in-vancouver
