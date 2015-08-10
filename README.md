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

We have those usual events: 

鼠标单击事件( onclick ）

鼠标经过事件（onmouseover）

鼠标移开事件（onmouseout）

光标聚焦事件（onfocus）

失焦事件（onblur）

内容选中事件（onselect）

文本框内容改变事件（onchange）

加载事件（onload）

卸载事件（onunload）

Window Object:

The window object represents an open window in a browser.

There are lots of properties and methods in Window Object. I will list some of them:

1.setInterval(code,time); code can be a function. time is in Millisecond.

2.clearInterval()；it is used to cancel the time,ex: var hehe = setInterval("clock()",1000); clearInterval(myVar);

history Object:

history: The history object contains the URLs visited by the user. var HL =  window.history;  property: length;
Method:

back():	Loads the previous URL in the history list

forward():	Loads the next URL in the history list

go():	Loads a specific URL from the history list

location Object:
The location object contains information about the current URL.

DOM Object: 

getElementById: to get a HTML element by ID.

getElementsByName: retrun an array of elements by their names, because names can be duplicates.

getElementsByTagName: return collection of HTMLelements by tags. 

getAttribute: element.getAttribute(attributeName); element can be returned by document.getElementById(id);

setAttribute: element.setAttribute(name,value); set an element's attribut.





 
 


 



