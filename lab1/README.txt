Kevan DuPont
duponk2

For the html structure I just used a wrapper for centering, and then two unordered lists, one for tweets and one
for hashtags. I processed the tweets.json by using getJSON function. I looped through each tweet, appending the
text of each tweet to the tweets list. I then looped through each hashtag array, and appended the hashtag text to
the hashtag list.

To display the tweets and hashtags, I created a structure to hold the data and then looped through it. In order to
have the tweets and hashtags appear asynchronously and not as entire lists, I had to use .delay( ). For every nth
tweet or hashtag, it would take n*3 seconds to fade in. In order to only have five tweets/hashtags visible at a time,
I set each tweet/hashtag to fadeOut after 15 seconds. I chose to create an effect of the tweet and hashtag being
separated/swiped away as the fadeOut. To do this, I animated the tweet to decrease its margin-left and set
opacity to zero, and animated the hashtag to increase its margin-left and set opacity to zero. I set the animations
to 500ms and the delay to 14500ms to add up to 15s. I decided to go with an orange color scheme.

Resources:
http://api.jquery.com/animate/
http://api.jquery.com/delay/
http://api.jquery.com/fadein/
http://api.jquery.com/eq/
https://gist.github.com/wadey/442463