<h1>Marvel Memory Game</h1>

<p>This is my second Milestone project for the 'Interactive Frontend Development' module with the Code Institute.
The main feature of this website is a simple, card matching memory game based on the Marvel Avengers. The game is designed to be both simple and enjoyable to play. It is inspired by a matching game I played as a child.<p>

<h2>UX</h2>

<p>My main goals when designing this website was to create something simple to play, visually appealing and suitable for all ages. The game is both desktop and mobile friendly and looks/plays very similar on both. There is a flip counter to track the amount of cards clicked, this allows the game to be played by a wide range of ages as it is so easy to play. The design is meant to be fun and add a Marvel feel to the site.</p>

<p>The game is suitable for ages approximately 5+ as it is very easy to play.</p>

<p>As a player, I can easily navigate through this website, read the instructions and play the game. I can see how I'm doing in the game based on the amount of moves I've made and restart to beat my score.</p>

<h2>How To Play</h2>

<p>Click on a card to reveal the Marvel character/icon, try to find the matching pair. Match all pairs to win. Click on the restart button to beat your moves score.</p>

<h2>Features</h2>

<h3>Existing Features</h3>

Collapsed navbar: Allows the user to access different sections easily and stays collapsed for a minimal look.<br>
Flips Counter: This counts every time a card is clicked and allows the player to track their progress.<br>
Contact Form: This form enables the player to contact me with any questions or issues.<br>

<h3>Features Left to Implement</h3>

A high score chart: That would enable the player to see their highest score.<br>
Contact Form: This form would enable  the player to contact me with any questions or issues.

<h2>Technologies Used</h2>

<p>In this section, I mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project.</p>

HTML - used for creating content and basic layout and validated with W3C<br>
CSS - used for customised styling and layout and validated with W3C<br>
JavaScript - used to provide interactivity and logic to the site<br>
GitPod - this was the IDE where I developed and ran my application<br>
Git - I pushed my files using Git, storing them in a repository on GitHub and used Git Hub Pages to deploy my site.<br>
jQuery - JavaScript library used to connect with APIs and custom-code for the site which allows for DOM manipulation<br>
CSS Minifier - used to minify my CSS data for deployment<br>
Google Maps JS - used to create a map with localised functionality<br>
Pixabay.com and marvelcinematicuniverse.com used for images (for the educational purposes of this project only) and TinyPNG.com used for image compression<br>
W3C Validator - HTML Validator, W3C CSS Validator, Esprima - JS Validator<br>
Google Developer Tools, Code-Institute Slack Community, Code-Institute module notes, W3Schools, CSS Tricks - all used for reference when I encountered a bug or needed extra support with any issues.<br>

<h2>Testing</h2>

<h3>Manual Testing</h3>
All tests were run manually for this website and game.<br>
Game:<br>
Cards are mixed up.<br>
Laid in rows, face down.<br>
Turn over any two cards, verify it turns and display the icon.<br>
If the two cards match, they stay.<br>
If they don't match, they turn back over.<br>
The game is over when all the cards have been matched, or the timer has run out.<br>
Click on the homepage, verify that all cards are flipped back around and shuffled, verify that flips counter is reset.<br>

I found a few bugs whilst developing this game.<br>

I found that once a card was clicked it couldn't be clicked again.<br>
With the counter, I found that if you clicked a card even if it didn't flip, the counter went up.<br>
I found that the cards weren't shuffling when the reset button was clicked.<br>
I have since fixed all these bugs and it is now running smoothly.<br>

I have tested the site and game on various screen sizes and browsers and found it to be responsive. I tested my project throughout development using Google Developer Tools to check the site was responsive. I continually made adjustments to my media-queries in CSS to ensure it looked good at all screen-widths, however I realised my laptop had a different screen size to the standard. I began to investigate a range of screen sizes and realised the best option was just to make it as responsive as I possibly could. There was an interesting (and frustrating) bug with Safari on the iPhone - the background image was very large and did not fit to the screen, all that could be seen was clouds. However, I appear to have fixed this by including a media-query for mobile-only.
There have been several issues throughout development with my JS code breaking, I worked hard using console.logs and debuggers to pinpoint errors and fix them. There shouldn't be any errors displaying in the console.

<h2>Deployment</h2>

<p>This project is hosted on GitHub pages here https://noelquirke.github.io/MS2/</p>

<h2>Credits</h2>

<h3>Content</h3>

All of the text content on the website was my own.<br>

This site has been created for educational purposes only<br>

<h3>Media</h3>
<p>The images displayed in this site sourced from the site https://marvelcinematicuniverse.fandom.com.</p>
<p>All images are for educational purposes only.</p>
<h3>Acknowledgements</h3>
<p>I received inspiration for this project from a childhood game I used to play and this website here.
I would also like to thank student care within the Code-Institute for the support shown during this difficult and uncertain time. I would also like to thank my new mentor Jonathan Munz, for providing me the confidence to continue my work and giving insight into areas for improvement.</p>
