# JodelPy

JodelPy is a rudimentary Python Interface for Jodel ( http://jodel-app.com )

### Features

  - Getting Posts
  - Posting
  - Setting Position
  - Seeing Karma
  - Up & Downvote
  - Posting Images
  - Getting an Access Token

### Votebot

  - Interactive Voting application
  - Edit Location in votebot.py !
  - Usage : python votebot.py

### JodelPull

  - Application to dump Jodels to JSON files.
  - Uni Bremen included as Location
  - Usage : python jodelpull.py -f <location-file> <output-file>

### JodelPost

  - Interactive posting
  - VoteBot included
  - Download for Windows : https://github.com/jafrewa/JodelPy/releases/download/0.1/JodelPost.0.1.zip

### Requirements

   - Python 2.7
   - Requests
   - requesocks (for TOR)

### TOR support
**CAUTION: Only for advanced users**

To really use JodelPy anonymously you can TOR. Please make sure you understand what you are doing!
1. Install tor as CLI tool: https://www.torproject.org/docs/installguide.html.en for your OS
2. Install requesocks
3. Run `$ tor$`
4. Append --tor to you script call
