# Exercicio15

#include <stdlib.h>
#include <stdio.h>
#include <string.h>

int main()
{
    system("color 0b");
    char nome[30];
    int i, tam;

    printf("Digite um nome ");
    gets(nome);
    tam=strlen(nome);
    for (i=tam; i>=0; i--)
    {
        printf("%s\n",&nome[i]);
    }

 return 0;
 }
