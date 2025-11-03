# welcome-first-words-firebot-setup
Upon a chat user's first words of the stream, display their Twitch avatar and name in a welcome box on stream.

# Compatibility
+ Firebot 5.64.0+

# Install
+ Download
    + Welcome.firebotsetup
+ Import the downloaded firebotsetup file
    + You will need to edit the preset effect to change the location of the html file. 
        + This will be handled by and import question.

# Usage
## Requirements for Chat
+ View must type something in chat

## Streamer Info
+ There is a filter that the chat user is not a known bot, the streamer, or recently banned
+ Recommend you add to an effect queue to allow them to play one after another
+ Customize the text and position
+ The chatter's Twitch color will be used as the gradient background color
+ If you set an alias in Firebot for the user
    + The included utility will select a random alias, if more than one are set
    + If there is no aliases set, it will default to the username

# Dependency (included in this setup)
+ [[Utility] Alias](https://github.com/arblane/Utility-Alias)
