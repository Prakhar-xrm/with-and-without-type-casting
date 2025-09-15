#include <stdio.h>
int main(){
  
  int num1;
  int num2;
  int without;
  float with;
  
  scanf("%d", &num1);
  scanf("%d", &num2);
  
  without = num1 / num2;
  with = (float)num1 / num2;
  
  printf("Without casting: %d / %d = %.2f\n", num1, num2, (float)without);
  printf("With casting: %d / %d = %.2f", num1, num2, with);
  
  return 0;
}
