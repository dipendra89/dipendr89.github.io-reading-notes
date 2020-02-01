<strong>HTML Book Chapter 6: Tables</strong>

In this chapter, we will learn about how to create tables, what information best fit in them, and the way to represent various data in tables. Whether you are watching your grades on table or you are looking at your flight schedule on the airport, you will see use of tables in many places in various ways. 

Fundamental of Tables:
The < table > element is used to create table. Then, we will go from there to see what we need to put as contents. You use < tr > and < /tr > as opening of row and closing of row respectively. Inside these tags, you put < td > element to put data. Also, <th > element is used just like < td > element but only difference is that < th > element is used to indicate the heading for either a column or a row. 
  Example: 
  
< table >

   < tr >
   
      < td >Sam< /td >
      
      < td >Joe< /td >
      
      < td >Mary< /td >
      
   < /tr>
   
< /table >

We can make cells of a table span more than a row or a column with the use of rowspan and colspan attributes. We can also split the table into a < thead >, < tbody >, and < tfoot > for long tables.


<strong>JS Book Chapter 3: Functions, Methods and Objects</strong>

We studied a little bit about objects, methods and functions in previous class. To recap, object is a set of variables and functions, function is a set of statements put together to perform a specific task and a method is same as a function except methods are created inside (and are part of) an object. We will also learn about keyword and constructor in this chapter.
Example:

var car = new object(); 
where new is keyword and object() is a constructor.
We will also learn about the keyword called ‘this’.
Example:

function Car(name, make, model) {

   this.name = name;
   
   this.make = make;
   
   this.model = model;
   
   this.checkAvailability = function() {
   
      return this.make – this.model;
      
   };
   
}

On this chapter, we will also study about storing data and talk more about arrays including arrays of objects & objects in arrays. Also, we will not miss built-in objects like String, Number, Math, and Date.

