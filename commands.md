# Commands

**Note:** Most command parts can be shortened to one letter. Examples:
- `-play [search]` → `-p [search]`
- `-play random next` → `-p r n`
- `-next` → `-n`
- `-loop playlist` → `-l pl`

<br>

### Adding to the queue

* `-play [link/search term]` Adds the song or playlist to the queue. If the input is a search term, it will automatically choose the first result
* `-search [search term]` Will prompt you to choose which search results you want to queue

[For more info on the queue add commands, click here](/marvdocs/commands/add)

<br>

### Viewing info about the queue

* `-queue` Shows the queue
* `-song` Shows the current track
* `-queuer` Shows who queued the current track
* `-link` Shows a link to the current track
* `-time` Displays info related to the duration of the song

##### Lyrics

* `-lyrics` Shows lyrics for the current song
* `-lyrics [song]` Shows lyrics for the inputted song

<br>

### Controlling the queue

##### Changing the current song

* `-next/skip` Skips to the next song
* `-back` Skips to the previous song
* `-jump [song index/title]` Jumps to the track at the specified index/title

##### Removing songs

* `-remove [song index/title]` Removes the track at the specified index/title
* `-remove last` Removes the last song
* `-remove current` Removes the current song
* `-clear` Clears the queue

##### Moving songs

* `-shuffle` Randomizes all the songs after the current one
* `-move [song index/title], [index]` Moves the specified song to the specified index

##### Autoplay

* `-autoplay` Enables automatic random song queueing when you run out of songs to play
* `-autoplay disable` Turns off autoplaying random songs

##### Experimental

* `-controls` Brings up a reaction control set

<br>

### Controlling the bot

* `-join` Makes the bot join your voice channel
* `-leave` Makes the bot leave your voice channel
* `-stop` Makes the bot stop

<br>

### Controlling the song

* `-volume [number between 1 and 100]` Allows you to change the volume
* `-pause` Pauses the song
* `-play` Resumes the song <br>
* `-ff` Fast forwards the song by 10 seconds
* `-rw` Rewinds the song by 10 seconds

[For more info on the fast-forward and rewind commands, click here](/marvdocs/commands/time)

<br>

### Looping

* `-loop` Cycles between the three loop settings
* `-loop track` Loops the current track
* `-loop queue` Loops the entire queue
* `-loop disable` Disables looping

<br>

### Settings

#### Server Prefix

The prefix you set here only applies to the current server.

* `-prefix set [new prefix]` Sets a new prefix
* `-prefix` Gets the current custom prefix
* `-prefix reset` Clears the custom prefix and reverts back to the normal one

#### User Prefix

The prefix you set here only applies to you. It will be the same, regardless of which server you are on.

* `-user prefix set [new prefix]` Sets a new prefix
* `-user prefix` Gets the current custom prefix
* `-user prefix reset` Clears the custom prefix and reverts back to the normal one

<br>

### Miscellaneous

* `-suggest [suggestion]` Posts a suggestion in Marv Support where people can vote up or vote down your idea
