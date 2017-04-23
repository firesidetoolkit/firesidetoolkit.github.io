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
Click the "File" drop down menu. Click the "New..." button.<br>
_Warning:_ Clicking this will remove everything in the currently open project. 
If you're working on an existing project, it is strongly urged that you save if 
you do not wish for any changes to be lost. After clicking the "New..." button, 
you will be in a new project.

### Saving a New Project or Copying a Project
Click the "File" drop down menu. Click the "Save As..." button. You will be prompted to select a 
directory to save your file in and to give the file a name. Your file will be given the ".fsp"
extension for "Fireside Project."

### Saving an Existing Project
Click the "File" drop down menu. Click the "Save" button. The toolkit will automatically update
your existing ".fsp" file.

### Loading a Project
Click the "File" drop down menu. Click the "Open..." button. You will be prompted to select the
directory of your desired ".fsp" file. Once there, select the file and the toolkit will open the
project!

## Attributes
Attributes are variables that you create to keep track of what is happening in your game. Attributes
come in three varieties: Global, Hub, and Player. 
- Global attributes are applied to the game as a whole. These are useful for things like keeping track of what round of play the game is currently on.
- Hub attributes apply to specific hubs, though there is an option to create a variable that applies to all hubs. These are useful for things like keeping track of the weather or population of a given area.
- Player attributes are applied to each player of your game, individually. These are useful for things like keeping track of of health of a given player or whether or not they are carrying a specific item.

### Creating an Attribute
Click the "Edit" drop down menu. Click the "Attributes" button. The Define Attributes screen will
appear. Select either the "Global," "Hub," or "Player" button to designate which type of attribute
you would like to create. If you are creating a Hub, you will need to select which Hub you would like
the Attribute to apply to on the drop down menu next to the "Hub" radio button. If you would like the
attribute to apply to all Hubs, check the "Apply to All Hubs" box under the "Name" field in the 
"Attribute Details" section of the screen. Give your attribute a name in the "Name" field and select
a starting value (between -1000000 and 1000000) that your attribute will be initialized to. When you're
done, click the "Add/Edit" button in the "Attribute Details" section.

### Editing an Attribute
Click the "Edit" drop down menu. Click the "Attributes" button. The Define Attributes screen will
appear. On the left side of the screen will be the list of existing attributes. Select the attribute 
you would like to edit and the appropriate fields for the attribute will be filled out. You may edit 
the details of the attribute and then click the "Add/Edit" button in the "Attribute Details" section 
of the screen to save your changes.

### Deleting an Attribute
Click the "Edit" drop down menu. Click the "Attributes" button. The Define Attributes screen will
appear. On the left side of the screen will be the list of existing attributes. Select the attribute
you would like to delete. Click the "Delete Selected" button in the "Attribute Details" section of
the screen to delete the attribute.<br>
_Warning:_ You cannot recover deleted Attributes.

## Characters
Characters are the physical representation of either the player or anyone they interact with. They are
a collection of images used to portray the individual you wish to represent. You may attach characters'
images to dialogues in the game during Path creation.

### Create a New Character
Click the "Edit" drop down menu. Click the "Characters" button. The Edit Characters screen will appear.
Fill in the "Character Name" field with the desired named. Click the "Create New" button to create the
character. The character's name will appear in the "Character Names" list on the right side on the
screen.

### Adding an Image to a Character
Click the "Edit" drop down menu. Click the "Characters" button. The Edit Characters screen will appear.
On the right side of the screen, you will see two lists: "Character Names" and "Character Images." From
the "Character Names" list, select the character you would like to add images to. In the "Add Images" 
section, click the "Choose Image..." button. You will be prompted to select the file location of the 
image you would like to use. The image you select will be displayed on the left side of the "Add Images" 
section. Fill in the "Image Name" field with the desired name. Click the "Add Character Image" button to 
add the selected image to the character. The image's name will appear in the "Character Images" list
whenever the character is selected.

### Deleting an Image from a Character
Click the "Edit" drop down menu. Click the "Characters" button. The Edit Characters screen will appear.
On the right side of the screen, you will see two lists: "Character Names" and "Character Images." From
the "Character Names" list, select the character you would like to delete images from. From the "Character
Images" list, select the image you would like to delete. Selecting the image will fill in the appropriate
fields in the "Add Images" section. Click the "Delete Image" button in the "Add Images" section. The image
name will no longer appear on the "Character Images" list.

### Delete an Existing Character
Click the "Edit" drop down menu. Click the "Characters" button. The Edit Characters screen will appear.
On the right side of the screen, you will see two lists: "Character Names" and "Character Images." From
the "Character Names" list, select the character you would like to delete. Click the "Delete Character"
button to delete the character. The character's name will no long appear on the "Character Names" list.

## Paths
### Creating a Path

### Selecting a Path Image

### Selecting Background Sound of a Path

### Adding Dialogue

### Adding Impacts to a Dialogue

### Adding Characters to a Dialogue

### Adding Buttons to a Path

### Saving a Path

### Deleting a Path

## Path Groups
### Creating a Path Group

### Tiers

### Adding a Path to a Tier
(Include Path Wieght Here)

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

