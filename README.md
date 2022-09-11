# JavaPractice
Helpful stuff for when I need to review java, alongside data structures and other more advanced topics.

# Contents:
1. [Basics](#Basics)
2. [Intellij](#Intellij)


## Basics and Syntax
### Resources:
[**Alex Lee Java Youtube Playlists**](https://www.youtube.com/c/AlexLeeYT/playlists)\
These tutorials are shown in eclipse and have a series of playlists, with around 25 vids each, beginner 1, beginner 2, Intermediate and further.
## Advanced and data structures
## Intellij
To create new projcet: File -> new -> project\
Can link up with a git repository inside the IDE.
### Creating a new class
New class files created by right clicking the src folder.\
The .java file can then be run by clicking the green play button located either top right or along the line numbers margin. If a template is used this will likely already be there but just creating the class file in Intellij without a template will just initiate the public class file as shown:
```
public class HelloWorld {

}
```
The most basic way to get something to run is to create a main function which takes a string of args[ ] (rather than int ArgC and Char* ArgV[ ] in c). The new class file would appear as follows and the green arrow will become active, allowing the program to be run.
```
public class HelloWorld {

    public static void main(String args[]){
        System.out.println("Hello World");
    }

}
```
