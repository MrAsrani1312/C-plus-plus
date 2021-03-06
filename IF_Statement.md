---
C++ If Statement
---

This lesson will teach you on how to use and use if statement in your
c++ programs.

**What does an If Statement do?**

The ***if*** statement evaluates your test expression present inside the parenthesis.

  -----------------------------------------------
  The general form of if statement:
  
  If (Test Expression)
  
  {
  
  Block of statement if test expression is True
  
  }
  -----------------------------------------------

If the value of your test expression is ***true***, then the block of
code inside the if statement is executed.

If the value of your test expression is ***false***, then the block of
code inside the if statement is skipped and your code continues.

Example of If Statement:

  --------------------- ---------------------
  True Statement        False Statement
                        
  int a= 10;            int a= 10;
                        
  if (a &lt; 20)        if (a &gt; 20)
                        
  {                     {
                        
  //execute block of    //skip block of
                        
  code                  Code
                        
  }                     }
                        
  //program continues   //program continues
  --------------------- ---------------------

Example In C++ :

  -------------------------------------------------------------------------------
  //Program to check if number entered by the user is positive
  
  //If negative, the block of code is skipped
  ```C++
  #include <iostream>;
  
  using namespace std;
  
  int main()
  
  {
  
  int no ;
  
  cout<<”Enter a number : ” ;
  
  cin>>no ;
  
  //If Statement to check if the number is positive
  
  if (no>0)
  
  {
  
  cout<<”You’ve entered a positive number :”<<no<<endl ;
  
  }
  
  //If number is not positive, then if statement is skipped a program continues
  
  cout &lt;&lt; “This step is always printed” &lt;&lt; endl ;
  
  return 0 ;
  
  }
  ```
  -------------------------------------------------------------------------------

Output :

  ---------------------------------------------------------------------
  OUTPUT 1                                OUTPUT 2
  --------------------------------------- -----------------------------
  Enter a number : 10                     Enter a number : -10
                                          
  You’ve entered a positive number : 10   This step is always printed
                                          
  This step is always printed             
  ---------------------------------------------------------------------


_CONGRATULATIONS . This is the end of the article on the IF statement_ 
 
 **Good Luck to all of you** 
 
 **Happy Coding ! :)**
 
 **Feel free to ask any queries on FreeCodeCamp's GitHub page or [FreeCodeCamp's Forum .](https://forum.freecodecamp.org/)**

By : Jaithra Bhatia and Hitarth Asrani