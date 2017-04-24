# Toolkit Support
Ready to make your own game or just trying to figure out how all this works? We're here to help!
Below, we take you through everything you're going to need to work with Fireside Toolkit.
If you're brand new to the toolkit, we advise you start from the top and read your way down!

## The Basic Game Loop

## Getting Started
Upon opening the toolkit, you'll be met with a blank Project Home screen. Before you are three
lists: one for Hubs, one for Path Groups, and one for Paths (more on each below). Across the top, 
you will see "File," "Edit," and "Create..." drop down menus next to the "Run Playtest" Button.

### Starting a New Project
From the Project Home Screen, click the "File" drop down menu. Click the "New..." button.<br>
_Warning:_ Clicking this will remove everything in the currently open project. 
If you're working on an existing project, it is strongly urged that you save if 
you do not wish for any changes to be lost. After clicking the "New..." button, 
you will be in a new project.

### Saving a New Project or Copying a Project
From the Project Home Screen, click the "File" drop down menu. Click the "Save As..." button. You 
will be prompted to select a directory to save your file in and to give the file a name. Your file 
will be given the ".fsp" extension for "Fireside Project."

### Saving an Existing Project
From the Project Home Screen, click the "File" drop down menu. Click the "Save" button. The toolkit 
will automatically update your existing ".fsp" file.

### Loading a Project
From the Project Home Screen, click the "File" drop down menu. Click the "Open..." button. You will be 
prompted to select the directory of your desired ".fsp" file. Once there, select the file and the toolkit 
will open the project!

## Attributes
Attributes are variables that you create to keep track of what is happening in your game. Attributes
come in three varieties: Global, Hub, and Player. 
- Global attributes are applied to the game as a whole. These are useful for things like keeping track of what round of play the game is currently on.
- Hub attributes apply to specific hubs, though there is an option to create a variable that applies to all hubs. These are useful for things like keeping track of the weather or population of a given area.
- Player attributes are applied to each player of your game, individually. These are useful for things like keeping track of of health of a given player or whether or not they are carrying a specific item.

### Creating an Attribute
From the Project Home Screen, click the "Edit" drop down menu. Click the "Attributes" button. The 
Define Attributes screen will appear. Select either the "Global," "Hub," or "Player" button to designate 
which type of attribute you would like to create. If you are creating a Hub, you will need to select which 
Hub you would like the Attribute to apply to on the drop down menu next to the "Hub" radio button. If you 
would like the attribute to apply to all Hubs, check the "Apply to All Hubs" box under the "Name" field in 
the "Attribute Details" section of the screen. Give your attribute a name in the "Name" field and select 
a starting value (between -1000000 and 1000000) that your attribute will be initialized to. When you're
done, click the "Add/Edit" button in the "Attribute Details" section.

### Editing an Attribute
From the Project Home Screen, click the "Edit" drop down menu. Click the "Attributes" button. The Define 
Attributes screen will appear. On the left side of the screen will be the list of existing attributes. 
Select the attribute you would like to edit and the appropriate fields for the attribute will be filled out. 
You may edit the details of the attribute and then click the "Add/Edit" button in the "Attribute Details" 
section of the screen to save your changes.

### Deleting an Attribute
From the Project Home Screen, click the "Edit" drop down menu. Click the "Attributes" button. The Define 
Attributes screen will appear. On the left side of the screen will be the list of existing attributes. 
Select the attribute you would like to delete. Click the "Delete Selected" button in the "Attribute Details" 
section of the screen to delete the attribute.<br>
_Warning:_ You cannot recover deleted Attributes.

## Characters
Characters are the physical representation of either the player or anyone they interact with. They are
a collection of images used to portray the individual you wish to represent. You may attach characters'
images to dialogues in the game during Path creation.

### Create a New Character
From the Project Home Screen, click the "Edit" drop down menu. Click the "Characters" button. The Edit 
Characters screen will appear. Fill in the "Character Name" field with the desired named. Click the 
"Create New" button to create the character. The character's name will appear in the "Character Names" 
list on the right side on the screen.

