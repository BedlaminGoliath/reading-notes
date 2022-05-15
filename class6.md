# Javascript

Javascript is a "Just-in-time" computing language. *just in time compilation* referes to a way computercode is "compiled" **during** the execution of a program rather than being compiled **before** the execution of the program. This style of language is refered to as a intreped language (which means that the code is run from top to bottom and the code is returned "immediatly" with no need to be transformed before the browser does its thing). This differes from another type of code called "compiled code" *this* type of code is "compiled" which means it is transformed before it is actually run by the computer, this takes the code and makes it "machine code". Although Javascript *does* get compiled (through "just in time" / realtime) compiling to make it perform better, Javascript gets compiled into binary **while** the script is actually being run. 

JaveScript itself is a "object-oriented-program" where the coder gets to "define" what certain "classes" are, because those programs on their own are not outright defined, however they get their "definition" when the user adds properties and methods to a class. These are like a set of instructions that gives the class not only what its refering to but also what is to do.

Javascript works with 3 variable declarations (var,let,const.) these three options are called variables, a variable is essentially a "Storgae container" that can store data/information. The "var" variable is "function based" an has a much broader scope of instructions, this variable can also be changed through-out the code, so although it is the oldest of the declarations it use is impactful but is not a "one size fits all", perhaps there is a moment where you want the info to STAY as is... then *const* would be a good fit.. this would make for a "stationary" use. The *let* variable (much like *const*) is "block scopped" which means its focus is much more pin-pointed than the *var* variable. The "block" in javascript is the info that is put inbetween the curly braces ``{}`` much like we have seen in CSS this is where the "commands" or "instructions" and specifics of the block sits.

## More fun

    Now we have this info what can we do with it? well.. this is more about what Javascript can do with it in the right hands. Javascript can run code in response to what is happening on the page, This brings up another topic "APIs" an API (Application Programming Interface). These are premade "code blocks" that helps the developer do certain things simply, that would otherwise be kind of a pain to do. Think of These like ikea furniture... no, not cause its cheaply made, more because it is essentially snapping some larger premade pieces together inorder to make that large piece come together much quicker than having to make those individual components on your own. Those pieces are premade and much like legos they come together with ease... or atleast they should. There a few different kinds of API's:

    1. DOM (document object Model): This helps you manipulate the HTML/CSS in real time "dynamically".. think like pop up windows and such
    2. Geolocation: This gets geographical info, like google maps.
    3. Canvas: This allows devs to creat either 2d or 3d graphics
    4. Audio & Video API: This one lets you do as it sounds. this lets you embed Video and even lets you play audio on the page
    5. Twitter API: This lets people display their tweets on a page.
    6. Google maps: This allows the user to embed maps info on the site.

### More About

    Javascript is kind of like algebra.. with all this talk of "variable" its easy to feel like youre in math class right now. Much like I stated earlier variables hold values 

    ``let x = 5;
      let y = 6;
      let z = x + y:``

    This is would leave you with the answer being "11".. see... its alot like algebra, not exactly.. but it does carry some of the principles. However unlike algebra you can you have these variables hold not just numbers but they can also hold "text values ('john doe') we also refer to as "strings" thats right we can rewrite that example above like this 

    ``let x = "john";
      let y = "doe";
      let z = x + y; ``

    Thats right! we just added words together! we got "z = john doe"... or you could say we used a "string". Now a string is written **inside** double quotes ("")... so with that being said it is possible to treat your numbers like we treated our words. instead of getting ``z = 11`` we would end up with ``z = 56`` simply by putting a double quote around the numbers... even putting it around one number would do the trick. 

### Beyond Javascript

    Now beyohd any language I feel its important to look at the computer as a whole. like "What makes a computer?" well to put simply a computer is there to manipulateb information. Now its obvious inorder to manipulate said information it would first need to recieve the information. Which brings me to my next point, every computer be it your: phone, tablet, desktop, watch etc. has 4 key functions... and these help answer the question "what makes a computer" a computer shoud be able to Reciece Information, store that information, process the information, then out put the information... that little bit if info I just gave you probably set off a light bulb in your head... thats right i just made your head a computer! an that new thought/ light bulb/ smirk was the output. I gave you the input, you repeated it and stored it, then processed it, then out came the images of every computer you have used, you probably feel a wrinkle in your brain forming as well. 

    The next question you probably have is: "how do they work"? 
    the language of computers is called "binary" this is a series of "1's and 0's" or whatever gives two optiones (on or off, true or false, 1 or 0) you can write just about everything in  binary, you can write colors, audio, images (so video as well) and words... all this can be taken from "binary". The smallest "bit" if info is referred to as a "bit" a bit consists of a series of 8 numbers (binary numbers) and the 8 bits create a "byte".Now... computers take the input in binary form and process is it via "circuits" there are different circuits and the different circuits can do different things (thanks to binary). a simple circuit is an "on and off" circuit... or think "binary" there is a way to "spell" or express information in the language of computers. One thing we noticed over the years was the size of the circuits... they have gotten smaller! and smaller circuits makes for a smaller distance the electricy would have to travel (electricity travels roughly at the speed of light) so the smaller circuits has made computers much faster. 

    Computers are made up of "hardware" and "software".. hardware is everything that is physical (like the circuits, the chips, the keyboard, the screen). while the software is the unsung hero, this consists of the code that is directing the computer on what to do. One of the most important things inside of this realm is the Operating system also known as the "OS" the OS is what directs what the cpu to focus on and what to do, it tells the hardware what to do as well.
