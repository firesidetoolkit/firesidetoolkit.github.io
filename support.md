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
- Hub attributes apply to specific Hubs, though there is an option to create a variable that applies to all Hubs. These are useful for things like keeping track of the weather or population of a given area.
- Player attributes are applied to each player of your game, individually. These are useful for things like keeping track of of health of a given player or whether or not they are carrying a specific item.

### Creating an Attribute
From the Project Home Screen, click the "Edit" drop down menu. Click the "Attributes" button. The 
Define Attributes screen will appear. Select either the "Global," "Hub," or "Player" radio button to designate 
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
Paths are where the action of your game will take place. Each Path is made up of a background image,
dialogues, and buttons. Dialogues have the ability to affect the various attributes you have created via 
impacts. Dialogues will play in the order they appear on the Dialogue list of the "Edit Path" screen.
Buttons give you the ability to have Paths lead to different destinations. Buttons are always the last
part of a path to be displayed. If you use default values, only two buttons may be created. If you use
custom coordinates, you will be able to add more than two buttons.

### Creating a Path
On the Project Home screen, click the "Create..." drop down menu. Click the "Path" button. You will be prompted 
to name your new Path. After clicking the "Ok" button, the "Edit Path" screen will appear. Click the "Save" button
at the bottom right of any of the tabs on this screen to save the Path.

### Editing an Existing Path
On the "Paths" list of Project Home screen, double click the Path you would like to edit. The "Edit Path" 
screen will appear with all the appropriate fields filled out. After making any edits you wish to the Path, 
click the "Save" button at the bottom right of any of the tabs on this screen to save the changes to the Path.

### Selecting a Path Image
On the right side of the "Dialogues" tab of the "Edit Path" screen, click the "Choose Path Image" button. 
You will be prompted to select the file location of the image you would like to use 
(.jpg, .jpeg, .jpe, .jfif, .png files only). Once you press "Ok," the image will appear above the button. 
Click the "Save" button at the bottom right of any of the tabs on this screen to save the image to the Path.

### Selecting Background Sound of a Path
On the right side of the "Dialogues" tab of the "Edit Path" screen, check the "Use Background Music" box. 
You will be prompted to select the file location of the sound you would like to use (.ogg, .wav, .flac, 
.aiff files only). The box will remain checked to identify that a sound has been selected for the Path. 
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
down buttons. Select the desired direction on the list that you wish the Path to be moved in. The Dialogue 
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
a Hub attribute, select the Hub whose attribute you would like to affect from the drop down menu next to
the "Hub" radio button. Select which attribute you would like to affect from the "Attribute" drop down menu 
in the "Add Impact" section. The operator drop down is used to designate if the Impact will add, subtract,
or set the attribute equal to the number given in the "Value" field (values may range from -1000000 to 1000000).
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
_Warning:_ You cannot recover deleted Impacts after you save your changes.

### Buttons
#### Adding a Text Button to a Path
On the top left of the "Buttons" tab of the "Edit Path" screen, enter the desired text for the button into the
"Button Text" field. If you would like the button to highlight when the player mouses over it, check the
"Highlight Text" box in the "Button Images" section. If you would like to use the default location for the button,
check the "Use Location Defaults" box under the Button Text field. If you would like to choose where the button
goes, uncheck the "Use Location Defaults" box and enter the X and Y coordinates in the appropriate fields under
the "Use Location Defaults" box (X coordinates may range from -959 to 960, Y coordinates may range from -539 to
540). To select the destination of the button, choose either the "Path," "Path Group," or "Hub" radio button
in the "Target Navigable" section. Select which Path, Path Group, or Hub you would like on the drop down menu
next to the "Path" radio button. Click the "Create Button" button and a new button will appear on the "Current
Buttons" list on the button left of the screen. The button will be named by the button's ordering in comparison
to the other buttons. The names will refresh whenever you return to the "Buttons" tab. Click the "Save" button at 
the bottom right of any of the tabs on this screen to save your buttons.

