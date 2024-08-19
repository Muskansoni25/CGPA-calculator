# CGPA Calculator

In this program we have created a basic CGPA calculator using C++ language. It includes if-else loop and a manin function in which we have used for loop and used the formula of CGPA which is CGPA= totalgradepoints / totalcredits.

# Explanation

Starting with header files it includes "iostream" and "string" for input/output operations and string class respectively.
"using namespace std;" allows use of standard library names without using "std::" again and again.
next, it defines a function named "calculateGradePoints" which is used to converti letter garde to numeric equivalent value.
In the same function it also uses "return 0;" to handle invalid grade.
Next, main function is defined. In this we declare a integer "numsubjects" to store the number of subjects. cin is used to take uer input for the same. 
It also initialize two variables namely "totalgradepoints" and "totalcredits".
Next, a for loop is started to iterate over each subject starting from  to "numsubjects".
Similar to "numsubjects", we declare two more variables "subjectname" and "credits" to input number of subject and their credit respectively.
If in case the credit entered is negative or invalid then, it will decrement i and iterate again. 
Next, garde is entered by the user and then total grade points and total credits are calculated separtately.
and finally CGPA is calculated using the formula CGPA=totalgradepoints / totalcredit
