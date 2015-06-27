#include<stdio.h>
#include<stdlib.h>
#include<conio.h>
#include<string.h>
typedef struct{
	int   codigo,quantidade,estoque_min=1,estoque_max,fornecedor;
	float preco_custo,preco_venda;
	char  usuario_adm,senha_adm,usuario,senha;
	char produto[100];
} cadastro;
int main(){

int opcao_1,opcao_2;




printf("\n***MENU***\n");
printf("\nEscolha a Opcao Desejada:\n");
printf("\n1-Produtos\n");
printf("\n2-Movimentacao\n");
scanf("%d",&opcao_1);
system("cls");
//Produtos
switch(opcao_1){
case 1:
printf("\n1-Cadastrar\n");
printf("\n2-Alterar\n");
printf("\n3-Excluir\n");
printf("\n4-Consultar\n");
printf("\n5-Relatorios\n");
scanf("%d",&opcao_2);
system("cls");
switch(opcao_2){

case 1:
printf("\n Digite a seguir os Dados Necessarios para o Cadastro:\n");
printf("\n Fornecedor do Produto:\n");
printf("\n 1-Samsung \n");
printf("\n 2-Multilaser \n ");
printf("\n 3-Genius \n");
printf("\n 4-Clone \n");
scanf ("%d",&cadastro.fornecedor);
switch(cadastro.fornecedor){
fflush(stdin);
break;

case 1:
	printf("Fornecedor Escolhido:Samsung");

	printf("\n Nome do Produto:\n");
gets(cadastro.produto);
fflush(stdin);
printf("\n Valor de Custo\n");
scanf("%f",&cadastro.preco_custo);
printf("\n Valor de Venda:");
cadastro.preco_venda=(cadastro.preco_custo*0.2)+cadastro.preco_custo;
printf("%.1f",cadastro.preco_venda);
printf("\nEstoque maximo\n");
scanf("%d",&cadastro.estoque_max);
	break;
	case 2:
	printf("Fornecedor Escolhido:Multilaser");

	printf("\n Nome do Produto:\n");
gets(nome);
fflush(stdin);
printf("\n Valor de Custo\n");
scanf("%f",&cadastro.preco_custo);
printf("\n Valor de Venda:");
cadastro.preco_venda=(cadastro.preco_custo*0.2)+cadastro.preco_custo;
printf("%.1f",cadastro.preco_venda);
printf("\nEstoque maximo\n");
scanf("%d",&cadastro.estoque_max);

	break;
	case 3:
	printf("Fornecedor Escolhido:Genius");

	printf("\n cadastro.produto do Produto:\n");
gets(cadastro.produto);
fflush(stdin);
printf("\n Valor de Custo\n");
scanf("%f",&cadastro.preco_custo);
printf("\n Valor de Venda:");
cadastro.preco_venda=(cadastro.preco_custo*0.2)+cadastro.preco_custo;
printf("%.1f",cadastro.preco_venda);
printf("\nEstoque maximo\n");
scanf("%d",&cadastro.estoque_max);

	break;
	case 4:
	printf("Fornecedor Escolhido:Clone");

	printf("\n cadastro.produto do Produto:\n");
gets(cadastro.produto);
fflush(stdin);
printf("\n Valor de Custo\n");
scanf("%f",&cadastro.preco_custo);
printf("\n Valor de Venda:");
cadastro.preco_venda=(cadastro.preco_custo*0.2)+cadastro.preco_custo;
printf("%.1f",cadastro.preco_venda);
printf("\nEstoque maximo\n");
scanf("%d",&cadastro.estoque_max);
	break;



break;


case 2:
printf("\n1-Comprar\n");
printf("\n2-Vender\n");
scanf("%d",&opcao_2);
system("cls");
break;
}
}
}
