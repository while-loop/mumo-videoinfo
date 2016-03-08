# mumo-videoinfo
Mumo plugin to get information on a YouTube video sent in mumble.

The plugin extracts messages sent to the server and checks for YouTube video IDs. The plugin sends back a message with the format:
`channelName :: videoTitle`
The plugin supports channel messages (non recursive) and private messages. 
It also has a feature to only run if the user sending the video is registered.

NOTE: If you want to get the title of ANY webpage, check out [title-for-mumo](https://github.com/while-loop/title-for-mumo).

Example usage:


![Example usage](http://anthonyalves.science/assets/videoinfo.png)
