#include <stdio.h>
int main (void)
{
	char jogador[20], resp1, resp2;
	
	printf ("\n Qual o nome do seu jodagor: \n ", jogador);
	scanf ( "%s", jogador);
	
	printf ("\n A hidrelétrica de Itaipu, que atualmente está entre as três maiores usinas hidrelétricas do mundo em capacidade instalada, abastece qual(s) pais (es)?");
	printf ("\n A - Somente o Brasil. \n B - Brasil, Paraguai e Uruguai. \n C - Brasil e Paraguai.  \n D - Brasil e Argentina. \n\n");
	fflush (stdin);
	resp1 = getchar();
	switch (resp1)
	{
	case 'A':
		printf ("\n Parabens!! Resposta certa.");
	
		break;
	case 'B':
		printf ("\n Vixe. Resposta errada.");
		
		break;
	case 'C':
		printf ("\n Vixe. Resposta errada.");
	
		break;
	case 'D':
		printf ("\n Vixe. Resposta errada.");
	
		break;
		
		 default:
        printf("Resposta Invalida");
	
	}
	printf ("\n Qual o país que mais utliza energia solar?");
	printf ("\n A - China. \n B - Japao. \n C - Alemanha. \n D - Estados Unidos \n\n");
	fflush (stdin);
	resp2 = getchar();
	switch (resp2) 
	{
	case 'A':
		printf ("\n Parabens!! Resposta certa.");
		printf ("\n\n HORA DA CURIOSIDADE: O país asiático tem a maior capacidade instalada de produção de energia solar do mundo, alcançando 130 gigawhatts — apenas a título de comparação, a capacidade brasileira atual fica em torno de 2 gigawhatts.");
		
		break;
	case 'B':
		printf ("\n Vixe. Resposta errada.");
		printf ("\n\n HORA DA CURIOSIDADE: A capacidade total do país, conforme dados de 2016, era de 42.800 megawhatts. \n Em novembro de 2018, foi inaugurada a maior usina geradora do país, com 900 mil painéis fotovoltaicos, ocupando uma área de 265 hectares.");
		
		break;
	case 'C':
		printf ("\n Vixe. Resposta errada.");
		printf ("\n\n HORA DA CURIOSIDADE: Apesar de estar longe de ser um país privilegiado em termos de insolação, como o Brasil, a capacidade de produção da Alemanha alcança 41.200 megawhatts, o que corresponde a 13,6% da produção global.");
		
		break;
		
	case 'D':
		printf ("\n Vixe. Resposta errada.");
		printf ("\n\n HORA DA CURIOSIDADE:O país conta com mais de 40 mil megawhatts de capacidade instalada, o que corresponde a mais de 13% da geração de energia solar no mundo. ");
		
		break;	
		 default:
        printf("Resposta Invalida");
		
	}
		
	
	
	
	
}
