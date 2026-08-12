**1. Find Sum of n Natural Numbers**

**C-Program:**

```c
#include <stdio.h>

int main()
{
    int n, i, sum = 0;

    printf("Enter n: ");
    scanf("%d", &n);

    for(i = 1; i <= n; i++)
        sum += i;

    printf("Sum = %d", sum);

    return 0;
}
```

**Sample Output:**

```text
Enter n: 10
Sum = 55
```

---

**2. Calculate Simple Interest**

**C-Program:**

```c
#include <stdio.h>

int main()
{
    float p, r, t, si;

    printf("Enter principal, rate and time: ");
    scanf("%f %f %f", &p, &r, &t);

    si = (p * r * t) / 100;

    printf("Simple Interest = %.2f", si);

    return 0;
}
```

**Sample Output:**

```text
Enter principal, rate and time: 10000 5 2
Simple Interest = 1000.00
```

---

**3. Print Multiplication Table**

**C-Program:**

```c
#include <stdio.h>

int main()
{
    int n, i;

    printf("Enter a number: ");
    scanf("%d", &n);

    for(i = 1; i <= 10; i++)
        printf("%d x %d = %d\n", n, i, n * i);

    return 0;
}
```

**Sample Output:**

```text
Enter a number: 5
5 x 1 = 5
5 x 2 = 10
5 x 3 = 15
5 x 4 = 20
5 x 5 = 25
5 x 6 = 30
5 x 7 = 35
5 x 8 = 40
5 x 9 = 45
5 x 10 = 50
```

---

**4. Find n Even Numbers**

**C-Program:**

```c
#include <stdio.h>

int main()
{
    int n, i;

    printf("Enter n: ");
    scanf("%d", &n);

    for(i = 1; i <= n; i++)
        printf("%d ", 2 * i);

    return 0;
}
```

**Sample Output:**

```text
Enter n: 5
2 4 6 8 10
```

---

**5. Find Factorial of Given Number**

**C-Program:**

```c
#include <stdio.h>

int main()
{
    int n, i;
    long long fact = 1;

    printf("Enter a number: ");
    scanf("%d", &n);

    for(i = 1; i <= n; i++)
        fact *= i;

    printf("Factorial = %lld", fact);

    return 0;
}
```

**Sample Output:**

```text
Enter a number: 5
Factorial = 120
```

---

**6. Swap Two Numbers**

**C-Program:**

```c
#include <stdio.h>

int main()
{
    int a, b, temp;

    printf("Enter two numbers: ");
    scanf("%d %d", &a, &b);

    temp = a;
    a = b;
    b = temp;

    printf("After swapping:\n");
    printf("a = %d\n", a);
    printf("b = %d", b);

    return 0;
}
```

**Sample Output:**

```text
Enter two numbers: 10 20
After swapping:
a = 20
b = 10
```

---

**7. Find Sum, Difference and Quotient**

**C-Program:**

```c
#include <stdio.h>

int main()
{
    float a, b;

    printf("Enter two numbers: ");
    scanf("%f %f", &a, &b);

    printf("Sum = %.2f\n", a + b);
    printf("Difference = %.2f\n", a - b);
    printf("Quotient = %.2f", a / b);

    return 0;
}
```

**Sample Output:**

```text
Enter two numbers: 20 5
Sum = 25.00
Difference = 15.00
Quotient = 4.00
```

---

**8. Convert Celsius to Fahrenheit**

**C-Program:**

```c
#include <stdio.h>

int main()
{
    float c, f;

    printf("Enter temperature in Celsius: ");
    scanf("%f", &c);

    f = (c * 9 / 5) + 32;

    printf("Temperature in Fahrenheit = %.2f", f);

    return 0;
}
```

**Sample Output:**

```text
Enter temperature in Celsius: 25
Temperature in Fahrenheit = 77.00
```

---

**9. Find Area and Perimeter**

**C-Program:**

```c
#include <stdio.h>

int main()
{
    float l, b, area, perimeter;

    printf("Enter length and breadth: ");
    scanf("%f %f", &l, &b);

    area = l * b;
    perimeter = 2 * (l + b);

    printf("Area = %.2f\n", area);
    printf("Perimeter = %.2f", perimeter);

    return 0;
}
```

**Sample Output:**

