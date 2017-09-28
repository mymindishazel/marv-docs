# Adding to the queue

* `-play [link/search term]` Adds the song or playlist to the queue. If the input is a search term, it will automatically choose the first result
* `-search [search term]` Will prompt you to choose which search results you want to queue
* `-play shuffle [playlist]` If you input a playlist, it will automatically shuffle the playlist before adding it to the queue
* `-play` If the command call message has audio attachments, it will add them to the queue

**Note:** You are able to queue multiple songs in the same message by putting them on seperate lines. Example:
- -play [song]<br>[song]<br>[song]

**Note:** Every command above can have the word `next` added before the input. This will queue the song in the position after the current track. Examples:
- `-play shuffle next [playlist]`
- `-play next [song]`
