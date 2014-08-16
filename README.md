ProgramasC
==========
/*
Programa: Calculo da media de um aluno
APC 1
Daniel Vieira
Professor: Ronaldo
Curso: Eng. da Computação
*/
#include <stdio.h>
#include <conio.h>
int main()
{
	float m1,m2,b1,b2,mb1,mb2,mf;
	char nome[50];
	printf(" Digite seu nome: ");
	scanf("%s",nome);
	printf(" Digite a nota que voce tirou na prova M1: ");
	scanf("%f",&m1);
	printf(" Digite a nota que voce tirou na prova B1: ");
	scanf("%f",&b1);
	printf(" Digite a nota que voce tirou na prova M2: ");
	scanf("%f",&m2);
	printf(" Digite a nota que voce tirou na prova B2: ");
	scanf("%f",&b2);
	mb1=(m1*4+b1*6)/10;
	mb2=(m2*4+b2*6)/10;
	mf=(mb1*4+mb2*6)/10;
	printf("    Nota M1= %.2f \n", m1);
	printf("    Nota B1= %.2f \n", b1);
	printf("    Nota M2= %.2f \n", m2);
	printf("    Nota B2= %.2f \n", b2);
	printf("    Nota MB1= %.2f \n", mb1);
	printf("    Nota MB2= %.2f \n", mb2);
	printf ("   MF= %.2f \n",  mf);
	if(mf>=5)printf(" %s voce esta aprovado !", nome);
	else
	printf(" %s voce esta reprovado !", nome);
	getch();
}
