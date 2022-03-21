# ttv-cl
Command line utility for watching and recording twitch.tv livestreams.
=======
ttv-cl is an extensible shell scripted created to manage twitch.tv livestreams, having the option to watch it on mpv or recording. It currently only supports *NIX systems.

## Instalation

```sudo chmod +x ttv-cl```
```./ttv-cl install```

## Usage

There are three modes for ttv-cl, watch, record and feed.

### Watch
The watch option needs an argument with the channel name and resolution to run, for example:
```ttv-cl watch xqcow 1080p60```

### Record

The syntax for recording is:
```ttv-cl record xqcow best file.mp4```
It defaults the save path to ~/Videos

### Feed
You can add a list of channels on your ttv-cl for easy acess. You need fzf to be installed, reminder: it is not an RSS feed. Twitch RSS feeds are very buggy.
#### Add a channel to ~/.config/ttv-urls
```ttv-cl add xqcow```
#### Go to your fzf feed
```ttv-cl feed```