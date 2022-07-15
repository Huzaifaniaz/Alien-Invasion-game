# Alien-Invasion-game
My first python alien invasion game by help of python crash course
Huzaifa Niaz PF Ass 3 20B-089-SE
Python project from the 
book python crash course
ALIEN Invasion
Step 1:
 Creating a window:
Huzaifa Niaz PF Ass 3 20B-089-SE
Initially, we need to introduce pygame library and afterward import the library in 
alien_invasion.py. Presently begin creating a game. Make a capacity pygame.init. 
This strategy is utilized to make foundation settings. Also, we utilized 
pygame.display.set_mode to make the screen show. After that, we set the 
tallness and width of the screen to be shown. At that point, we utilized while 
circle and for circle. We made for the occasion which helps the player or client to 
a remarkable game.
 Setting the bg-color:
Pygame makes a dark screen naturally that is the reason we changed the tone by 
utilizing bg_color strategy. After that we use screen.fill (bg_color) to make the 
screen obvious.
 OUTPUT:
Huzaifa Niaz PF Ass 3 20B-089-SE
make another python record settings.py. Use class settings and added screen 
width, heigth and bg coloe tone.
Huzaifa Niaz PF Ass 3 20B-089-SE
Import settings in main program and store this in ai_settings. Now 
ai_settings.bg_color used to fill the background screen.
Huzaifa Niaz PF Ass 3 20B-089-SE
Now, create a new python file name ship. In ship.py we used the class ship. In this 
class we created init function. After that we downloaded the ship image and used 
it. To extract the image from exact location we used image.rect method. Image 
appears at the bottom center of the screen. Secondly, we create a function blit. 
To update the screen.
Huzaifa Niaz PF Ass 3 20B-089-SE
In main program we import a ship.py file and its method.
OUTPUT:
Huzaifa Niaz PF Ass 3 20B-089-SE
We create a new python file name game_function. in this file we created a new 
function called check events. In the function copy a for loop. Its already declare in 
a main program.
Huzaifa Niaz PF Ass 3 20B-089-SE
In a main program we import a game function file. and access its library by the 
help of gf method. In while loop we us gf.check events and remove a for loop 
path.
Huzaifa Niaz PF Ass 3 20B-089-SE
In game function file we create a new function name update screen. And copy a 
method. Its already declare in main function.
Huzaifa Niaz PF Ass 3 20B-089-SE
Now, in main program we use update function and remove method which we 
declared in while loop because it is already declare in update function.
Huzaifa Niaz PF Ass 3 20B-089-SE
We modify our program. In a game function file, we modify a check event 
function () and add ship in parameter. In check event function we add 
pygame.keydown. when user press right so ship move to right.
Huzaifa Niaz PF Ass 3 20B-089-SE
In this step we added ship check event parameter in a main program.
Huzaifa Niaz PF Ass 3 20B-089-SE
In a ship.py file we created update function () and we declare it when the user 
pressed right key the flag is true and the ship moves after that we added flag in a 
init function 
In a game function, we modified check event function. In this function we create 
another elif block. In this block we use pygame.keyup so that when the user stop 
pressing a key the flag is flag is false.
In a main program we create a ship update method.
Huzaifa Niaz PF Ass 3 20B-089-SE
In ship.py file. We modify update function, it is same as we done above when the 
user press the left key the ship moves left.
In a game function file we add pygame.leftkey in a check down block. Same 
process we did for right key.
Huzaifa Niaz PF Ass 3 20B-089-SE
In settings.py file we added ship speed.
Now, we added new things in ship file. Rect.centerx method is use to control the
position of a ship. Self. Center adjust amount of speed.
Huzaifa Niaz PF Ass 3 20B-089-SE
In a main program we added ship to control speed.
In ship.py file. We added some new command line in update function. These line 
use to stop the ship when it moves right and touches the corner. Same process 
we done for left key.
Huzaifa Niaz PF Ass 3 20B-089-SE
In a game function file we created two functions key up and key down. And in key 
down we write the same lines which declare in elif key down block. Same process 
will be done for keyup.
 
