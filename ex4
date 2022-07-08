#include<stdio.h>
#include<stdlib.h>
#include<time.h>
char  name[100];
int head=0,tail=0,num;
int main () {
  srand(time(NULL));
  printf ("Who are you?\n");
  scanf ("%s",&name);
  printf ("Hallo, %s!\n",name);
  printf ("Tossing a coin...\n");
  for (int i=1;i<=3;i++){
    printf("Round %d: ",i);
    if ((num=rand()%2) ==0){
      printf("Heads\n");
      head++;
    } else {
      printf ("Tails\n");
      tail++;
    }
  }
  printf ("Heads: %d, Tails: %d\n",head,tail);
  if (head > tail) printf ("%s won!\n",name);
  else printf ("%s lost!\n",name);
  return 0;
}
