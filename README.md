# AssignmentC-
Use for loop and while loop to Write a program to print first 5 prime numbers
#include <iostream>

using namespace std;



int main()

{

    int i, j, count;

    cout << "First 5 prime numbers are : ";

    for (i = 2; i <= 10; i++)

    {

        count = 0;

        for (j = 2; j <= i / 2; j++)

        {

            if (i % j == 0)

            {

                count++;

                break;

            }

        }

        if (count == 0 && count < 5)

        {

            cout << i << " ";

        }

    }

    return 0;

}

