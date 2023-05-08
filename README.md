Download Link: https://assignmentchef.com/product/solved-soen287-assignment-3
<br>
<strong>purpose: </strong>The purpose of this assignment is to help you learn the JavaScript and HTML documents, and dynamic documents with JavaScript.

<strong>CEAB/CIPS Attributes: </strong>This assignment is primarily evaluating your use of JavaScript and HTML, and dynamic documents with JavaScript. (Use of engineering tools).







<strong><u>General Guidelines When Writing Programs</u>: </strong>

–    Refer to handout for Assignment 1 &amp; 2




<h1>Question #1</h1>

Write a JavaScript script called “<em><u>CharacterOccurences.JS</u></em>” that inputs several lines of text and a search character and uses String method <strong>indexOf()</strong> to determine the number of occurrences of the character in text.

<ol>

 <li>You have to use the external CSS file called “<em><u>CSS</u></em>” to set the margin of the paragraph to the value 0 (zero).</li>

 <li>You have to declare in your HTML form four (04) ids :

  <ol>

   <li>“searchString” as textarea id in paragraph with 4 rows and 55 columns</li>

   <li>“characters” as input id in paragraph with text type and size equal 5</li>

   <li>“searchButton” as input id in paragraph with button type and its value equal</li>

  </ol></li>

</ol>

“Search”

<ol>

 <li>“output” as id in paragraph is for the final result.</li>

</ol>

<ol>

 <li>The JavaScript file (<em><u>CharacterOccurences</u></em>.js) contains three (03) global variables and two (02) functions:</li>

 <li>Global variables :

  <ol>

   <li>searchStr to get the id of “searchString”</li>

   <li>ch to get the id of “characters”</li>

  </ol></li>

</ol>

<ul>

 <li>outResult to get the id of “output”</li>

</ul>

<ol>

 <li>The function <strong>getAllDomElement()</strong> that

  <ol>

   <li>Accesses the “searchButton” element and adds the search button using its id by using the existing the function <u>addEventListener</u>(), which takes three (03) arguments: (a) the name of event as a string literal (here is “click”), (b) the function searchOccurrences, and (c) the Boolean value false.</li>

   <li>Gets all id elements of “searchString”, “characters”, “output” using the existing function <em><u>getElementById()</u></em></li>

  </ol></li>

 <li>The function searchOccurrences() to search the character we look for and count the number of occurrences of that character.

  <ol>

   <li>4 local variables: count, chValue, searchStr, result.</li>

   <li>Use the functions: charAt( 0 ), toLowerCase() and indexOf().</li>

  </ol></li>

</ol>

<ul>

 <li>If the variable <strong>count</strong> equal 0 (zero) display the message: the character <strong>ch</strong> not found. Otherwise display the result.</li>

</ul>

<ol>

 <li>At the end of the JavaScript file, finish with this line to fire the load event when a resource and its dependent resources have finished loading:</li>

</ol>

window.addEventListener( “load”, getAllDomElement, false );

<u>Here is a sample output to illustrate the expected behavior of your program</u>:










<h1>Question #</h1>

Write a script that contains a button (in the external file called “<em><u>Counter.js</u></em>”) and a counter in a &lt;div&gt; (in the html document called “<em><u>Counter.html</u></em>“). The button’s event handler should increment the counter each time it’s clicked.

<ol>

 <li>You have to use the external CSS file called “<em><u>CSS</u></em>” to set the margin of the paragraph to the desired value, for example 4 or 5, etc.</li>

 <li>The JavaScript file (<em>Counter</em>.js) contains two (02) variables and two (02) functions:

  <ol>

   <li>Global variables: counter = 0 and dom.</li>

   <li>The function <strong>getElementBtnIncrement()</strong> that reads the counter element using the existing function <em><u>getElementById()</u></em> to access to the element and adds the increment button using its id by using the function <u>addEventListener</u>() to register the event handler, which takes three (03) arguments : a) the name of event as a string literal (here is “click”), (b) the handler function increment, and (c) the Boolean value false.</li>

   <li>The function <strong>increment()</strong> that increments the counter by 1 before and assign this new counter value to the <em><u>dom</u></em> variable which references the innerHtml.</li>

  </ol></li>

 <li>At the end of the JavaScript file, finish with this line to fire the load event when a resource and its dependent resources have finished loading:</li>

</ol>

window.addEventListener( “load”, getElementBtnIncrement, false ); <u>Here is a sample output to illustrate the expected behavior of your program</u>:




<h1>Question #</h1>

You have a server-side script called “Ampersands.js” that cannot handle any ampersands

