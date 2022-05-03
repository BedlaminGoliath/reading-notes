# The Brain: A text editors most important extension (a story in 3 parts).

# The sunkin ship *is* the Treasure
 The Hunt tends to be a huge part of what we do, I mean we as humans were (are?) hunter gatheres and it's kind of our thing. Although in this context we are not hunting for food, we are hunting for a tool... a tool to help us not only wrangle text, we are also wrangling computers and with that one could say we are wrangling imaginations, or just trying to make life alittle more simple by allowing our phone to unlock without removing your mask (the *mask* part was very telling of the era this was written.)

 # What is said treasure ?
 Its important to back track alittle bit and talk about what a text editor is. Okay really it's just as it sounds, it edits text. It is a very important tool for developers, because it is the devs medium. it is our *canvas* so to speak. This is where we write those lines of awesome intricate looking code... those long strings, of beautifully colored code (some text editors have a highlight feature to make writing..most importantly reading code **easier**.) The hours spent to impress your friends to display "Hello World" (tears of joy) is often written on a Text Editor. Now a Text editor can be as intricate or as simple as you want, because there are options. There is Visual Studios and Sublime (My two favorites) they have really neat features that can help keep you from straining your eyes and even a screen on the side to display your code with-out having to refresh your browser page to update what is being displayed. There are many plug-ins to help ease the writing of code. let's not forget the predicitive text....(emmet) it does just as it sounds, it finishes your tags and there is even help to set you up with a closing tag, that can honestly half the amount of time spent Writing. The most simple form is a text editor we all have on our computers : Note pade, and text edit (to name a few) are fully capabale of rendering code an can act as a platform for you to begin your coding journey. 

# Okay there is something inside the actual ship, not gold but a decision to be made.
The choice one makes really is dependant on what they feel most comfortable with, The choice of the Text editor can be daunting one, however there is no wrong or right answer, well i guess the right answer is: which one works for you and your task at hand ? I mean there aree different tools for different reasons. The simplicity of Note Pad seems pleasing especially when taking on an undertaking of learning code, but i feel the perks of having a text editor really out weighs any of that stuff. Seek the features that speak to you and your needs: do your eyes strain easy? get one that can add a blue blocker, Do you think that all those tags will look alike? get one that will highlight code, Do you like effeciency? Then pick one (VS code) because emmet is a sweet being. 
# Beyond the editor (one step beyond).
Beyond the text editors, we have IDE's ( Integrated  Developement Environment) which is a topic unto itself. Although there are differences, one of the most notable will be the ability to debug, Complile, and Manage files within the space.. for me thats like having a music studio and fully running kitchen staff in my house..I would have no reason to leave. An IDE has the ability to not just edit the text but to compile the text, what does it mean to compile the text ? W3 reads this
>A compiler is system software (a set of a computer program) that converts source code written in a programming language (source language, usually HLL) into another computer language (target language). It processes every statement written in a particular programming language and turns them to machine language. After writing the program the programmer runs the code in an appropriate language compiler specifying the name of the file that contains the source statements. [^1]. 

The conecept of an IDE is sort of like a box store like TARGET, it not only carries groceries, but your able to buy a TV, Socks, and maybe even a new pair of pants (or suspenders). Think of it as a one stop shop. I personally feel its a good choice to find a text editor that you can grow into... i did just that. I initially started out with SUblime text, but when i really started to enjoy and take to coding i went with VS code.

### Dont be shy jump on in, the water is fine. 

![comfortable](https://user-images.githubusercontent.com/99520664/165551583-7d2e0e35-42d7-4fa8-a136-a642c0d7ed26.jpeg)




![fin](https://i.ytimg.com/vi/77xkcpf3KDw/hqdefault.jpg)

*****

# BUT WAIT THERE'S MORE!!
![Drama Bomb](https://user-images.githubusercontent.com/99520664/165584450-f83632e1-bdb8-41c9-9b4e-325dd3088c6b.jpeg)

# Chapter 2: GUI and THE TERMINAL!!!
most people assume and likely dont care too much to aknowledge what actually goes on within the computer and how it works, however some people do... and we are likely those people. Most folks boot up ther computer, wait a few seconds and then enter their password and then off to the races to watch as many cat videos as possible, while listening to a podcast they enjoy all the while they are looking for a new spanish rice recipe. What seems to ~~mean~~ matter most, is the GUI (graphic user interface) you know the thing that essentially uses graphics (pointer, folders, you know all of it) to help you get from point A to point B. But.. what if I told you there was a way to navigate without the use of a GUI... well its possible, with the "terminal". The terminal is that awesome little black box with boring letters that everyone has likely seen atleast once in their life. That little black box for me always looked so cool and I would leave it open to just feel like a hacker. However that Terminal is a bit more useful that cool looks, you are able to navigate from folder to folder in search for that special file.Actually you are able to even create a new file within the terminal, hell you can even destroy files (not as dramatic as that, but in a sense its true.) The terminal is actually a very fast way to navigate and can improve the speed of your workflow.

# Commands 
Opening the terminal is easy enough, especially for Mac users. In order to open the terminal on a Mac its as easy as hitting the magnifying glass and searching for "terminal" and voala! That beautiful black box (the terminal) has walked in.
When the terminal opens usually the first thing that happens is you will enter a command into the terminal. Following the command you will receive an output that usually is displayed right under the command itself (like a conversation), however unlike some conversations if you did something "wrong" or something is missing within your command then you recieve an error. then rinse and repeat (so to speak). However you are able to able navigate from folder to folder to find a certain file and open that file (in this context) in your text editor.

# Shells
Within terminals you have what is known as a "shell", the shell pretty "dictates how the terminal acts and looks after you execute (enter) your command. A very common shell is called a *BASH* (Bourne again shell).

# Fun Stuff
Below I will note a "cheat sheet" for common shortcuts that will help navigate this new world.
1. **pwd** (Printing Working Directory): Tells you your current Space.
2. **lS** (List) 
3. **lS -l** (long list) Which states weither file is directoy (d)or normal file (-) with more inso stating permission, number of block, owner, group file belongs too. [^2]

4.(~) Is a short cut to home directory.
5.(.) Is a reference to current directory.
6.(..) Is a reference to parent directory.

# Paths (relative & absolute) 
While utilizing the terminal of course you will have to get around, to do so you will need to use different paths. A reltive path is the item you are looking for in relation to where you are, while the absolute file is in relation to the actual root of the file system itself.

# Files
* An important piece of information to know is that everything is actually a file, from the software to how the hardware communicates with the software.
* Maybe we are aware with passwords but linuxs terminal is case sensitive and can change the file you are trying to get to by making a character capital or lower case. 
* There is a method to hide or "unhide" files `` .`` before the file name. these files are not displayed, however if you want to display these files you can add `` -a `` to ``ls``
``ls -a Documents``
* One of the most important features to be is the TAB feature where, you can hirt TAB after beinging to write a file name and it can pull it up for you by completeing the name (of coure more letters are better if necessary. 

*****



*table of contents:*
* [Class1](class1reading.md)
* [Class3](class3.md)
* [Class3_retro](class3-retro.md)
* [Home](README.md)

*resources:*

 [^1]:[W3 complier link](https://www.w3schools.in/what-is-compiler)
 [^2]:[Ryanstutorials.net](https://ryanstutorials.net/linuxtutorial/navigation.php)
 