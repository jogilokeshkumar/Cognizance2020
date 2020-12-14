# Task 6

># **ARMSTRONG NUMBERS**


>PSEUDO CODE FOR ARMSTRONG NUMBERS 

**Start**

* **Declare** 

    
    * num as integer
    * sum as integer
    * digit as integer

* **Now Assign**

    * num = number
    * sum = 0
* Now create a **while loop** for the condition number > 0
* In while loop , 
        
    * if the _while_ condition is true ,  Assign

       *  digit = number % 10
       *  sum = sum + (digit)^3 
       *  sum =sum + (digit)^4
       *  number = number/10

    * if the _while_ condition is false , 
      
      * if sum == num is true , then give the number is a **Armstrong number**.
      * if sum == num is false , then give the number is not a **Armstrong number**.

  **End**