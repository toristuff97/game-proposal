# game-proposal
My proposal for the Mod 1 project!

# Bass Champion!

## Rules of the Game
<!-- This is basically a Guitar Hero clone. When the note circles reach the hit zone, the player must tap the corresponding key on their keyboard. The "two-player" aspect is that they must have a higher score or possibly a higher accuracy rate than the Computer (which will have its accuracy randomized within a certain range). I would like there to be two different possible lose states, one for if they get a lower score than the Computer and one for if their accuracy dips below 60%, at which point they will be booed off the stage (like in the real game, you see lol). The player also has the option to tap their space bar to activate Star Power, which gives them a multiplier on their score. -->
This is a music-rhythm game in which the player has to beat the Computer's score, whose accuracy will be randomized within a certain range. There are green circles that act as timing indicators; the player must hit the given note before the circle disappears to get the points for it. If they miss the note, the word "MISS" pops up (ideally). If the player does not beat the Computer's score, a lose screen is shown with an option to choose another song or replay the last one. If they win, they can do these same two things. My stretch goals are adding Star Power multipliers for reaching a certain combo of correct notes and having scrolling lyrics at the bottom of the play screen. Another stretch goal may be giving more or less points and feedback for how close the green circle is to the note when the player hits it. (ex. They hit it right when its touching the note border and "GREAT" pops up and they get additional points).
## Technical Challenges
- Listening to each song and figuring out the timing of the notes may be difficult (I may just have it be a 1 minute section of each song)
- Doing the animation for the timing indicator shouldn't be too hard but getting the player input at the right time would be the difficult-ish part
- I can see turning Star Power (which is a stretch goal for me at this point in time) on and off and altering the points based around it being a challenge for sure, as well as showing the feedback pop-ups for timing correctly.

## Wireframes 
The screen you see when the page is first opened. The BASS CHAMPION will glow (ideally).
![](./wireframes/start-screen.png)


The screen you're taken to when you click "HOW TO PLAY" on the start screen
![](./wireframes/how-to-play2.png)

The screen you're taken to when you click "CONTROLS" on the start screen
![](./wireframes/controls-screen.png)

Once you click "CLICK TO START" on the start screen, you get to pick which song you want to play here. (Clicking on any part of the song box will play a preview of it, while clicking on the play button will take you to the play screen.)
![](./wireframes/song-selection.png)

This is what the actual play screen will look like (the computer's notes are shown on the right (I may just have it say COMP and have its accuracy and points shown below it instead of showing the notes), the player's notes are in the center). I would also like to have the lyrics to the chosen song scrolling at the bottom (stretch goal).
![](./wireframes/play-screen-2.png)

This just shows all the icons/elements I "drew" and what they are specifically. 
![](./wireframes/icons2.png)

## Timeline
<ul>
<li>Tuesday: Start pseudocoding, figuring out what exact methods/functions/etc. I'm going to need for this to work. Hopefully start on JS
<br>
<li> Wednesday: Focus entirely on JS (work on controls and scoring system as well as note classes), and start acquiring assets (turning my wireframe icons into game assets, saving mp3s of the songs, album covers, etc.), also linking the pages together.
<br>
<li> Thursday: Create the keyframes for the timing indicators and figure out how to time them perfectly with the songs (maybe use delays or setTimeout?). Also work on conditionals for the points and accuracy counters. Also create functions and such for the Computer.
<br>
<li> Friday: Ideally finish all major JS (including song/note timing), start working on CSS
<br>
<li> Saturday: Flesh out minor JS (stretch goals like star power and scrolling lyrics), and continue working on CSS (can be saved for later if JS is not cooperating)
<br>
<li> Sunday: Make any final changes and finish up CSS. Test, test, test!