```text
Enter length and breadth: 10 5
Area = 50.00
Perimeter = 30.00
```

---

**10. Check Even or Odd**

**C-Program:**

```c
#include <stdio.h>

int main()
{
    int n;

    printf("Enter a number: ");
    scanf("%d", &n);

    if(n % 2 == 0)
        printf("Even number");
    else
        printf("Odd number");

    return 0;
}
```

**Sample Output:**

```text
Enter a number: 24
Even number
```

---

**11. Reverse the Digits of Given Number**

**C-Program:**

```c
#include <stdio.h>

int main()
{
    int n, rev = 0, rem;

    printf("Enter a number: ");
    scanf("%d", &n);

    while(n != 0)
    {
        rem = n % 10;
        rev = rev * 10 + rem;
        n /= 10;
    }

    printf("Reverse = %d", rev);

    return 0;
}
```

**Sample Output:**

```text
Enter a number: 12345
Reverse = 54321
```

---

**12. Check Prime Number**

**C-Program:**

```c
#include <stdio.h>

int main()
{
    int n, i, flag = 0;

    printf("Enter a number: ");
    scanf("%d", &n);

    if(n <= 1)
        flag = 1;

    for(i = 2; i <= n / 2; i++)
    {
        if(n % i == 0)
        {
            flag = 1;
            break;
        }
    }

    if(flag == 0)
        printf("Prime number");
    else
        printf("Not a prime number");

    return 0;
}
```

**Sample Output:**

```text
Enter a number: 17
Prime number
```

---

**13. Print Multiplication Table**

**C-Program:**

```c
#include <stdio.h>

int main()
{
    int n, i;

    printf("Enter a number: ");
    scanf("%d", &n);

    for(i = 1; i <= 10; i++)
        printf("%d x %d = %d\n", n, i, n * i);

    return 0;
}
```

**Sample Output:**

```text
Enter a number: 7
7 x 1 = 7
7 x 2 = 14
7 x 3 = 21
7 x 4 = 28
7 x 5 = 35
7 x 6 = 42
7 x 7 = 49
7 x 8 = 56
7 x 9 = 63
7 x 10 = 70
```

---

**14. Print Fibonacci Series**

**C-Program:**

```c
#include <stdio.h>

int main()
{
    int n, i, a = 0, b = 1, c;

    printf("Enter number of terms: ");
    scanf("%d", &n);

    for(i = 1; i <= n; i++)
    {
        printf("%d ", a);
        c = a + b;
        a = b;
        b = c;
    }

    return 0;
}
```

**Sample Output:**

```text
Enter number of terms: 7
0 1 1 2 3 5 8
```

---

**15. Find Sum of Even Numbers**

**C-Program:**

```c
#include <stdio.h>

int main()
{
    int n, i, sum = 0;

    printf("Enter n: ");
    scanf("%d", &n);

    for(i = 2; i <= n; i += 2)
        sum += i;

    printf("Sum of even numbers = %d", sum);

    return 0;
}
```

**Sample Output:**

```text
Enter n: 10
Sum of even numbers = 30
```

---

**16. Find Biggest Among Three Numbers**

**C-Program:**

```c
#include <stdio.h>

int main()
{
    int a, b, c, big;

    printf("Enter three numbers: ");
    scanf("%d %d %d", &a, &b, &c);

    big = a;

    if(b > big)
        big = b;

    if(c > big)
        big = c;

    printf("Biggest number = %d", big);

    return 0;
}
```

**Sample Output:**

```text
Enter three numbers: 25 45 30
Biggest number = 45
```

---

**17. Check Armstrong Number**

**C-Program:**

```c
#include <stdio.h>

int main()
{
    int n, temp, rem, sum = 0;

    printf("Enter a number: ");
    scanf("%d", &n);

    temp = n;

    while(temp != 0)
    {
        rem = temp % 10;
        sum += rem * rem * rem;
        temp /= 10;
    }

    if(sum == n)
        printf("Armstrong number");
    else
        printf("Not an Armstrong number");

    return 0;
}
```

**Sample Output:**

```text
Enter a number: 153
Armstrong number
```

---

**18. Find Sum of Digits**

**C-Program:**