Now we have to add some bullets and it speed that’s why we write new lines in 
settings.py file. And set its width, height and color.
Create a new file name bullet and in this file we import a sprite library to 
generate bullet. After that we created a class bullet. And in this class we added
init function.in this function we added a bullet color, bullet position and height.
Huzaifa Niaz PF Ass 3 20B-089-SE
In the same file we created two function update and draw bullet. Update function 
mange a bullet speed. We set the bullet traveling direction as .y coordinate which
means bullet will travel in vertical position.
In Second function we draw a bullet on the screen and set its color and position.
Huzaifa Niaz PF Ass 3 20B-089-SE
In a main program, we imported spirit library and secondly we added a 
group of bullets.
Also added the bullet on update screen.
Huzaifa Niaz PF Ass 3 20B-089-SE
In a game function.py file we created elif. And also we added a pygame. K space
and added bullet, which means that when a user press enter the bullet release in 
ship.
In this step, we added a bullet variable in a check keydown parameters. Also In 
check keyup.
In the main function. We enter a condition in while loop. This condition is for the 
bullet to disappear, when reaches the top of the screen.
Huzaifa Niaz PF Ass 3 20B-089-SE
In a setting function. We added bullets limit, which mean how many bullets will 
release at a time.
In a game function. We added a line in a K space. To fix a number of bullet release 
in a ship.
In a game function we created a new function name update_bullets and from this 
function we copied for loop in a main program.
Huzaifa Niaz PF Ass 3 20B-089-SE
In main program we added update bullets function.
In a game function file. We created a fire bullet function. This function is used, 
when a user presses the space bar the bullets will appear on the screen. In check 
key down function () we call a function fire bullet. 
Huzaifa Niaz PF Ass 3 20B-089-SE
In a game function file. We added a pygame.K_q method call in a pygame. 
Keydown.pygame.k_q, it used when the user press Q the game is exit.
Now create alien file. In this file we added class alien and in this class we add 
function name init. And in this function we added lines. To add alien image same 
process as we did for ship image and set alien width, height. While Second 
function used for image and setting load.
Huzaifa Niaz PF Ass 3 20B-089-SE
In a main program we import alien file. And in the function we call alien setting. 
After that we added alien in update screen.
Huzaifa Niaz PF Ass 3 20B-089-SE
In game function, we added alien.blitme function which is used for 
alien screen appearance.
In a main program we added alien group. The program store a group of alien and 
call a create fleet function. After update a screen.
Huzaifa Niaz PF Ass 3 20B-089-SE
In a game function file we created {create_fleet function}. In this function we 
added alien width, alien space alien place in horizontal place, and adding aliens in 
row.
Huzaifa Niaz PF Ass 3 20B-089-SE
In a game function. We added number of alien and to copy create_fleet line 
which we already declare in above step.
Huzaifa Niaz PF Ass 3 20B-089-SE
In create fleet function to add get number rows and create alien 
function. In a setting file we add alien speed in init function.
In alien.py file, we added a speed factor and alien position in update 
function.
Now, in main program, we added update aliens.
Huzaifa Niaz PF Ass 3 20B-089-SE
In a setting.py file we add alien drop speed and its direction. How the 
alien moves and what its speed.
In alien file. Create a new function name check edges. In this function, 
we added a condition that when alien value is greater than right 
attribute alien moves left. Same process as for left.
In the same file, add alien speed and right and left.
Huzaifa Niaz PF Ass 3 20B-089-SE
In a game function file, add two function name fleet direction and fleet 
edges. Flat direction function use to control alien direction and fleet 
edges function used to check fleet direction value when a function is 
return true the alien change its direction and to break a loop.
After add check fleet edges function in update function.
After that we add update alien in a main program.
Huzaifa Niaz PF Ass 3 20B-089-SE
In a game function.py file. Create a new function name check bullet 
alien collision. In this function add pygame.spirit.groupcollide method. 
Means when a bullet hits alien. It will disappear from the screen, after 
ship shots all alien it will appear again on the screen.
Secondly, in update bullet function call a check bullet alien collision 
function. 
In main program update bullet.
Huzaifa Niaz PF Ass 3 20B-089-SE
In a setting file add bullet speed.
To update alien function. In this function we used
pygame.spirit.spiritecollideany method. In this method, any alien hits a 
ship. Ship will be disappeared from the screen and print ship hit. After 
again game start.
Huzaifa Niaz PF Ass 3 20B-089-SE
In a main program we added update alien function.
Create a new file name game stats. In this file, add game stats class and
add function name init. In this function. We used reset stats. When
alien collide to ship. Ship disappear from the screen and again it 
appears on the screen.
Huzaifa Niaz PF Ass 3 20B-089-SE
In main program, we imported game stats file. 
In setting.py file add a ship limit.
Huzaifa Niaz PF Ass 3 20B-089-SE
In game function file. Create a new function name ship hit. In this function, we 
use sleep method which means when alien hits a ship. The game will pause. After 
that ship will appear again in a center and store bullet.
In a ship.py file create a new function name center ship, it is because 
when ship disappear from the screen after few seconds it will again 
appear on a center of the screen.
Huzaifa Niaz PF Ass 3 20B-089-SE
In a game function file create a new function name alien bottom. In this function 
add alien bottom value. When alien bottom value is greater than the declared
value. It will break a loop. And after few second. Update all setting. 
In a game stats.py file, we add a condition that if there any ship if left 
than continue a game.
Huzaifa Niaz PF Ass 3 20B-089-SE
In the game function file, we added a condition in a ship hit function. 
Whereas, else is a number of ship that did not left which means to stop 
the game.
In the main program, we added the condition in a while loop. If the user 
press q the all program stop at the time and the game window 
disappear.
Huzaifa Niaz PF Ass 3 20B-089-SE
In a game stats file, we add a line game active which is used to stop the 
game when user does not want to play the game. The game does not 
start.
Create a button file, in this file we added call few method. Like font, color. In this 
file we imported font and create a class and in this class create a function. In this 
function call button font color and txt color and its width, which position it 
appears. 
 Second function is prep_msg in this function we used Boolean argument. 
