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

LOOP PATTERN 
closed square 
#include <stdio.h>
int main() {
    for (int i = 0; i < 5; i++) {
        for (int j = 0; j < 5; j++) {
            printf("* ");
        }
        printf("\n");
    }
    return 0;
}

closed rectangle 
#include <stdio.h>
int main() {
    for (int i = 0; i < 3; i++) {
        for (int j = 0; j < 6; j++) {
            printf("* ");
        }
        printf("\n");
    }
    return 0;
} 

Increasing Star Triangle (Right angle triangle)
#include <stdio.h>
int main() {
    for (int i = 1; i <= 5; i++) {
        for (int j = 1; j <= i; j++) {
            printf("* ");
        }
        printf("\n");
    }
    return 0;
} 

Decreasing Star Triangle (Inverse of Right angle triangle)
#include <stdio.h>
int main() {
    for (int i = 5; i >= 1; i--) {
        for (int j = 1; j <= i; j++) {
            printf("* ");
        }
        printf("\n");
    }
    return 0;
} 

Right-Aligned Triangle
#include <stdio.h>
int main() {
    for (int i = 1; i <= 5; i++) {
        for (int j = 1; j <= 5 - i; j++) {
            printf("  "); 
        }
        for (int k = 1; k <= i; k++) {
            printf("* ");
        }
        printf("\n");
    }
    return 0;
} 

Inverse Right-Aligned Triangle 
#include <stdio.h>
int main() {
    for (int i = 5; i >= 1; i--) {
        for (int j = 1; j <= 5 - i; j++) {
            printf("  ");
        }
        for (int k = 1; k <= i; k++) {
            printf("* ");
        }
        printf("\n");
    }
    return 0;
} 

Hollow Square 
#include <stdio.h>
int main() {
    for (int i = 1; i <= 5; i++) {
        for (int j = 1; j <= 5; j++) {
            if (i == 1 || i == 5 || j == 1 || j == 5) {
                printf("* ");
            } 
            else {
                printf("  "); 
            }
        }
        printf("\n");
    }
    return 0;
}  

Hollow Right Triangle
#include <stdio.h>
int main() {
    for (int i = 1; i <= 5; i++) {
        for (int j = 1; j <= i; j++) {
            if (j == 1 || i == 5 || j == i) {
                printf("* ");
            } 
            else {
                printf("  ");
            }
        }
        printf("\n");
    }
    return 0;
} 

Hollow Inverted Right Triangle
#include <stdio.h>
int main() {
    for (int i = 5; i >= 1; i--) {
        for (int j = 1; j <= i; j++) {
            if (i == 5 || j == 1 || j == i) {
                printf("* ");
            } 
            else {
                printf("  "); 
            }
        }
        printf("\n");
    }
    return 0;
} 

Hollow Pyramid 
#include <stdio.h>
int main() {
    for (int i = 1; i <= 5; i++) {
        for (int j = 1; j <= 5 - i; j++) {
            printf(" ");
        }
        for (int k = 1; k <= (2 * i - 1); k++) {
            if (k == 1 || k == (2 * i - 1) || i == 5) {
                printf("*");
            } 
            else {
                printf(" ");
            }
        }
        printf("\n");
    }
    return 0;
} 

Hollow Inverted Pyramid 
#include <stdio.h>
int main() {
    for (int i = 5; i >= 1; i--) {
        for (int j = 1; j <= 5 - i; j++) {
            printf(" ");
        }
        for (int k = 1; k <= (2 * i - 1); k++) {
            if (i == 5 || k == 1 || k == (2 * i - 1)) {
                printf("*");
            } 
            else {
                printf(" ");
            }
        }
        printf("\n");
    }
    return 0;
} 

Hollow Diamond 
#include <stdio.h>
int main() {
    for (int i = 1; i <= 5; i++) {
        for (int j = 1; j <= 5 - i; j++) {
            printf(" ");
        }
        for (int k = 1; k <= (2 * i - 1); k++) {
            if (k == 1 || k == (2 * i - 1)) {
                printf("*");
            } else {
                printf(" ");
            }
        }
        printf("\n");
    }
    for (int i = 4; i >= 1; i--) {
        for (int j = 1; j <= 5 - i; j++) {
            printf(" ");
        }
        for (int k = 1; k <= (2 * i - 1); k++) {
            if (k == 1 || k == (2 * i - 1)) {
                printf("*");
            } else {
                printf(" ");
            }
        }
        printf("\n");
    }
    return 0;
}