```c
#include <stdio.h>

int main()
{
    int n, sum = 0, rem;

    printf("Enter a number: ");
    scanf("%d", &n);

    while(n != 0)
    {
        rem = n % 10;
        sum += rem;
        n /= 10;
    }

    printf("Sum of digits = %d", sum);

    return 0;
}
```

**Sample Output:**

```text
Enter a number: 12345
Sum of digits = 15
```

---

**19. Calculate Electricity Bill**

**C-Program:**

```c
#include <stdio.h>

int main()
{
    float units, bill;

    printf("Enter units consumed: ");
    scanf("%f", &units);

    if(units > 800)
        bill = units * 4;
    else if(units > 400)
        bill = units * 3;
    else if(units > 200)
        bill = units * 2.50;
    else if(units >= 100)
        bill = units * 1.50;
    else
        bill = units * 1;

    printf("Electricity Bill = Rs. %.2f", bill);

    return 0;
}
```

**Sample Output:**

```text
Enter units consumed: 500
Electricity Bill = Rs. 1500.00
```

---

**20. Find Sum of Even Terms in Fibonacci Series**

**C-Program:**

```c
#include <stdio.h>

int main()
{
    int n, i, a = 0, b = 1, c, sum = 0;

    printf("Enter number of terms: ");
    scanf("%d", &n);

    for(i = 1; i <= n; i++)
    {
        if(a % 2 == 0)
            sum += a;

        c = a + b;
        a = b;
        b = c;
    }

    printf("Sum of even terms = %d", sum);

    return 0;
}
```

**Sample Output:**

```text
Enter number of terms: 10
Sum of even terms = 44
```

---

**21. Find Biggest of n Numbers**

**C-Program:**

```c
#include <stdio.h>

int main()
{
    int n, i, num, big;

    printf("Enter n: ");
    scanf("%d", &n);

    printf("Enter number 1: ");
    scanf("%d", &big);

    for(i = 2; i <= n; i++)
    {
        printf("Enter number %d: ", i);
        scanf("%d", &num);

        if(num > big)
            big = num;
    }

    printf("Biggest number = %d", big);

    return 0;
}
```

**Sample Output:**

```text
Enter n: 5
Enter number 1: 10
Enter number 2: 45
Enter number 3: 20
Enter number 4: 67
Enter number 5: 30
Biggest number = 67
```

---

**22. Count Positive and Negative Numbers in Array**

**C-Program:**

```c
#include <stdio.h>

int main()
{
    int a[100], n, i;
    int positive = 0, negative = 0;

    printf("Enter number of elements: ");
    scanf("%d", &n);

    printf("Enter elements:\n");

    for(i = 0; i < n; i++)
    {
        scanf("%d", &a[i]);

        if(a[i] > 0)
            positive++;
        else if(a[i] < 0)
            negative++;
    }

    printf("Positive numbers = %d\n", positive);
    printf("Negative numbers = %d", negative);

    return 0;
}
```

**Sample Output:**

```text
Enter number of elements: 5
Enter elements:
10
-5
20
-8
7
Positive numbers = 3
Negative numbers = 2
```

---

**23. Sum and Average of Array Elements**

**C-Program:**

```c
#include <stdio.h>

int main()
{
    int a[100], n, i, sum = 0;
    float average;

    printf("Enter number of elements: ");
    scanf("%d", &n);

    printf("Enter elements:\n");

    for(i = 0; i < n; i++)
    {
        scanf("%d", &a[i]);
        sum += a[i];
    }

    average = (float)sum / n;

    printf("Sum = %d\n", sum);
    printf("Average = %.2f", average);

    return 0;
}
```

**Sample Output:**

```text
Enter number of elements: 5
10 20 30 40 50
Sum = 150
Average = 30.00
```

---

**24. Search an Element in Array**

**C-Program:**

```c
#include <stdio.h>

int main()
{
    int a[100], n, i, search, found = 0;

    printf("Enter number of elements: ");
    scanf("%d", &n);

    printf("Enter elements:\n");

    for(i = 0; i < n; i++)
        scanf("%d", &a[i]);

    printf("Enter element to search: ");
    scanf("%d", &search);

    for(i = 0; i < n; i++)
    {
        if(a[i] == search)
        {
            found = 1;
            break;
        }
    }

    if(found)
        printf("Element found at position %d", i + 1);
    else
        printf("Element not found");

    return 0;
}
```