### Adding an Image to a Character
From the Project Home Screen, click the "Edit" drop down menu. Click the "Characters" button. The Edit 
Characters screen will appear. On the right side of the screen, you will see two lists: "Character Names" 
and "Character Images." From the "Character Names" list, select the character you would like to add images 
to. In the "Add Images" section, click the "Choose Image..." button. You will be prompted to select the 
file location of the image you would like to use (.jpg, .jpeg, .jpe, .jfif, .png files only). The image you 
select will be displayed on the left side of the "Add Images" section. Fill in the "Image Name" field with 
the desired name. Click the "Add Character Image" button to add the selected image to the character. The 
image's name will appear in the "Character Images" list whenever the character is selected.

### Deleting an Image from a Character
From the Project Home Screen, click the "Edit" drop down menu. Click the "Characters" button. The Edit 
Characters screen will appear. On the right side of the screen, you will see two lists: "Character Names" 
and "Character Images." From the "Character Names" list, select the character you would like to delete 
images from. From the "Character Images" list, select the image you would like to delete. Selecting the 
image will fill in the appropriate fields in the "Add Images" section. Click the "Delete Image" button in 
the "Add Images" section. The image name will no longer appear on the "Character Images" list.<br>
_Warning:_ You cannot recover a deleted character image.

### Delete an Existing Character
From the Project Home Screen, click the "Edit" drop down menu. Click the "Characters" button. The Edit 
Characters screen will appear. On the right side of the screen, you will see two lists: "Character Names" 
and "Character Images." From the "Character Names" list, select the character you would like to delete. 
Click the "Delete Character" button to delete the character. The character's name will no long appear on 
the "Character Names" list.<br>
_Warning:_ You cannot recover a deleted character.

## Paths
Paths are where the action of your game will take place. Each path is made up of a background image,
dialogues, and buttons. Dialogues have the ability to affect the various attributes you have created via 
impacts. Dialogues will play in the order they appear on the Dialogue list of the "Edit Path" screen.
Buttons give you the ability to have paths lead to different destinations. Buttons are always the last
part of a path to be displayed. If you use default values, only two buttons may be created. If you use
custom coordinates, you will be able to add more than two buttons.

### Creating a Path
Click the "Create..." drop down menu. Click the "Path" button. You will be prompted to name your new
path. After clicking the "Ok" button, the "Edit Path" screen will appear. Click the "Save" button
at the bottom right of any of the tabs on this screen to save the path.

### Editing an Existing Path
On the "Paths" list of Project Home screen, double click the path you would like to edit. The "Edit Path" 
screen will appear with all the appropriate fields filled out. After making any edits you wish to the path, 
click the "Save" button at the bottom right of any of the tabs on this screen to save the changes to the path.

### Selecting a Path Image
On the right side of the "Dialogues" tab of the "Edit Path" screen, click the "Choose Path Image" button. 
You will be prompted to select the file location of the image you would like to use 
(.jpg, .jpeg, .jpe, .jfif, .png files only). Once you press "Ok," the image will appear above the button. 
Click the "Save" button at the bottom right of any of the tabs on this screen to save the image.

### Selecting Background Sound of a Path
On the right side of the "Dialogues" tab of the "Edit Path" screen, check the "Use Background Music" box. 
You will be prompted to select the file location of the sound you would like to use (.ogg, .wav, .flac, 
.aiff files only). The box will remain checked to identify that a sound has been selected for the path. 
Click the "Save" button at the bottom right of any of the tabs on this screen to save the sound.

### Adding Dialogue
On the center of the "Dialogues" tab of the "Edit Path" screen is the "Dialogue Text" field. Fill this 
field with an individual line of dialogues you would like to appear, one at a time. Click the "Create Dialogue" 
button below the "Dialogue Text" field. Dialogues will appear in the game in the order they appear on the 
Dialogue list. At the top of the "Dialogues" tab, you can edit the size of the dialogue using the "Dialouge Font
Size" field (values may range from 0 to 100). Click the "Save" button at the bottom right of any of the tabs 
on this screen to save your changes.

### Editing Existing Dialogue
On the left side of the "Dialogues" tab of the "Edit Path" screen you will see the Dialogue list. 
Select the dialogue you would like to change the text of. Upon selecting the dialogue, the text 
will appear in the "Dialogue Text" field. You may change the text as you desire. When you are done, 
press the "Edit" button below the "Dialogue Text" field. The updated text will appear in the Dialogue 
list. Click the "Save" button at the bottom right of any of the tabs on this screen to save your changes.

