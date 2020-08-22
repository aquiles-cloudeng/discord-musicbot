# discord-musicbot
Discord bot to play music from youtube

# Usage
First, download and install Python 3.6
Then, you will have to download the following requirments:

```
python -m pip install -U youtube_dl
```

NOTE: You will need to have discord.py[voice] installed for this to work. Install it by using:

```
python -m pip install -U discord.py[voice]
```

After that just run 
```
python musicafuncional.py
```

Then in discord run this, replacing the URL with a youtube URL
```
.yt URL
```
Note that this will download the video, for streaming you can use .stream instead but it may not work smoothly. Also you can run .play to play locally downloaded files.

To stop it you can run
```
.stop
```

To adjust volume run
```
.volume
```