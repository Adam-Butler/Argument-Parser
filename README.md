# Argument-Parser
This repo contains an Argument Parser program in which the user can add his/her arguments to the command line, separated by spaces. The arguments can be numbers, words, or letters. Some arguments can also contain one or two dashes if front of the argument to denote it as an optional argument. The program will also throw custom exceptions to describe any errors.	
	
	- **Note:** The Readme will only cover a few of the classes involved with the program since there were many contributers.
## Classes
- **Argument.java**: This class defines what an argument for the program is. An Argument can have the following datatypes: Integer, Float, Boolean, or String. An Argument can be composed of a name string, a description string, and a datatype, or it can be composed of a name string, a description string, a datatype, and a list of restricted values. The class allows for the functionalities of: adding a specified value to the argument object, getting the name of the argument object, getting the value of the argument object, giving the argument an index value, getting the datatype of the argument, and getting the description of the argument.
- **TooFewArgsException.java**: This class is a custom exception for when the user does not add enough arguments to the command line. For example, if the user were to add a "length" argument and a "height" argument, but supplied three data arguments, he/she would receive an exception message saying that they were missing an argument for the third data argument. 
- **ArgsParser.java**: This class contains the functionality of the program. It includes many methods, including, but not limited to:
	- **parse**: This method allows for the program to check for certain exceptions, and then continues to take the command line arguments and parse them to their matching user given argument names and descriptions.
	- **addArg**: The class contains many varitations of the addArg method, which adds the arguments supplied by the user to the program. A few of these varitations include adding	an argument given an argument object(see argument.java), adding an argument given a name, description, and a datatype, and adding an argument with just a name and a datatype.
	- **"Getters"**: There are a few different "getter" functions that retrieve the number of arguments, the program name, the program description, and getting an argument given a name.
## Contributers
- Avery Whitecotton
- Colby Morris
- Grady Houlditch
- Colby Hilyer
- Cody McGee
## What I Learned
This project was extremely time consumming, i had to learn to balance all of my other schoolwork with this one. I also learned that sometimes people will have to go out of their way to make up for some members not being able or not wanting to pull their own weight. I learned the process of Scrum, an agile methodology.
	
