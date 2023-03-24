#include<stdio.h>
#include<conio.h>
#include<stdlib.h>
#include<string.h>


struct members{
    char name[20], phone_num[10],member_status[20];
    int member_ID,age;
    int hours_spent;
    int opt;
    }m[200];
 
int main(){
    
int n,i;
int normal_amt;
int option;
int discount_price, discount_amt;

printf("Enter number of people: ");
scanf("%d",&n);

for(i=0;i<n;i++){
    printf("NAME :");
    scanf("%s",m[i].name);
    
    printf("MEMBER ID :");
    scanf("%d",&m[i].member_ID);
    
    printf("AGE :");
    scanf("%d",&m[i].age);
    
    printf("PHONE NUMBER :");
    scanf("%s",m[i].phone_num);
    
    printf("MEMBERSHIP STATUS :");
    printf("1.GOLD \t 2.SILVER \t 3.PLATINUM \t 4.NONE \n");
    
    scanf("%d %s",&m[i].opt,m[i].member_status);
    
    printf("Enter hours spent: ");
    scanf("%d",&m[i].hours_spent);
    
    
}

for(i=0;i<n;i++){
    printf("---------------------------\n");
    printf("INDEX : %d\n",i+1);
    printf("NAME : %s\n",m[i].name);
    printf("MEMBER ID : %d\n",m[i].member_ID);
    printf("AGE : %d\n",m[i].age);
    printf("PHONE NUMBER : %s\n",m[i].phone_num);
    printf("MEMBERSHIP STATUS : %s\n",m[i].member_status);
    printf("HOURS SPENT : %d\n",m[i].hours_spent);
    
    switch(m[i].opt){
    case 1:
        discount_amt=5*(1000*m[i].hours_spent)/100;
        discount_price=((1000*m[i].hours_spent)-discount_amt);
        
        printf("AMOUNT :%d\n",discount_price);
        break;
    
    case 2:
        discount_amt=20*(1000*m[i].hours_spent)/100;
        discount_price=((1000*m[i].hours_spent)-discount_amt);
        
        printf("AMOUNT :%d\n",discount_price);
        break;
    
    case 3:
        discount_amt=30*(1000*m[i].hours_spent)/100;
        discount_price=((1000*m[i].hours_spent)-discount_amt);
        
        printf("AMOUNT :%d\n",discount_price);
        break;
    
    case 4:
        
        normal_amt=1000*m[i].hours_spent;
        printf("AMOUNT :%d\n",normal_amt);
        break;
    }
}

getch();
return 0;


}
