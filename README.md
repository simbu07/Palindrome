## Ex-2 Palindrome
### Date:28/3/2023

### Aim:
To write a C# program to find whether the given string is a Palindrome or not.
### Algorithm:

### Step1: 
Start the program.

### Step2:
Create a class and declare two variable with string datatype.

### Step3:
Loop over the entire string and reverse it.

### Step4: 
Use if condition to check whether the string and the reversed string is equal or not.

### Step5:
Print palindrome if it's equal else print not a palindrome.

### Step6:
End the program.
### Program:
```
Delevoped By : Silambarasan K
Reg No: 212221230101
```
```c#
using System;
namespace exp2
{
    class Program
    {
        static void Main(string[] args)
        {
            string s, rev = "";
            Console.WriteLine(" Enter string");
            s = Console.ReadLine();
            for (int i = s.Length - 1; i >= 0; i--)
            {
                rev += s[i];
            }
            if (rev == s)
            {
                Console.WriteLine("{0} is Palindrome", s);
            }
            else
            {
                Console.WriteLine("{0} is not Palindrome", s);
            }
        }
    }
}
```
### Output:
![P1](https://user-images.githubusercontent.com/94525786/226187726-cba1d8f2-6c62-42a9-b89d-0e716a6b1dfd.png)
![P2](https://user-images.githubusercontent.com/94525786/226187728-b794a19c-e3fa-4f3b-b3ee-9579007551d4.png)

### Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
