# Project2_Crypto_db
-------------------------------------------------------------------------------
Analysis Between Types of Cryptocurrencies 
-------------------------------------------------------------------------------

Crypto-currency has not only grown in popularity, but in value as well. As a team, we are attempting to determine the trends occurring between each type of crypto: Bitcoin, Dogecoin, and Ethereum, and eventually, find which one is the most valuable. We decided to create an analysis from data collected over the past 3 years (2019, 2020, and 2021) for each crypto type, to come to a decision regarding this manner. Throughout this project, the following skills were used: cleaning data using Pandas, uploading data onto MongoDB, filtering data based on potential questions to answer, and the use of certain functions needed to replace the original data that was provided. 

We began by dropping the null values and unnecessary columns from the datasets in order to look at relevant information. After formatting and renaming the columns, we set the values in the according decimal values (e.g. values to the hundredth or ten-thousandth place). The main function that was used to reframe this dataset was using the function to convert an epoch timestamp to a readable timestamp. By importing "datetime", the function was ran and converted the time to year, month, date, hour, minute, and second, respectively. We inserted the modified data into the column so that everything was fluently understood. The same code was ran through the three years for each crypto-currency. 

Once the data was cleaned in Pandas, the new and updated CSV files were uploaded onto MongoDB. The process of having all nine datasets in the database did not take a long time. We were immediately able to see each input, and even filter it out by crypto-currency type. This step was helpful by having all information in one database where it could be modified once granted access to it. For the upcoming year, this is where the inputs would be added. 

Potential analysis could range in a wide amount of questions. The ones that we listed, and thought would be interesting to answer are the following:

1. What trends are there based on time by cryptocurrency?
2. What was the highest increase out of the four calendar quarters?
3. What (year, quarter, month) had the most volume? The least?
4. Which cryptocurrency trades the most?

In conclusion, ETL is used to easily access the data, modify, and add to the inputs that have been placed there. MongoDB was one of the databases where the data could easily be read and manipulated, thus, the reason why we chose it specifically. A lot of analysis could be derived from this, as well as future predictions being made. A combination of skills that we have learned throughout this course were used to accomplish the goal as well. Utilizing Pandas, specific functions to change the epoch time, and loading the data onto MongoDB was where we collaboratively worked for this project. 

***********************************
Data Limitations
-----------------------------------
Some of the data limitations that we faced for this specific project included the fact that the nine (9) total CSV files would take a long time to upload. Once every dataset was imported into MongoDB, pushing the data back into Jupyter to make some further analysis would take about 30 minutes, even more at times. Other times, it would cause the computer to crash. Total, there were about 4.2 million inputs form all 9 datasets, therefore, it would take longer for any data that has more than what was uploaded in this project. Another data limitation that we would consider for this specific project would be the inconsistencies in each of the inputs. For example, there would be a day that does not have any inputs for 20 minutes total, and the next has trades for each minute of the day. Depending on the analysis that is being done, this could negatively affect the data. 

Some way to fix these problems is simply allow room for error. By displaying the analysis in a box and whisker plot, the diagram would give us a better idea as to what exactly we may be looking for. Another way to fix this issue would be to simply further clean the data and create different tables for each question that is being asked. Although it may take longer to code, it would not take as much time to be pushed back into Jupyter once uploaded onto MongoDB. Overall, however, the analysis can be done.

***********************************

***********************************


Utilized Data Files:
-----------------------------------
Bitcoin CSV Files:

•https://www.kaggle.com/yamqwe/cryptocurrency-extra-data-bitcoin?select=full_data__1__2019.csv

•https://www.kaggle.com/yamqwe/cryptocurrency-extra-data-bitcoin?select=full_data__1__2020.csv

•https://www.kaggle.com/yamqwe/cryptocurrency-extra-data-bitcoin?select=full_data__1__2021.csv

Dogecoin CSV Files:

•https://www.kaggle.com/yamqwe/cryptocurrency-extra-data-dogecoin?select=full_data__4__2019.csv

•https://www.kaggle.com/yamqwe/cryptocurrency-extra-data-dogecoin?select=full_data__4__2020.csv

•https://www.kaggle.com/yamqwe/cryptocurrency-extra-data-dogecoin?select=full_data__4__2021.csv

Ethereum CSV Files:

•https://www.kaggle.com/yamqwe/cryptocurrency-extra-data-ethereum?select=full_data__6__2019.csv

•https://www.kaggle.com/yamqwe/cryptocurrency-extra-data-ethereum?select=full_data__6__2020.csv

•https://www.kaggle.com/yamqwe/cryptocurrency-extra-data-ethereum?select=full_data__6__2021.csv

**************************************

Below are the slides for the data presentation:


![Slide1](https://user-images.githubusercontent.com/72631173/145684091-d43680ff-4678-4929-9e0b-e5918c825c39.png)
![Slide2](https://user-images.githubusercontent.com/72631173/145684099-e09cdb1e-f992-46bd-b10d-e6df8d8cb012.png)
![Slide3](https://user-images.githubusercontent.com/72631173/145684110-d946f24f-6dce-46d4-8155-6ea53bbe12a4.png)
![Slide4](https://user-images.githubusercontent.com/72631173/145684117-c835063e-91b4-4cc7-88c5-7e3f3ab55ecf.png)
![Slide5](https://user-images.githubusercontent.com/72631173/145684123-a7e22b5e-30e7-43fd-a3f0-ea090f05e031.png)
![Slide6](https://user-images.githubusercontent.com/72631173/145684129-7d07abc5-c2ea-41cb-bab8-4a447a994bdd.png)
![Slide7](https://user-images.githubusercontent.com/72631173/145684135-7e3454df-c52a-4dcb-849c-ff1e302b899b.png)
![Slide8](https://user-images.githubusercontent.com/72631173/145684142-94efdab2-e05f-4706-a7ad-02ade82335db.png)
