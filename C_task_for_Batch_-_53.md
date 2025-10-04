

**Que 1 :**

**--------**



 **Write a program to convert  uppercase Character to Lowercase Character without using ternary operator and control statements.**





**Sample Input:-**

	**Enter a Uppercase Character : H**

**Output-**

	**Lowercase Character : h**



\#include <stdio.h>



int main() {

&nbsp;   char c;

&nbsp;   printf("Enter a Uppercase Character :");

&nbsp;   scanf("%c", \&c);

&nbsp;   printf("Lowercase Character : %c", c+32);

&nbsp;   return 0;

}



**=======================================================================================**

**Que 2 :**

**--------**

 **Write a program to convert Lowercase Character to uppercase Character without using ternary operator and control statements.**





**Sample Input:-**

	**Enter a Lowercase  Character : a**

**Output-**

	**Uppercase Character : A**



\#include <stdio.h>



int main() {

&nbsp;   char c;

&nbsp;   printf("Enter a Lowercase  Character :");

&nbsp;   scanf("%c", \&c);

&nbsp;   printf("Uppercase Character : %c", c-32);

&nbsp;   return 0;

}



**=======================================================================================**

**Que 3 :**

**--------**



**Write a C program to check a given integer three digit or not using ternary operator.**



**if three digit print "True"** 

**if not three digit print "false"**



**input :**

	**Enter a number :123**

**output :**

	**true** 

**input :**

	**Enter a number :1233**

**output :**

	**false**



// Online C compiler to run C program online

\#include <stdio.h>



int main() {

&nbsp;   int num;



&nbsp;   printf("Enter the number:");

&nbsp;   scanf("%d", \&num);

&nbsp;   

&nbsp;   (num>99  \&\& num<1000)?

&nbsp;   printf("true"):printf("false");

&nbsp;   

&nbsp;   return 0;

}



**=======================================================================================**

**Que 4 :**

**--------**

**Write a C program to check if two given non-negative integers have the same last digit.**



**input :**

	**Enter two number : 23 43** 

**output :**	

	**last digit is same**



**input :**

	**Enter two number : 89 43** 

**output :**	

	**last digit not same**

