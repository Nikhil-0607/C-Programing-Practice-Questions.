**1)A shopkeeper buys a TV set for Rs. 3500 and sells it at a profit of 27%. Apart from this a VAT of 12.7% and Service Charge is 3.87% is charged.** 

	 **Write a C program to Display total selling price, profit along with vat and service charge.**

         **To calculate the selling price, profit, VAT, and service charge, follow these steps:**



         **1) Calculate the selling price:**



            **Selling Price = Cost Price + Profit**



            **Selling Price = Rs. 3500 + (27% of Rs. 3500)**





         **2) Calculate the profit:**



            **Profit = Selling Price - Cost Price**





         **3) Calculate VAT:**



            **VAT = 12.7% of Selling Price**





         **4) Calculate Service Charge:**



            **Service Charge = 3.87% of Selling Price**











// Online C compiler to run C program online

\#include <stdio.h>



int main() {

&nbsp;  int costPrice = 3500;

&nbsp;  int sellingPrice;

&nbsp;  int profit;

&nbsp;  int vat;

&nbsp;  int serviceCharge;

&nbsp;  

&nbsp;  sellingPrice = costPrice + ((27.0/100)\*3500);

&nbsp;  profit = sellingPrice - costPrice;

&nbsp;  vat = (12.7/100)\*sellingPrice;

&nbsp;  serviceCharge = (3.87/100)\*sellingPrice;

&nbsp;  

&nbsp;  printf("sellingPrice is : %d\\n",  sellingPrice);

&nbsp;  printf("profit is : %d\\n",  profit);

&nbsp;  printf("vat is : %d\\n",  vat);

&nbsp;  printf("serviceCharge is : %d\\n",  serviceCharge);

&nbsp;  



&nbsp;   return 0;

}

**===================================================================================================================================================**

**2)Write a 'C' program to check and print that given number is even or odd using ternary operator.**

**--------**



**Sample input : int a = 10**

**Sample Output : EVEN**



**Sample input : int a = 125**

**Sample Output : ODD**







// Online C compiler to run C program online

\#include <stdio.h>



int main() {

&nbsp;   int a;

&nbsp;   scanf("%d", \&a);

&nbsp;   (a % 2 == 0)? printf("EVEN"):printf("ODD");

&nbsp;   return 0;

}

**=================================================================================================================================================================**

**3)  Write a 'C' program to reverse the given 3 digit number without using control statments.**



**Sample input : int a = 123;**

**Sample Output : reverse =  321**





\#include <stdio.h>



int main() {

&nbsp;   int a;

&nbsp;   printf("Enter the number: ");

&nbsp;   scanf("%d", \&a);//123

&nbsp;   int b=a%10;//3

&nbsp;   a=a/10;//12

&nbsp;   int c=a%10;//2

&nbsp;   a=a/10;//1

&nbsp;   printf("%d%d%d",b,c,a);

&nbsp;   

&nbsp;

&nbsp;   return 0;

}

**==================================================================================================================================================================**

**4) Using ternary operator write a C program for a bookstore named "BookWorld" that calculates the discounted amount based on the total purchase amount.** 



**The store provides three types of discounts to its customers:**

**-> If the total purchase amount is less than Rs. 1000, there is no discount.**

**-> If the total purchase amount is between Rs. 1000 and Rs. 5000 (inclusive), customers get a 5% discount on the total purchase amount.**

**-> If the total purchase amount is greater than Rs. 5000, customers get a 10% discount on the total purchase amount.**



**Sample input  : purchase amount = 999**

**Sample output : total amount = 999**

**int >**

**Sample input  : purchase amount = 2000**

**Sample output : total amount including 5% discount = 1900**



**Sample input  : purchase amount = 10000**

**Sample output : total amount including 10% discount = 9000**





// Online C compiler to run C program online

\#include <stdio.h>



int main() {

&nbsp;   int amount;



&nbsp;   scanf("%d",\&amount);

&nbsp;   (amount<1000)?printf("%.2f",amount):(amount>=1000\&\&amount<=5000)?printf("%d",amount-(int)(amount\*0.05)):(amount>5000)?printf("%.2f",amount-(amount\*0.1)):printf("not in the range");

&nbsp;   return 0;

}





