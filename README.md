# EGM-my-game-maker
the source code is not available yet.
you can use the software but you can't copy the source code yet.



EGM Documentation 0.1 Alpha 
EGM Documentation 
You can find most of these functions and routines etc. in the script menu, go to Insert > Item
If you’re having any difficulty with coding EGM feel free to send me a message and I will help you. Please 
forward all bugs, suggestions and any of your feedback you have to me too, please. 
Functions and variables
Room_Height(“SET”, 0) Sets the height of the room to 0, change 0 to the 
height you want
Room_Height(“GET”, 0) Returns the value of the room’s height. You could 
use it in a variable i.e 
Dim HeightTest = Room_Height(“GET”) 
If HeightTest = 0 Then
‘Your code here
End If
Room_Width(“SET”, 0) These work the same as above but width
Room_Width(“GET”, 0) These work the same as above but width
Room_Dimension(0, 0) Set the width and height of the room, x by y
Score(0, True) Set the score, 0 is the score. True is Relative, if 
you set the Score to true the score will be ADDED 
to the total score, if you set the score to False the 
total score will be set to the score you submitted 
DrawScore() Displays the total score on the window of the 
game
xLives The total amount of lives the player has
Lives() Displays the total lives in the window of the game 
Draw_Sprite(“SpriteName”, xlocation, ylocation, 
xsize, ysize)
You must have created a sprite first and have set 
the sprite’s name. Draw_Sprite will draw the 
sprite at the location you specify and the size you 
specify. 
xScore The total score the player has, you can call this 
directly to modify the score, you will need to call 
DrawScore for it to update, though. 
Sub Routines 
LeftUp() When you create this routine it will be called 
whenever the player releases the Left arrow key
LeftDown() When you create this routine it will be called 
whenever the player presses down the Left arrow 
key
Creative Programming
EGM Documentation 0.1 Alpha 
RightUp() When you create this routine it will be called 
whenever the player releases the Right arrow key
RightDown() When you create this routine it will be called 
whenever the player presses down the Right
arrow key
DownUp() When you create this routine it will be called 
whenever the player releases the Down arrow 
key
DownDown() When you create this routine it will be called 
whenever the player presses down the Down
arrow key
UpUp() When you create this routine it will be called 
whenever the player releases the Up arrow key
UpDown() When you create this routine it will be called
whenever the player presses Up the Left arrow 
key
Ⓒ zv800 2021