#### Adding an Image Button to a Path
In the "Button Images" section of the "Buttons" tab of the "Edit Path" screen, check the "Use Button Image"
box. You will be prompted to select the file location of the image you would like to use 
(.jpg, .jpeg, .jpe, .jfif, .png files only). If you would like the button to be highlighted using a second
image when the player mouses over it, check the "Use Highlighted Image" box. You will be prompted to select 
the file location of the image you would like to use (.jpg, .jpeg, .jpe, .jfif, .png files only). Select the 
size of the image by filling in the "Width" and "Height" fields (Width values may range from 1 to 1920, 
Height Values may range from 1 to 1080). If you would like to use the default location for the button, check 
the "Use Location Defaults" box under the Button Text field. If you would like to choose where the button goes, 
uncheck the "Use Location Defaults" box and enter the X and Y coordinates in the appropriate fields under the 
"Use Location Defaults" box (X coordinates may range from -959 to 960, Y coordinates may range from -539 to 540). 
To select the destination of the button, choose either the "Path," "Path Group," or "Hub" radio button in the 
"Target Navigable" section. Select which Path, Path Group, or Hub you would like on the drop down menu next to the 
"Path" radio button. Click the "Create Button" button and a new button will appear on the "Current Buttons" list on 
the button left of the screen. The button will be named by the button's ordering in comparison to the other buttons. 
The names will refresh whenever you return to the "Buttons" tab. Click the "Save" button at the bottom right of any 
of the tabs on this screen to save your buttons.

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
_Warning:_ You cannot recover deleted buttons after you save your changes.

### Paths with No Buttons
Paths with no buttons serve several purposes, such as being used in your games ending or for the start or end of a
round of gameplay. In these cases, do not add any buttons and leave the fields in the "Default Target Navigable of
Path" section blank. However, if you wish for your Path to lead to another destination, similar to a button, without
the use of a button, check the "Use Default Target" box, above the "Default Target Navigable of Path" section. Select
either the "Path," "Path Group," or "Hub" radio button of the "Default Target Navigable of Path" section. Select which 
Path, Path Group, or Hub you would like on the drop down menu next to the "Path" radio button. Click the "Save" button 
at the bottom right of any of the tabs on this screen to save your changes.

### Deleting a Path
On the "Paths" list of Project Home screen, select the Path you would like to delete. Click the "Delete" button on the
bottom right side of the screen. The Path's name will be removed from the "Paths" list.<br>
_Warning:_ You cannot recover deleted Paths.

## Path Groups
Path Groups are structures you can use to randomize what the player goes to next. The player will
never see a Path Group, but buttons often lead to them. Path Groups have 10 potential tiers 
(0 through 9). Tiers vary in importance and are evaluated by the Path Group in descending order 
(tier 9 is of higher precedence than tier 0). Each tier is made of either Paths or Path Groups 
that have a weight and condition given to them. The weight determines the chance the Path or Path
Group has of being selected by a Path Group to appear. Only one Path or Path Group will be selected.

### Creating a Path Group
On the Project Home screen, click the "Create..." drop down menu. Click the "Path Group" button. 
You will be prompted to name your new Path Group. After clicking the "Ok" button, the "Edit Path Group" 
screen will appear. Click the "Save" button on the bottom right side of the screen to save your
Path Group.

### Adding Paths or Path Groups to a Tier
On the left side of the "Edit Path Group" you will see the "Paths Not in this Group" list and the
"Add to Tier" drop down menu. From the "Add to Tier" drop down menu, select which tier you would
like to add to. Select any number of Paths or Path Groups you would like to add to the tier from the
"Paths Not in this Group" list. If you select a Path or Path Group you did not mean to, click it again
and it will be removed from the selection to be added. Before you add your selection, note the "Tier
Information" section to the right of the "Paths in this Group" list. You may adjust the "Path Weight" 
field to increase your selection's chance of being selected by the Path Group compared to other Paths or
Path Groups in the tier (Path Weight value may range from 1 to 2000000). If you would like your selections to
only be visited once and never again within that Path Group, check the "1 Visit Max" box, also in the "Tier
Information" section. Click the right arrow button at the bottom right of the "Paths Not in this Group" list 
to add your selection to the tier. Your selections will be added to the "Paths in this Group" list and no 
longer appear in the "Paths Not in this Group" list. You will also see the selections added to the "Paths 
in Tier" list in the "Requirements" section at the bottom of the screen, which will have the list of all 
Paths or Path Groups in the tier you have currently selected. Click the "Save" button on the bottom right 
side of the screen to save your changes.

