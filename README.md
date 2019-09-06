# Project-1Michael

Theme: Top 5 Greatest Producers
I selected this theme because I love the composition of music and all of the art and talent that goes into making music. One of my favorite producers is Kanye West. Next to JDilla, Kanye West is one of the best producers that use samples from different songs. This project focuses on Kanye West, his music, and what's currently being said about him on twitter. 

------Implementation------
APIs:
This project uses the Genius API to grab the album artwork, song, and artists from the Genius database. In addition to the Genius API, I used the Twitter API to retrieve tweets based on a keyword: "Kanye West". This will display what people are saying about Kanye West. 
This project uses Flask to integrate python and HTML. Heroku will be used to view the web app via url.

------Problems / Issues--------
1) Understanding and getting the hang of committing and pushing to github.
I solved this issue by making a sample environment and repo to practice working with changes to my code.

2) Pushing my web app to Heroku!!!!!
After pushing my web app to Heroku, I got an Application Error. I solved this issue by running the Heroku log command. In the logs I realized that I left out requests_oauthlib inside of the requirements.txt file. Heroku was unable to to install the packages needed to run the app.

3) App crashes periodically
The app would display content and then upon refresh the app would crash. I solved this issue by adjusting the range for the random functions. Apparently the values that I have set was out of the range. 

4) Appearance
The appearance of my web app isn’t appealing. The solution of this issue is in the works. Currently learning CSS. Look out for the update coming soon ;)
