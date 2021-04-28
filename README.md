# Weekly-Salary-Calculator
Calculates weekly salary for user.


Create a program that will allow an employee to calculate his or her weekly salary.
The program will prompt the employee for their name. This should be accomplished by the
getName method with the following method signature:
public static String getName()
This value should be returned to the main method.
Then the program will prompt the user for hourly wage. If the hourly wage is less than 10
dollars or more than 100 dollars then the program will print an error message and prompt the
user again for another hourly wage. The program will continue to prompt the user for the hourly
wage until the user enters a wage between 10 and 100 dollars. This should be accomplished by
the getHourlyWage method with the following method signature:
public static double getHourlyWage()
This value should be returned to the main method.
Then the program will prompt the user for the number of hours they have worked this week. If
the numbers hours worked is less than 0 or greater than 100 then the program will print an error
message and prompt the user again for the number of hours worked. The program will continue
to prompt the user for the number of hours worked until the user enters hours between 0 and 100.
This should be accomplished by the getNumberOfHours method with the following method
signature:
public static int getNumberOfHours()
This value should be returned to the main method.
Then the program will calculate the weekly salary based on the hourly wage and number of
hours worked by mulitplying the hourly wage by the number of hours worked. This should be
accomplished by calculateWeeklySalary method with the following method signature:
public static double calculateWeeklySalary(double hourlyWage, int numberOfHours)
This value should be returned to the main method.
Then the program will print the user's name, hourly wage, number of hours worked, and the
weekly salary. This will be accomplished by the printInformation method with the following
method signature:
public static void printInformation(String name, double hourlyWage, int numberOfHours,
double weeklySalary)
