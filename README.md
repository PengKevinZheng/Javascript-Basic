# Javascript-Basic

Why do we need to learn Javascript?
JavaScript is one of the 3 languages all web developers must learn:

   1. HTML to define the content of web pages

   2. CSS to specify the layout of web pages

   3. JavaScript to program the behavior of web pages

Javascript is in <script></script> block.
get Javasctipt file form other place: <script src="script.js"></script>
Javascript code can be put in <head></head> and <body></body> block but can also be put anywhere.

Interaction with user:

1.document.write(str); str will be shown in the window.

2.alert(str);str will be shown in the subwindow;

3.confirm(str);return type is boolean. the str represents for a question. If user click OK, it returns true; If user click cancel, it returns flase;

4.prompt(str1, str2); str1 is shown in the subwinsow which cannot be changed. str2 will be shown in the input of subwindow which can be changed. If user click OK, it returns the input(str2), if user click cancel,it returns null.

5.window.open(URL, window's name, parameter list); a new window will come out. the parameter includes followwing: top. left, width,height, menubar,toolbar,scrollbar,status.

About DOM:

With the HTML DOM, JavaScript can access and change all the elements of an HTML document.

 1.document.getElementById(“id”); get the element with it's ID;
 
 2.Object.innerHTML;Object is obtained by document.getElementById("ID"). It can be used to change the content of the Object.
 
 3.Object.style.property=new style; It can be used to change the style of certain Object. ex: mychar.style.color="red";
   mychar.style.fontSize="20";
   mychar.style.backgroundColor ="blue";
   
 4.Object.style.display ="none"; It can be used to hide the element;
 
   Object.style.display = "block"; It can be used to show the elemtn;
   
 5.object.className = classname;
 
 Array:
 
 If you want to add new element to the array a,just use a[new index]=element;
 
 Function:
 
 Define a new function
 
 function  name( )
{
     //implement the function
}

Clikc a button and excute a function: <input type="button"  value="click me" onclick="function()">  


Event:

HTML events are "things" that happen to HTML elements.


When JavaScript is used in HTML pages, JavaScript can "react" on these events.

An HTML event can be something the browser does, or something a user does.

Here are some examples of HTML events:

An HTML web page has finished loading
An HTML input field was changed
An HTML button was clicked
Often, when events happen, you may want to do something.

JavaScript lets you execute code when events are detected.

HTML allows event handler attributes, with JavaScript code, to be added to HTML elements.
 
 


 