### Removing a Path or Path Group from a Tier
In the center of the "Edit Path Group" screen you will see the "Paths in this Group" list. Select the
Path or Path Group you would like to remove from their current tier. Click the left arrow button at the
bottom left of the "Paths in this Group" list. The Path or Path Group will be removed from their tier and
the "Paths in this Group" list. The Path or Path Group will now appear in the "Paths Not in this Group" list.
Click the "Save" button on the bottom right side of the screen to save your changes.

### Adding a Condition to a Path or Path Group
At the bottom left of the "Edit Path Group" screen, you will see the "Paths in Tier" list. Select the
Path or Path Group you would like to add a condition to. Select either the "Global," "Hub," or "Player" radio
button to designate what type of attribute you would like access to the Path or Path Group to depend upon. If 
you are selecting a Hub attribute, select the Hub whose attribute you would like from the drop down 
menu next to the "Hub" radio button. Select which attribute you would like to use from the "Attribute" drop 
down menu. The "Comparison" drop down is used to designate if the condition will need to be greater than, less than, 
or equal to the number given in the "Value" field (values may range from -1000000 to 1000000). Click the "Add
Condition" button to create the condition. The attribute who the path now depends on will appear in the Conditions
list on the bottom right side of the screen. Click the "Save" button on the bottom right side of the screen to 
save your changes.<br>
_Note:_ You may add multiple conditions of a single attribute to a Path or Path Group. This way you can create a
range of values, such as if you wanted an attribute to be more than a value, but no greater than another value.

### Removing a Condition from a Path or Path Group
At the bottom left of the "Edit Path Group" screen, you will see the "Paths in Tier" list. Select the
Path or Path Group you would like to remove a condition from. On the bottom right side of the screen,
the Conditions list will populate will all the conditions attached to the selected Path or Path Group.
On the Conditions list, select which condition you would like to remove. The appropriate fields of the
"Requirements" section will fill in. Click the "Remove" button, to the left of the Conditions list. The
condition will be removed from the list. Click the "Save" button on the bottom right side of the screen 
to save your changes.<br>
_Warning:_ You cannot recover deleted conditions after you save your changes.

### Deleting a Path Group
On the "Paths Groups" list of Project Home screen, select the Path you would like to delete. Click the 
"Delete" button on the bottom right side of the screen. The Path Group's name will be removed from the 
"Paths Groups" list.<br>
_Warning:_ You cannot recover deleted Path Groups.

## Hubs
Hubs are a resting place before you direct the player in a number of possible destinations. Hubs consist of a 
single screen filled with several buttons and a background image. Buttons allow the player to choose where
they would like to go. With this set up, it is simple to create a house with several explorable rooms or
a campsite with several destinations in the distance for the player to visit.

### Creating a Hub
On the Project Home screen, click the "Create..." drop down menu. Click the "Hub" button. You will be prompted 
to name your new Hub. After clicking the "Ok" button, the "Edit Hub" screen will appear. Click the "Save" button
at the bottom right of the screen to save the Hub.

### Editing an Existing Hub
On the "Hubs" list of Project Home screen, double click the Hub you would like to edit. The "Edit Hub" 
screen will appear with all the appropriate fields filled out. After making any edits you wish to the Hub, 
click the "Save" button at the bottom right of the screen to save the changes to the Hub.

### Selecting a Hub Image
On the left side of the "Edit Hub" screen, click the "Choose Hub Image" button. You will be prompted to select 
the file location of the image you would like to use (.jpg, .jpeg, .jpe, .jfif, .png files only). Once you press 
"Ok," the image will appear to the left of the button. Click the "Save" button at the bottom right of the screen 
to save the image to the Hub.

### Selecting Background Sound of a Hub
On the left side of the "Edit Hub" screen, check the "Use Music" box in the "Background Music" section. 
You will be prompted to select the file location of the sound you would like to use (.ogg, .wav, .flac, 
.aiff files only). The box will remain checked to identify that a sound has been selected for the Hub. 
Click the "Save" button at the bottom right of the screen to save the sound to the Hub.

