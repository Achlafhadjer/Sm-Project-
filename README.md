# Sm-Project-

#include <stdio.h>
#include <stdlib.h>

/* run this program using the console pauser or add your own getch, system("pause") or input loop */

int main(int argc, char *argv[]) {


#include<stdio.h>
int main()
{
int M;/*M:The number that determines which base to convert to*/

int N;/*N:The number being converted*/

int k;/*Help value*/
int D;/*Help value*/
int S;/*Help value*/
int C;/*Help value*/
int H;/*H:In order to find out whether the digits of a number are equal5 ? 6 ? 7 ? 8 ? 9 */


int j;/*Help value*/
int L;/*Help value*/
int T;/*Help value*/

Printf("Enter a number\n ");
scanf("%d",&M);
   if (M=1){
Ptintf("10 To 7");
}
else if (M=2){
Printf("5 To 2 ");
}
else if (M!=1 || M!=2){/*M is Different 2 or 1 */
Printf("Enter a nother number");
}

switch (M ) {


    case 1:

printf("Enter a number ");
scanf("%d",&N);
k=0;
D=1;
while(N!=0){      
S=N;/*In order to keep the number entered by the user*/
S=S%7;/* In order to find the remainder of the Euclidean division */
N=N/7;/*In order to find the Euclidean quotient */

k=S*D+k;


D=D*10;/*In order to arrange the numbers that make up a number*/
}
printf("The number in base 7 %d",k);

scanf("%d",&k);

     break;
 

case 2 :
 while (T != 1){/*for T is different to 1 */


    Printf("Enter a number");
    scanf("%d",&N);
    H=0;

    j=0;
  while(N!=0){/*for N is different to 0*/
    H=N%10 ;/*In order to know the numbers that make up the number*/
    switch (H){

    case 5 ... 9 :
       L=1 ;
     default :L=0 ;
     break;
    }
    j=j + L ;/*To calculate the numbers in the number N*/
    N=N / 10 ;}/*in order to find the Euclidean quotient*/
   
    if ( j=0 ){
T=1 ;}/*This means that the number set by the user does not contain any number from 5 6 7 8 9 so the number in the system has a base of 5*/
    else T=0 ;}/*The user continues to give the number*/
    
   
   
   k=0;


   C=1;
   while (N!=0)  {
     S=N;/*In order to keep the number entered by the user*/
     D=S%2;/*In order to find the remainder of the Euclidean division */
     N=D/2;/*In order to find the Euclidean quotient */

     k=S*D+k;


     D=D*10; /*In order to arrange the numbers that make up a number*/
 
      } Printf(" the number in  base 2 %d:",k);

break;

default:
Printf(" the nmbre is !=1 or 2 \n");/*In order to enter 1 or 2 and nothing else*/


}
}
return 0;
}
