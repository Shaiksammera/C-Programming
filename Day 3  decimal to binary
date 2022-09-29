#include<stdio.h>
long tobinary(int);
int main(){
   long bno;
   int dno;
   printf(" Enter any decimal number : ");
   scanf("%d",&dno);
   bno = tobinary(dno);
   printf("\n The Binary value is : %ld\n\n",bno);
   return 0;
}
long tobinary(int dno){
   long bno=0,rem,f=1;
   while(dno != 0){
      rem = dno % 2;
      bno = bno + rem * f;
      f = f * 10;
      dno = dno / 2;
   }
   return bno;;
}
