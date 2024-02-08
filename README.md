## pandas-course-project
## Zero to Pandas Course Project **_Analysis on Catholic Population Around the World_** hosted by [jovian.com](https://jovian.com/dajo09/catholic-population-worldwide-analysis)
<img src="https://www.crossed-flag-pins.com/animated-flag-gif/gifs/Vatican-City_240-animated-flag-gifs.gif"
style="width:490px; float: left; margin: 0 0px 0px 0px;"></img>

# Data Analysis on Catholic Population Around the World


The **Vatican City** officially the **Vatican City State** is the smallest independent state in the world and residence of the spiritual leadership of the Roman Catholic Church. Its territory is surrounded by the Italian capital city Rome, and priests and nuns of many nationalities make up almost all of the population

***



#### The dataset used in this analysis is from [Wikipedia](https://en.wikipedia.org/wiki/Catholic_Church_by_country)

sample Panda source code:

plt.figure(figsize=(11,8))
plt.rcParams.update({'font.size': 12})

#rotate labels 90 degrees
plt.xticks(rotation=85) 

#chart title
plt.title('20 Countries with the most Catholic Population')
sns.barplot(x = top_cath_pop.Country, y = top_cath_pop.TotalCatholicPerCountry, 
            palette='rocket');

<img width="722" alt="sample Panda chart" src="https://github.com/dajo09/zero-to-pandas-project-Data-Analysis-on-Catholic-Population-Around-the-World-/assets/33592524/7899fb1e-9f2d-4b26-a67b-5bac2092b120">

[view Course Certificate](https://jovian.com/certificate/MFQTEOJRGU)

