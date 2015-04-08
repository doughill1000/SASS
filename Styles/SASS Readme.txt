SASS requires Web Workbench Extension

---Mixins---
-Require @include to use 

---Variables---
-Require $[name]
-Mathematics can be used

/*EXAMPLE*/
height: (400px / 2); //Use parenthesis with division

---Inheritance---
Uses @extend in the child class

---Nesting---
-Should be 3 to four levels
-Allows you to structure css like html

/*EXAMPLE*/
article{
   width:10px;
   p{
      font-size:10px;
   }
}

---Files---
@import '[location]' used to import files
uses an underscore before sass file prevents css generation

---Debugging---
@debug '[message]' shows in Web Workbench debug console
@warn shows as warning in Web Workbench debug console

---List Functions---
length //Number of items
nth //Gives the index

join([list1],[list2]);

append([list],[value]);

index([list],[value])

