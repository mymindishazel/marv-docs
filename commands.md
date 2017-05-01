# Commands

If you have any issues using Marv, hop on our the [**support server**](https://discord.gg/WmDyx7C) and we'll get back to ASAP :)

**Note:** Most command parts can be shortened to one letter. For example, `-play monstercat` can be shortened to `-p monstercat`

Command | Description
--- | ---
**Adding to the queue**
`-play [link/search term]` |  Adds the song or playlist to the queue. If the input is a search term, it will automatically choose the first result
`-search [search term]` | Will prompt you to choose which search results you want to queue
`-play shuffle [playlist]` | If you input a playlist, it will automatically shuffles the playlist before adding it to the queue
`-play random` | Adds a random song to the queue
`-play` | If the command call message has audio attachments, it will add them to the queue


### Adding to the queue

* `-play [link/search term]` Adds the song or playlist to the queue. If the input is a search term, it will automatically choose the first result
* `-search [search term]` Will prompt you to choose which search results you want to queue
* `-play shuffle [playlist]` If you input a playlist, it will automatically shuffles the playlist before adding it to the queue
* `-play random` Adds a random song to the queue
* `-play` If the command call message has audio attachments, it will add them to the queue

**Note:** Every command above can have the word `next` added before the input. This will queue the song in the position after the current track. For example, `-play choose next [link/search term]`

### Viewing info about the queue

* `-queue` Shows the queue
* `-song` Shows the current track
* `-queuer` Shows who queued the current track
* `-lyrics` Shows lyrics for the current song
* `-lyrics [song]` Shows lyrics for the inputted song
* `-link` Shows a link to the current track
* `-time` Displays info related to the duration of the song

### Controlling the queue

* `-next/skip` Skips to the next song
* `-back` Skips to the previous song
* `-remove [song index/title]` Removes the track at the specified index/title
* `-remove last` Removes the last song
* `-remove current` Removes the current song
* `-jump [song index/title]` Jumps to the track at the specified index/title
* `-clear` Clears the queue
* `-shuffle` Randomizes all the songs after the current one
* `-move [song index/title], [index]` Moves the specified song to the specified index
* `-controls` **EXPERIMENTAL** Brings up a control set

### Controlling the bot

* `-join` Makes the bot join your voice channel
* `-leave` Makes the bot leave your voice channel
* `-stop` Makes the bot stop

### Controlling the song

* `-pause` Pauses the song
* `-play` Resumes the song
* `-ff` Fast forwards the song by 10 seconds
* `-rw` Rewinds the song by 10 seconds

[For more info on the fast forward and rewind commands, click here](/marv/commands/time)

### Looping

* `-loop` Cycles between the three loop settings
* `-loop track` Loops the current track
* `-loop queue` Loops the entire queue
* `-loop disable` Disables looping
