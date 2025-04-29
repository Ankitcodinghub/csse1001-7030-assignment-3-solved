# csse1001-7030-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [CSSE1001-7030 Assignment 3 Solved](https://www.ankitcodinghub.com/product/csse1001-assignment-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116007&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSSE1001-7030 Assignment 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Introduction

This assignment will use concepts taught throughout the course to extend the functionality of the provided tile based game. This assignment will ask you to extend the game with basic, intermediate and advanced features. For CSSE7030 students there will also be an open-ended component.

The assignment will focus on the concept of Graphical User Interfaces (GUIs). You will be requested to implement extra functionality to the base game including extending the GUI for a better game experience.

Assignment Tasks

Task Breakdown

CSSE1001 students will be marked out of 20 and CSSE7030 students will be marked out of 25 based on the following breakdown.

Task 2

Intermediate

Features Auto-Playing Game

1 mark

2 mark

Mark Breakdown

Download the Files

Before beginning work on the assignment you must download a3_files.zip provided from the course website.

Inside a3_files.zip, there should be a file called a3.py. This is the file where you will write your assignment. The other files are support files. These must not be edited. Their purpose is explained below.

Support Code

You have been supplied with a large amount of support code to help you complete this assignment. To begin the assignment, you do not need to understand much of this code. As you progress through the tasks, the degree to which you should understand this code will increase.

Concrete modelling &amp; app classes for each game mode. Task 1:

Simple

Task 3: Solid

Mappings of colour names to codes. Task 1

High score management. Task 2

GridView widget. Task 2

Abstract modelling classes. Task 3

Concrete tile generator classes. Task 3

Third-party libraries. Task 3

*Note: Ideally, each game type would be in a subdirectory called game, without the game_ prefix. However, this would add complixity for managing this, so the prefix was chosen instead for simplicity.

Event Listeners

Note: In this section, the word function is used to mean anything that is able to be called like a function, such as a method, a lambda, etc.

The *Game classes (AbstractGame and its subclasses) and the GridView class follow a pattern which allows you to attach a function to be called when an event is triggered. This can be referred to as binding to or listening for an event.

This pattern is called the Event Emitter pattern, and is an implementation of the Observer pattern (the Publisher/Subscriber pattern is similar).

While it is also quite a similar approach to how Tkinter handles commands for button presses, the Event Emitter pattern is far more flexible in general.

The events that games and grid views emit are useful in completing the assignment. For task 1 you should consider listening for the select event to appropriately update the score. Postgraduate students are encouraged to consider emitting their own events.

Task 1 — Basic GUI

Basic GUI Example

Basic GUI

The very first part of this task is to implement a class for the basic GUI. This class should be named LoloApp and should inherit from BaseLoloApp. The BaseLoloApp class provides some support code to simplify the complex process of animating.

The title of the window should be set to something appropriate (i.e. Lolo :: {game_mode_name} Game). This also applies to any window in subsequent tasks.

As the basic GUI is improved in subsequent tasks, the LoloApp class will need to be modified accordingly.

Status Bar

Define a class named StatusBar, which inherits from tk.Frame. This class must display two labels, with the following text and alignment:

• {game_mode_name} Game(Left)

The name of whichever game mode the player is currently playing. See

AbstractGame.get_name.

• Score: {score}(Right)

Must be updated whenever the player’s score changes.

Note: For convenience, you should have two methods, one for each of the relevant labels: set_game(game_mode) &amp; set_score(score).

Logo

Define a class named LoloLogo, which inherits from tk.Canvas. This class must draw a simple logo, similar to the one seen in examples, made out of canvas shapes. It does not need to be resizable.

File Menu

Implement a menu bar, with a File menu. The File menu should have the following entries:

• New Game: Restarts the game.

• Exit: Exits the application.

Note: On Mac OS X, this should appear in the global menu bar (top of the screen).

Lightning Button

When the lightning ability is active and the user selects a tile, instead of being joined with the surrounding tiles, it should be deleted from the game grid. Doing so uses one lightning.

Place the lightning button below the GridView. When pressed, this button should toggle the lightning ability if the user has any lightning available. Otherwise, this button should be disabled. When the lightning ability is active, the button’s text should indicate this to the user. It should also include the number of lightning the user has remaining.

At the beginning of a game, the user should receive one lightning. Every so often, the user should gain one lightning. This could be implemented in a variety of ways, some more interesting than others, such as:

• Fixed number of turns (i.e. every 20 turns)

• Randomly (i.e. there is a 5% chance of the user gaining a lightning each turn) • Increasing number of turns (i.e. 5, 10, 20, 40, etc. – 5×2i )

• etc.

BaseLoloApp.remove facilitates the proper removal of tiles at arbitrary position(s), similar to BaseLoloApp.activate.

Dialog

Implement the following dialog boxes:

