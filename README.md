# IF,ELSE,ELSE IF,SHORT HAND(TERNARY OPERATOR):


# THE IF STATEMENT

##syntax                     

     if(condition)
     {
       //Code to be executed if the condition is True
     }
     
##Example on if condition

      int Nani = 20;
      int Kannamma = 18;
      if (Nani > kannamma) 
     {
        Console.WriteLine("Nani Loves Mummy");                      //output: Nani Loves Mummy
     }
     
 # THE ELSE STATEMENT
 
 ##Syntax
 
    if (condition)
      {
         // block of code to be executed if the condition is True
      } 
    else 
      {
        // block of code to be executed if the condition is False
      }
 
 ##Example on else statement
 
 int time = 10;
 if (time < 12) 
  {
  Console.WriteLine("Morno Nani");
  } 
else 
  {
  Console.WriteLine("Aftnn Nani");                  //output: Morno Nani
  }
  
  
  #THE ELSE IF STATEMENT
  
  if (condition1)
  {
  // block of code to be executed if condition1 is True
  } 
   else if (condition2) 
  {
  // block of code to be executed if the condition1 is false and condition2 is True
  } 
   else
  {
  // block of code to be executed if the condition1 is false and condition2 is False
  }
  
  ##Example on else if statement
  
int coffee  = 20;
if (coffee == 10) 
{
  Console.WriteLine("Regular coffee is selected");
} 
else if (coffee == 20) 
{
  Console.WriteLine("Large Coffee is selected");                      //output: Large Coffee is selected
} 
else 
{
  Console.WriteLine("Please enter a valid number");
}

# SHORT HAND IF...ELSE (Ternary Operator)

There is also a short-hand if else, which is known as the ternary operator because it consists of three operands. It can be used to replace multiple lines of code with a single line. It is often used to replace simple if else statements:

##Syntax
variable = (condition) ? expressionTrue :  expressionFalse;
 
 ##Example on If else ternary operator
 
 int MoodSwing = 20;
 string result = (MoodSwing < 30) ? "Bongaina" : "Kannamma";          //output: Kannamma
 Console.WriteLine(result);


 
        
   
            








