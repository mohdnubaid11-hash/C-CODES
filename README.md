# C- code 
to find largest number 
#include <stdio.h>
int main() {
    int num1, num2, num3;
    int largest;
    printf("Enter three numbers: ");
    scanf("%d %d %d", &num1, &num2, &num3);
    largest = num1;
    if (num2 > largest) {
        largest = num2;  
    }
    if (num3 > largest) {
        largest = num3;
    }
    printf("The largest number is: %d\n", largest);
    return 0;
}

to find smallest number 
#include <stdio.h>
int main() {
    int num1, num2, num3;
    int smallest;
    printf("Enter three numbers: ");
    scanf("%d %d %d", &num1, &num2, &num3);
        smallest = num1;
    if (num2 < smallest) {
        smallest = num2; 
    }
    if (num3 < smallest) {
        smallest = num3; 
    }
    printf("The smallest number is: %d\n", smallest);
    return 0;
}

to find even odd 
#include <stdio.h>
int main() {
    int number;
    printf("Enter a number: ");
    scanf("%d", &number);
    if (number % 2 == 0) {
        printf("%d is an EVEN number.\n", number);
    } 
    else {
        printf("%d is an ODD number.\n", number);
    }
    return 0;
}

divisibilty checker 
#include <stdio.h>
int main() {
    int number;
    printf("Enter a number: ");
    scanf("%d", &number);
    if (number % 5 == 0) {
        printf("%d can be divided by 5.\n", number);
    } 
    else {
        printf("%d cannot be divided by 5.\n", number);
    }
    return 0;
}

 to check voting eligibility 
 #include <stdio.h>
int main() {
    int age;
    printf("Enter your age: ");
    scanf("%d", &age);
    if (age >= 18) {
        printf("You are eligible to vote!\n");
    } 
    else {
        printf("You are NOT eligible to vote yet.\n");
    }
    return 0;
} 

for electricity bill
#include <stdio.h>
int main() {
    int units;
    int total_bill;
    printf("Enter the total units consumed: ");
    scanf("%d", &units);
    if (units <= 100) {
        total_bill = units * 2;
    } 
    else if (units <= 200) {
        total_bill = units * 3;
    } 
    else if (units <= 300) {
        total_bill = units * 5;
    } 
    else {
        total_bill = units * 7;
    }
    printf("Your total electricity bill is: ₹%d\n", total_bill);
    return 0;
} 

to find profit and loss 
#include <stdio.h>
int main() {
    int cost_price, selling_price;
    int amount
    printf("Enter Cost Price: ");
    scanf("%d", &cost_price);
    printf("Enter Selling Price: ");
    scanf("%d", &selling_price);
    if (selling_price > cost_price) {
        amount = selling_price - cost_price;
        printf("Profit of: %d\n", amount);
    } 
    else if (cost_price > selling_price) {
        amount = cost_price - selling_price;
        printf("Loss of: %d\n", amount);
    } 
    else {
        printf("No Profit No Loss\n");
    }
    return 0;
} 

a simple calculator 
#include <stdio.h>
int main() {
    char op;
    int num1, num2;
    printf("Enter operator (+, -, *, /): ");
    scanf(" %c", &op); 
    printf("Enter two numbers: ");
    scanf("%d %d", &num1, &num2);
    if (op == '+') {
        printf("Result: %d\n", num1 + num2);
    }
    if (op == '-') {
        printf("Result: %d\n", num1 - num2);
    }
    if (op == '*') {
        printf("Result: %d\n", num1 * num2);
    }
    if (op == '/') {
        printf("Result: %d\n", num1 / num2);
    }
    return 0;
} 

to join college 
#include <stdio.h>
int main() {
    int math, physics, chemistry;
    printf("Enter marks for Math, Physics, Chemistry: ");
    scanf("%d %d %d", &math, &physics, &chemistry);
    if (math >= 60 && physics >= 50 && chemistry >= 50) {
        printf("You are ELIGIBLE for admission.\n");
    } 
    else {
        printf("You are NOT ELIGIBLE for admission.\n");
    }
    return 0;
} 