**Sample Output:**

```text
Enter number of elements: 5
10 20 30 40 50
Enter element to search: 30
Element found at position 3
```

---

**25. Sort the Given Set of Elements in Increasing Order**

**C-Program:**

```c
#include <stdio.h>

int main()
{
    int a[100], n, i, j, temp;

    printf("Enter number of elements: ");
    scanf("%d", &n);

    printf("Enter elements:\n");

    for(i = 0; i < n; i++)
        scanf("%d", &a[i]);

    for(i = 0; i < n - 1; i++)
    {
        for(j = 0; j < n - i - 1; j++)
        {
            if(a[j] > a[j + 1])
            {
                temp = a[j];
                a[j] = a[j + 1];
                a[j + 1] = temp;
            }
        }
    }

    printf("Ascending order:\n");

    for(i = 0; i < n; i++)
        printf("%d ", a[i]);

    return 0;
}
```

**Sample Output:**

```text
Enter number of elements: 5
50 20 40 10 30
Ascending order:
10 20 30 40 50
```

---

**26. Find Duplicate Elements in Array**

**C-Program:**

```c
#include <stdio.h>

int main()
{
    int a[100], n, i, j;

    printf("Enter number of elements: ");
    scanf("%d", &n);

    printf("Enter elements:\n");

    for(i = 0; i < n; i++)
        scanf("%d", &a[i]);

    printf("Duplicate elements:\n");

    for(i = 0; i < n; i++)
    {
        for(j = i + 1; j < n; j++)
        {
            if(a[i] == a[j])
            {
                printf("%d ", a[i]);
                break;
            }
        }
    }

    return 0;
}
```

**Sample Output:**

```text
Enter number of elements: 6
10 20 30 20 40 10
Duplicate elements:
10 20
```

---

**27. Addition of Two Matrices**

**C-Program:**

```c
#include <stdio.h>

int main()
{
    int a[10][10], b[10][10], c[10][10];
    int r, col, i, j;

    printf("Enter rows and columns: ");
    scanf("%d %d", &r, &col);

    printf("Enter first matrix:\n");

    for(i = 0; i < r; i++)
        for(j = 0; j < col; j++)
            scanf("%d", &a[i][j]);

    printf("Enter second matrix:\n");

    for(i = 0; i < r; i++)
        for(j = 0; j < col; j++)
            scanf("%d", &b[i][j]);

    for(i = 0; i < r; i++)
        for(j = 0; j < col; j++)
            c[i][j] = a[i][j] + b[i][j];

    printf("Result:\n");

    for(i = 0; i < r; i++)
    {
        for(j = 0; j < col; j++)
            printf("%d ", c[i][j]);

        printf("\n");
    }

    return 0;
}
```

**Sample Output:**

```text
Enter rows and columns: 2 2
Enter first matrix:
1 2
3 4
Enter second matrix:
5 6
7 8
Result:
6 8
10 12
```

---

**28. Matrix Multiplication**

**C-Program:**

```c
#include <stdio.h>

int main()
{
    int a[10][10], b[10][10], c[10][10];
    int r1, c1, r2, c2, i, j, k;

    printf("Enter rows and columns of first matrix: ");
    scanf("%d %d", &r1, &c1);

    printf("Enter rows and columns of second matrix: ");
    scanf("%d %d", &r2, &c2);

    if(c1 != r2)
    {
        printf("Matrix multiplication not possible");
        return 0;
    }

    printf("Enter first matrix:\n");

    for(i = 0; i < r1; i++)
        for(j = 0; j < c1; j++)
            scanf("%d", &a[i][j]);

    printf("Enter second matrix:\n");

    for(i = 0; i < r2; i++)
        for(j = 0; j < c2; j++)
            scanf("%d", &b[i][j]);

    for(i = 0; i < r1; i++)
    {
        for(j = 0; j < c2; j++)
        {
            c[i][j] = 0;

            for(k = 0; k < c1; k++)
                c[i][j] += a[i][k] * b[k][j];
        }
    }

    printf("Result:\n");

    for(i = 0; i < r1; i++)
    {
        for(j = 0; j < c2; j++)
            printf("%d ", c[i][j]);

        printf("\n");
    }

    return 0;
}
```

**Sample Output:**