Like off and on. When a player click a button the game is start. Third function is 
draw button. This function is used to draw a button on a screen.
Huzaifa Niaz PF Ass 3 20B-089-SE
In the main program we imported a button file to add play button
In a game function file, we added play button. It function as If the user 
not click a button the game does not start. 
After that edit update screen to add play button.
Huzaifa Niaz PF Ass 3 20B-089-SE
In a game function, update a check play button to act when the user click a play 
button or when the user refresh the game. It reset the setting. 
To modify a check event add pygame mouse button down which means 
to restrict a function for a user. If user click anywhere on a screen. The 
game does not start. 
Huzaifa Niaz PF Ass 3 20B-089-SE
In a game function. Update check play button. To add condition. If 
player clicked a play button mouse cursor is not visible on pygame 
screen. This condition is pygame.mouse.set visible is false and the 
mouse cursor is hidden.
To update ship hit, when a game is inactive mouse cursor is visible on a screen. 
This condition is pygame.mouse.set_visible. True. When a game restart. 
In a main program to update a check event function.
Huzaifa Niaz PF Ass 3 20B-089-SE
In a setting file, we added game speed. When player reach a new level. 
Game speed is increases. By the help speedup scale. Second a new 
function create. In this function. To set initial value of a ship, alien. And 
a bullet. It increase when a player reach a new level. When restart a 
game it reset again. Last function is where a ship kill last alien. It 
increase speed. To all object. 
In a check bullet alien collision. Call increase speed function.
Huzaifa Niaz PF Ass 3 20B-089-SE
In a game function. Add initialize dynamic setting. To reach a new level. It clear a 
screen and again appear alien. This time its speed increase and also a game 
speed. It more difficult. 
In a setting file. Add initial score is 0. To increase a score, player have
kill alien. To restart a new game it will be again 0. 
Huzaifa Niaz PF Ass 3 20B-089-SE
Add another file named scoreboard. In this document to import textual style and 
to add class name scoreboard. In this class case another capacity name init. To 
seem a score on a screen. Also, its tone. Second make another capacity name 
prep score. In this capacity to seem a score on screen as a picture and score 
esteem proclaim in setting. This picture show a privilege and to set a width and 
tallness to set this utilization score.rect.right and score.rect.top. To set a worth. 
And furthermore pronounce its tone. To make Third capacity is show score.in this 
capacity to utilize bilit technique. By the assistance of this technique. To show up 
picture on screen
Huzaifa Niaz PF Ass 3 20B-089-SE
In a game function. Add show score function in update screen function.
In a main program, import a scoreboard file. And save its value in the sb variable.
After add screen.
Huzaifa Niaz PF Ass 3 20B-089-SE
In a setting.py file, add alien points. On kill adds 50 points.
In function file. add alien collision line. When a bullets hits alien the score board 
changes.
To add bullets function call check bullet alien collision function.
Huzaifa Niaz PF Ass 3 20B-089-SE
In the main program, add parameters in bullets function.
In the setting file, add alien points. And when hits every alien increase 
speed of game. 
Huzaifa Niaz PF Ass 3 20B-089-SE
In increase speed function add alien points. Each alien hits. Its print a points 
onthe program.
In stats.py file, add high score. And the initial value is 0.
Huzaifa Niaz PF Ass 3 20B-089-SE
In scoreboard file, add prep high score function.
In score board file, create a function prep high score. It is used to declare its 
width, height and position and its image, and add high score image and its 
position.
In function create a new function check high score in this function there are two 
parameters. First to check a current score and high score and sb to modify high 
score. so If current score is greater than high score so updates high score. 
Huzaifa Niaz PF Ass 3 20B-089-SE
In a check bullet alien collision function call check high score function.
In the stats.py file, add game level in a reset stats having initial value 1.
In score board call prep level function.
Huzaifa Niaz PF Ass 3 20B-089-SE
In score board create a new function named prep level. In this function add image 
height, position to declare image position value is 10.
After adding show score, add level image, and position.
Huzaifa Niaz PF Ass 3 20B-089-SE
In the function.py file, add check bullet alien collision function. In this 
function add stats level line and prep level function, which means to 
hits all alien level image is update. And increment 1.
Also add a check play button function. The score board is reset and it 
opens after update.
From check event, add sb and stats parameter in play button.
Huzaifa Niaz PF Ass 3 20B-089-SE
Add a check event function. In a main program
In a ship, import spirit. Spirit library use in graphic in class ship to add spirit 
parameters.. 
Huzaifa Niaz PF Ass 3 20B-089-SE
In the score board file, add the prep ship function.
In a score board record, make new capacity name prep transport. This capacity 
used to hold gathering of boat. Besides, apply condition by the assistance of for 
circle. To run a circle. Will situate a boat and each boat annihilated. To include a 
boat screen. Also, to less an all out number of boat. This picture shows on upper 
screen. So we have as of now proclaim picture position.
So to create a show score function add ship draw method. To show a 
total number of ship.
Huzaifa Niaz PF Ass 3 20B-089-SE
In function.py file, update check play button function to call prep ship function as 
this function used to display a number of ships left.
In thhe game, modify update alien function in this function add sb parameters in 
the ship hit function.
Huzaifa Niaz PF Ass 3 20B-089-SE
After in boat hit capacity to call prep transport work by the assistance of sb boundaries add sb boundary 
in boat hit work. This capacity assists with showing the right number of boats left.
After updating ship hit parameters which gives check alien bottom.
Sb pass in update aliens, In the main program.
Huzaifa Niaz PF Ass 3 20B-089-SE
OUTPUT:
To see one possibility is misfortune a player. After number of ships left its show up on the left of the top.
