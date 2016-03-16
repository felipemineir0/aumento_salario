# aumento_salario

/*5)Faça um programa que receba o salário de um funcionário e o percentual de aumento, 
	calcule e mostre o valor do aumento e o novo salário.*/
#include <stdio.h>
#include <stdlib.h>
main(){
	
  float salario, aumento, novo_salario, porc;
  
  printf("Digite o salario do funcionario: ");
  scanf("%f",&salario);
  printf("Porcentagem de aumento: ");
  scanf("%f",&porc);
  
  aumento = salario * (porc / 100);
  novo_salario = salario + aumento;
  printf("Aumento = R$ %.2f \n\n",aumento);
  printf("Novo Salario = R$ %.2f \n",novo_salario);
	
system("pause>null");
}
