Things to Cover
---------------

1. How to take Input in JS and Display Output in Javascript

2. How to declare Varibale in JS

3. How to Learn Javascript

4. Difference between var ,let ,const

5. Simple Example : 

   - Simple Intrest Calculator Desing

   - Student Result sheet Generator 

1. How to take Input in JS and Display Output in Javascript

   A. Desing HTML Input tag and get value using JS DOM property

   B. Prompt Dialouge Box


Problem : Find Sum of two number

sum.html
--------
<html>
   <head>
      
   </head>
   <body>
       <table>
          <tr>
             <td>Enter Num 1 :</td>
             <td>
               <input type="number" id="txtNum1" />
             </td>
          </tr>
          <tr>
             <td>Enter Num 2 :</td>
             <td>
               <input type="number" id="txtNum2" />
             </td>
          </tr>
          <tr>
             <td colspan="2">
                 <button>Find Sum</button>
             </td>
          </tr>
       </table>
       <script>
        </script>
   </body>
</html>



# 17-01-2024 (WED) :

 - Dialouge Boxes

   -> alert
   -> Confirm
   -> Prompt

 - document.write
 
 - Variable in JS

 - Datatypes

 - Operators

      ==    ===

 - Literals

 - Control Statements

   a. Conditional Control Statement
      ternary operator
      if statement
      if else statement
      nested if statement
      else if ladder

      switch statement
     
   b. Loop Control Statement
   - for loop
   - while loop
   - do while loop

   c. Jumping Statement
      
      break
      continue

- function in JS

- Array in JS

- String Handling Function in JS
- Date Handling Function in JS
- Array Handling Function in JS
- Number handling Function in JS
- Mathematic Functions in JS

- Object Cration in JS

- JSON

- DOM (Document Object Model)
- BOM (Browser Object Model)

ES6 Features
-------------

- Arrow Function
- Clousers
- Hoisting
- Destructring
- Default Parameter
- ?? Null Colescing Operator
- Rest Parameter
- this keyword

-----------------

# 1.  Dialouge Boxes

   -> alert

      syntax :

         alert("Welcome to JS");

         - It don't have any Return type
         - It only used to display message

      Example:

         alert("");

         var x =5;

         alert(x);
         alert("");
         var y =5;
         alert(y);
         alert("y");
         alert(5*3);
         alert("y="+y);

   -> Confirm

        Syntax :

           confirm("Messegae")

         - It will return true or false
         - If you click on ok then it will return true
         - If you click on cancel then it will return false

         Example:
           
             var res =confirm("Do You want to delete ?");

             alert(res);

   -> Prompt

            - It is used to accept input from the user

            - 
                var name = prompt('Enter Your Name');
                alert("You have entered "+name);

            - If you click on OK button then it will return you input value

            - If you click on Cancel then it will return you null

            - Value accepted from prompt is string type

            -

            WAP to accept P,t,r from prompt box then calculate SimpleInterest

             si = p * t * r /100


  ## 2.  
         document.write()          
         document.writeln()

         document

         JS is an ObjectBased Scripting Language.
         i.e in JS There are many predefined Objects.

         Object consists of Properties and Methods

         NOTE:
         Never Use this function in real project
         It is only used for testing purpose

## 3. Variables in JS :

      - Variables are the valid tokens in JS ,which are used to reserve
        the memory for storing data.

      - Variables are the container which contains value.

      - The value present inside the variabel can be vary with the flow 
        of program execution.

      -NOTE:
       -> JS is loosely types language.
          var x ;
          x = 50;
          console.log(typeof x); //number
          x = "Alok";
          console.log(typeof x); // string
       -> JAVA is strongly Typed
          int x ;
          x=5; //ok
          x="ddf";//Wrong

      - In JS the type of variable will be decided during run time based
        on the value assigned to it.


      - How to create Variable in JS
    
        - There are 3 Keywords we may use to create JS variables

        - var , let ,const keyword
        - var is Global Scope
        - let is Block Scope
        - Const is used to create constant,it is also block scoped

        - Syntax :(Rule of Progeamming language is called Syntax)
           
           <var or let> <variable_name> [= value];

           <> -> ANY
           [] -> Optional

        - Example :
      
          var empSalary = 50000; //Variable Initialization with Declaration
         
          var empName ; //Declaration

          empName = "Rakesh"; //Initialization
          
        - NOTE:
           JS Variable name follows CamelCase naming Convention.


        - Rule Of Giving Name to the Variable:
          -----------------------------------

          Rule for Identifiers :
          ---------------------

          Identifiers are the user defined names used in the program
          to identify programming elements such as variable,function,
          array etc.

          a. The Name can be in SmallCase or in uppercase or in mixed case.

             var empsalary;
             var EMPSALARY;
             var EmpSalary;

          b. The variable name can contains digit ,but it should not be the
             first character.

             var 1empSalary ;//invalid

             var emp1Salary ;//valid

         c. No other symbols except _ (under Score ) and $ is allowed in the name

            var emp_salary = 5000;

            var emp-salary = 5000;

         d. No Keywords can be used as name.

            var if ;//invalid

         e. No blank space is allowed in the name

            var emp Salary ; //invalid

       - Example to Illustrate the difference between let,var and const

          var x = 5;
          let y = 3;
          const z =8;

          console.log(x);
          console.log(y);
          console.log(z);

          //z = 30;//Error
          //console.log(z);

          {
          let p =90;
          var q =80;
          console.log("Inside the block:"+p);
          console.log("Inside the block:"+q);
       }
       //console.log("Outside the block:"+p);//Error
       console.log("Outside the block:"+q);
      

      NOTE:
       -If you declare a variable using const keyword then
        it must be initialized with the value otherwise it will
        show error.

       - Once you initialize the const variable the you can not modify
        it's value all through the program.


        
























                 










