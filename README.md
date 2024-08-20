# Atividade-5

#include <stdio.h>
#include <stdlib.h>

int main() {
	
    // Declaração da variável para armazenar o número
    int num1, num2, num3;
    
    printf("Digite tres numeros: \n");
    scanf("%i", &num1);
    scanf("%i", &num2);
    scanf("%i", &num3);


    // Verificar o resultado
    float media = (num1 + num2 + num3)/3;
	
	printf("A media e: %.1f", media); 
    
    return 0;
}
