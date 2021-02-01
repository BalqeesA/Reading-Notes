

CSS

CSS allows you to create rules that specify how the content of an element should appear. For example, you can specify that the background of the page is cream, all paragraphs should appear in gray using the Arial typeface, or that all level one headings should be in a blue, italic, Times typeface

Once you have learned how to write a CSS rule, learning CSS mostly involves learning the different properties you can use. 


 ## underStandIng cSS: thI nk Ing InSI de the Box

The key to understanding how CSS works is to imagine that there is an invisible box around every HTML element

 CSSYou may remember from pages 185-186that in there is a difference between block level and inline elements and how how browsers display them.Block level elements look like they start on a new line.  Examples include the <h1>-<h6>, <p> and <div> elements.Inline elements flow within the text and do not start on a new line. Examples include <b>, <i>, <img>, <em> and <span>.The key to understanding how CSS works is to imagine that there is an invisible box around every HTML element

CSSCSS allows you to create rules that control the way that each individual box (and the contents of that box) is presented.

## Color can really bring your pages to life

### Foreground Color
color
The color property allows you to specify the color of text inside an element. You can specify any color in CSS in one of three ways

rgb values
These express colors in terms of how much red, green and blue are used to make it up. For example: rgb(100,100,90).

hex codes
These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash #sign. For example: #ee3e80

color names
There are 147 predefined color names that are recognized by browsers. For example:
DarkCyan

## Background color
background-color
CSS treats each HTML element as if it appears in a box, and the background-color property sets the color of the background for that box. You can specify your choice of background color in the same three ways you can specify foreground colors: RGB values, hex codes, and color names (covered on the next page). 
If you do not specify a background color, then the background is transparent. By default, most browser windows have a white background, but browser users can set a background color for their windows, so if you want to be sure that the background is white you can use the background-color property on the <body> element.

### Understanding Color
Every color on a computer screen is created by mixing amounts of red, green, and blue. To find the color you want, you can use a color picker

Computer monitors are made up of thousands of tiny squares called pixels (if you look very closely at your monitor you should be able to see them). When the screen is not turned on, it's black because it's not emitting any light. When it's
on, each pixel can be a different color, creating a picture. The color of every pixel on the screen is expressed in terms of a mix of red, green, and blue — just like on a television screen.

Color picking tools are available in image editing programs like Photoshop and GIMP. You can see the RGB values specified next to the radio buttons that say R, G, B.

RGB Values
Values for red, green, and blue are expressed as numbers between 0 and 255.

Hex Codes
Hex values represent values for red, green, and blue in hexadecimal code.

Color Names
Colors are represented by predefined names. However, they are very limited in number.

Hue
Hue is near to the colloquial idea of color. Technically speaking however, a color can also have saturation and brightness a well as hue.

Saturation
Saturation refers to the amount of gray in a color. At maximum saturation, there would be no gray in the color. At minimum saturation, the color would be mostly gray.

Brigh tness
Brightness (or "value") refers to how much black is in a color. At maximum brightness, there would be no black in the color. At minimum brightness, the color would be very dark.

## Contrast
When picking foreground and background colors, it is important to ensure that there is enough contrast for the text to be legible.

Low Contrast
Text is harder to read when there is low contrast between background and foreground colors. 
A lack of contrast is particularly a problem for those with
visual impairments and color blindness. 
It also affects those with poor monitors and sunlight on their screens (which is increasingly common as people use handheld
devices outdoors).

High Contrast
Text is easier to read when there is higher contrast between background and foreground colors.
If you want people to read a lot of text on your page, however, then too much contrast can make it harder to read, too.

Medium Contrast
For long spans of text, reducing the contrast a little bit improves
readability.
You can reduce contrast by using dark gray text on a white background or an off-white text on a dark background.


## CSS3: Opacity
opacity, rgba
CSS3 introduces the opacity property which allows you to specify the opacity of an element and any of its child elements.
The value is a number between 0.0 and 1.0 (so a value of 0.5 is 50% opacity and 0.15 is 15% opacity).
The CSS3 rgba property allows you to specify a color, just like you would with an RGB value, but adds a fourth value to indicate opacity. This value is known as an alpha value and is a number between 0.0 and 1.0 (so a value of 0.5 is 50% opacity
and 0.15 is 15% opacity). The rgba value will only affect the element on which it is applied (not child elements).
Because some browsers will not recognize RGBA colors, you can offer a fallback so that they display a solid color. If there are two rules that apply to the same
element, the latter of the two will take priority. To create the
allback, you can specify a color as a hex code, color name or RGB value, followed by the rule that specifies an RGBA value. If the browser understands RGBA colors it will use that rule. If it doesn't, it will use the RGB value.


## CSS3: HSL Colors
CSS3 introduces an entirely new and intuitive way to specify colors using hue, saturation, and lightness values.

hue
Hue is the colloquial idea of color. In HSL colors, hue is often represented as a color circle where the angle represents the color, although it may also be shown as a slider with values from 0 to 360.

saturation
Saturation is the amount of gray in a color. Saturation is represented as a percentage. 100% is full saturation and 0% is a shade of gray.

ligh tness
Lightness is the amount of white (lightness) or black (darkness) in a color. Lightness is represented as a percentage. 0% lightness is black, 100% lightness is white, and 50% lightness is normal. Lightness is sometimes referred to as luminosity.

## CSS 3: HSL & HSLA
The hsl color property has been introduced in CSS3 as an alternative way to specify colors. The value of the property starts with the letters hsl, followed
by individual values inside parentheses for:

hue
This is expressed as an angle (between 0 and 360 degrees).

saturation
This is expressed as a percentage.

lightness
This is expressed as a percentage with 0% being white, 50% being normal, and 100%
being black. The hsla color property allows you to specify color properties using hue, saturation, and lightness as above, and adds a fourth value which represents
transparency (just like the rgba property). The a stands for:

alpha
This is expressed as a number between 0 and 1.0. For example, 0.5 represents
50% transparency, and 0.75 represents 75% transparency