### Buttons
#### Adding a Text Button to a Hub
In the "Add Button" section of the "Edit Hub" screen, enter the desired text for the button into the
"Button Text" field. If you would like the button to highlight when the player mouses over it, check the
"Highlight Text" box in the "Button Images" section on the top right of the screen. Enter the X and Y 
coordinates for the button on the Hub in the appropriate fields under the "Target Navigable" section 
(X coordinates may range from -959 to 960, Y coordinates may range from -539 to 540). To select the destination 
of the button, choose either the "Path," "Path Group," or "Hub" radio button in the "Target Navigable" section. 
Select which Path, Path Group, or Hub you would like on the drop down menu next to the "Path" radio button. 
Click the "Create Button" button and a new button will appear on the "Current Buttons" list on the button left 
side of the screen. The button will be named by the button's ordering in comparison to the other buttons. The names 
will refresh whenever you return to the "Buttons" tab. Click the "Save" button at the bottom right of the screen to 
save your buttons to the Hub.

#### Adding an Image Button to a Hub
In the "Button Images" section of the "Edit Hub" screen, check the "Use Button Image" box. You will be 
prompted to select the file location of the image you would like to use (.jpg, .jpeg, .jpe, .jfif, .png files only). 
If you would like the button to be highlighted using a second image when the player mouses over it, check the 
"Use Highlighted Image" box. You will be prompted to select the file location of the image you would like to use 
(.jpg, .jpeg, .jpe, .jfif, .png files only). Select the size of the image by filling in the "Width" and "Height" fields 
(Width values may range from 1 to 1920, Height Values may range from 1 to 1080). Enter the X and Y coordinates for 
the button on the Hub in the appropriate fields under the "Button Text" field (X coordinates may range from -959 
to 960, Y coordinates may range from -539 to 540). To select the destination of the button, choose either the "Path," 
"Path Group," or "Hub" radio button in the "Target Navigable" section. Select which Path, Path Group, or Hub you would 
like on the drop down menu next to the "Path" radio button. Click the "Create Button" button and a new button will 
appear on the "Current Buttons" list on the button left of the screen. The button will be named by the button's ordering 
in comparison to the other buttons. The names will refresh whenever you return to the "Buttons" tab. Click the "Save" 
button at the bottom right of any of the tabs on this screen to save your buttons.

#### Deleting a Button from a Hub
On the bottom left of the "Buttons" tab of the "Edit Hub" screen is the "Current Buttons" list. Select the button 
you would like to delete. Click the "Delete Button" button on the bottom right of the "Button Properties" section.
The button's name will be removed from the "Current Buttons" list. Click the "Save" button at the bottom right of 
the screen to save your buttons.<br>
_Warning:_ You cannot recover deleted buttons after you save your changes.

### Deleting a Hub
On the "Hubs" list of Project Home screen, select the Hub you would like to delete. Click the 
"Delete" button on the bottom right side of the screen. The Hub's name will be removed from the 
"Hub" list.<br>
_Warning:_ You cannot recover deleted Hubs.

## Ending Generator
The Ending Generator is similar to a Path Group, with some key differences. Its purpose is to
allow you to customize the ending of each individual player's game. Endings are shown after the
Game Over Requirements have been met (set in Game Settings). Like Path Groups, the Ending
Generator has tiers. In the Path Group, only one Path from all tiers is chosen to be seen, 
whereas in the Ending Generator, a Path is selected from each tier to form a complex ending of 
your creation.

### Adding Paths to a Tier
From the Project Home Screen, click the "Edit" drop down menu. Click the "Endings" button. The
"Ending Generator" screen will appear. On the right side of the screen, you will see the "Tier"
drop down menu. Select which tier you would like to add to. On the left side of the screen, you
will see the "Unused Paths" list. Select the Paths you would like to add to the tier. If you
select a Path you did not mean to, click it again and it will be removed from the selection to
be added. Click the right arrow button next to the "Unused Paths" list to add the Paths to the
Tier. The names will appear under a tier designation on the "Ending Paths" list. Click the "Save"
button to the right side of the screen to save your changes to the Endings Generator.

### Removing a Path from a Tier
In the center of the "Ending Generator" screen, you will see the "Ending Paths" list. Select the 
Path you would like to remove. Click the left arrow button to the left of the "Ending Paths" list. 
The Path will be removed from the "Endings Path" list and added to the "Unused Paths" list on the 
left side of the screen. Click the "Save" button on the right side of the screen to save your changes 
to the Ending Generator.

