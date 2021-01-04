#include <stdio.h>
#include <stdlib.h>
#include <string.h>
#include <math.h>

int main(){
    int ticket, casos, bilhete, vet[10001],clones,a;


    scanf("%d %d", &ticket, &casos);
    while(ticket && casos){
        for(a=1;a<=ticket;a++){
            vet[a] = 0;
        }
        for(a=0;a<casos;a++){
            scanf("%d", &bilhete);
            vet[bilhete]++;
        }
        clones = 0;
        for(a=1;a<=ticket;a++){
            if(vet[a] > 1){
                clones++;
            }
        }

        printf("%d\n", clones);

        scanf("%d %d", &ticket, &casos);
    }
    return 0;
}
