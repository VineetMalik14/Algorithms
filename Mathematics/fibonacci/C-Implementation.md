# C-Implementation of Fibonacci Prgram

```c

#include <iostream.h>
#include <stdio.h>

int main()
{
        // Fibonacci sequence size
        const int n = 10;
        
        // Array to store the Fibonacci series
	int Fib[105];
        // Initializing the first two elements of series
	Fib[0] = 0; Fib[1] = 1;
        
	for(int i = 2; i < n; i++)
                // Calculate the the 'i'th element by 
                // adding 'i-1'th and 'i-2'th elements
                Fib[i] = Fib[i-1] + Fib[i-2];
        
        // Print the first n elements of the Fibonacci sequence
	for(int i = 0; i < n; i++)
        {
                cout << i << " : " << Fib[i] ;
                cout << endl;
        }
	
    return 0;
}

```
