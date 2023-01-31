<h1>Mario-Kart-Game</h1>

<p> A Mario Kart game that runs on a Linux machine and takes input from a SNES controller connected to a Raspberry Pi
    (RPI).</p>

<h2>Technical Details</h2>
<ul>
    <li>Resolution: 1920 * 1080</li>
    <li>Programming language: C</li>
    <li>Graphics software: GIMP</li>
</ul>

<h2>Gameplay</h2>
<p>The game consists of 4 different challenges with varying difficulties. Mario starts at the initial position and must
    collect the key in each challenge in order to advance to the next. The game ends when the player successfully
    collects all 4 keys and a "Game Won!" screen is displayed.</p>

<h3>Value Packs</h3>
<p>Each challenge contains 3 value packs:</p>
<ul>
    <li>Red heart: Increases the player's lives by one</li>
    <li>Black heart: decreases the player's lives by one</li>
    <li>Coin: Increases player's score by 5 points</li>
</ul>
<h3>Moving Obstacles</h3>
<p>Each challenge also contains moving obstacles that decrease the player's remaining lives by one and return Mario to
    the starting position upon collision.</p>

<ul>
    <li>Challenge 1: Moving obstacles are horizontal.</li>
    <li> Challenge 2: Moving obstacles are vertical.</li>
    <li> Challenge 3: Moving obstacles are diagonal from top right to bottom left.</li>
    <li> Challenge 4: Moving obstacles are diagonal from bottom left to top right.</li>
</ul>

<h2> Game Over</h2>
<p>In the event that the player has no remaining lives or the allowed game time has finished, a "Game Over!" screen will
    be
    displayed with the option to restart the game or terminate.</p>