```text
Enter rows and columns of first matrix: 2 2
Enter rows and columns of second matrix: 2 2
Enter first matrix:
1 2
3 4
Enter second matrix:
5 6
7 8
Result:
19 22
43 50
```

---

**29. Find Transpose of Given Matrix**

**C-Program:**

```c
#include <stdio.h>

int main()
{
    int a[10][10], r, c, i, j;

    printf("Enter rows and columns: ");
    scanf("%d %d", &r, &c);

    printf("Enter matrix:\n");

    for(i = 0; i < r; i++)
        for(j = 0; j < c; j++)
            scanf("%d", &a[i][j]);

    printf("Transpose:\n");

    for(i = 0; i < c; i++)
    {
        for(j = 0; j < r; j++)
            printf("%d ", a[j][i]);

        printf("\n");
    }

    return 0;
}
```

**Sample Output:**

```text
Enter rows and columns: 2 3
Enter matrix:
1 2 3
4 5 6
Transpose:
1 4
2 5
3 6
```

---

**30. Find Sum of Diagonal Elements of Given Matrix**

**C-Program:**

```c
#include <stdio.h>

int main()
{
    int a[10][10], n, i, j, sum = 0;

    printf("Enter size of matrix: ");
    scanf("%d", &n);

    printf("Enter matrix:\n");

    for(i = 0; i < n; i++)
        for(j = 0; j < n; j++)
            scanf("%d", &a[i][j]);

    for(i = 0; i < n; i++)
        sum += a[i][i];

    printf("Sum of diagonal elements = %d", sum);

    return 0;
}
```

**Sample Output:**

```text
Enter size of matrix: 3
Enter matrix:
1 2 3
4 5 6
7 8 9
Sum of diagonal elements = 15
```

---

**31. Find Length of a String Without Using Built-in Function**

**C-Program:**

```c
#include <stdio.h>

int main()
{
    char str[100];
    int i = 0;

    printf("Enter a string: ");
    scanf(" %[^\n]", str);

    while(str[i] != '\0')
        i++;

    printf("Number of characters = %d", i);

    return 0;
}
```

**Sample Output:**

```text
Enter a string: Hello World
Number of characters = 11
```

---

**32. Arrange Given Set of Names in Alphabetical Order**

**C-Program:**

```c
#include <stdio.h>
#include <string.h>

int main()
{
    char name[10][50], temp[50];
    int n, i, j;

    printf("Enter number of names: ");
    scanf("%d", &n);

    printf("Enter names:\n");

    for(i = 0; i < n; i++)
        scanf("%s", name[i]);

    for(i = 0; i < n - 1; i++)
    {
        for(j = i + 1; j < n; j++)
        {
            if(strcmp(name[i], name[j]) > 0)
            {
                strcpy(temp, name[i]);
                strcpy(name[i], name[j]);
                strcpy(name[j], temp);
            }
        }
    }

    printf("Alphabetical order:\n");

    for(i = 0; i < n; i++)
        printf("%s\n", name[i]);

    return 0;
}
```

**Sample Output:**

```text
Enter number of names: 4
Ravi
Arun
Kumar
Bala
Alphabetical order:
Arun
Bala
Kumar
Ravi
```

---

**33. Check Palindrome or Not**

**C-Program:**

```c
#include <stdio.h>
#include <string.h>

int main()
{
    char str[100];
    int i, len, flag = 0;

    printf("Enter a string: ");
    scanf("%s", str);

    len = strlen(str);

    for(i = 0; i < len / 2; i++)
    {
        if(str[i] != str[len - i - 1])
        {
            flag = 1;
            break;
        }
    }

    if(flag == 0)
        printf("Palindrome");
    else
        printf("Not a palindrome");

    return 0;
}
```

**Sample Output:**

```text
Enter a string: madam
Palindrome
```

---

**34. Count Vowels, Consonants and Special Characters in Given Text**

**C-Program:**

