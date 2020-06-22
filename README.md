# Movie-Industry-Analysis
An analysis of the movie industry for prospective business stakeholders.

# Repository
Questions answered by the team are located in the "Team Questions Folder"
"How Big Should the Budget be? How has that changed over the Years?" is located in the "Median Budget Changes.ipynb" file
"What is the most profitable genre?" is located in the "What is the Highest Grossing Genre.ipynb" file (the question and the file are labeled wrong: "What is the most profitable genre?" should be used instead of the "What is the Highest Grossing Genre"

My personal question and my part of cleaning is located in the "Teammate Work" folder in the "Alex cleaning and personal question (how does budget affect profitability and revenue).ipynb"	
The question is "How does budget affect revenue and profitability"
The dataframes cleaned are located under the "Dataframes cleaned by Alex" heading (AT1: dataframe_id_imdb_title_basics_gz.csv AT2: dataframe_id_imdb_title_crew_gz.csv AT3: dataframe_id_imdb_title_principals_gz.csv)

The presentation is the "Movie Industry Analysis(1).pdf" file

The rest of the files in the home folder are a mix of original datasets and cleaned versions, "ZipFolders" contains the majority of the original datasets, Backups and Copies" contains the initial workbooks we used to clean data and answer questions, "Miscellaneous" contains a mix of merged and cleaned dataframes and partial attempts to answer some questions

## Goals
Microsoft has asked us to give a presentation on how to get started in the movie business.  

To that end, in this study we will answer the following:
* What is the highest grossing genre on average?
* How much should the you spend on a film production? How have budgets changed over the years?
* What time of the year is it most profitable to release a movie?

### Data Sets and Resources:
We used API's from the following databases:
* Box Office Mojo
* IMDB
* Rotten Tomatoes
* TheMovieDB.org

## What is the highest grossing genre on average?
### Initial impressions
With the popularity of frachises such as the Marvel Cinematic Universe and Star Wars,
it goes without saying that the "Adventure" genre is pretty popular, but what are some other popular genres?

### Findings and Conclusions
![Imgur](https://i.imgur.com/kpjkSiN.png)

There we have it! Adventure is the most profitible genre with animation not far behind it. Documentaries, despite being popular on Netflix, just don't sell well at the box office. This is probably a result it having a niche audience. One caveat about our analysis is that it is too linear. This implies that each movie only falls under a single genre. This is rarely the case, however, since most movies fall into multiple genres.

### Recommendations

For now, it is safe to say that you should create an adventure film, but it would be worth looking into what combination of genres will yield the most profit (e.g., Adventure, Animation, and Fantasty, or Romantic-Comedy/Fantasy).

## How much should the you spend on a film production? How have budgets changed over the years?

### Initial Thoughts 

Initially, we thought that the median budget for a film was around $50 million.  Considering big budget films like Harry Potter and the Chamber of Secrets had a budget of $100 million (TheNumbers), $50 million seems like a modest amount.

### Findings and Conclusions
![Imgur](https://i.imgur.com/gkI3Skq.png)

Well, we were off by a few million! Thanks to advent of modern technology, such as, visual studio effects, CGI, etc, budgets have decreased. 30 years ago, that extra expenditure  would have gone towards, car explosions, pyrotechnics, and stuntmen.  However, we do see that, even during the recession in the 2000's, there is a slow but steady increase in the amount of money spent on the production budget.

### Recommendation

Currently we recommend the budget be set to $38 million, as our studies have concluded to the be the median amount spent.  We also want you to keep in kind that the budget, according to the market trend, will continue to rise as demands for spectacle increase.

## What time of the year is it most profitable to release a movie?

### Initial Thoughts
This one is a little a little tricky for me personally because I know that summer is usually when a lot of the big hitter movies come out.  Winter has always been heavy with movie releases.  Then there's the fact that all of the Oscar contenders usually release in the fall.  Personally, I felt that summer was probably most profitable, are there other profitable times as well?

### Findings and Conclusions
![Imgur](https://i.imgur.com/mEVnN3U.png)

Well, summer wins by a land slide, though you want to get started quickly.  To maximize profits, you're going to want to release starting in May and no later than June.  There is a steep drop off once you hit July and people are spending money on Back-to-School supplies.  The holiday season is also very profitable since families are spending a lot of time together.  Those profits drop off steeply come the beginning of the year, most likely because of people wanting to replenish their bank accounts after the holiday season.  As for why Oscar contenders are released during a less profitable time, I believe it's because the studios don't want to have their movies overlooked during the flood of cinema releases during the summer.  

### Recommendation

To maximize profit, begin releasing in May and no later than June. 

## How does budget affect revenue and profitability?

### Initial Thoughts 
My initial thinking was that the higher budget could lead to lower profitability because higher level of revenues would be required to make a movie profitable. The relationship between budget and revenue was also not clear since there are many examples of movies that were popular, even though they had a low budget. Furthermore, some movies historically failed to gain traction despite high budget.

### Findings and Conclusions

![Imgur](https://i.imgur.com/5AEIB9W.png)
![Imgur](https://i.imgur.com/YKiOwrd.png)

As we can see from the "Budget versus profit trend" visualization, there is a strong relationship between the size of the budget and the revenue. As budget of the movie increases, its revenue also increases. As we can see from the "Budget and profitability" visualization, when the budget is on the lower side (sub $150MM USD) there is a higher proportion of movies that are unprofitable. This can be explained by that the higher budget movies are typically blockbuster that appeal to a wider audience and the fact that movies with higher budgets are more rigourously vetted.

### Conclusion
To increase the chances of profitability, be prepared to increase the budget!

## Thank you for considering our team for your research!

