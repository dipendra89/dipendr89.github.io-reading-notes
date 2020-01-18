<b>Chapter 3 (HTML Book): Lists</b>

This chapter talks about the Lists and its various types. HTML mainly has 3 types of Lists. 

a.	<em>Ordered lists:</em> Lists where each item in the list is numbered. In real life, there are several examples where you have to follow certain steps while completing tasks. 
We use ol element for ordered lists. 

b.	<em>Unordered lists:</em> Lists those begin with bullet point instead of characters which indicate order. We use ul element for unordered lists. 

c.	<em>Definition Lists:</em> The book says that definition lists are made up of set of terms along with the definitions for each of those terms. 
These are used to define terminologies. dl element is used in these lists and inside the dl element, we use dt and dd elements. 

Nested Lists: when you create a second list (sub list) inside a list, it is called nested list. 

<b>Chapter 13 (HTML Book): Boxes</b>

Chapter 13 talks about the <em>boxes</em> and how we can control, modify and use boxes depending upon our needs. 
Obviously, it is not talking about the boxes you can buy in U-Haul stores. 
CSS can be used to control the dimensions, borders, margins and padding for boxes. 
Not only that, CSS let you create image borders and rounded borders. So, we will be getting more detail on border, 
margin and padding making us able to use color, image etcetera for our pages. 


<b>Chapter 4 (JS Book): Decisions and Loops</b>

I was told that ‘conditional statements’ are widely used in software development world. These allow the program to make decisions on what to do next. We use various comparison operators on loops like ===, !==, !=, <, >, <=, >= etc. We also have logical operators like AND, OR, NOT. 
If …else statements which we call conditional statements let us to run a set of code to see if it is true or false. 
For example:      if (score <=90) {
                                  pass();
                              }
                               else {
                                   fail();
                               }
There is also ‘Switch Statements’. You will see different ‘cases’ on switch statements. 
It will look like this:

                 switch(something) {
                 case ‘One’:
                 color = ‘Black’;
                 break;

                 case ‘Two’:
                 color = ‘White’;
                 break;

                 case ‘Three’:
                 color = ‘Red’;
                 break;
             }

Loops: We have three types of loops: <em>for loops, while loops</em> and <em>do…while loops</em>. 
‘For Loops’ are normally used to loop through the items in an array. On the case of ‘While Loop’, loop will continue to run for as long as the condition you have in the parentheses is true.  On the other hand, we have ‘do…while’ loops. Main difference between while loop and a do while is that statement in the code block comes before the condition in do while loop. 

Example:     

               var text = ""
               var i = 0;
               do {
               text += "<br>The number is " + i;
               i++;
               }
               while (i < 5);


                               