### Changing the Order of Paths in a Tier
On each tier, precedence of Paths chosen is from left to right. In the center of the "Ending Generator" 
screen, you will see the "Ending Paths" list. Select the Path you would like to move. Select either
the right or left arrow button the on the right side of the "Ending Paths" to move the Path in the
desired direction. The ordering of "Ending Paths" list will reflect the change. Click the "Save"
button to the right side of the screen to save your changes to the Endings Generator.

### Adding Conditions to a Path
In the center of the "Ending Generator" screen, you will see the "Ending Paths" list. Select the 
Path you would like to add a requirement to. In the "Requirements" section of the screen, select 
either the "Global," "Hub," or "Player" radio button to designate what type of attribute you would 
like access to the Path to depend upon. If you are selecting a Hub attribute, select the Hub whose 
attribute you would like from the drop down menu next to the "Hub" radio button. Select which attribute 
you would like to use from the "Attribute" drop down menu. The "Comparison" drop down is used to designate 
if the requirement will need to be greater than, less than, or equal to the number given in the "Value" 
field (values may range from -1000000 to 1000000). Click the "Add Condition" button to create the requirement.
The attribute of the requirement will appear on the Requirements list on the right side of the screen.
Click the "Save" button on the right side of the screen to save changes to the Ending Generator.<br>
_Note:_ You may add multiple requirements of a single attribute to a Path. This way you can create a range of 
values, such as if you wanted an attribute to be greater than a value, but no greater than another value.

## Game Settings
Game Settings covers a broad range of requirements the game loop has to run properly, including the
Game Over Requirements, the Main Menu, default values for dialogues, and more. All Game Settings must
be filled out in some capacity. We recommend working with most of these fields last, as many require
Paths, Path Groups, or Hubs to already have been created. You may acces the Game Settings by clicking
the "Edit" drop down menu on the Project Home screen and clicking the "Game Settings" button.

### Visible Attributes
Just because you have created an attribute does not mean the player has to be aware of it.
On the "Attributes" tab of of the "Game Settings" screen, you will find the "Visible Player
Attributes" and "Visible Global Attributes" sections. Here you can determine which attributes
you would like to appear on the screen for your players as the game runs. Player attributes will
only show up on a given players turn and be color coded to highlight that they belong to a different
player. Global attributes that are made visible are always visible during gameplay.

#### Adding a Visible Player Attribute
In the "Visible Player Attributes" section of the "Attributes" tab on the "Game Settings" screen, 
you will see the "Player Attributes" drop down menu. Select which player attribute you would like
to make visible from the drop down menu. Click the "Add Attribute" button under the "Player Attributes"
drop down menu. The player attribute will be listed in the Visible Player Attributes list on the right
side of the "Visible Player Attributes" section. Click the "Save" button at the bottom of any tab on
the "Game Settings" screen to save your changes.

#### Removing a Visible Player Attribute
In the "Visible Player Attributes" section of the "Attributes" tab on the "Game Settings" screen,
you will see the Visible Player Attributes list, with all currently visible player attributes.
Select the player attribute you would no longer like to be visible during gameplay. Click the
"Remove" button to the left of the Visible Player Attributes list. The player attribute will
be removed from the Visible Player Attributes list. Click the "Save" button at the bottom of any tab on
the "Game Settings" screen to save your changes.

#### Adding a Visible Global Attribute
In the "Visible Global Attributes" section of the "Attributes" tab on the "Game Settings" screen, 
you will see the "Global Attributes" drop down menu. Select which global attribute you would like
to make visible from the drop down menu. Click the "Add Attribute" button under the "Global Attributes"
drop down menu. The global attribute will be listed in the Visible Global Attributes list on the right
side of the "Visible Global Attributes" section. Click the "Save" button at the bottom of any tab on
the "Game Settings" screen to save your changes.

#### Removing a Visible Global Attribute
In the "Visible Global Attributes" section of the "Attributes" tab on the "Game Settings" screen,
you will see the Visible Global Attributes list, with all currently visible global attributes.
Select the global attribute you would no longer like to be visible during gameplay. Click the
"Remove" button to the left of the Visible Global Attributes list. The global attribute will
be removed from the Visible Global Attributes list. Click the "Save" button at the bottom of any tab on
the "Game Settings" screen to save your changes.

### Setting the Start of Player Turn Navigable
The "Start of Player Turn Navigable" is the Path, Path Group, or Hub that all players start
their turn on. The "Start of Player Turn Navigable" drop down menu can be found on the "Attributes"
tab of the "Game Settings" screen. Click on the drop down menu and select the desired Path, Path
Group, or Hub. Click the "Save" button at the bottom of any tab on the "Game Settings" screen to
save your changes.

