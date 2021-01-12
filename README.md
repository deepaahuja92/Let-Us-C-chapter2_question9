//# Let-Us-C-chapter2_question9
#include<stdio.h>
int main()
{
int amount,notes,sum=0;
printf("Enter amount:");
scanf("%d",&amount);
notes=amount/100;
printf("No. of notes of 100 is %d\n",notes);
amount%=100;
sum+=notes;
notes=amount/50;
printf("No. of notes of 50 is %d\n",notes);
amount%=50;
sum+=notes;
notes=amount/10;
printf("No. of notes of 10 is %d\n",notes);
amount%=10;
sum+=notes;
notes=amount/5;
printf("No. of notes of 5 is %d\n",notes);
amount%=5;
sum+=notes;
notes=amount/2;
printf("No. of notes of 2 is %d\n",notes);
amount%=2;
sum+=notes;
printf("No. of notes of 1 is %d\n",amount);
sum+=amount;
printf("Total no. of notes %d\n",sum);
return 0;
}
