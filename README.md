# unity-coding-conventions
I want my own projects to follow same coding conventions. I wrote this note so I don't have to always google again how something was supposed to be written. Maybe this will give inspiration to you too :)

This is partly Unity's best practices, partly Microsoft's C# conventions and partly just how I like to do it myself.

## Naming Guidelines

### Unity Editor

#### Folders
All folders that are created should start with underscore. This way when downloading packages to Unity, the folders won't get mixed up. For example _Scenes.

### Code

#### Classes
Classes are written in PascalCase. For example GameManager.

#### Interfaces
Interfaces are written in PascalCase. Interface starts with "I". For example IAnimal.

#### Methods
All methods are written in PascalCase. For example DoThis().

#### Fields

#### Enums
Enums should be written in PascalCase. The name should be singular. For example public enum Status { Idle, NotSet }