### Setting the Start of Round Path Group
The "Start of Round Path Group" is a Path Group that decides what to place at the start of every
round of gameplay. The "Start of Round Path Group" drop down menu can be found on the "Attributes"
tab of the "Game Settings" screen. Click on the drop dwon menu and select the desired Path Group.
Click the "Save" button at the bottom of any tab on the "Game Settings" screen to save your changes.

### Setting the End of Round Path Group
The "End of Round Path Group" is a Path Group that decides what to place at the end of every
round of gameplay. The "End of Round Path Group" drop down menu can be found on the "Attributes"
tab of the "Game Settings" screen. Click on the drop down menu and select the desired Path Group.
Click the "Save" button at the bottom of any tab on the "Game Settings" screen to save your changes.

### Setting Player Count
The "Player Count" is the number of players your game will always contain. The "Player Count"
field can be found on the "Attributes" tab of the "Game Settings" screen. Input the desired value
into the field (Player Count may range from 1 to 12). Click the "Save" button at the bottom of any tab
on the "Game Settings" screen to save your changes.

### Main Menu Options
The Main Menu is made of a background image, and "Start Game" and "Quit Game" buttons. Your game
will always begin on the main menu and return to it after a game has ended.

#### Setting the Main Menu Image
In the center of the "Main Menu" tab of the "Game Settings" screen, click the "Select Main Menu Image" 
button. You will be prompted to select the file location of the image you would like to use 
(.jpg, .jpeg, .jpe, .jfif, .png files only). Once you press "Ok," the image will appear above the "Select
Main Menu Image" button. Click the "Save" button at the bottom of any tab on the "Game Settings" screen to 
save the image to the Main Menu.

#### Adding a Background Sound
At the bottom of the "Main Menu" tab of the "Game Settings" screen, check the "Use Background Sound" box in 
the "Sounds" section. You will be prompted to select the file location of the sound you would like to 
use (.ogg, .wav, .flac, .aiff files only). The box will remain checked to identify that a background sound 
has been selected for the Main Menu. Click the "Save" button at the bottom of any tab on the "Game Settings" 
screen to save the background sound to the Main Menu.

#### Removing a Background Sound
At the bottom of the "Main Menu" tab of the "Game Settings" screen, uncheck the "Use Background Sound" box in 
the "Sounds" section. The sound file will automatically be removed from the Main Menu. Click the "Save" button 
at the bottom of any tab on the "Game Settings" screen to save the change to the Main Menu.

#### Adding a Play Button Sound
Play Button is the sound played when the player clicks the "Start Game" button on the Main Menu.
At the bottom of the "Main Menu" tab of the "Game Settings" screen, check the "Use Play Button Sound" box in 
the "Sounds" section. You will be prompted to select the file location of the sound you would like to 
use (.ogg, .wav, .flac, .aiff files only). The box will remain checked to identify that a Play Button sound 
has been selected for the Main Menu. Click the "Save" button at the bottom of any tab on the "Game Settings" 
screen to save the Play Button sound to the Main Menu.

#### Removing a Play Button Sound
At the bottom of the "Main Menu" tab of the "Game Settings" screen, uncheck the "Use Play Button Sound" box in 
the "Sounds" section. The sound file will automatically be removed from the Main Menu. Click the "Save" button 
at the bottom of any tab on the "Game Settings" screen to save the change to the Main Menu.

#### Choosing a Main Menu Font
Main Menu Font is the font applied to the buttons on the Main Menu. At the bottom of the "Main Menu"
tab of the "Game Settings" screen, click the "Choose Font" button. You will be prompted to select the 
file location of the font you would like to use (.otf, .ttf files only). The "X" next to the "Choose
Font" button will turn to a check mark. Click the "Save" button at the bottom of any tab on the "Game 
Settings" screen to save the Main Menu font to the Main Menu.

### Default Dialogue Options
#### Setting a Dialogue Scroll Sound
The scroll sound of a dialogue is the sound that plays as the text of the dialogue is appearing on the 
screen. On the "Dialogue" tab of the "Game Settings" screen, you will see the "Choose Scroll Sound"
button. Click the button and you will be prompted to select the file location of the sound you would like 
to use (.ogg, .wav, .flac, .aiff files only). The "X" next to the "Choose Scroll Sound" button will turn 
to a check mark. Click the "Save" button at the bottom of any tab on the "Game Settings" screen to save 
the default dialogue scroll sound.

