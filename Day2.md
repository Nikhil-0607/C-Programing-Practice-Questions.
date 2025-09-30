**+Que 1:  Write a 'C' program to print following pattern/diagram using printf() function only.**

**-------**



**Sample Output :** 

                **# # # # #**

                **#       #**

                **#       #**

                **#       #**    

                **# # # # #**    





// Online C compiler to run C program online

\#include <stdio.h>



int main() {

&nbsp;   // Write C code here

&nbsp;   printf("\* \* \* \* \*\\n");

&nbsp;   printf("\*       \*\\n");

&nbsp;   printf("\*       \*\\n");

&nbsp;   printf("\*       \*\\n");

&nbsp;   printf("\* \* \* \* \*\\n");



&nbsp;   return 0;

}

**=============================================================================================================================**

**Que 2 :  Write a 'C' program to declare and initialize two variable like int a=10,b=20 and print the Addition, substraction, multiplication,division,Modulation operation.**

**-------**



**Sample input : a=20, b=10;**



**Sample Output :** 

               **Addition is : 30**

               **substraction is : 10**

               **Multiplication is : 200**

               **Division is : 2**

               **Modulation is : 0**





// Online C compiler to run C program online

\#include <stdio.h>



int add(int a, int b){

&nbsp;      int sum = a + b;

&nbsp;      return sum;

&nbsp;  }

&nbsp;  

int sub(int a, int b){

&nbsp;      int Diff = a - b;

&nbsp;      return Diff;

&nbsp;  }



int mul(int a, int b){

&nbsp;      int Product = a \* b;

&nbsp;      return Product;

&nbsp;  }

&nbsp;  

int div(int a, int b){

&nbsp;      int divResult = a / b;

&nbsp;      return divResult;

&nbsp;  }



&nbsp;  

&nbsp;  

&nbsp;  

int main() {

&nbsp;  

&nbsp;  int addition = add(10, 20);

&nbsp;   printf("%d\\n", addition);

&nbsp;   

&nbsp;   int subtraction = sub(40, 20);

&nbsp;   printf("%d\\n", subtraction);

&nbsp;   

&nbsp;   int multiplication = mul(10, 20);

&nbsp;   printf("%d\\n", multiplication);

&nbsp;   

&nbsp;   int division = div(40, 20);

&nbsp;   printf("%d\\n", division);

&nbsp;   

&nbsp;   return 0;

}

**=================================================================================================================================**

**Que 3:  Write a 'C' program to print sum of first and last digit of given any 3 digit number**

**-------**



**Sample input : int number = 123;**



**Sample Output : 4**



**Explanation : given number is = 123 . so the result is (1+3)=4**





\#include <stdio.h>



int main() {

&nbsp;   int num = 123;

&nbsp;   

&nbsp;   int fristNum = num / 100

&nbsp;   int lastNum = num % 10;

&nbsp;   

&nbsp;   int sum = fristNum + lastNum;

&nbsp;   printf("%d", sum);

&nbsp;   

&nbsp;   return 0;

}

**===================================================================================================================================**

**Que 4: Write a C program to calculate and print the area of a square and rectangle.**

**-------**



**Sample input :**

**Side of square is : 5**

**Length and breadth of rectanngle is : 4 , 5**



**Sample output :**

**The area of the square with side 5 is: 25**

**The area of the rectangle with length 4 and breadth 5 is: 20**





\#include <stdio.h>



int main() {

&nbsp;   int side = 5;

&nbsp;   int length = 4, breadth = 5;

&nbsp;   

&nbsp;   int areaofSquare = side \* side;

&nbsp;   int areaofRectangle = length \* breadth;

&nbsp;   printf("%d\\n"areaofSquare);

&nbsp;   printf("%d",areaofRectangle);

&nbsp;   return 0;

} 

**======================================================================================================================================**

**Que 5:   Without using control statments Write a C program to determine the next or previous multiple of 10 for a given two-digit number.** 

**--------**  

          **The program should follow these rules:**

          **If the last digit of the given number is greater than or equal to 5, the program should print the next multiple of 10.**

          **If the last digit of the given number is less than 5, the program should print the previous multiple of 10..**





**Sample Input1  : int a = 34;**

**Sample Output1 : 30** 



**Sample Input2  : int  a = 25;**

**Output2 : 30**



**Sample Input3  : int a = 86;**

**Sample Output3 : 90**





**-------------------------------------------------------------------------------------------------------------**

**Scenario: Grocery Store Bill Calculation** 

**You went to a grocery store and bought:**



**2 kg of apples (₹120 per kg)**



**1 kg of bananas (₹60 per kg)**



**1.5 kg of oranges (₹80 per kg)**



**Write a C program that calculates:**



**1. The total cost of each fruit.**



**2. The overall bill amount.**



**3. How much you need to pay if you give ₹500.**





**Travel Time Calculation**

**You travel 150 km with an average speed of 60 km/h.**

**How much time will it take?**



**Salary Increment**



**Your salary is ₹50,000. You get a 10% increment. Calculate the new salary.**





 **Loan EMI Interest Calculatio** 

**You borrowed ₹10,000 with 5% annual interest.**

**How much interest do you pay in a year?**



// Online C compiler to run C program online

\#include <stdio.h>

int main() {

&nbsp;   int appleprice = 120;

&nbsp;   int bananaPrice = 60;

&nbsp;   int orangePrice = 80;

&nbsp;   

&nbsp;   int totalofApple;

&nbsp;   int totalofBanana;

&nbsp;   int totalofOrange;

&nbsp;   

&nbsp;   int overalPrice;

&nbsp;   

&nbsp;   

&nbsp;   printf("Total Cost od apple :%d\\n",totalofApple = appleprice \* 2);

&nbsp;   printf("Total Cost od banana :%d\\n",totalofBanana = bananaPrice \* 2);

&nbsp;   printf("Total Cost od orange :%d\\n",totalofOrange = orangePrice \* 2);

&nbsp;   

&nbsp;   printf("Overall Price :%d\\n", overalPrice =totalofApple + totalofBanana +  totalofOrange);

&nbsp;   

&nbsp;   printf("How much you need to pay if you give : %d",( overalPrice - 500 ) );



&nbsp;   return 0;   

}