(&amp;) in the form data. Write a script to convert all ampersands to ″ and ″ in the form field when the field loses <strong>focus</strong> element (<strong>blu</strong>r).

<ol>

 <li>Your script contains one (01) variable and two (02) functions:

  <ol>

   <li>Global variable: dom.</li>

   <li>The function <strong>getElementAmpersand()</strong> that reads the field element by using the existing function <em><u>getElementById()</u></em> to access to the element using its id (″field″) specified in your HTML file by using the function <u>addEventListener</u>() to register the event handler, which takes three (03) arguments : (a) the name of event as a string literal (here use “<strong>blur</strong>“), (b) the handler function convertAmpersands, and (c) the Boolean value false.</li>

   <li>The function “<strong>convertAmpersands()</strong>” that converts all ampersands in the form field to ” and ” when the field loses focus (“<strong>blur</strong>“).</li>

   <li>The html document called “Ampersand<em>.html</em>“, which invokes the “Ampersand.js” in the head section.</li>

  </ol></li>

 <li>At the end of the JavaScript file, finish with this line to fire the load event when a resource and its dependent resources have finished loading:</li>

</ol>

window.addEventListener( “load”, getElementAmpersand, false ); <u>Here is a sample output to illustrate the expected behavior of your program</u>:




<h1>Question #</h1>

Copy and paste the following HTML code into a new document:




&lt;!DOCTYPE html PUBLIC “-//W3C//DTD XHTML 1.0 Strict//EN”

“http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd”&gt;

&lt;html xmlns=”http://www.w3.org/1999/xhtml”&gt;

&lt;head&gt;&lt;title&gt;Exercise 4&lt;/title&gt;

&lt;/head&gt;

&lt;body&gt;

&lt;div id=”container”&gt;

&lt;h2&gt;Order Books Online&lt;/h2&gt;

&lt;form action=”” method=”post” id=”frm”&gt;

&lt;fieldset&gt;

&lt;table border=”0″&gt;

&lt;tr&gt;

&lt;th&gt;Book&lt;/th&gt;

&lt;th&gt;Quantity&lt;/th&gt;

&lt;th&gt;Price&lt;/th&gt;

&lt;/tr&gt;

&lt;tr&gt;

&lt;td&gt;Basic XHTML&lt;/td&gt;

&lt;td&gt;&lt;input type=”text” size=”3″ id=”book_1″ /&gt;&lt;/td&gt;

&lt;td&gt;$19.99&lt;/td&gt;

&lt;/tr&gt;

&lt;tr&gt;

&lt;td&gt;Intro to PHP&lt;/td&gt;

&lt;td&gt;&lt;input type=”text” size=”3″ id=”book_2″ /&gt;&lt;/td&gt;

&lt;td&gt;$86.00&lt;/td&gt;

&lt;/tr&gt;

&lt;tr&gt;

&lt;td&gt;Advanced JQuery&lt;/td&gt;

&lt;td&gt;&lt;input type=”text” size=”3″ id=”book_3″ /&gt;&lt;/td&gt;

&lt;td&gt;$55.00&lt;/td&gt;

&lt;/tr&gt;

&lt;/table&gt;

&lt;br /&gt;&lt;br /&gt;

&lt;input type=”submit” value=”Place Order” id=”sub” /&gt;

&lt;/fieldset&gt;

&lt;/form&gt;

&lt;/div&gt;

&lt;/body&gt;

&lt;/html&gt;

Write JavaScript code that is executed during form submission to calculate the cost of each book (based on quantity specified) and the overall total cost. The results should be displayed on the same page beneath the form submission button. Use any CSS at your discretion if desired.

All JavaScript code must be external. If any fields are left blank or do not contain a number, an alert box should display an appropriate error message upon form submission.







The resulted page looks like the following.










<h1>Question #5</h1>

The running problem to build a website of apartment search (To be continued in Assignment 4). We resume the Nancy’s Apartment Search Web site in Assignment 1. Please create another section called “Expert suggestions” after the section of “What you are looking for”. Style it properly and make it invisible at first. Once the user’s selections meet the following criteria, use JavaScript to insert the suggested text into this section and make it visible.

<ul>

 <li>If the size is “More than 51/2” and the location is “Downtown”, show the expert suggestion after “Downtown” is selected: “It is very difficult to find an apartment larger than 51/2 in downtown”.</li>

 <li>If the size is “4 ½” and above, the location is “Downtown”, and the price range is less than 1000$, show the expert suggestion after 1000$ or less options are selected: “Normally an apartment of 4 ½ and above costs more than 1000$ in downtown area”.</li>

</ul>

<strong> </strong>


