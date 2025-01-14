# wholenumber-average
A C program that will ask the user to enter 3 whole numbers. The program will calculate the average of these three numbers.


    #include <stdio.h> 
    int main (void)

    {
    int a = 0;
    int b = 0;
    int c = 0;
    float average = 0 
    printf("Please enter the first number: ");
    scanf("%d", &a);
    printf("Please enter the second number: ");
    scanf("%d", &b);
    printf("Please enter the third number: ");
    scanf("%d", &c);

    average = (a + b + c) / 3.0;

    printf("The average of the three numbers is %.2f\n", average);
    return 0;


    }
