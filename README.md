# unity-coding-conventions
I want my own projects to follow same coding conventions. I wrote this note so I don't have to always google again how something was supposed to be written. Maybe this will give inspiration to you too :)

This is partly Unity's best practices, partly Microsoft's C# conventions and partly just how I like to do it myself.

## Naming Guidelines

## Unity Editor

### Folders
All root folders (folders in Assets) that are created should start with underscore. This way when downloading packages to Unity, the folders won't get mixed up. For example <b>_Scenes</b>.

Folders inside root folders are named using PascalCase, for example <b>SideQuestScripts</b>.

### File names
C# file names are the same as the class name. Names are written in PascalCase. For example <b>GameManager</b>.

Scene files are written in PascalCase. For example <b>MainMenu</b>.

### Hierarchy gameobjects
All gameobjects use PascalCase. Keep the most descriptive word on left, for example FireZombie instead of ZombieFire. Name should end with the type of the gameobject so it's easier to see which object it is, for example <b>PauseButton</b> or <b>HighScoreBackgroundPanel</b>.

## Code

### Classes
Classes are written in PascalCase. For example <b>GameManager</b>.

### Interfaces
Interfaces are written in PascalCase. Interface starts with "I". For example <b>IAnimal</b>.

### Methods
All methods are written in PascalCase. For example <b>DoThis()</b>.

### Fields

### Enums
Enums should be written in PascalCase. The name should be singular. For example <b>public enum Status { Idle, NotSet }</b>

### Attributes
When using attributes with properties, it's marked on same line and not separately.<br>
For example: <br>
<b>[SerializeField] private float _speed</b> <br>
instead of<br>
<b>[SerializeField]</b><br>
<b>private float _speed</b><br>
