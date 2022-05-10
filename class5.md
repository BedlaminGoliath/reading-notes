# CSS

## The big picture

CSS stands for "Cascading Style Sheets". Css is how you start to flesh out your markup, or how you add "walls" to your structure. Here is where you get to adjust your specific font, your font-size, back-ground color, font color, spaces between paragraphs, everything that pretty much makes your site "pretty".

CSS is known as a "rule based language", where the person who is writing the "code" must "define" the group or groups of styling that is going to be applied to a speceific element or elements. Here you are able to select weither you want to add style to all your ``<h1>`` or your ``<p>`` (you get the pciture), now beyond that you are able to even just select your background color(font size/font style.. etc.) for those speicific elements as well.

There are a couple of different ways to go about adding style your markup (often HTML), you are able to add it either: externally, interrnally or inline. you can even utilize all three methods to accomplish a certain goal or style (although I myself cant think of a reason why you'd do it... im sure there's a reason).

### The inner workings

Now we get to the fun stuff.
first things first.. how does css even look ?
``h1 {
    color: blue:
}``
here you see what appears to be just the name of the element of a "header1" element, well that is the "selector" that is where we do just that, we pick which element we are focused on styling, in this case we are looking at the ``<h1>`` element. Below it we see some "curly braces" this is where we put our "declarations" in this context its a "property" (color) and its "value" (blue). The property is what we are doing, it could be "font-size" or "background color", but right now we are just focusing on the actual color of the text of the header element. One thing youll notice is the colon placed inbetween the porperty and the value, that is a must to distinquish the two and then you have the semi-colon which ends that "declaration" of what you are doing, if you wish to adjust more then you would place another property seperated by a colon from its value and end it with a semi-colon again... and so forth... The value is what we are actually applying to it. We can add and adjust many different things in it. Lets not forget the unsung hero's the "curly braces" all this information regarding the property and value must be placed inside the curly braces while the selector (the element/ elements you are working on) are left at the top of the braces.

As mentioned earlier we have 3 different ways to "link" the styling to the initial markdown document.

1. internal.
2. external.
3. inline.

(1.)*Interanl css*: is done by adding a ``<style>`` element inside the``<head>``section of the document. Inbetween

    `` <head>
    <style>
    h1 {
    background-color: black; 
    }
    </style>
       </head> ``

(2.)*External css*: is done adding another file to your HTML file. The file should be saved as a ".css" file. You would need to add it to your HTML file via a ``<link>`` inside the the ``<head>`` element it should look something like this (on your HTML file.)

    `` <head>
        <link rel="stylesheet" href="mystyle.css">
        </head>
    ``
Then on youre ".css" page you would have something like this.
    ``h1 {
        font-size: 32px;
    }``
    This is assuming that you have a ``<h1>`` within your HTML file, would make the "font-size" adjust to whatever you wanted it to... in this case it adjusting the fontsize.

(3.)*inline css*: This can be used to apply a styling to a single element, within your css folder (with no external file or no ``<style>`` element needed.) This is a very straight foward use of this.
    ``<h1 style="color:blue;text-align:right;">Heading text</h1>``

This would all be done on one line and give whatever change you are trying to make the "value" of your "property".

### Colors

The last small topic worth discussing will be "colors" within CSS because this is the first one I myself really had fun with. So as above mentioned you can adjust the colors of your font or background or anything really.There are a few different ways to achieve certain colors; we have "Hex colors" which is a color defined by a hexidecimal value, (we will use the color "red" in this example) red = #ff0000. You can adjust the subtle changes in your colors by way of adjusting the letters and number (like a numeric lock) This is a while other topic so we wont get into it here. 

Next we have the simple "red" we can just call it the name of the color, these colors alongside their name are all available online, much so are the the hex color values, so they are easy to find. Next we have a RGB(A) Which is the Red,Green and Blue value the color you are seeking, the "A" stands for "alpha" which is there to adjust the transparancey... the RGB would look like this.
    ``h1 {
        color: rgd(rgb 0,2,221)
    }``

    The "A" for the Alpha would be added to the end of that as you could imagine. 

There is another one i discovered which is the "HSL" which stands for Hue,saturation, lightness (alpha as well as above mentioned). this would look the same, however the last two values would be written as a percentage.

#### IN THE END

In the end, we have only scratched the surface of the art of CSS, it is a wonderous world that is worth getting to know, inorder to develope your own "style" or at the very least you can give your client whatever it is they want. From where I am coming from I feel its important to have "your thing/style", yes learn to follow the rules and understand the why, but when you learn the "whys" you are able to bend things a bit more.

Within these readings, ive learned alot about css and developed a better understanding of the "rgb" and the "hsl aspect. 