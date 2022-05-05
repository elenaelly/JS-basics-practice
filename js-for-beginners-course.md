Решение задачек с курса Javascript for Beginners на Stepik

Task 51

In this task, you need to write in the specified place the code that will assign the variable "x" the name of the digit transferred to the variable "a". The number in the variable "a" will be transferred randomly and can be in the range from 0 to 9, the name should be written in English with a capital letter - "Zero", "One", "Two", etc.
Sample Input:
3
 
Sample Output:
Three

Answer:

```
function testCase(a) {
    var x="";
    switch (a){
            case x=0: a="Zero"
        break;
            case x=1: a="One"
        break;
            case x=2: a="Two"
        break;
            case x=3: a="Three"
        break;
            case x=4: a="Four"
        break;
            case x=5: a="Five"
        break;
            case x=6: a="Six"
        break;
            case x=7: a="Seven"
        break;
            case x=8: a="Eight"
        break;
            case x=9: a="Nine"
        break;
    }
    return a;
}
```

Task 52

In this task, you need to calculate the factorial for the number passed to our function and return it doubled value. Just in case, we recall that the factorial of a is the product of all integers from 1 to a, for example, if a = 5, then the factorial a is equal to
1 * 2 * 3 * 4 * 5
Sample Input 1:
5
Sample Output 1:
240
Sample Input 2:
1
Sample Output 2:
2

Answer:

```
function testFactorial(a) {
   var x = 1;
  for (var i = 2; i <= a; i++)
    x *= i;
  return x*2;
}
```

Task 53

In this task, two lines are passed to our testStr function. You need to return a string from the function that will include both of these lines, converting all the letters to lowercase in the first line, and to capital letters in the second.
Sample Input:

Hello World!
Sample Output:

helloWORLD!

My answer:

```
function testStr(a, b) {
    let first = 'hello';
    let second = 'world';
    return (first.toLowerCase()+ second.toUpperCase())
}
```

