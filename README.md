batalha_naval
=============

Projeto Final para Algoritmos

Para Fazer:
 - Tabuleiro
 - Barcos
 - Posiçao dos barcos
 - Tudo o resto

Codigo para por o tabuleiro, tentei criar um ficheiro novo para por isto mas nao deixou xD (tens de adicionar a biblioteca conio, procura na net onde sacar, basta pores o ficheiro .c e .h na pasta "CodeBlocks\MinGW\include" e o .lib em "CodeBlocks\MinGW\lib")

#include <stdio.h>
#include <stdlib.h>
#include <conio.c>


void tabuleiro(){

    int c,l,n=10;

    textcolor(15); // poem a cor do texto em branco brilhante
    printf("      -------------------------------------------\n");
    for(l=0; l<10; l++){

            printf("  %2.d |",n);
        for(c=0;c<10;c++){
            textcolor(9); // poem a cor do texto em azul claro
            printf("   ~");
        }
        textcolor(15); // poem a cor do texto em branco brilhante
        printf("   |");
        printf("\n");
        n--;
    }
    printf("      -------------------------------------------\n");
    printf("         A   B   C   D   E   F   G   H   I   J   \n");
    textcolor(7); // poem a cor do texto em branco
}


void main (void){

    char tabuleiro2[11][11];
    printf("\n");
    tabuleiro();

}
