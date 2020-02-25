# SMALLLARGEINT-DOUBLE
FINDS THE SMALLEST AND LARGEST INT AND DOUBLE
// ConsoleApplication2.cpp : Defines the entry point for the console application.
// Jonathan Sessom

#include "stdafx.h"
#include <iostream>
#include <climits>
#include<cfloat>

using namespace std;
int main()
{
	


	cout << "smallest integer = " << SHRT_MIN << endl;

	cout << "largest integer = " << SHRT_MAX << endl;
	cout << "smallest real # = " << FLT_MIN << endl;
	cout << "smallest double # = " << DBL_MIN << endl;
	cout << "largest real number = " << FLT_MAX << endl;
	cout << "largest real double number = " << DBL_MAX << endl;
	
    return 0;
}
