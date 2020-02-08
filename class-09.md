HTML Book Ch 7: FORMS

The term ‘form’ has referred to a printed document which contains spaces to fill in information, traditionally. HTML uses the concept of a form to refer to different elements which allow us to collect information from visitors to our site. We use forms in various ways in our daily lives whether it is a searching for something filling out some online applications. HTML forms provide us a set of elements to collect data from our users. In this chapter, we will learn how to create a form for the site, different tools collecting data, different forms control etcetera. Example:
<form action="/action_page.php">
  First name:<br>
  <input type="text" name="firstname" value="John"><br>
  Last name:<br>
  <input type="text" name="lastname" value="Smith"><br><br>
  <input type="submit" value="Submit">
</form>
On this chapter, we will learn form-structure, text input, password input, text area, radio button, checkbox, drop down list box, multiple select box, file input box, submit button, image button, button & hidden controls, labeling form controls, grouping form elements, form validation, date input, search input etc. 


HTML Book Ch 14: LISTS, TABLES, and FORMS

The chapter 14 talks lists, tables and forms which explain things like specifying bullet points styles, adding borders and backgrounds to tables, changing the appearance of form elements. Talking about bullet point styles, there are multiple ways to use bullet points as we have seen: we have unordered lists which will have bullet points or disc, circle, square or none, we have ordered lists which will have decimal (1 2 3), decimal leading zero, lower alpha, upper alpha, lower-roman, upper-roman (I II III).We can also use images for bullets.
If we need to make more readable table using different CSS properties, we can also do that like background color on table, border on empty cells, gap between cells. 
Another important thing is styling forms. Like I mentioned above, when we use forms a lot on our daily basis for various purposes, we want to make them more readable, user friendly and responsive. So, we need some sort of styling on forms. It might be styling on text inputs, submit buttons, aligning form controls, cursor styles etcetera. 

JS Book Ch 6: EVENTS

Our browsers register different types of events when we browse the web. Generally, scripts respond to events by updating the content of the web page via Document Object Model (DOM) which makes the page mor interactive. On this chapter, we will learn about interactions creating events, events triggering code, code responding to users and other materials. 
We use various events without even realizing them. For example, various mouse events: click, dbclick, mousedown, mouseup, mouseout etc.  Example:
<p onmousedown="myFunction()">Click the text!</p>
OR
<button onclick="this.innerHTML=Date()">The time is?</button>