### Changing the Order of Dialogues
On the left side of the "Dialogues" tab of the "Edit Path" screen, you will see the Dialogue list. 
Select the dialogue you would like to move. Next to the bottom right of the Dialogue list are up and
down buttons. Select the desired direction on the list that you wish the path to be moved in. The Dialogue 
list will update with the new order of dialogues. Click the "Save" button at the bottom right of any of 
the tabs on this screen to save your changes.

### Adding a Character to a Dialogue
On the left side of the "Impacts" tab of the "Edit Path" screen, you will see the Dialogue list. Select the
dialogue you would like to have a character's image appear over. Below the Dialogue list is the "Character
on Dialogue" section. Check the "Use Character" box from here. The "Character" and "Character Image" drop down 
menus will become enabled. Select which character you would like to choose an image of from the "Character" 
drop down menu. Select which image you would like to use from the "Character Image" drop down menu. Your choice
will be added to the dialogue as soon as it is selected. Click the "Save" button at the bottom right of any 
of the tabs on this screen to save your changes.

### Removing a Character from a Dialogue
On the left side of the "Impacts" tab of the "Edit Path" screen, you will see the Dialogue list. Select the
dialogue you would like to have remove a character's image from. Below the Dialogue list is the "Character
on Dialogue" section. Uncheck the "Use Character" box from here. The character image will be removed from the
dialogue as soon as you do this. Click the "Save" button at the bottom right of any of the tabs on this screen 
to save your changes.

### Impacts
#### Adding Impacts to a Dialogue
On the left side of the "Impacts" tab of the "Edit Path" screen, you will see the Dialogue list.
Select the dialogue you wish to add an impact to. Select either the "Global," "Hub," or "Player" radio
button to designate what type of attribute you would like your dialogue to affect. If you are selecting
a hub attribute, select the hub whose attribute you would like to affect from the drop down menu next to
the "Hub" radio button. Select which attribute you would like to affect from the "Attribute" drop down menu 
in the "Add Impact" section. The operator drop down is used to designate if the Impact will add, subtract,
or set the attribute equal to the number given in the "Value" field. Values may range from -1000000 to 1000000.
Click the "Edit/Create Impact" button to create the impact. The attribute will appear in the "Dialogue Impacts"
list. Click the "Save" button at the bottom right of any of the tabs on this screen to save your changes.

#### Editing Impacts
On the left side of the "Impacts" tab of the "Edit Path" screen, you will see the "Dialogue Impacts" list.
Select the impact you wish to edit. The appropriate fields in the "Add Impact" section will fill out. You
may edit the way in which an impact affects an attribute. When you are done, click the "Edit/Create Impact" 
button to edit the impact. Click the "Save" button at the bottom right of any of the tabs on this screen to save 
your changes.

#### Deleting Impacts
On the left side of the "Impacts" tab of the "Edit Path" screen, you will see the "Dialogue Impacts" list.
Select the impact you wish to delete. The appropriate fields in the "Add Impact" section will fill out. Click
the "Delete Impact" button at the bottom of the "Add Impact" section. The attribute will be removed from the
"Dialogue Impacts" list. Click the "Save" button at the bottom right of any of the tabs on this screen to save 
your changes.<br>
_Warning:_ You cannot recover deleted Impacts.

### Buttons
#### Adding a Text Button to a Path
On the top left of the "Buttons" tab of the "Edit Path" screen, enter the desired text for the button into the
"Button Text" field. If you would like the button to highlight when the player mouses over it, check the
"Highlight Text" box in the "Button Images" section. If you would like to use the default location for the button,
check the "Use Location Defaults" box under the Button Text field. If you would like to choose where the button
goes, uncheck the "Use Location Defaults" box and enter the X and Y coordinates in the appropriate fields under
the "Use Location Defaults" box (X coordinates may range from -959 to 960, Y coordinates may range from -539 to
540). To select the destination of the button, choose either the "Path," "Path Group," or "Hub" radio button
in the "Target Navigable" section. Select which path, path group, or hub you would like on the drop down menu
next to the "Path" radio button. Click the "Create Button" button and a new button will appear on the "Current
Buttons" list on the button left of the screen. The button will be named by the button's ordering in comparison
to the other buttons. The names will refresh whenever you return to the "Buttons" tab. Click the "Save" button at 
the bottom right of any of the tabs on this screen to save your buttons.

