
# HTML 
## html image 

#### Earlier, the webpages used to comprise of only texts, which made them appear quite boring and uninteresting. Fortunately, it wasn’t long enough that the ability to embed images on web pages was added for users. Let’s see how to add images on a webpage.

##### Adding images on a webpage :
##### The “img” tag is used to add images on a webpage. The “img” tag is an empty tag, which means it can contain only a list of attributes and it has no closing tag.

##### <img src="url" alt="some_text">

#### src:

##### src stands for source. Every image has a src attribute which tells the browser where to find the image you want to display. The URL of the image provided points to the location where the image is stored.
##### alt:If the image cannot be displayed then the alt attribute acts as an alternative description for the image. The value of the alt attribute is an user-defined text.

##### Setting width and height of Image :The width and height attributes are used to specify the height and width of an image. The attribute values are specified in pixels by default.

## html color
![color](https://nestify.io/blog/wp-content/uploads/2019/10/What-is-the-psychology-of-colors-Html-Codes-Colors-Rgb.jpg)
##### So you are wondering "Does this weird combination of letters and numbers have any meaning?" Well the answer is "Yes" and this is how it goes:)

##### HTML Codes format:
##### Each HTML code contains symbol "#" and 6 letters or numbers. These numbers are in hexadecimal numeral system. For example "FF" in hexadecimal represents number 255 in Decimal.

##### Meaning of symbols:
##### The first two symbols in HTML color code represents the intensity of red color. 00 is the least and FF is the most intense. The third and fourth represents intensity of green and fifth and sixth represents the intensity of blue. So with combining the intensity of red, green and blue we can mix almost any color that our heart desire;)

##### Examples:
##### #FF0000 - With this HTML code we tell browser to show maximum of red and no green and no blue. The result is of course pure red color:     

##### #00FF00 - This HTML code shows just green and no red and blue. The result is:     

##### #0000FF - This HTML code shows just blue and no red and green. The result is:     

##### #FFFF00 - Combination of red and green color gives us yellow:     

##### #CCEEFF - Take some red a bit more of green and maximum of blue to get color of sky.
## html text
##### HTML provides us with the ability to format text just like we do in MS Word or any text editing program. In this article, we'll look at some of these options.
 

##### Make text bold or strong: We can make text bold using the <b> tag. The tag uses both the open and close tag. The text which should be bold must be inside the <b> and </b> tag.
##### We can also use the <strong> tag to make the text strong, while adding semantic significance. It also opens with a <strong> tag and ends with </strong>.
##### An example of several instances of text:

 ##### <! DOCTYPE html>
##### <html>

##### <head>
#####  <title> Bold </title>
##### </head>
##### <Body>
#####     <! - Plain Text ->
     
##### <p> Hey GeeksforGeeks </p>
 
#####     <! - Bold text ->
     
##### <p> <b> Hey GeeksforGeeks </b> </p>
 
#####     <! - Text in Strong ->
     
##### <p> <strong> Hey GeeksforGeeks </strong> </p>
 
#####     <! - Text in italics ->
     
##### <p> Hey GeeksforGeeks </i> </p>
 
#####     <! - Text in confirmation ->

##### <p> <em> Hey GeeksforGeeks </em> </p>

#####   <! - Featured Text ->
     
##### <p> <mark> Hey GeeksforGeeks </mark> </p>

#####  <! Superscript ->
     
##### <p> Hello <sup> GeeksforGeeks </sup> </p>
 
#####     <! - Subscript Text ->
     
##### <p> Hey <sub> GeeksforGeeks </sub> </p>


#####     <! - Small text ->
     
##### <p> <small> Hey GeeksforGeeks </small> </p>

#####    <! - Text in delete ->
     
##### <p> <del> Hey GeeksforGeeks </del> </p>

##### </body>