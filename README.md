# lista2
//exercicio1_lista2;

#include <stdio.h>

int main(){
	
	int km, horas, velocidade;
	
	printf("qual a distancia em km dessa viagem?");
	scanf("%d", &km);
	
	printf("qual o tempo da viagem em horas?");
	scanf("%d", &horas);
	
	velocidade = km/horas;
	
	printf("\nSua velocidade media foi de %dkm/h\n", velocidade);
	
	if (velocidade > 110){
		printf("Voce ultrapassou o limite!");
	} else if (velocidade == 110){
		printf("Voce ficou no limite!");
	}else{
		printf("Voce nao ultrapassou o limite!");
	}
	
	return 0;
}
