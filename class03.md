# HTML
## HTML Lists
#### are used to specify lists of information. All lists may contain one or more list elements. There are three different types of HTML lists:

* Ordered List or Numbered List (ol)
###### <ol>  
###### <li>ALI</li>
###### </ol> 
* Unordered List or Bulleted List (ul)
###### <ul>
###### <li>ALI</li>  
###### </ul>  
* Description List or Definition List (dl)
###### <dl>  
  ###### <dt>example</dt>  
  ###### <dd>ali examples</dd> 
###### </dl>
## HTML Boxes
* The content —
The content can be a text or it can be a another box, as I mentioned above hierarchy of boxes.
* The padding —
The Padding is a space between the content and the border.
* The border —
The border separates the padding and the maring of the box.
* The margin —
The margin is space between the surrounding boxes.

# JAVA SCRIPT
## Basic JavaScript Instructions
* JavaScript is case-sensitive.
* Statements should end in a semicolon (;).
* Variables:

* Must be defined before being used. The variable name can contain A – Z, a – z, underscore or digits and must start with a letter or an underscore (“_”).
* Assume the type of the data that is put into the variable. The data type does not have to be explicitly defined
* Are global variables when defined outside of a function, and are available anywhere in the current script context. Variables created within a function are local variables, and can be used only within that function.
* Strings have to be enclosed in quotation marks, either a single or double. For example: print(”Hello ” + ‘world ‘+ Country.name) produces the following: Hello world US.
* Special characters that are displayed literally must be preceded by a backslash character (\). Quotes within a string can be entered preceded by a backslash as well.
* To increment a variable, such as a = a + 1, you can use a++. You can decrement a variable in the same way, as in a--.
* To enter comments in the script, use "//" to start a single line comment or the combination of "/*" and "*/" to enclose a multi-line comment.
* Values that are not defined as a data type (string, number, Boolean) may be defined as an object, such as Date, Array, Boolean, String, and Number. As an example you could define: var ArrayList=new Array(”test”, ” this”, ” list”);.
* Dots in Service Manager field names must be replaced by an underscore (_) in JavaScript. For example contact.name becomes contact_name.
* Service Manager field names that are reserved words in JavaScript have to be preceded by an underscore, such as “_class” for the “class” field.
## Decisions and Loops "switch statements"
#### A switch statement can replace multiple if checks.

#### It gives a more descriptive way to compare a value with multiple variants.

###### switch(x) {
  ###### case 'value1':  // if (x === 'value1')
   ######  ...
    ###### [break]

  ###### case 'value2':  // if (x === 'value2')
    ###### ...
    ###### [break]

  ###### default:
    ###### ...
    ###### [break]
###### }
* The value of x is checked for a strict equality to the value from the first case (that is, value1) then to the second (value2) and so on.
* If the equality is found, switch starts to execute the code starting from the corresponding case, until the nearest break (or until the end of switch).
* If no case is matched then the default code is executed (if it exists).