#### Setting a Dialogue End Sound
The end sound of the dialogue is the sound that plays when the text appearing on the screen has reached
its end. It is highly recommended that this sound not be more than one to two seconds. On the "Dialogue" 
tab of the "Game Settings" screen, you will see the "Choose End Sound" button. 
Click the button and you will be prompted to select the file location of the sound you would like to use 
(.ogg, .wav, .flac, .aiff files only). The "X" next to the "Choose End Sound" button will turn to a check 
mark. Click the "Save" button at the bottom of any tab on the "Game Settings" screen to save the default
dialogue end sound.

#### Setting a Dialogue Font
The default font is the font applied to all dialogues that have not been given a specific font by their
path. On the "Dialogue" tab of the "Game Settings" screen, you will see the "Choose Dialogue Font" button.
Click the button and you will be prompted to select the file location of the font you would like to use 
(.otf, .ttf files only). The "X" next to the "Choose End Sound" button will turn to a check 
mark. Click the "Save" button at the bottom of any tab on the "Game Settings" screen to save the default
dialogue font.

#### Setting an Enter Key Texture
The enter key texture is the image used to prompt the user to press the "Enter" key to continue to the
dialogue. This image will accompany every dialogue you create. On the "Dialogue" tab of the "Game Settings"
screen, you will see the "Choose "Enter" Texture" button. Click the button and you will be prompted to select 
the file location of the image you would like to use (.jpg, .jpeg, .jpe, .jfif, .png files only). The "X"
next to the "Choose "Enter" Texture" will turn to a check mark. Click the "Save" button at the bottom of any
tab on the "Game Settings" screen to save the enter key texture.

#### Setting an Enter Key Position
The enter key position will determine where on the screen the enter key texture will appear. The position is
the point of the top left of the enter key texture; keep this in mind as you choose the coordinates. This 
position will be fixed across all paths. On the "Dialogue" tab of the "Game Settings" screen, you will
see the "Enter Key Postion" section with "X" and "Y" fields. Enter the desired X and Y coordinate values
(X values may range from -959 to 959, Y values may range from -539 to 540). Click the "Save" button
at the bottom of any tab on the "Game Settings" screen to save the Enter Key Position.

#### Setting a Pane Texture
The pane texture is the image used as the container of the dialogue. It will appear everywhere dialogue
appears. On the "Dialogue" tab of the "Game Settings" screen, you will see the "Choose Pane Texture" button.
Click the button and you will be prompted to select the file location of the image you would like to use 
(.jpg, .jpeg, .jpe, .jfif, .png files only). Keep in mind that the pane will be formatted to 1500x300 pixels.
The "X" next to the "Choose Pane Texture" button will turn to a check mark. Click the "Save" button at the 
bottom of any tab on the "Game Settings" screen to save the dialogue pane texture.

#### Setting a Pane Position
The pane position will determine where on the screen the dialogue pane will appear. The position gives the
point of the top left corner of the pane; keep this in mind as you choose the coordinates. On the "Dialogue"
tab of the "Game Settings" screen, you will see the "Pane Position" section with "X" and "Y" fields. Enter
the desired X and Y coordinate values (X values may range from -959 to 960, Y values may range from -539
to 540). Click the "Save" button at the bottom of any tab on the "Game Settings" screen to save the
dialogue pane position.

#### Setting a Character Position
The Character position will determine where on the screen a Character's image will appear, should
you choose to add one to a path. The position gives the point of the top left corner of the Character image; 
keep this in mind as you choose the coordinates. This position will be fixed across all paths, so the Character 
will always appear in this position. On the "Dialogue" tab of the "Game Settings" screen, you will see the
"Player Position" section with "X" and "Y" fields. Enter the desired X and Y coordinate values (X values
may range from -959 to 960, Y values may range from -539 to 540). Click the "Save" button at the bottom of
any tab on the "Game Settings" screen to save the Character position.


### Setting Game Over Requirements
#### Adding a Game Over Condition

#### Removing a Game Over Condition

## Creating the Game
### Run Playtest

