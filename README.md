#include <stdio.h>
int main() {
    int i;
    printf("Demonstration of continue:\n");
    for(i = 1; i <= 10; i++) {
        if(i == 5) {
             }
        printf("%d ", i);
    }
    printf("\n\nDemonstration of break:\n");
    for(i = 1; i <= 10; i++) {
        if(i == 5) {
            break;   
        }
        printf("%d ", i);
    }
    return 0;
}
