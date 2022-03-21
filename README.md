<<<<<<< HEAD
# twitch-cli
Command line utility for watching and recording twitch.tv livestreams.
=======
twitch-cli is an extensible shell scripted created to manage twitch.tv livestreams, having the option to watch it on mpv or recording. It currently only supports *NIX systems.

## Instalation

```sudo chmod +x twitch-cli```
```./twitch-cli install```


## Usage

There are three modes for twitch-cli, watch, record and feed.

### Watch
The watch option needs an argument with the channel name and resolution to run, for example:
```twitch-cli watch xQc 1080p60```

### Record

The syntax for recording is:
```twitch-cli record xqcow best file.mp4```
It defaults the save path to ~/Videos

### Feed
You can add a list of channels on your twitch-cli for easy acess. You need fzf to be installed, reminder: it is not an RSS feed. Twitch RSS feeds are very buggy.
#### Add a channel to ~/.config/twitchclirc
```twitch-cli add xqcow```
#### Go to your fzf feed
```twitch-cli feed```
#### Add a channel to ~/.config/twitchclirc
```twitch-cli add xqcow```
#### Go to your fzf feed
```twitch-cli feed```
>>>>>>> 4086af3 (Initial commit)
