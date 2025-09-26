/* 
Lab 1
Jasmine Tran
CET 2411, Section D02L
9/19/2025

This program displays "Hello World!" for arbitrary times that user inputs 
*/

#include <iostream>
using namespace std;

int main() 
{
    int numberOfRuns; 

    cout << "This program runs "Hello World!" for the number of times the user inputs.\n" ;
    cout << "Please enter a number to output "Hello World!" for arbitrary times: "; 
    cin >> numberOfRuns; // Stores user input into "numberOfRuns" variable

    for ( int i = 0; i < numberOfRuns; i++) // Starts i at 0, increasing its value by 1 until it hits the # the user input
    {
    cout << "Hello World!" << endl; // Outputs "Hello World!", inserting a new line for the start of each loop run
    }

    return 0; // Ends the program
}
