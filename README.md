# Song-Recommendation
Music Recommendation system based on the User's Mood
Music plays a significant part in one’s life. It is 
known to uplift the mood of a person. Analyzing the expression of 
an individual would help to understand the emotion one is going 
through. Many users have a playlist so large that they are unable 
to decide which song to play, thus a recommendation system 
would suggest songs based on the mood of the individual. The user 
image is given as an input to our system which predicts the 
emotion of the image and according to the emotion songs are 
recommended. The songs are classified into happy, sad, calm and 
energetic based on the features from the Spotify API. Three 
models were applied to the classified song data set namely Support 
Vector Machine, Random Forest and K-Nearest Neighbor 
Algorithm of which Random Forest showed the maximum test 
accuracy of 85%. The algorithms used for expression detection 
includes Convolution Neural Network, Support Vector Machine, 
K-Nearest Neighbor Algorithm of which Convolution Neural 
Network showed the maximum test accuracy of 64%. Thus, we 
used Convolution Neural Network and Random Forest for our 
project. We also have a provision to add new songs, the song input 
should be the trackid from the Spotify API. These songs would be 
dynamically classified and added to the playlist
