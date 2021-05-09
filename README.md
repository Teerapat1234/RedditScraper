DESCRIPTION:<br/>
This project is one of the 2 main part project, called "Using SIR to predict and visualize the rise and fall of meme trends on Reddit".<br/>
This repositry only contains the code that will scrape data from 3 subreddits, being r/dankmemes, r/memes, r/funny, and save them in a formatted Json file.

WORKING FOLDER:<br/>
The main primary working code (Python 3.8) of this project is located in Redditscraper/crontab/main.py<br/>

HOW TO RUN:<br/>
-First, you need to set up a "database", in this case, you need to create a folder named "json" with 3 sub-folders inside being "dankmemes", "memes", and "funny". <br/>
-Next, go open up Redditscraper/crontab/main.py and redirect every single path variables in the project to that of your newly created json folder.<br/>
-In that file, you'll see a Reddit API missing important components on line 105. This is where you have to create your own Reddit account along with creating your own key. You can follow the instructions here
 https://stackoverflow.com/questions/28955541/how-to-get-access-token-reddit-api<br/>
-Lastly, import the necessary imports listed in the file, and you're set!

DISCLAIMER:<br/>
-The site takes forever to run, so keep that in mind.
