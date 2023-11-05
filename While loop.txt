#include <stdio.h>

int main() {
  int num, i, fact = 1;

  printf("Enter a number: ");
  scanf("%d", &num);

  i = num;
  while (i >= 1) {
    fact = fact * i;
    i--;
  }

  printf("The factorial of %d is %d.\n", num, fact);

  return 0;
}