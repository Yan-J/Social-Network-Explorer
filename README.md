# Social-Network-Explorer
# REPORT

Tweets About Your Favorite Artists In Music

1. short explanation of what the application is doing, what APIs and endpoints are used, and how they are used; what analysis is done and how.

The application we built will get user's most listened 25 artists on Spotify, and 5 related artists of the 25 aritsts.
Then, when user click the picture or the name of the artist, the app will show 20 tweets about that artist.

We used the Personalization Endpoint of Spotify Spotify Web API to get a user's top artists, which is based their listening history.
The we used Artist’s Related Artists Endpoint of Spotify Web API to get the artists' related artists, which might also be the artists user like.

Spotify OAuth Code is from: https://github.com/ecliu110/Spotify-OAuth-2.0-Python

