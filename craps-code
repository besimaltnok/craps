/*
SDU Yazilim Kulübü Programlama
Algoritma Günleri
Besim Altınok
Seda Saz
*/
#include<stdio.h>
#include<time.h>
#include<stdlib.h>
#include<unistd.h>
 
int main(){
 
    int zar1, zar2, toplam=0, toplam1=0;
    sleep(2);
    srand(time(NULL));
    zar1 = rand()%6+1;
    zar2 = rand()%6+1;
    toplam = zar1+zar2 ;
 
    printf("Zar1 = %d\n",zar1);
    printf("Zar2 = %d\n",zar2);
    printf("Toplam = %d\n",toplam);
 
    if(toplam == 7 || toplam == 11){
        printf("You win!!");
    }
    else if((toplam == 2) || (toplam == 3) || (toplam == 12)){
        printf("You lose and you craps!!");
    }
    else{
        toplam1 = toplam ;
        do{
            toplam = 0 ;
            sleep(2);
            srand(time(NULL));
            zar1 = rand()%6+1;
            zar2 = rand()%6+1;
            toplam = zar1 + zar2 ;
            printf("Zar1 = %d\n",zar1);
            printf("Zar2 = %d\n",zar2);
            printf("Toplam = %d\n",toplam);
            if(toplam == toplam1){
                printf("You winnnnnnn\n");
                break ;
            }
 
        }while(toplam!=7);
 
        if(toplam==7)
        printf("You loseeeeeeeee\n");
 
    }
 
    return 0 ;
}
