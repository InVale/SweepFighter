Sweep Fighter is a small school project of a fighting game exclusively played with graphics tablet.

###About
Find more information about the game on ShakeThatButton.

###Set-Up
Because of the impossibility of using two tablets on the same computer, we had to use network. As network wasn't our top priority, we used the basic network system of Unity. Our net code is pretty bad, so you will want to play in LAN.
The game use one screen from each computer to show the whole stage, so you will need to put the two screens side to side. The player on the left should be the host.
We hard coded a lot of things, as such the only supported resolution is 16:10.
The tablet area of effect should cover the whole screen and any short cut to a functionality (especially Windows base functionality for Tablets) should be disabled.

###Game Information
The game start to read for an input when there is a click and interpret it when it's released. So just put the pen on tablet draw the right figure and release. The screen is basically divided in 9 areas which represent the different joystick position (neutral, up, down, left, right and the 4 diagonals).
*Jump is a swipe from the bottom to the upper areas.
*A short side swipe (neutral to side) gives a Dash attack while a long swipe (side to side) gives a long dash.
*Hadouken is made with a quarter circle motion (for example : down, down-left, left).
*Shoryuken is done through the dragon motion (for example : down-left, neutral, down-left).
*A quick Triple taps gives the basic attack.