# JAVA SCRIPT

## Object Literals
##### In plain English, an object literal is a comma-separated list of name-value pairs inside of curly braces,Those values can be properties and function
##### There are three ways of creating an object in javascript:
##### Using Object literals
##### Using new keyword.
##### By defining object constructor and then create an object constructor type.

##### JavaScript Object Literals Simplified
##### Instantiating Objects
##### You are likely familiar with instantiating strings and arrays in javascript:

##### var myString = new String();
##### var myArray = new Array();
##### Array and String are both objects, extended from the Object object. String and Array are objects inheriting all the properties of the Object object, and adding new properties and methods that are specific to the Array and String objects respectively. In these cases, the new keyword creates a new instance of the String and Array objects respectively.

##### There are several ways to declare an object in Javascript, including:

##### var myObject = new Object();

##### var myObject = {};
##### JavaScript Dot Notation
##### If you are on this site, you have likely used javascript dot notation for properties and methods of objects. The following hopefully looks familiar to you:

##### var myFirstLink = document.getElementById('myDiv').getElementsByTagName('a')[0]; 
##### //returns the first link in the parent element with ID of "myDiv"

##### myFirstLink.className = "myClass" 
##### // or, not as good, but still valid, myFirstLink.style.color = "#ff0000"
##### and if you have used any javascript libraries, or have coded more advanced javascript, you have likely used javascript dot notation in creating new methods, such as

##### myObject.somemethod = function(){
#####    // code here
##### }
##### Declaring methods and properties with Dot notation
##### Using dot notation your code may look something like this:

##### var myObject = new Object();
#####	myObject.myProperty = value;
##### 	myObject.yourProperty = value;
##### 	myObject.myMethod = function(){
##### 	  //code here
##### 	}
##### 	myObject.yourMethod = function(){
##### 	  //more code
##### }
##### Note: remember that undefined properties of objects return undefined. Unlike undeclared variables, they do “exist”, so they don’t throw an error. If we us the examples above, (myString.typoed_property == undefined) returns true.

##### Declaring methods and properties using Object Literal syntax
##### ou could declare the properties and methods listed above using cleaner Object Literal syntax:

##### var myObject ={
##### 	myProperty : value,
##### 	yourProperty : value,
##### 	myMethod : function(){
##### 	  //code here
##### 	},
##### 	yourMethod : function(){
##### 	  //more code
##### 	}
##### }
##### A few things to note:

##### The Object literal notation is basically an array of key:value pairs, with a colon separating the keys and values, and a comma after every key:value pair, except for the last, just like a regular array. Values created with anonymous functions are methods of your object. Simple values are properties.
##### if you are mixing code sources, using libraries or sharing code, you want to use static methods and properties rather than public methods and properties, to safeguard against overwriting functions or variables / methods or properties declared outside your current javascript file.
##### Unlike public functions, which can appear anywhere in your code, including after lines using your function, methods declared using object literal notation do not exist until execution of that section of the script.
##### This method instantiates a new object, so don’t try to create a instance using the new keyword

## THE DOM
##### Every web page resides inside a browser window which can be considered as an object.

##### A Document object represents the HTML document that is displayed in that window. The Document object has various properties that refer to other objects which allow access to and modification of document content.

##### The way a document content is accessed and modified is called the Document Object Model, or DOM. The Objects are organized in a hierarchy. This hierarchical structure applies to the organization of objects in a Web document.

##### Window object − Top of the hierarchy. It is the outmost element of the object hierarchy.

##### Document object − Each HTML document that gets loaded into a window becomes a document object. The document contains the contents of the page.

##### Form object − Everything enclosed in the <form>...</form> tags sets the form object.

##### Form control elements − The form object contains all the elements defined for that object such as text fields, buttons, radio buttons, and checkboxes.


##### There are several DOMs in existence. The following sections explain each of these DOMs in detail and describe how you can use them to access and modify document content.

##### The Legacy DOM − This is the model which was introduced in early versions of JavaScript language. It is well supported by all browsers, but allows access only to certain key portions of documents, such as forms, form elements, and images.

##### The W3C DOM − This document object model allows access and modification of all document content and is standardized by the World Wide Web Consortium (W3C). This model is supported by almost all the modern browsers.

##### The IE4 DOM − This document object model was introduced in Version 4 of Microsoft's Internet Explorer browser. IE 5 and later versions include support for most basic W3C DOM features.