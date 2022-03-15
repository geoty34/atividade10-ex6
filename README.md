# atividade10-ex6
programa
{
	
	funcao inicio()
	{
		inteiro primeiro_num
		inteiro segundo_num

		escreva ("Digite o primeiro número: ")
		leia (primeiro_num)

		escreva ("Digite o segundo número: ")
		leia (segundo_num)

		se (primeiro_num < segundo_num){
			para (primeiro_num ; primeiro_num <= segundo_num ; primeiro_num++)
			escreva("\n",primeiro_num,"\n","\n","\n")
		}
		senao{
			para (primeiro_num ; primeiro_num >= segundo_num ; primeiro_num--)
			escreva("\n",primeiro_num,"\n","\n","\n")
		}
	}
}
