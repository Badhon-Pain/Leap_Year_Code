# Leap_Year_Code
 #include<stdio.h>
 int main ()
  {
int y;
scanf("%d",&y);
if(y%100==0 || (y%4!=0 && y%400 !=0))
printf("NO\n");
else 
printf("YES\n");





    return 0;
 }
 
