Writing the song status info directly to an HTML file has a few problems mainly that the page needs to be reloaded to display new info.
This template periodically reads the data from a seperate song status json file instead of reloading the whole site. 

The benefits of doing it this way are:
- Animations during the song are possible
- Animations between songs are possible
- The staus updates almost immediately
- Better performance

You can simply write HTML and CSS as usual and everything should work.
___
Inspired by [WitchyRe's template](https://github.com/WitchyRe/SRSongStatusFormat)
