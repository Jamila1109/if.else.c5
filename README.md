 Check if number is multiple of 3 

#include <stdio.h>
int main() {
    int num;
    printf("Enter a number: ");
    scanf("%d", &num);
    
    if (num % 3 == 0) {
        printf("The number is a multiple of 3.\n");
    } else {
        printf("The number is not a multiple of 3.\n");
    }
    return 0;
}
