// ATIVIDADE 06 //
#include<stdio.h>
#include<math.h>

main(){
	int numero, resultado;
	
	printf("Digite um número:");
	scanf("%d", &numero);
	
	resultado = (numero % 2);
	
	if(resultado == 0){
		printf("é par mano");
	}else{
		printf("é impar mano");
	}
}

// ATIVIDADE 07 //
#include<stdio.h>
#include<math.h>

main(){
	float prova1, prova2, prova3, media;
	
	printf("digite as notas das tres provas:");
	scanf("\n%f", &prova1);
	scanf("\n%f", &prova2);
	scanf("\n%f", &prova3);
	
	media = (prova1+prova2+(prova3*2))/4;
	
	if(media >= 7){
		printf("aprovado, q genio");
	}else{
		printf("reprovado, q burro");
	}
}

// ATIVIDADE 08 //
#include<stdio.h>
#include<math.h>

main(){
	int idade, tempoTrab;
	
	printf("Qual a tua idade?:\n");
	scanf("%d", &idade);
	
	printf("A quanto tempo voce trabalha?:\n");
	scanf("%d", &tempoTrab);

	if((idade >= 65) || (tempoTrab >= 30)){
		printf("pode aposentar velho");
	}
	else if((idade >= 60) && (tempoTrab >= 25)){
		printf("pode aposentar velho");
	}
	else{
		printf("falta pouco pra jogar no INSS");
	}
}

// ATIVIDADE 09 //
#include<stdio.h>
#include<math.h>

main(){
	float salarioAtual, reajuste, salarioFinal;
	int tempServ, bonus;
	
	printf("Qual o seu salário atual?\n");
	scanf("%f", &salarioAtual);
	
	printf("Quanto tempo voce trabalha?(em anos)\n");
	scanf("%d", &tempServ);

	if((salarioAtual <= 500)){
		reajuste = (salarioAtual*25)/100;
	}else if((salarioAtual > 500) && (salarioAtual <= 1000)){
		reajuste = (salarioAtual*20)/100;
	}else if((salarioAtual > 1000) && (salarioAtual <= 1500)){
		reajuste = (salarioAtual*15)/100;
	}else if((salarioAtual > 1500) && (salarioAtual <= 2000)){
		reajuste = (salarioAtual*10)/100;
	}else if(salarioAtual > 2000){
		reajuste = (salarioAtual*0)/100;
	}
	if(tempServ < 1){
		bonus = 0;
	}
	else if((tempServ > 1) && (tempServ <= 3)){
		bonus = 100;
	}else if((tempServ > 3) && (tempServ <= 6)){
		bonus = 200;
	}else if((tempServ > 6) && (tempServ <= 10)){
		bonus = 300;
	}else if(tempServ > 10){
		bonus = 500;
	}
	salarioFinal = salarioAtual + reajuste + bonus;
	
	printf("O seu salario será de %.2f", salarioFinal);
}

// ATIVIDADE 10 //
#include<stdio.h>
#include<math.h>

main(){
	int valorA, valorB, valorC, delta, x1, x2;
	
	printf("Digite o valor de A:\n");
	scanf("%d", &valorA);
	
	printf("Digite o valor de B:\n");
	scanf("%d", &valorB);
	
	printf("Digite o valor de C:\n");
	scanf("%d", &valorC);
	
	delta = (pow(valorB,2)) - (4*valorA*valorC);

	if(delta < 0){
		printf("Não existe raiz");
	}else if(delta == 0){
		x1 = (valorB + sqrt(delta)) / (2*valorA);
		printf("A raiz é %d", x1);
	}else if(delta > 0){
		x1 = (valorB + sqrt(delta)) / (2*valorA);
		x2 = (valorB - sqrt(delta)) / (2*valorA);
		printf("As raizes são %d e %d", x1, x2);
	}
}
