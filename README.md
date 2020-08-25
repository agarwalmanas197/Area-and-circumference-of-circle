Program to calculate Area and Circumference of Circle


Here we are writing a simple C program that calculates the area and circumference of circle based on the radius value provided by user.

Formula:
Area = 3.14 * radius * radius
Circumference = 2 * 3.14 * radius

Program to calculate Area and Circumference based on user input
To calculate area and circumference we must know the radius of circle. The program will prompt user to enter the radius and based on the input it would calculate the values. To make it simpler we have taken standard PI value as 3.14 (constant) in the program. Other details are mentioned as comments in the below example program.

#include <stdio.h>
int main()
{
   int circle_radius;
   float PI_VALUE=3.14, circle_area, circle_circumf;

   //Ask user to enter the radius of circle
   printf("\nEnter radius of circle: ");
   //Storing the user input into variable circle_radius
   scanf("%d",&circle_radius);

   //Calculate and display Area
   circle_area = PI_VALUE * circle_radius * circle_radius;
   printf("\nArea of circle is: %f",circle_area);

   //Caluclate and display Circumference
   circle_circumf = 2 * PI_VALUE * circle_radius;
   printf("\nCircumference of circle is: %f",circle_circumf);

   return(0);
}
Output:

Enter radius of circle: 2
Area of circle is: 12.560000
Circumference of circle is: 12.560000
If you want more accurate results then take PI value as 22/7 instead of 3.14, it would give you the exact values of area and circumference.
Here we are writing a simple C program that calculates the area and circumference of circle based on the radius value provided by user.

Formula:
Area = 3.14 * radius * radius
Circumference = 2 * 3.14 * radius

Program to calculate Area and Circumference based on user input
To calculate area and circumference we must know the radius of circle. The program will prompt user to enter the radius and based on the input it would calculate the values. To make it simpler we have taken standard PI value as 3.14 (constant) in the program. Other details are mentioned as comments in the below example program.

#include <stdio.h>
int main()
{
   int circle_radius;
   float PI_VALUE=3.14, circle_area, circle_circumf;

   //Ask user to enter the radius of circle
   printf("\nEnter radius of circle: ");
   //Storing the user input into variable circle_radius
   scanf("%d",&circle_radius);

   //Calculate and display Area
   circle_area = PI_VALUE * circle_radius * circle_radius;
   printf("\nArea of circle is: %f",circle_area);

   //Caluclate and display Circumference
   circle_circumf = 2 * PI_VALUE * circle_radius;
   printf("\nCircumference of circle is: %f",circle_circumf);

   return(0);
}
Output:

Enter radius of circle: 2
Area of circle is: 12.560000
Circumference of circle is: 12.560000
If you want more accurate results then take PI value as 22/7 instead of 3.14, it would give you the exact values of area and circumference.
