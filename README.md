# CSA0234
C programming for adding two numbers
#include <stdio.h>

int main() {
    int a, b, sum;

    printf("Enter 1,2: ");
    scanf("%d,%d", &a, &b);

    sum = a + b;

    printf("Sum = %d", sum);

    return 0;
}
C programming to find the area of square
#include <stdio.h>

int main() {
    int side = 4;
    int area;

    area = side * side;

    printf("Side of square = %d\n", side);
    printf("Area of square = %d\n", area);

    return 0;
}
C programming to add two float variable 
#include <stdio.h>

int main() {
    float a = 4.5;
    float b = 3.5;
    float sum;

    sum = a + b;

    printf("Sum = %.2f", sum);

    return 0;
}
C programming to find the area of the circle
#include <stdio.h>

int main() {
    float radius = 5;
    float area;
    float pi = 3.14;

    area = pi * radius * radius;

    printf("Radius of circle = %.2f\n", radius);
    printf("Area of circle = %.2f\n", area);

    return 0;
}
C programming to find the area of the rectangle 
#include <stdio.h>

int main() {
    int length = 5;
    int breadth = 4;
    int area;

    area = length * breadth;

    printf("Length = %d\n", length);
    printf("Breadth = %d\n", breadth);
    printf("Area of Rectangle = %d\n", area);

    return 0;
}
C programming to find the perimeter of the rectangle
#include <stdio.h>

int main() {
    int length = 5;
    int breadth = 4;
    int perimeter;

    perimeter = 2 * (length + breadth);

    printf("Length = %d\n", length);
    printf("Breadth = %d\n", breadth);
    printf("Perimeter of Rectangle = %d\n", perimeter);

    return 0;
}
c programming to find the area of the triangle
#include <stdio.h>

int main() {
    float base = 6;
    float height = 4;
    float area;

    area = 0.5 * base * height;

    printf("Base = %.2f\n", base);
    printf("Height = %.2f\n", height);
    printf("Area of Triangle = %.2f\n", area);

    return 0;
}
c programming to convert celcius into fahrenheit
#include <stdio.h>

int main() {
    float celsius = 40;
    float fahrenheit;

    fahrenheit = (celsius * 9 / 5) + 32;

    printf("Celsius = %.2f\n", celsius);
    printf("Fahrenheit = %.2f\n", fahrenheit);

    return 0;
}
c programming to convert fahrenheit to celcius
#include <stdio.h>

int main() {
    float fahrenheit = 104;
    float celsius;

    celsius = (fahrenheit - 32) * 5 / 9;

    printf("Fahrenheit = %.2f\n", fahrenheit);
    printf("Celsius = %.2f\n", celsius);

    return 0;
}
c programming to find the simple interest
#include <stdio.h>

int main() {
    float principal = 2000;
    float rate = 5;
    float time = 3;
    float simple_interest;

    simple_interest = (principal * rate * time) / 100;

    printf("Principal = %.2f\n", principal);
    printf("Rate = %.2f\n", rate);
    printf("Time = %.2f years\n", time);
    printf("Simple Interest = %.2f\n", simple_interest);

    return 0;
}
c programming to change into hexa decimal 
#include <stdio.h>

int main() {
    int decimal = 100;

    printf("Decimal number = %d\n", decimal);
    printf("Hexadecimal number = %X\n", decimal);

    return 0;
}
c programming to change into decimal number
#include <stdio.h>

int main() {
    int hex = 0x64;

    printf("Hexadecimal number = %X\n", hex);
    printf("Decimal number = %d\n", hex);

    return 0;
}
c programming for quotient and remainder
int main() {
    int dividend = 20;
    int divisor = 3;
    int quotient, remainder;

    quotient = dividend / divisor;
    remainder = dividend % divisor;

    printf("Dividend = %d\n", dividend);
    printf("Divisor = %d\n", divisor);
    printf("Quotient = %d\n", quotient);
    printf("Remainder = %d\n", remainder);

    return 0;
}





