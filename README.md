
# T20_2022_players_analysis



Problem statement
We are going to have a Cricket match with folks from other planet so we want to Find top 11 cricket players from earth for that we analysed players based on T20 World Cup 2022.

This project so good with a lot of learning

## 1.Web Scrapping
Learned web scrapping, used beautiful soup and a selenium
wrote code for scrapping all matches
wrote code for scrapping all batting summary and bowling summary from all matches
wrote code for fetching players profiles this a bit challenging as all data wasn't in a single table, also need to scrap image and there is a problem in image scrapping there some websites who uses lazy loading that means while whole website is laoding they put random image with very small size so if you scrap data using beautifulsoup you will get those lazy images so i used selenium is like browser in terminal, so i opend that website through it, and waited for laoding (10 sec) then scrapped data and images from it took near 2hr time to run whole program and scarp data although in between code breaks many times and i have to debug it.
finally all data scrapped got all 4 csv files (matches, batting summary, bowling summary, profile ).
## 2. Data Transformation and cleaning
Removed depulicates row from all files
Removed extra charcaters from coloumns
Trimmed the columns
Found out that there are some duplicates row in profiles csv due to lazy images so have to delete them also there were some columns got wrong data due to change in profile section of website which i missed while writing the scrapping code for profile
so used profile file provided by codebasics to correct mine.
## 3. Dashboarding
Dashboarding of this project was beautiful and functional which taught me alot, I used buttons, tooltip, learned how to navigate through pages using buttons, it is like my intro to so many things that powerBI can do still there is lot to know and lot to learn which i will learn by doing such projects slowly.

Below is Final Dashboard, created button to navigate through different pages, this page is for power hitters showing some metrices of power hitters
## Player Analysis  ![thumbnil](https://github.com/nahidkawsar/T20_2022_players_analysis/assets/149723828/94d5d608-e152-4097-8d47-6376eb8eea4d)

## Final Selection For Best 11 players ![1](https://github.com/nahidkawsar/T20_2022_players_analysis/assets/149723828/15df03f6-4762-474d-9e41-e6ef0646199a)