```c
#include <stdio.h>

int main()
{
    char str[200];
    int i, vowels = 0, consonants = 0, special = 0;

    printf("Enter a string: ");
    scanf(" %[^\n]", str);

    for(i = 0; str[i] != '\0'; i++)
    {
        if((str[i] >= 'a' && str[i] <= 'z') ||
           (str[i] >= 'A' && str[i] <= 'Z'))
        {
            if(str[i] == 'a' || str[i] == 'e' ||
               str[i] == 'i' || str[i] == 'o' ||
               str[i] == 'u' || str[i] == 'A' ||
               str[i] == 'E' || str[i] == 'I' ||
               str[i] == 'O' || str[i] == 'U')
                vowels++;
            else
                consonants++;
        }
        else if(str[i] != ' ')
        {
            special++;
        }
    }

    printf("Vowels = %d\n", vowels);
    printf("Consonants = %d\n", consonants);
    printf("Special characters = %d", special);

    return 0;
}
```

**Sample Output:**

```text
Enter a string: Hello@123
Vowels = 2
Consonants = 3
Special characters = 4
```

---

**35. Convert All Lowercase into Uppercase Without Built-in Function**

**C-Program:**

```c
#include <stdio.h>

int main()
{
    char str[100];
    int i;

    printf("Enter a string: ");
    scanf(" %[^\n]", str);

    for(i = 0; str[i] != '\0'; i++)
    {
        if(str[i] >= 'a' && str[i] <= 'z')
            str[i] = str[i] - 32;
    }

    printf("Uppercase string = %s", str);

    return 0;
}
```

**Sample Output:**

```text
Enter a string: hello world
Uppercase string = HELLO WORLD
```

---

**36. Read 5 Students' Details and Print the Result**

**C-Program:**

```c
#include <stdio.h>

struct Student
{
    int regno;
    char name[50];
    char department[50];
    int mark[5];
    int total;
    float average;
};

int main()
{
    struct Student s[5];
    int i, j;

    for(i = 0; i < 5; i++)
    {
        printf("\nEnter details of student %d\n", i + 1);

        printf("Register No: ");
        scanf("%d", &s[i].regno);

        printf("Name: ");
        scanf("%s", s[i].name);

        printf("Department: ");
        scanf("%s", s[i].department);

        s[i].total = 0;

        printf("Enter 5 subject marks:\n");

        for(j = 0; j < 5; j++)
        {
            scanf("%d", &s[i].mark[j]);
            s[i].total += s[i].mark[j];
        }

        s[i].average = s[i].total / 5.0;
    }

    printf("\n----- STUDENT RESULT -----\n");

    for(i = 0; i < 5; i++)
    {
        printf("\nRegister No: %d", s[i].regno);
        printf("\nName: %s", s[i].name);
        printf("\nDepartment: %s", s[i].department);
        printf("\nTotal = %d", s[i].total);
        printf("\nAverage = %.2f", s[i].average);

        if(s[i].average >= 50)
            printf("\nResult: PASS\n");
        else
            printf("\nResult: FAIL\n");
    }

    return 0;
}
```

**Sample Output:**

```text
Enter details of student 1
Register No: 101
Name: Arun
Department: CSE
Enter 5 subject marks:
80 75 90 85 70

----- STUDENT RESULT -----

Register No: 101
Name: Arun
Department: CSE
Total = 400
Average = 80.00
Result: PASS
```

---

**37. Define a Structure Student and Display the Details of the Student**

**C-Program:**

```c
#include <stdio.h>

struct Student
{
    int rollno;
    char name[50];
    float marks;
};

int main()
{
    struct Student s;

    printf("Enter Roll Number: ");
    scanf("%d", &s.rollno);

    printf("Enter Name: ");
    scanf("%s", s.name);

    printf("Enter Marks: ");
    scanf("%f", &s.marks);

    printf("\nStudent Details\n");
    printf("Roll Number = %d\n", s.rollno);
    printf("Name = %s\n", s.name);
    printf("Marks = %.2f", s.marks);

    return 0;
}
```

**Sample Output:**

```text
Enter Roll Number: 101
Enter Name: Arun
Enter Marks: 85

Student Details
Roll Number = 101
Name = Arun
Marks = 85.00
```

---

**38. Define a Structure Employee and Display the Details of Three Employees**

**C-Program:**