• Invalid Activation: If the user attempts to activate a tile that cannot be activated, show an error dialog with an appropriate message.

• Game Over: When the game ends, show a dialog informing the user of their score.

Keyboard Shortcuts

Implement the following keyboard shortcuts:

• ctrl + n: Start new game.

• ctrl + l: Performs the lightning action.

Note: Ideally, cmd would be used on Mac instead of ctrl. It is permitted to also bind to cmd on Mac, however ctrl must also be implemented.

Task 2 — Intermediate Features

The purpose of this task is to extend the functionality of the basic GUI by adding a loading screen and high score window.

Instead of the basic GUI, the loading screen should be displayed upon launching the game.

Loading Screen Example

High Scores Window Example

Auto-Playing Game

Implement a class, AutoPlayingGame, which inherits from BaseLoloApp.

This class must be able to display either a static or automatically played game.

Hint: this can be achieved by initially displaying a static representation of the game, and implementing a method that begins the game playing.

The player should not be able to interact with this class. For automatically played games, a random valid tile should be chosen each move, and the game should restart after the game ends.

Loading Screen

Required components:

• Logo: Should be reused from task 1 (see 4.3 Logo).

• Name Entry: For recording high scoring player’s name.

• Auto Playing Game: Randomly playing a game (see auto-playing game above).

High Score Window

The high score window should be displayed in a separate window to the main application. It can be accessed through the button on the loading screen, or through the file menu (a new entry must be added).

The high score window contains all of the components from the example above, laid out as shown.

Required components:

• Best Player: Display the name, score, and a static visual representation of how their game ended (see Auto-Playing Game above).

• Text Leaderboard: display a row of text with the player’s name and score for each player on the leaderboard. Name and score should be left-aligned and right-aligned respectively

Task 3 — Advanced Features

Multiple Game Modes

On the loading screen, add a Game Mode button underneath New Game. When pressed, this should open a window that allows the user to choose the game mode. If the user hasn’t entered their name yet, they should be prompted with a dialog box.

The window must have a series of Radiobuttons, one for each available game mode, with the current game mode pre-selected. It must also contain a visual example and the name of the currently selected game mode. The visual example must update whenever a Radiobutton is selected. For the visual example, AutoPlayingGame can be reused here.

Modify New Game so that it starts a game of the currently selected mode.

Initially, your application must include all of the provided game types (Regular, Make 13, Lucky 7, Unlimited). Any additional game types added must also be included (see objective game mode and open-ended task below).

Objective Game Mode

An objective game mode is an extension of the regular game mode, in which the player has a number of tiles as objectives. The player’s goal is to join tiles to eliminate each objective tile. For each objective tile, the player must form a tile with the same type and with at least the value of the objective. Once this happens, the objective tile is eliminated, and tile that was joined should be removed from the game grid.

Objective game modes should be able to be loaded from a JSON file in the following format:

{

“mode”: “objective”, “min_group”: 3, // the minimum number of tiles to form a group

“types”: 4, // the number of tile types

“size”: [6, 6], // the number of [rows, columns] “starting_grid”: …, // optionally defines the starting grid “objectives”: […], // a representation of the objective tiles “limit”: 90, // the number of moves the user can make }

Open-Ended — CSSE7030 Only

You are encouraged to utilize extra Python modules to help you implement your desired functionality.

Install the Pillow module with pip using the command: pip install Pillow

Suggestions

• Saving and loading a game

• Background music/event sounds

• Additional custom game modes

• Various animations (e.g. row completion animation, picking up and placing tiles, failed tile placement)

• Multiplayer (local or network)

Assignment Submission

Your assignment must be submitted via the assignment three submission link on Blackboard. You must submit a zip file, a3.zip, containing a3.py and all the files required to run your application (excluding the support code). You should not have made modifications to any of the support files. If you are a CSSE7030 student, this zip file must also contain your description.pdf file.

All requests for extension must be submitted on the UQ Application for Extension of Progressive Assessment form:

Change Log

• Status Bar: Fixed typo to indicate that only the two indicated labels are required.

• High Score Window: Fixed typo that repeated the required components from loading screen.

• Basic GUI: Mandated window title.

• Lightning button

• Expanded requirements for lightning button.

• Added BaseLoloApp.remove to aid in implementing lightning button.

• Updated screenshot of Basic GUI Example to include lightning button.

• Replaced error dialog logic in BaseLoloApp.activate with raising of

IndexError (error dialog logic must be implemented by students in LoloApp.activate).

• Decreased the default tile size of GridView to accommodate smaller screen sizes.

• Added the get_name method to AbstractGame and its subclasses to simplify retrieval of the name of a game (see status bar).

• Replaced increase_score method of AbstractGame with set_score method.

• Fixed missing internal links.

Note: No further modifications will be made to the support code after 1.1.0 (except for bug fixes).
