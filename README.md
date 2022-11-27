<h> LetterboxdGlobalWatcher </h>

<b> So by using Jasmine's letterboxd data that I extracted from TMDB and using <a href="https://github.com/amotter443/movies">this repository</a> as instructions, I attempted to answer the question of if Jasmine is a "global watcher?" </b>

Using these three graphs, I answered the questions, "What Genre Does Jasmine Watch the Most of?", "Does Having a Letterboxd Account Affect How You Watch Movies?", and "What Cultural Region Does Jasmine Enjoy Watching the Most?" 

One Question of Further Exploration is by taking the Genre graph and seeing how can I seperate the bars into different colors for different cultural regions? For example, how much of the Drama bar is comprised of Asian Films? How much of the Documentary bar is comprised of European films?

<img width="561" alt="whichgenredoiwatchthemost" src="https://user-images.githubusercontent.com/89553284/192156971-07262199-2f39-4034-8423-fce2e9f5ca63.png">
Jasmine clearly watches Dramas more than any other genre with it being at 250 movies and the second most being 125 movies. How I would want to explore this further is having a legend to specify the cultural regions that comprise each bar.

<img width="557" alt="doeshavingletterboxdhelpdiversifyyourwatchlist" src="https://user-images.githubusercontent.com/89553284/192156976-66575829-6696-4a24-9272-52844d7d106b.png">
This is my favourite chart since I believe it gives a lot of insight on how letterboxd changes your view on watching movies. In the beginning of her letterboxd weeks (week0-week19), Jasmine seems to watch movies that she likes with ratings ranging from 3-4.5. 

However, in week 20-30, she fluctuates dramatically with ratings as low as 0.5 [all reviews that were 0 were taken out of the dataframe] and as high as 4.5. There are also the most data points here which gives a more accurate representation on her movie journey. What I interpret from this is that Jasmine was more experimental with the movies she watched. Causes from this may be her exposure to different titles from lists and her friends' reviews, or her opinions got stronger as she read more reviews. Letterboxd and their community changes their users to have more dramatic and extreme views than before. 

After week 30, Jasmine lowest review is a 2.5 (an outlier) and the rest are on the higher side with her first 5 star rating in the end. While this goes against my claim before, I also believe that this is a less accurate representation of Jasmine's movie journey because there being less data points here than week 20-30. 

<img width="511" alt="whichculturalregionhastheaveragehighestmovierating" src="https://user-images.githubusercontent.com/89553284/192156989-b99d4627-30aa-462c-8947-7cc2c3ad4fda.png">

This interactive graph shows that the cultural region with the best average rating is Asian movies with a 3.8. The amount of movies watched in each cultural region does not affect the overall average sum.
