<strong>JS Book Ch 10: ERROR HANDLING AND DEBUGGING</strong>

It will not be practical to think that a good programmer doesn’t have a bug or an error on his/her code. Everyone makes mistakes when writing codes. In this chapter we will learn about debugging and error handling on JavaScript. 

We will learn about the ‘Console and Dev Tools’, ‘Common Problem’, ways to ‘Handle Error’ etcetera. To find the source of error, it is important to know the order of execution of the code. We might think that the order should be as simple as ordered lists where everything is on order, that might not be the case on coding. 

The concept of Stack on JavaScript is that the JavaScript interpreter processes one line of code at a time. When a statement needs data from different function, it stacks the new function on top of the current task. Once the new task has been performed, the interpreter can go back to the task in hand. 
When a JavaScript statement generates an error, it throws an exception then the interpreter stops and looks for exception-handling code. Also, it is important to know the debugging workflow. Eliminating potential causes of an error is a way to go on debugging. Here are few steps to find where the problems are:

	Looking at the error (it will tell us a lot of things)

	Checking how far the script is running

	Using break points where things went wrong

This chapter also talks about how the browser dev tools and JavaScript console works. Also, typing in the console in various browsers is a good way to work on debugging. Not only that, the chapter also has information on how to handle error using try, catch, finally statements. 
