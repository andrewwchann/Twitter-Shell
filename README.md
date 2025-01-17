# Twitter-Shell

This project is a Python-based command-line interface (CLI) application designed to simulate a simplified version of Twitter. It provides functionality for user authentication, tweeting, retweeting, hashtag tracking, user search, and more using an SQLite database.

## Features

1. **User Authentication**
   - Login, sign-up, and logout functionalities.
   - Passwords are securely handled using `getpass`.

2. **Tweet Management**
   - Compose tweets and post them to your feed.
   - Reply to tweets and retweet others.
   - Search for tweets by keyword, hashtag, or text content.
   - View tweet statistics, including retweets and replies.

3. **User Management**
   - Search for users by name or city.
   - View and manage followers and followees.
   - View user profiles, including tweet count, followers, and recent tweets.
   - Follow/unfollow other users.

4. **Hashtag Tracking**
   - Automatically tracks and manages hashtags in tweets.
   - Search for tweets containing specific hashtags.

5. **Database Management**
   - All data is stored in an SQLite database for persistence.
   - Schema includes tables for users, tweets, retweets, follows, hashtags, and mentions.

6. **Pagination**
   - Paginated views for tweets and user lists to enhance usability.
