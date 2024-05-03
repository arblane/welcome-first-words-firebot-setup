# welcome-first-words-firebot-setup
Upon a chat user's first words of the stream, display their Twitch avatar and name in a welcome box on stream.

# Compatibility
+ Firebot 5.62.1+

# Install
+ Download
    + Welcome.firebotsetup
    + welcomes.html
+ Import the downloaded firebotsetup file
    + You will need to edit the preset effect to change the location of the html file.

# Usage
## Requirements for Chat
+ Must type something in chat

## Streamer Info
+ There is a filter that the chat user is not a known bot or the streamer
+ Recommend you add an effect queue to allow them to play one after another
+ Customize the text, and position
+ The chatter's Twitch color will be used as the gradient background color
+ If you set an alias in Firebot for the user, the included utility will select the first one for use, otherwise the alias will default to their username
    + Upcoming change will pick a random alias, if more than one are set

# Dependency (included in this setup)
+ [[Utility] Alias](https://github.com/arblane/Utility-Alias)