#### Adding an Image Button to a Path
In the "Button Images" section of the "Buttons" tab of the "Edit Path" screen, check the "Use Button Image"
box. You will be prompted to select the file location of the image you would like to use 
(.jpg, .jpeg, .jpe, .jfif, .png files only). If you would like the button to be highlighted using a second
image when , check the "Use Highlighted Image" box. You will be prompted to select the file location of the image 
you would like to use (.jpg, .jpeg, .jpe, .jfif, .png files only). Select the size of the image by filling in the
"Width" and "Height" fields (Width values may range from 1 to 1920, Height Values may range from 1 to 1080). If you 
would like to use the default location for the button, check the "Use Location Defaults" box under the Button Text 
field. If you would like to choose where the button goes, uncheck the "Use Location Defaults" box and enter the X 
and Y coordinates in the appropriate fields under the "Use Location Defaults" box (X coordinates may range from -959 
to 960, Y coordinates may range from -539 to 540). To select the destination of the button, choose either the "Path," 
"Path Group," or "Hub" radio button in the "Target Navigable" section. Select which path, path group, or hub you would 
like on the drop down menu next to the "Path" radio button. Click the "Create Button" button and a new button will 
appear on the "Current Buttons" list on the button left of the screen. The button will be named by the button's ordering 
in comparison to the other buttons. The names will refresh whenever you return to the "Buttons" tab. Click the "Save" 
button at the bottom right of any of the tabs on this screen to save your buttons.

#### Changing the Order of the Buttons
Changing the ordering of your buttons should only be of concern if you are using the default button locations.
On the bottom left of the "Buttons" tab of the "Edit Path" screen is the "Current Buttons" list. Select the button 
whose ordering you would like to change. Click the up or down button next to the "Creaton Button" list to move the button 
in the desired direction. Click the "Save" button at the bottom right of any of the tabs on this screen to save your 
buttons.

#### Deleting Buttons from a Path
On the bottom left of the "Buttons" tab of the "Edit Path" screen is the "Current Buttons" list. Select the button 
you would like to delete. Click the "Delete Button" button on the bottom right of the "Button Properties" section.
The button's name will be removed from the "Current Buttons" list. Click the "Save" button at the bottom right of any 
of the tabs on this screen to save your buttons.<br>
_Warning:_ You cannot recover deleted Buttons.

### Paths with No Buttons
Paths with no buttons serve several purposes, such as being used in your games ending or for the start or end of a
round of gameplay. In these cases, do not add any buttons and leave the fields in the "Default Target Navigable of
Path" section blank. However, if you wish for your path to lead to another destination, similar to a button, without
the use of a button, check the "Use Default Target" box, above the "Default Target Navigable of Path" section. Select
either the "Path," "Path Group," or "Hub" radio button of the "Default Target Navigable of Path" section. Select which 
path, path group, or hub you would like on the drop down menu next to the "Path" radio button. Click the "Save" button 
at the bottom right of any of the tabs on this screen to save your changes.

### Deleting a Path
On the "Paths" list of Project Home screen, select the path you would like to delete. Click the "Delete" button on the
bottom right side of the screen. The path's name will be removed from the "Paths" list.<br>
_Warning:_ You cannot recover deleted Paths.

## Path Groups
### Creating a Path Group

### Tiers

### Adding a Path to a Tier
(Include Path Weight Here)

### Removing a Path from a Tier

### Adding a Condition to a Path

### Removing a Condition from a Path

### Saving a Path Group

### Deleting a Path Group

## Creating a Hub
### Selecting a Hub Image

### Selecting Background Sound of a Hub

### Adding Buttons to a Hub

### Saving a Hub

### Deleting a Hub


## Ending Generator
### Tiers

### Adding a Path to a Tier

### Adding Conditions to a Path


## Game Settings
### Visible Attributes

### Start of Player Turn Navigable

### Start of Round Path Group

### End of Round Path Group

### Max Player Count


### Default Dialogue Options
#### Setting a Dialogue Scroll Sound

#### Setting a Dialogue Font

#### Setting a Pane Texture

#### Setting a Pane Position

#### Setting a Dialogue End Sound

#### Setting an Enter Key Texture

#### Setting an Enter Key Position

#### Setting a Character Position


### Setting Game Over Requirements
#### Adding a Game Over Condition

#### Removing a Game Over Condition

## Creating the Game
### Run Playtest