```c
#include <stdio.h>

struct Employee
{
    int id;
    char name[50];
    float salary;
};

int main()
{
    struct Employee e[3];
    int i;

    for(i = 0; i < 3; i++)
    {
        printf("\nEnter details of Employee %d\n", i + 1);

        printf("Employee ID: ");
        scanf("%d", &e[i].id);

        printf("Name: ");
        scanf("%s", e[i].name);

        printf("Salary: ");
        scanf("%f", &e[i].salary);
    }

    printf("\nEmployee Details\n");

    for(i = 0; i < 3; i++)
    {
        printf("\nEmployee %d\n", i + 1);
        printf("ID = %d\n", e[i].id);
        printf("Name = %s\n", e[i].name);
        printf("Salary = %.2f\n", e[i].salary);
    }

    return 0;
}
```

**Sample Output:**

```text
Enter details of Employee 1
Employee ID: 101
Name: Arun
Salary: 25000

Enter details of Employee 2
Employee ID: 102
Name: Bala
Salary: 30000

Enter details of Employee 3
Employee ID: 103
Name: Kumar
Salary: 28000

Employee Details

Employee 1
ID = 101
Name = Arun
Salary = 25000.00

Employee 2
ID = 102
Name = Bala
Salary = 30000.00

Employee 3
ID = 103
Name = Kumar
Salary = 28000.00
```

---

**39. Define a Structure Book and Display the Book Information Entered by the User**

**C-Program:**

```c
#include <stdio.h>

struct Book
{
    int id;
    char title[50];
    char author[50];
    float price;
};

int main()
{
    struct Book b;

    printf("Enter Book ID: ");
    scanf("%d", &b.id);

    printf("Enter Book Title: ");
    scanf("%s", b.title);

    printf("Enter Author Name: ");
    scanf("%s", b.author);

    printf("Enter Price: ");
    scanf("%f", &b.price);

    printf("\nBook Information\n");
    printf("Book ID = %d\n", b.id);
    printf("Title = %s\n", b.title);
    printf("Author = %s\n", b.author);
    printf("Price = %.2f", b.price);

    return 0;
}
```

**Sample Output:**

```text
Enter Book ID: 101
Enter Book Title: CProgramming
Enter Author Name: Dennis
Enter Price: 450

Book Information
Book ID = 101
Title = CProgramming
Author = Dennis
Price = 450.00
```

---

**40. Define a Structure Product and Calculate the Total Cost Using Quantity and Unit Price**

**C-Program:**

```c
#include <stdio.h>

struct Product
{
    int id;
    char name[50];
    int quantity;
    float unitprice;
    float totalcost;
};

int main()
{
    struct Product p;

    printf("Enter Product ID: ");
    scanf("%d", &p.id);

    printf("Enter Product Name: ");
    scanf("%s", p.name);

    printf("Enter Quantity: ");
    scanf("%d", &p.quantity);

    printf("Enter Unit Price: ");
    scanf("%f", &p.unitprice);

    p.totalcost = p.quantity * p.unitprice;

    printf("\nProduct Details\n");
    printf("Product ID = %d\n", p.id);
    printf("Product Name = %s\n", p.name);
    printf("Quantity = %d\n", p.quantity);
    printf("Unit Price = %.2f\n", p.unitprice);
    printf("Total Cost = %.2f", p.totalcost);

    return 0;
}
```

**Sample Output:**

```text
Enter Product ID: 101
Enter Product Name: Pen
Enter Quantity: 10
Enter Unit Price: 20

Product Details
Product ID = 101
Product Name = Pen
Quantity = 10
Unit Price = 20.00
Total Cost = 200.00
```

---

**41. Define a Structure Rectangle and Calculate Its Area and Perimeter**

**C-Program:**

```c
#include <stdio.h>

struct Rectangle
{
    float length;
    float breadth;
    float area;
    float perimeter;
};

int main()
{
    struct Rectangle r;

    printf("Enter Length: ");
    scanf("%f", &r.length);

    printf("Enter Breadth: ");
    scanf("%f", &r.breadth);

    r.area = r.length * r.breadth;
    r.perimeter = 2 * (r.length + r.breadth);

    printf("\nRectangle Details\n");
    printf("Length = %.2f\n", r.length);
    printf("Breadth = %.2f\n", r.breadth);
    printf("Area = %.2f\n", r.area);
    printf("Perimeter = %.2f", r.perimeter);

    return 0;
}
```

**Sample Output:**

```text
Enter Length: 10
Enter Breadth: 5

Rectangle Details
Length = 10.00
Breadth = 5.00
Area = 50.00
Perimeter = 30.00
```
