![C#]

# Ajudinha para as aulas
Datas nos nomes = YY-MM-DD

## Concatenação
    using static System.Console;
	string var = "texto";
	WriteLine($" usando uma variavel direta {var}");
	WriteLine(" usando um operador " + var);

## Condicionais
### If else
	using static System.Console;
	int num = 0;
	if (num == 0)
	{
	    WriteLine("Num é igual a zero");
	}
	else
	{
	    if (num != 0)
	    {
	        WriteLine("Num é diferente de zero");

	    }
	}
### Switch case
	using static System.Console;

	string frase1 = "esta é a frase 1";
	string frase2 = "aqui escrevo a frase 2";
	string frase3 = "leia aqui a frase 3";
	char opcao;

	WriteLine("escolha uma opcao de 1 - 3");
	opcao = (char)Read();
	switch (opcao)
	{
	    case '1':
	        WriteLine(frase1);
	        break;
	    case '2':
	        WriteLine(frase2);
	        break;
	    case '3':
	        WriteLine(frase3);
	        break;

	    default:
	        WriteLine("Caracter inválido !");
	        break;
	}
### for
	using static System.Console;

	for (int i = 0; i < 10; i++)
	{
	    WriteLine($"loop atual : {i}");
	}
### do while
	using static System.Console;
	int i = 0;
	do {
	    WriteLine($"loop atual : {i+1}");
	    i++;
	}while (i< 10);
### while
	using static System.Console;
	int i = 0;
	while (i < 10)
	{
	    WriteLine($"loop atual : {i+1}");
	    i++;
	}


### operações logicas
	a == b	-> A é igual B
	a != b	-> A Diferente de B
	a < b 	-> A menor q B
	a <= b	-> A Menor ou igual a B
	a > b 	-> A maior q B
	a >= b 	-> A maior ou igual q B
	!a	-> negação do A, se A for TRUE, será considerado FALSE

### Operador aritméticos
	+	adição
	-	subtração
	*	multiplicação
	/	divisão
	%	módulo (resto da divisão)


### Operador Logico
	&&	And = E
	||	OR = OU
	!	NOT = NÃO
