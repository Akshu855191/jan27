
Jan-27
Recap

- Boilerplate :- Already prepared, ready to consume code

- Data types :- Type of data, It gives information about the type of data we have in the variable.

-Interepreted language are executed line by line
-compiled language are executed as a whole code

-How to check the data type:- type of operator.
*Operator:- Operator not having any function. It haing operator
1. unary operator:- It takes only 1 operand( E.g type of  var a)
2. Binary Operator:- it takes 2 operands (E.g +,-,/,* e.g 10+15)
2. Ternary operator:- It takes 3 operands (e.g ?:)

 


1.  Nesting:- Having 1 thing (if,loop,for,while,switch,object,function,array)
              inside another is called nesting.
 
//check if the nummber is positive or negative.
//if the number is zero, It is considered as neutral.                   
// Negative, Neutral, Positive:3 condition
   var num = 0;
   if(num < 0)
{
    console.log("Number is negative");
}
  else
{
    if(num == 0)
    {
     console.log("Number is Neutral");
    }
    else
    {
    console.log("Number is positive");
    }
}

//This is called nesting condition:- Eak ke aander eak.
 
2. if else/else if:- Benefit You can have multiple
   var num = 0;
   if(num < 0)
{
    console.log("Number is negative");
}
  else if(num == 0)
    {
     console.log("Number is Neutral");
    }
  else
    {
    console.log("Number is positive");
    }


*else if ladder:- Its a chain of if/else if/ else if/ else if/else if/ else(optional).
Another example:-
 //If else/else if
var character = "a";
if (character == "a")
{
    console.log("Vowel");
}
else if(character == "e")
{
    console.log("Vowel");
}
else if(character == "i")
{
    console.log("Vowel");
}
else if(character == "o")
{
    console.log("Vowel");
}
else if(character == "u")
{
    console.log("Vowel");
}
else
{
    console.log("Character is not a Vowel");
}




2. Switch
3. Indentation  {done)
4. Array (Create, Read, Update, Delete)
5. object
8.Indentation(Space) :-In js we not have a syntax of indentation. Other language havng the syntax
                - It is the spac which we give before starting the line f code. It is helpful
                  for allignment. It is helpful for code readability. (2 spaces, 4 spaces). 
                 var num = 10;
                 var rem = num % 2;
                 if(rem == 0){
                     console.log("Number is even")
                 }
                 else{
                     console.log("Number is odd");
                 }

9. Array:- Collection of similar type of data. In a systamatic way
          - Collection of same data types
          -collection of homogenous data
homogenous:- same type.
hetrogenous:- mixed data.
How to create an array?[]
Ans:- 1. Create a variable == [];
      2. for array [] semibracket;
     E.g var arr1 = [];
         console.log(arr1);
        -Again it prove js is doesnt care data types
        - E.g var arr1 = [1234, "Something", false, null];
              console.log(arr1);
              output:- It will print all number,string,boolean,null data types and show the output.
        -Array is not data strucure/type in js. It alwaysn an object.
        - E.g:- var arr1 = [1234, "Something", false, null];
                console.log(type of arr1);
              output:- It always show the type is an object.
        - Array is just writing the fancy way of an object.
        - Elements are saparated by comma,
Q.How to access/get data particular element which is in diffent postion in array?
Ans:-    var arr1 = [1234, "Something", false, null];
         console.log(arr1[2]);

Q. How to access particular element data types which is presnt in array?
Ans:-  var arr1 = [1234, "Something", false, null];
        console.log(arrayof arr1[1]);
        output:- String
  

            var arr1 = [1234, Something, false, null];
              console.log(arr1);
        Note:- If we not create something is double quates or in string than it act like a variable.
               In such case we need to create a varible something and assign some value to that varable.
           For example:- var Something = 4523;
                        var arr1 = [1234, Something, false, null];
                       console.log(arr1);
            Output:- 1234 4523 false null


  

