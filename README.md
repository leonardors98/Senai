![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=c-sharp&logoColor=white)

# Ajudinha para as aulas
Nome dos arquivos => Datas nos nomes YY-MM-DD



<details>
  <summary> Concatenação </summary>
	
	using static System.Console;
	string var = "texto";
	WriteLine($" usando uma variavel direta {var}");
	WriteLine(" usando um operador " + var);

</details>
	
## Condicionais

<details>
  <summary> If else </summary>
	
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
	
</details>


<details>
  <summary> Switch case </summary>

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
	
</details>


<details>
  <summary> for </summary>

	using static System.Console;

	for (int i = 0; i < 10; i++)
	{
	    WriteLine($"loop atual : {i}");
	}
	
</details>



<details>
  <summary> do while </summary>
	
	using static System.Console;
	int i = 0;
	do {
	    WriteLine($"loop atual : {i+1}");
	    i++;
	}while (i< 10);
	
</details>


<details>
  <summary> while </summary>

	using static System.Console;
	int i = 0;
	while (i < 10)
	{
	    WriteLine($"loop atual : {i+1}");
	    i++;
	}

</details>

### Operadores	
	
<details>
  <summary> operações logicas </summary>

	a == b	-> A é igual B
	a != b	-> A Diferente de B
	a < b 	-> A menor q B
	a <= b	-> A Menor ou igual a B
	a > b 	-> A maior q B
	a >= b 	-> A maior ou igual q B
	!a	-> negação do A, se A for TRUE, será considerado FALSE
</details>
	

<details>
  <summary> Operador aritméticos </summary>
	
	+	adição
	-	subtração
	*	multiplicação
	/	divisão
	%	módulo (resto da divisão)
	
</details>


<details>
  <summary> Operador Logico </summary>

	&&	And = E
	||	OR = OU
	!	NOT = NÃO
</details>

### Outros itens
<details>
  <summary> read line e convert </summary>

	WriteLine("Escreva seu nome");
	nome = ReadLine();
	WriteLine("escreva sua idade");
	idade = Convert.ToInt32(ReadLine());
</details>
